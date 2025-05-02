# BlendModeMaterialsAsset

**Namespace:** `Spine.Unity`


## Fields

- `Material multiplyMaterialTemplate`

- `Material screenMaterialTemplate`

- `Material additiveMaterialTemplate`

- `Boolean applyAdditiveMaterial`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BlendModeMaterialsAsset : SkeletonDataModifierAsset
{
	public Material multiplyMaterialTemplate; // 0x18
	public Material screenMaterialTemplate; // 0x20
	public Material additiveMaterialTemplate; // 0x28
	public Boolean applyAdditiveMaterial; // 0x30


	// RVA: 0x621b6c4 VA: 0x75988336c4
	public override Void Apply(SkeletonData skeletonData) { }
	// RVA: 0x621b6dc VA: 0x75988336dc
	public static Void ApplyMaterials(SkeletonData skeletonData, Material multiplyTemplate, Material screenTemplate, Material additiveTemplate, Boolean includeAdditiveSlots) { }
	// RVA: 0x621bf0c VA: 0x7598833f0c
	public Void .ctor() { }
}
```