# HDRP_DrawCustomRenderer_setupStackLitSSS
Unity 2021.3.6f1 DrawRendererCustomPass proof of concept :


https://user-images.githubusercontent.com/28776336/179323663-f6d4c159-484c-40f0-bbcf-db7964ec6814.mp4


- Open Sample Scene
- Each Sphere contains a different material : Lit (SSS) and Stack Lit (transmission+dual lob), both connect to the same diffusion profile
- Each Sphere is draw on his own Layer, to allow the Draw Renderer Custom Pass to draw them (they are not draw by the camera anyway)

![Capture d’écran (12)](https://user-images.githubusercontent.com/28776336/179323314-eb2392da-4274-4ca6-9be1-aba4d8900fbc.png)


![Capture d’écran (13)](https://user-images.githubusercontent.com/28776336/179323610-71044316-dc47-4a3c-9154-2e0934624dee.png)


![Capture d’écran (14)](https://user-images.githubusercontent.com/28776336/179323612-0f21ebe7-40d3-4f25-994e-680489a39625.png)
