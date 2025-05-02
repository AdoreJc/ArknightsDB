# SpineSpriteAtlasAsset

**Namespace:** `Spine.Unity`


## Fields

- `SpriteAtlas spriteAtlasFile`

- `Atlas atlas`

- `Boolean updateRegionsInPlayMode`


## Methods

- `Void Reset()`

- `Void AssignRegionsFromSavedRegions(Sprite[], Atlas)`

- `Atlas LoadAtlas(SpriteAtlas)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SpineSpriteAtlasAsset : AtlasAssetBase
{
	public SpriteAtlas spriteAtlasFile; // 0x18
	public Material[] materials; // 0x20
	protected Atlas atlas; // 0x28
	public Boolean updateRegionsInPlayMode; // 0x30
	protected SavedRegionInfo[] savedRegions; // 0x38

	public override Boolean IsLoaded { get; }
	public override IEnumerable`1 Materials { get; }
	public override Int32 MaterialCount { get; }
	public override Material PrimaryMaterial { get; }

	// RVA: 0x61fae10 VA: 0x7598812e10
	public override Boolean get_IsLoaded() { }
	// RVA: 0x61fae20 VA: 0x7598812e20
	public override IEnumerable`1 get_Materials() { }
	// RVA: 0x61fae28 VA: 0x7598812e28
	public override Int32 get_MaterialCount() { }
	// RVA: 0x61fae40 VA: 0x7598812e40
	public override Material get_PrimaryMaterial() { }
	// RVA: 0x61fae68 VA: 0x7598812e68
	public static SpineSpriteAtlasAsset CreateRuntimeInstance(SpriteAtlas spriteAtlasFile, Material[] materials, Boolean initialize) { }
	// RVA: 0x61faf10 VA: 0x7598812f10
	private Void Reset() { }
	// RVA: 0x61faf1c VA: 0x7598812f1c
	public override Void Clear() { }
	// RVA: 0x61faf28 VA: 0x7598812f28
	public override Atlas GetAtlas() { }
	// RVA: 0x61fb78c VA: 0x759881378c
	protected Void AssignRegionsFromSavedRegions(Sprite[] sprites, Atlas usedAtlas) { }
	// RVA: 0x61fb2fc VA: 0x75988132fc
	private Atlas LoadAtlas(SpriteAtlas spriteAtlas) { }
	// RVA: 0x61fbb9c VA: 0x7598813b9c
	public static Texture2D AccessPackedTexture(Sprite[] sprites) { }
	// RVA: 0x61fbbc8 VA: 0x7598813bc8
	public static Sprite[] AccessPackedSprites(SpriteAtlas spriteAtlas) { }
	// RVA: 0x61fbc50 VA: 0x7598813c50
	public Void .ctor() { }
}
```