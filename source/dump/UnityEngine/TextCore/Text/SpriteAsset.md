# SpriteAsset

**Namespace:** `UnityEngine.TextCore.Text`


## Properties

- `FaceInfo faceInfo`

- `Texture spriteSheet`


## Methods

- `FaceInfo get_faceInfo()`

- `Texture get_spriteSheet()`

- `Void Awake()`

- `Void UpdateLookupTables()`

- `Int32 GetSpriteIndexFromHashcode(Int32)`

- `Int32 GetSpriteIndexFromUnicode(UInt32)`

- `Int32 GetSpriteIndexFromName(String)`

- `Void SortGlyphTable()`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class SpriteAsset : TextAsset
{
	internal Dictionary`2 m_NameLookup; // 0x38
	internal Dictionary`2 m_GlyphIndexLookup; // 0x40
	internal FaceInfo m_FaceInfo; // 0x48
	internal Texture m_SpriteAtlasTexture; // 0xa8
	private List`1 m_SpriteCharacterTable; // 0xb0
	internal Dictionary`2 m_SpriteCharacterLookup; // 0xb8
	private List`1 m_SpriteGlyphTable; // 0xc0
	internal Dictionary`2 m_SpriteGlyphLookup; // 0xc8
	public List`1 fallbackSpriteAssets; // 0xd0
	internal Boolean m_IsSpriteAssetLookupTablesDirty; // 0xd8
	private static HashSet`1 k_searchedSpriteAssets; // 0x0

	public FaceInfo faceInfo { get; set; }
	public Texture spriteSheet { get; set; }
	public List`1 spriteCharacterTable { get; set; }
	public Dictionary`2 spriteCharacterLookupTable { get; set; }
	public List`1 spriteGlyphTable { get; set; }

	// RVA: 0x69052ec VA: 0x7598f1d2ec
	public FaceInfo get_faceInfo() { }
	// RVA: 0x6905308 VA: 0x7598f1d308
	internal Void set_faceInfo(FaceInfo value) { }
	// RVA: 0x690532c VA: 0x7598f1d32c
	public Texture get_spriteSheet() { }
	// RVA: 0x6905334 VA: 0x7598f1d334
	internal Void set_spriteSheet(Texture value) { }
	// RVA: 0x690533c VA: 0x7598f1d33c
	public List`1 get_spriteCharacterTable() { }
	// RVA: 0x6905888 VA: 0x7598f1d888
	internal Void set_spriteCharacterTable(List`1 value) { }
	// RVA: 0x6902b7c VA: 0x7598f1ab7c
	public Dictionary`2 get_spriteCharacterLookupTable() { }
	// RVA: 0x6905890 VA: 0x7598f1d890
	internal Void set_spriteCharacterLookupTable(Dictionary`2 value) { }
	// RVA: 0x6905898 VA: 0x7598f1d898
	public List`1 get_spriteGlyphTable() { }
	// RVA: 0x69058a0 VA: 0x7598f1d8a0
	internal Void set_spriteGlyphTable(List`1 value) { }
	// RVA: 0x69058a8 VA: 0x7598f1d8a8
	private Void Awake() { }
	// RVA: 0x6905360 VA: 0x7598f1d360
	public Void UpdateLookupTables() { }
	// RVA: 0x69058b4 VA: 0x7598f1d8b4
	public Int32 GetSpriteIndexFromHashcode(Int32 hashCode) { }
	// RVA: 0x690593c VA: 0x7598f1d93c
	public Int32 GetSpriteIndexFromUnicode(UInt32 unicode) { }
	// RVA: 0x69059d0 VA: 0x7598f1d9d0
	public Int32 GetSpriteIndexFromName(String name) { }
	// RVA: 0x6905a10 VA: 0x7598f1da10
	public static SpriteAsset SearchForSpriteByUnicode(SpriteAsset spriteAsset, UInt32 unicode, Boolean includeFallbacks, out Int32 spriteIndex) { }
	// RVA: 0x6905be8 VA: 0x7598f1dbe8
	private static SpriteAsset SearchForSpriteByUnicodeInternal(List`1 spriteAssets, UInt32 unicode, Boolean includeFallbacks, out Int32 spriteIndex) { }
	// RVA: 0x6905d88 VA: 0x7598f1dd88
	private static SpriteAsset SearchForSpriteByUnicodeInternal(SpriteAsset spriteAsset, UInt32 unicode, Boolean includeFallbacks, out Int32 spriteIndex) { }
	// RVA: 0x6905e38 VA: 0x7598f1de38
	public static SpriteAsset SearchForSpriteByHashCode(SpriteAsset spriteAsset, Int32 hashCode, Boolean includeFallbacks, out Int32 spriteIndex, TextSettings textSettings) { }
	// RVA: 0x690617c VA: 0x7598f1e17c
	private static SpriteAsset SearchForSpriteByHashCodeInternal(List`1 spriteAssets, Int32 hashCode, Boolean searchFallbacks, out Int32 spriteIndex) { }
	// RVA: 0x6906324 VA: 0x7598f1e324
	private static SpriteAsset SearchForSpriteByHashCodeInternal(SpriteAsset spriteAsset, Int32 hashCode, Boolean searchFallbacks, out Int32 spriteIndex) { }
	// RVA: 0x69063d4 VA: 0x7598f1e3d4
	public Void SortGlyphTable() { }
	// RVA: 0x690652c VA: 0x7598f1e52c
	internal Void SortCharacterTable() { }
	// RVA: 0x6906688 VA: 0x7598f1e688
	internal Void SortGlyphAndCharacterTables() { }
	// RVA: 0x69066a0 VA: 0x7598f1e6a0
	public Void .ctor() { }
}
```