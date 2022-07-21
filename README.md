<h1 align="center" >DaVinci Image/Video Enhancement Toolkit</h1>

## Introduction
DaVinci was a famous Renaissance painter who had the ability to turn corruption into magic. The DaVinci Toolkit is a set of intelligent image/video enhancement tools, aiming to solve the pain points of existing video enhancement and restoration tools，give full play to the advantages of AI technology and lower the threshold for users to process video footage.

## Recent Updates
- ✅Release the general image super-resolution toolkit.
- ✅Release the compressed video super-resolution toolkit.
  
## Toolkit and Usage

### Image Super-Resolution
Enhance the low-resolution images to high-resolution ones and reduce artifacts including noise, blur and JPEG blocking.

![ISR_Demo](figs/ISR_Demo.png)
<p align="center">Left: Input Low-Quality Image, Right: DaVinci Enhanced Result</p>

Three [executable files](https://azsjae.blob.core.windows.net/davinci/release/DaVinci_ISR_General_20220622.zip) are provided in the Toolkit:
- DaVinci_ISR_General_Tool_X2/3/4.exe

  To restore the general image with different scale factors.

```cmd
DaVinci_ISR_General_Tool_X2/3/4.exe input.png output.png
```

### Compressed Video Super-Resolution
Recovery from compressed low-resolution video frames to high-resolution video frames.


<video src="https://user-images.githubusercontent.com/53380424/180170775-797e22f6-0ff9-4002-b723-7c116a84d898.mp4">
<p align="center">Left: Input Low-Quality Video, Right: DaVinci Enhanced Result</p>

Two [executable files](https://azsjae.blob.core.windows.net/davinci/release/DaVinci_VSR_Small_Face_20220622.zip) are provided  in the Toolkit:
- DaVinci_VSR_Small_Face_Online_X4.exe
  
  Simulate the use of video conferencing scenarios that reconstruct the low-resolution images acquired by the camera to high-resolution images in real time.
  
```cmd
DaVinci_VSR_Small_Face_Online_X4.exe
```

- DaVinci_VSR_Small_Face_Offline_X4.exe

  Reconstruct compressed low-resolution video to high-resolution video offline

```cmd
DaVinci_VSR_Small_Face_Offline_X4.exe  input_video output_video
```

## Related Projects
We sincerely recommend some of our excellent works that make the DaVinci toolkit happen. Please don't hesitate to star to these projects. :sparkles:  
* [TTSR: Learning Texture Transformer Network for Image Super-Resolution](https://github.com/researchmm/TTSR)
* [DMSR: Degradation-Guided Meta-Restoration Network for Blind Super-Resolution](https://arxiv.org/abs/2207.00943v1)
* [CKDN: Learning Conditional Knowledge Distillation for Degraded-Reference Image Quality Assessment](https://github.com/researchmm/CKDN)
* [TTSR: Learning Texture Transformer Network for Image Super-Resolution](https://github.com/researchmm/TTSR)
* [TTVSR: Learning Trajectory-Aware Transformer for Video Super-Resolution](https://github.com/researchmm/TTVSR)
* [FTVSR: Learning Spatiotemporal Frequency-Transformer for Compressed Video Super-Resolution](https://github.com/researchmm/FTVSR)

## Team Members
- [Huan Yang](https://github.com/hyang0511) and [Jianlong Fu](https://github.com/Jianlong-Fu)
  Lead this whole project. 
- [Yin Chen](https://github.com/cyinen)
  Integrate models into executable files and build these toolkit.
- [Huiguo He](https://github.com/hehuiguo)
  Process training data for compressed video super-resolution.

## Acknowledgment
This toolkit is built on [ncnn](https://github.com/Tencent/ncnn). Some of the models are trained with [BasicSR](https://github.com/XPixelGroup/BasicSR). We sincerely thank all the authors of these projects.

## Contact
If you have any questions, please feel free to send an email to davinci@microsoft.com.

## Contributing
This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks
This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
