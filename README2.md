# souce code & guidance & models
1.souce code :https://github.com/AUTOMATIC1111/stable-diffusion-webui
2.guidance :https://phazertech.com/tutorials/rocm.html
3.models:https://huggingface.co/stabilityai/stable-diffusion-2-1/tree/main

# attention according to the guidance 
1.Do not use root as user 
2.webui.sh was modified to use rocm6.0
3.you will met this issue:ValueError: Unknown scheme for proxy URL URL('socks://127.0.0.1:1089/')
use this in the command line to fix: unset all_proxy && unset ALL_PROXY
4. modules.devices.NansException: A tensor with all NaNs was produced in Unet. This could be either because there's not enough precision to represent the picture, or because your video card does not support half type. Try setting the "Upcast cross attention layer to float32" option in Settings > Stable Diffusion or using the --no-half commandline argument to fix this. Use --disable-nan-check commandline argument to disable this check.


