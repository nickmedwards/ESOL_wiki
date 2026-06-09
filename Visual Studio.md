
Evergreen bootstrappers for older versions
https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-history#evergreen-bootstrappers

[[Welcome]]

fix not finding cuda
You can resolve this instantly by manually copying the missing build files into Visual Studio’s build customizations directory. [[1](https://stackoverflow.com/questions/15481314/build-customization-for-cuda-5-0-not-found-in-visual-c)]

1. Open your File Explorer and navigate to the **CUDA MSBuild Extensions** folder:  
    `C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v13.1\extras\visual_studio_integration\MSBuildExtensions\`
2. Select and **copy** all files in this directory (including `CUDA 13.1.props`, `CUDA 13.1.targets`, `CUDA 13.1.xml`, etc.).
3. Navigate to your **Visual Studio Build Customizations** directory (adjust the path depending on your edition, such as Community, Professional, or Enterprise):  
    `C:\Program Files\Microsoft Visual Studio\2022\Community\MSBuild\Microsoft\VC\v170\BuildCustomizations\`
4. **Paste** the copied files into this folder.