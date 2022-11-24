- 👋 Hi, I’m @zy-gdou
- 👀 I’m interested in CFD simulations with applications to oceanic and atmospheric flows using idealized numerical models scripted in MATLAB.
- 🌱 One of such idealized models is the surface quasi-geostrophic (SQG) model. This model allows one to diagnose the 3D flow current using a single snapshot of the surface density perturbaiton (which is usually proportional to the sea surface temperature, SST). Modern satellite remote sensing of SST could reach a high spatial resolution of ~1 km, thus the diagnosed field can resolve part of the submesoscales, with resolution beyond the 1/4 degree of the commonly-used a
ltimetry product(AVISO). Another interesting feature is that the SQG flow could bear an abundance of small-scale structures, with filaments and vortices surviving for quite a long time. In contrast, in the two-dimensional (or Quasigeostrophic/QG) turbulence, the large-scale structures outlives the small ones. Therefore, the SQG model might be able to explain part of the generation of the submesoscale structures in the ocean.

Surface buoyancy perturbation is conserved with the parcel in the SQG flow. When there is a background (steady) density gradient at the surface due to imhomogeneosous heating at large scales, the SQG dynamics is unsurprisingly subject to a certain type of the beta-effect. "beta-SQG/" adds the $\beta$-effect into the classic SQG current. Here, one can explore the Rossby wave dynamics, the Rhines scales and stuff related to the $\beta$-effect in the context of the SQG dynamics. It should be noted that the Lagrangian-conserved quantity in the SQG flow is the surface buoyancy perturbation $b_s(x,y,t)$, intead of the absolute vorticity in the QG counterpart.

However, the SQG model is still constrained by the assumption of the small Rossby number. At submesoscales, the Rossby number is not necessarily small and nonlinear advectoin plays a significant role. In order to better capture the nonlinearity but still under a small Rossby number, two high-order (in terms of the small Rossby number expansion) variants of the SQG model are proposed: the SQG+1 model and the SSG model.

"SSG/" contains the code used for free-decaying SSG turbulence.



