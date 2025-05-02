# BlendModeMaterials

**Namespace:** `Spine.Unity`


## Fields

- `Boolean requiresBlendModeMaterials`

- `Boolean applyAdditiveMaterial`


## Properties

- `Boolean RequiresBlendModeMaterials`


## Methods

- `Boolean get_RequiresBlendModeMaterials()`

- `Void set_RequiresBlendModeMaterials(Boolean)`

- `Void ApplyMaterials(SkeletonData)`

- `AtlasRegion CloneAtlasRegionWithMaterial(AtlasRegion, List`1)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BlendModeMaterials
{
	protected Boolean requiresBlendModeMaterials; // 0x10
	public Boolean applyAdditiveMaterial; // 0x11
	public List`1 additiveMaterials; // 0x18
	public List`1 multiplyMaterials; // 0x20
	public List`1 screenMaterials; // 0x28

	public Boolean RequiresBlendModeMaterials { get; set; }

	// RVA: 0x61f80ec VA: 0x75988100ec
	public Boolean get_RequiresBlendModeMaterials() { }
	// RVA: 0x61f80f4 VA: 0x75988100f4
	public Void set_RequiresBlendModeMaterials(Boolean value) { }
	// RVA: 0x61f8100 VA: 0x7598810100
	public Void ApplyMaterials(SkeletonData skeletonData) { }
	// RVA: 0x61f8664 VA: 0x7598810664
	protected AtlasRegion CloneAtlasRegionWithMaterial(AtlasRegion originalRegion, List`1 replacementMaterials) { }
	// RVA: 0x61f8848 VA: 0x7598810848
	public Void .ctor() { }
}
```