# NiagaraFluid

Fluid simulation(SPH) and water rendering in Unreal Engine 5 Niagara(GPU simulation stage)

Demo : https://www.youtube.com/watch?v=EEXcR8ROdnM

Note : This repository is not associated with "Niagara Fluids"(Epic's official plugin). This is another implementation and uses SPH.

Computational Order : In this implementation, the computational order is O(N^2) because we are using a full search to compute the interaction. If we optimize the nearest neighbor search, this could be reduced to O(NlogN).

![GIF 8-14-2022 4-22-10 PM](https://user-images.githubusercontent.com/26865534/184529081-7178c81c-4608-4519-ba0b-40f59fb07af4.gif)


## References
・Matthias Müller et al, "Particle-based fluid simulation for interactive applications", ACM SIGGRAPH/Eurographics symposium on Computer animation, 2003

https://dl.acm.org/doi/10.5555/846276.846298

・Doyub Kim, "Fluid Engine Development", A K Peters/CRC Press, 2017

https://www.amazon.co.jp/-/en/Doyub-Kim-ebook/dp/B01MRDA6S8

・Indie Visual Lab, "Unity Graphics Programming Vol.1", 2017

https://indievisuallab.github.io/

・monguri / UE4NiagaraSandbox

https://github.com/monguri/UE4NiagaraSandbox

・Unreal Engine 4 Content Examples (Niagara Advanced map)

https://docs.unrealengine.com/4.26/en-US/Resources/ContentExamples/

・Screen Space Fluid Rendering for Games - Nvidia

https://developer.download.nvidia.com/presentations/2010/gdc/Direct3D_Effects.pdf
