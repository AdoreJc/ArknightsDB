# SpineAtlasAsset

**Namespace:** `Spine.Unity`


## Fields

- `TextAsset atlasFile`

- `Atlas atlas`


## Methods

- `Void Reset()`

- `Mesh GenerateMesh(String, Mesh, out, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SpineAtlasAsset : AtlasAssetBase
{
	public TextAsset atlasFile; // 0x18
	public Material[] materials; // 0x20
	protected Atlas atlas; // 0x28

	public override Boolean IsLoaded { get; }
	public override IEnumerable`1 Materials { get; }
	public override Int32 MaterialCount { get; }
	public override Material PrimaryMaterial { get; }

	// RVA: 0x61f9bf4 VA: 0x7598811bf4
	public override Boolean get_IsLoaded() { }
	// RVA: 0x61f9c04 VA: 0x7598811c04
	public override IEnumerable`1 get_Materials() { }
	// RVA: 0x61f9c0c VA: 0x7598811c0c
	public override Int32 get_MaterialCount() { }
	// RVA: 0x61f9c24 VA: 0x7598811c24
	public override Material get_PrimaryMaterial() { }
	// RVA: 0x61f9c4c VA: 0x7598811c4c
	public static SpineAtlasAsset CreateRuntimeInstance(TextAsset atlasText, Material[] materials, Boolean initialize) { }
	// RVA: 0x61f9d00 VA: 0x7598811d00
	public static SpineAtlasAsset CreateRuntimeInstance(TextAsset atlasText, Texture2D[] textures, Material materialPropertySource, Boolean initialize) { }
	// RVA: 0x61fa128 VA: 0x7598812128
	public static SpineAtlasAsset CreateRuntimeInstance(TextAsset atlasText, Texture2D[] textures, Shader shader, Boolean initialize) { }
	// RVA: 0x61f9cf4 VA: 0x7598811cf4
	private Void Reset() { }
	// RVA: 0x61fa210 VA: 0x7598812210
	public override Void Clear() { }
	// RVA: 0x61fa21c VA: 0x759881221c
	public override Atlas GetAtlas() { }
	// RVA: 0x61fa724 VA: 0x7598812724
	public Mesh GenerateMesh(String name, Mesh mesh, out Material material, Single scale) { }
	// RVA: 0x61fab24 VA: 0x7598812b24
	public Void .ctor() { }
}
```