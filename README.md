# Unity URP Aniso Highlight Hair Shader

![CathyShih_ShaderComparisonDemo](Images/CathyShih_ShaderComparisonDemo.png)

This shader was put together to enhance the rendering of hair models in Unity URP using Shader Graph. 

* Unity 2022.3.16f1LTS
* URP 14.0.9
* Shader Graph 14.0.9

It contains a custom lighting function/subgraph from the Unity project [BoatAttack](https://github.com/Unity-Technologies/BoatAttack) to get main light's direction and color. It requires an anisotropic direction texture. Here is an example showcasing reflection changes based on light direction:

![CathyShih_MoveMainLightDemo](cathyhlshih/UnityURPAnisoHighlightHair/Images/CathyShih_MoveMainLightDemo.gif)

Testures used for testing:
![CathyShih_TexturesforTesting](cathyhlshih/UnityURPAnisoHighlightHair/Images/CathyShih_TexturesforTesting.png)

It also aims to improve visual quality for [UMA](https://github.com/umasteeringgroup/UMA) users who have chosen WillB's hair packs. UMA is a free character creation and modification system and users often leverage material color changes for character modification. Here is a demonstration of hair color change below:

![CathyShih_ColorChangeDemo](cathyhlshih/UnityURPAnisoHighlightHair/Images/CathyShih_ColorChangeDemo.gif)



The shader can be easily modified for use with other hair models.
