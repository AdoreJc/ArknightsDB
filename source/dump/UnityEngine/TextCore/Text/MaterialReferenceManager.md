# MaterialReferenceManager

**Namespace:** `UnityEngine.TextCore.Text`


## Methods

- `Void AddFontAssetInternal(FontAsset)`

- `Void AddSpriteAssetInternal(Int32, SpriteAsset)`

- `Void AddFontMaterialInternal(Int32, Material)`

- `Void AddColorGradientPreset_Internal(Int32, TextColorGradient)`

- `Boolean TryGetFontAssetInternal(Int32, out)`

- `Boolean TryGetSpriteAssetInternal(Int32, out)`

- `Boolean TryGetColorGradientPresetInternal(Int32, out)`

- `Boolean TryGetMaterialInternal(Int32, out)`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
internal class MaterialReferenceManager
{
	private static MaterialReferenceManager s_Instance; // 0x0
	private Dictionary`2 m_FontMaterialReferenceLookup; // 0x10
	private Dictionary`2 m_FontAssetReferenceLookup; // 0x18
	private Dictionary`2 m_SpriteAssetReferenceLookup; // 0x20
	private Dictionary`2 m_ColorGradientReferenceLookup; // 0x28

	public static MaterialReferenceManager instance { get; }

	// RVA: 0x6903d60 VA: 0x7598f1bd60
	public static MaterialReferenceManager get_instance() { }
	// RVA: 0x6903f60 VA: 0x7598f1bf60
	public static Void AddFontAsset(FontAsset fontAsset) { }
	// RVA: 0x6903f80 VA: 0x7598f1bf80
	private Void AddFontAssetInternal(FontAsset fontAsset) { }
	// RVA: 0x6904130 VA: 0x7598f1c130
	public static Void AddSpriteAsset(Int32 hashCode, SpriteAsset spriteAsset) { }
	// RVA: 0x6904160 VA: 0x7598f1c160
	private Void AddSpriteAssetInternal(Int32 hashCode, SpriteAsset spriteAsset) { }
	// RVA: 0x6904234 VA: 0x7598f1c234
	public static Void AddFontMaterial(Int32 hashCode, Material material) { }
	// RVA: 0x6904264 VA: 0x7598f1c264
	private Void AddFontMaterialInternal(Int32 hashCode, Material material) { }
	// RVA: 0x69042cc VA: 0x7598f1c2cc
	public static Void AddColorGradientPreset(Int32 hashCode, TextColorGradient spriteAsset) { }
	// RVA: 0x69042fc VA: 0x7598f1c2fc
	private Void AddColorGradientPreset_Internal(Int32 hashCode, TextColorGradient spriteAsset) { }
	// RVA: 0x69043a0 VA: 0x7598f1c3a0
	public static Boolean TryGetFontAsset(Int32 hashCode, out FontAsset fontAsset) { }
	// RVA: 0x69043d0 VA: 0x7598f1c3d0
	private Boolean TryGetFontAssetInternal(Int32 hashCode, out FontAsset fontAsset) { }
	// RVA: 0x6904448 VA: 0x7598f1c448
	public static Boolean TryGetSpriteAsset(Int32 hashCode, out SpriteAsset spriteAsset) { }
	// RVA: 0x6904478 VA: 0x7598f1c478
	private Boolean TryGetSpriteAssetInternal(Int32 hashCode, out SpriteAsset spriteAsset) { }
	// RVA: 0x69044f0 VA: 0x7598f1c4f0
	public static Boolean TryGetColorGradientPreset(Int32 hashCode, out TextColorGradient gradientPreset) { }
	// RVA: 0x6904520 VA: 0x7598f1c520
	private Boolean TryGetColorGradientPresetInternal(Int32 hashCode, out TextColorGradient gradientPreset) { }
	// RVA: 0x6904598 VA: 0x7598f1c598
	public static Boolean TryGetMaterial(Int32 hashCode, out Material material) { }
	// RVA: 0x69045c8 VA: 0x7598f1c5c8
	private Boolean TryGetMaterialInternal(Int32 hashCode, out Material material) { }
	// RVA: 0x6903de8 VA: 0x7598f1bde8
	public Void .ctor() { }
}
```