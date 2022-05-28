## What is it

The [release page](https://github.com/Tugcga/OIDN-Windows-Binaries/releases) of the repository contains compiled version of the [OpenImageDenoise](https://github.com/OpenImageDenoise/oidn) library. Default distribution of the OIDN contains simple denoising application ```oidnDenoise.exe```, but it supports only ```ppm``` and ```ppf``` image formats. Version in this repository compiled with [OpenImageIO](https://github.com/OpenImageIO/oiio) and supports many other image formats.

## How to use

Call in the terminal

```.\oidnDenoise.exe --ldr .\image.png -o image_denoise.png```

Here ```image.png``` is an input noisy image, ```image_denoise.png``` is a name of the new file, where denoised result will be saved.

If you would like to denoise image in hdr-format (```*.exr``` for example), then call

```.\oidnDenoise.exe --hdr .\image.exr -o image_denoise.exr```
