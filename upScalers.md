## Upscalers
Midjourney首先为每个工作生成低分辨率图像选项。  
您可以使用Midjourney放大模型对任何图像进行放大以增加其尺寸并添加更多细节。  
有多个升级模型可用于放大图像。

U1 U2 U3 U4按钮用来放大选中的图片
### Midjourney的维度和尺寸
所有大小均适用于正方形1:1的纵横比。  
![image](https://user-images.githubusercontent.com/61191265/232320338-90c87133-590c-4366-9451-6fd56a7a2d3e.png)
> *表示每个Midjourney的默认版本模型。  
** 表示Max Upscale，是一种资源密集型的较老的升频器，仅在用户处于Fast模式时可用。  
> #### Midjourney Model 5
> 最新的Midjourney模型版本，可以生成高分辨率的1024 x1024像素图像，无需额外的图像升级步骤。  
> 当使用Midjourney Model Version 5时，每个图像网格下的U1 U2 U3 U4按钮将分离所选图像和初始图像。  
### 默认Upscaler
最新的默认放大模型可以增加图像的大小并平滑或改进细节。在初始的图像和完成的放大版本之间可能会有一些小的元素变化。
### Light Upscaler
轻量级放大模型创建一个1024px x 1024px的图像，并添加适度数量的细节和纹理。  
在使用旧版Midjourney模型版本时，轻量级升频器对于面部和光滑表面非常有用。  
使用--uplight参数来更改U1 U2 U3 U4升频按钮的行为以使用轻量级升频器。  
### 细节Upscaler
细节放大模型会生成1024px x 1024px的高分辨率图像，并在图像上添加许多额外的细节。  
使用Detailed upscaler进行放大的图像可以使用Upscale to Max按钮再次进行放大，以获得最终的1664px x 1664px分辨率。  
在快速模式下才能使用Upscale to Max。  
Detailed upscaler是Midjourney Model版本V1、V2、V3和hd的默认选项。  
### Beta Upscaler
Beta放大模型可以创建一个2048px x 2048px的图像，而不添加很多额外的细节。  
Beta Upscaler在处理面部和平滑表面时非常有用。  
使用--upbeta参数可以更改U1 U2 U3 U4升级按钮的行为，以使用Beta Upscaler。  
### 动画Upscaler
动画放大模型是--niji模型的默认放大模型。  
它将图像放大到1024像素x1024像素，并针对插图和动画风格进行了优化。  
使用--upanime参数可以更改U1 U2 U3 U4放大按钮的行为，以使用动画放大模型。  
### Remaster
它是先前使用V1、V2或V3模型版本进行过放大的图像的附加选项。    
Remaster将再次使用--test和--creative参数对图像进行放大，将原始图像和新的--test模型生成图混合起来。  
通过单击原始放大图像下方的🆕 Remaster按钮来重新制作任何先前放大的作业。  

要重新制作非常旧的作业，请使用/show命令在Discord中刷新该作业。
> Remaster的注意事项：  
> 仅适用于长宽比为2：3或3：2的图像    
> 使用多个prompt会导致结果不一致  
> 无法加上图片URL进行图生图操作  
