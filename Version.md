## Version
Midjourney定期发布新的模型版本以提高效率、连贯性和质量。  
最新的模型是默认的，但可以使用--version或--v参数或使用/settings命令并选择一个模型版本来使用其他模型。  
不同的模型擅长于不同类型的图像。
> --version 值为1，2，3，4，5
> --version 可以省略为 --v

## 最新模型
Midjourney V5 模型是最新和最先进的模型，于 2023 年 3 月 15 日发布。  
要使用此模型，请在提示语的末尾添加 --v 5 参数，或使用 /settings 命令并选择 5️⃣ MJ Version 5。  
该模型具有非常高的连贯性，擅长解释自然语言提示，分辨率更高，并支持使用 --tile 重复模式等高级功能。
## 现在的模型
Midjourney V4模型是一个全新的代码库和全新的AI架构，由Midjourney设计并在新的Midjourney AI超级群集上进行训练。  
最新的Midjourney模型对生物、地点、物体等方面有更多的知识。它更擅长处理细节，可以处理具有多个角色或物体的复杂提示。  
版本4模型支持高级功能，如图像提示和多提示。  
这个模型的连贯性非常高，擅长处理图像提示。  
### V4的4a,4b,4c
Midjourney的V4模型有三个略微不同的“风格”，对模型的风格调整进行了微调。  
通过在V4提示的末尾添加--style 4a、--style 4b或--style 4c来尝试这些版本。  
--v 4 --style 4c是当前的默认设置，不需要在提示的末尾添加。  
> #### 说明Style 4a和4b的注意事项：  
>--style 4a和--style 4b仅支持1：1、2：3和3：2的纵横比。  
>--style 4c支持高达1：2或2：1的纵横比。  

## 之前的模型
你可以使用 --version 或 --v 参数或使用 /settings 命令并选择模型版本来访问早期的 Midjourney 模型。  
不同的模型擅长不同类型的图像。  
提示示例：/imagine prompt vibrant California poppies --v 1  

## Niji 模型
“niji”模型是Midjourney和Spellbrush的合作项目，旨在产生动漫和插图风格的图像。  
--niji模型具有更多的动漫、动漫风格和动漫美学相关的知识。  
它擅长于动态和行动镜头，以及一般的以人物为中心的构图。
提示示例： /imagine prompt vibrant California poppies --niji
> ### 对 --niji 模型的说明  
> Niji 模型不支持 --stylize 参数。使用 /settings 命令并选择 Style Med 以重置所有 --niji 提示的默认样式设置。  
> Niji 支持多提示或图像提示。  

## 测试模型
偶尔会发布新模型供社区测试和反馈。  
目前有两个可用的测试模型：--test和--testp，可以与--creative参数结合使用以获得更多种类的构图。  
例如：/imagine prompt vibrant California poppies --testp --creative  
> 关于当前测试模型--test和--testp的注意事项：  
> 测试模型只支持--stylize值在1250-5000之间。  
> 测试模型不支持多提示或图像提示。  
> 测试模型的最大长宽比为3：2或2：3。    
> 当长宽比为1：1时，测试模型只生成两个初始网格图像。  
> 当长宽比不为1：1时，测试模型只生成一个初始网格图像。  
> 提示中靠近前面的单词可能比靠近后面的单词更重要。  

## 如何切换模型
### 使用Version 或者 test 参数
在提示词后添加--v 1, --v 2, --v 3, --v 4, --v 4 --style 4a, --v4 --style 4b --test,   
--testp, --test --creative,--testp --creative or --niji  
### 使用setting命令
键入  /setting 从目录中选择你喜欢的版本

