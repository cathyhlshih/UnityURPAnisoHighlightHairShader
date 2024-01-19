# Unity URP Aniso Highlight Hair Shader

![CathyShih_ShaderComparisonDemo](/UnityURPAnisoHighlightHair/Images/CathyShih_ShaderComparisonDemo.png)

This shader was put together to enhance the rendering of hair models in Unity URP using Shader Graph. 

* Unity 2022.3.16f1LTS
* URP 14.0.9
* Shader Graph 14.0.9

It contains a custom lighting function/subgraph from the Unity project [BoatAttack](https://github.com/Unity-Technologies/BoatAttack) to get main light's direction and color. It requires an anisotropic direction texture. The render result was done with WillB's [UMA](https://github.com/umasteeringgroup/UMA) Hair packs. Here is an example showcasing reflection changes based on light direction:

<img src="/UnityURPAnisoHighlightHair/Images/CathyShih_MoveMainLightDemo.gif" alt="CathyShih_MoveMainLightDemo" style="width:300px;"/>

Textures used for testing:

<img src="/UnityURPAnisoHighlightHair/Images/CathyShih_TexturesforTesting.png" alt="CathyShih_MoveMainLightDemo" style="width:300px;"/>

UMA is a free character creation and modification system and users often leverage material color changes for character modification. Here is a demonstration of hair color change below:

<img src="/UnityURPAnisoHighlightHair/Images/CathyShih_ColorChangeDemo.gif" alt="CathyShih_MoveMainLightDemo" style="width:300px;"/>

The shader can be easily modified for use with other hair models.
