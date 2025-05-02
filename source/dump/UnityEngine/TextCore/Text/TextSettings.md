# TextSettings

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `String m_Version`

- `FontAsset m_DefaultFontAsset`

- `String m_DefaultFontAssetPath`

- `Boolean m_MatchMaterialPreset`

- `Int32 m_MissingCharacterUnicode`

- `Boolean m_ClearDynamicDataOnBuild`

- `SpriteAsset m_DefaultSpriteAsset`

- `String m_DefaultSpriteAssetPath`

- `UInt32 m_MissingSpriteCharacterUnicode`

- `TextStyleSheet m_DefaultStyleSheet`

- `String m_StyleSheetsResourcePath`

- `String m_DefaultColorGradientPresetsPath`

- `UnicodeLineBreakingRules m_UnicodeLineBreakingRules`

- `Boolean m_DisplayWarnings`


## Properties

- `String version`

- `FontAsset defaultFontAsset`

- `String defaultFontAssetPath`

- `Boolean matchMaterialPreset`

- `Int32 missingCharacterUnicode`

- `Boolean clearDynamicDataOnBuild`

- `SpriteAsset defaultSpriteAsset`

- `String defaultSpriteAssetPath`

- `UInt32 missingSpriteCharacterUnicode`

- `TextStyleSheet defaultStyleSheet`

- `String styleSheetsResourcePath`

- `String defaultColorGradientPresetsPath`

- `UnicodeLineBreakingRules lineBreakingRules`

- `Boolean displayWarnings`


## Methods

- `String get_version()`

- `FontAsset get_defaultFontAsset()`

- `Void set_defaultFontAsset(FontAsset)`

- `String get_defaultFontAssetPath()`

- `Void set_defaultFontAssetPath(String)`

- `Void set_fallbackFontAssets(List`1)`

- `Boolean get_matchMaterialPreset()`

- `Void set_matchMaterialPreset(Boolean)`

- `Int32 get_missingCharacterUnicode()`

- `Void set_missingCharacterUnicode(Int32)`

- `Boolean get_clearDynamicDataOnBuild()`

- `Void set_clearDynamicDataOnBuild(Boolean)`

- `SpriteAsset get_defaultSpriteAsset()`

- `Void set_defaultSpriteAsset(SpriteAsset)`

- `String get_defaultSpriteAssetPath()`

- `Void set_defaultSpriteAssetPath(String)`

- `Void set_fallbackSpriteAssets(List`1)`

- `UInt32 get_missingSpriteCharacterUnicode()`

- `Void set_missingSpriteCharacterUnicode(UInt32)`

- `TextStyleSheet get_defaultStyleSheet()`

- `Void set_defaultStyleSheet(TextStyleSheet)`

- `String get_styleSheetsResourcePath()`

- `Void set_styleSheetsResourcePath(String)`

- `String get_defaultColorGradientPresetsPath()`

- `Void set_defaultColorGradientPresetsPath(String)`

- `UnicodeLineBreakingRules get_lineBreakingRules()`

- `Void set_lineBreakingRules(UnicodeLineBreakingRules)`

- `Boolean get_displayWarnings()`

- `Void set_displayWarnings(Boolean)`

- `Void InitializeFontReferenceLookup()`

- `FontAsset GetCachedFontAssetInternal(Font)`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class TextSettings : ScriptableObject
{
	protected String m_Version; // 0x18
	protected FontAsset m_DefaultFontAsset; // 0x20
	protected String m_DefaultFontAssetPath; // 0x28
	protected List`1 m_FallbackFontAssets; // 0x30
	protected Boolean m_MatchMaterialPreset; // 0x38
	protected Int32 m_MissingCharacterUnicode; // 0x3c
	protected Boolean m_ClearDynamicDataOnBuild; // 0x40
	protected SpriteAsset m_DefaultSpriteAsset; // 0x48
	protected String m_DefaultSpriteAssetPath; // 0x50
	protected List`1 m_FallbackSpriteAssets; // 0x58
	protected UInt32 m_MissingSpriteCharacterUnicode; // 0x60
	protected TextStyleSheet m_DefaultStyleSheet; // 0x68
	protected String m_StyleSheetsResourcePath; // 0x70
	protected String m_DefaultColorGradientPresetsPath; // 0x78
	protected UnicodeLineBreakingRules m_UnicodeLineBreakingRules; // 0x80
	protected Boolean m_DisplayWarnings; // 0x88
	internal Dictionary`2 m_FontLookup; // 0x90
	private List`1 m_FontReferences; // 0x98

	public String version { get; set; }
	public FontAsset defaultFontAsset { get; set; }
	public String defaultFontAssetPath { get; set; }
	public List`1 fallbackFontAssets { get; set; }
	public Boolean matchMaterialPreset { get; set; }
	public Int32 missingCharacterUnicode { get; set; }
	public Boolean clearDynamicDataOnBuild { get; set; }
	public SpriteAsset defaultSpriteAsset { get; set; }
	public String defaultSpriteAssetPath { get; set; }
	public List`1 fallbackSpriteAssets { get; set; }
	public UInt32 missingSpriteCharacterUnicode { get; set; }
	public TextStyleSheet defaultStyleSheet { get; set; }
	public String styleSheetsResourcePath { get; set; }
	public String defaultColorGradientPresetsPath { get; set; }
	public UnicodeLineBreakingRules lineBreakingRules { get; set; }
	public Boolean displayWarnings { get; set; }

	// RVA: 0x690dae0 VA: 0x7598f25ae0
	public String get_version() { }
	// RVA: 0x690dae8 VA: 0x7598f25ae8
	internal Void set_version(String value) { }
	// RVA: 0x690daf0 VA: 0x7598f25af0
	public FontAsset get_defaultFontAsset() { }
	// RVA: 0x690daf8 VA: 0x7598f25af8
	public Void set_defaultFontAsset(FontAsset value) { }
	// RVA: 0x690db00 VA: 0x7598f25b00
	public String get_defaultFontAssetPath() { }
	// RVA: 0x690db08 VA: 0x7598f25b08
	public Void set_defaultFontAssetPath(String value) { }
	// RVA: 0x690db10 VA: 0x7598f25b10
	public List`1 get_fallbackFontAssets() { }
	// RVA: 0x690db18 VA: 0x7598f25b18
	public Void set_fallbackFontAssets(List`1 value) { }
	// RVA: 0x690db20 VA: 0x7598f25b20
	public Boolean get_matchMaterialPreset() { }
	// RVA: 0x690db28 VA: 0x7598f25b28
	public Void set_matchMaterialPreset(Boolean value) { }
	// RVA: 0x690db34 VA: 0x7598f25b34
	public Int32 get_missingCharacterUnicode() { }
	// RVA: 0x690db3c VA: 0x7598f25b3c
	public Void set_missingCharacterUnicode(Int32 value) { }
	// RVA: 0x690db44 VA: 0x7598f25b44
	public Boolean get_clearDynamicDataOnBuild() { }
	// RVA: 0x690db4c VA: 0x7598f25b4c
	public Void set_clearDynamicDataOnBuild(Boolean value) { }
	// RVA: 0x690db58 VA: 0x7598f25b58
	public SpriteAsset get_defaultSpriteAsset() { }
	// RVA: 0x690db60 VA: 0x7598f25b60
	public Void set_defaultSpriteAsset(SpriteAsset value) { }
	// RVA: 0x690db68 VA: 0x7598f25b68
	public String get_defaultSpriteAssetPath() { }
	// RVA: 0x690db70 VA: 0x7598f25b70
	public Void set_defaultSpriteAssetPath(String value) { }
	// RVA: 0x690db78 VA: 0x7598f25b78
	public List`1 get_fallbackSpriteAssets() { }
	// RVA: 0x690db80 VA: 0x7598f25b80
	public Void set_fallbackSpriteAssets(List`1 value) { }
	// RVA: 0x690db88 VA: 0x7598f25b88
	public UInt32 get_missingSpriteCharacterUnicode() { }
	// RVA: 0x690db90 VA: 0x7598f25b90
	public Void set_missingSpriteCharacterUnicode(UInt32 value) { }
	// RVA: 0x690db98 VA: 0x7598f25b98
	public TextStyleSheet get_defaultStyleSheet() { }
	// RVA: 0x690dba0 VA: 0x7598f25ba0
	public Void set_defaultStyleSheet(TextStyleSheet value) { }
	// RVA: 0x690dba8 VA: 0x7598f25ba8
	public String get_styleSheetsResourcePath() { }
	// RVA: 0x690dbb0 VA: 0x7598f25bb0
	public Void set_styleSheetsResourcePath(String value) { }
	// RVA: 0x690dbb8 VA: 0x7598f25bb8
	public String get_defaultColorGradientPresetsPath() { }
	// RVA: 0x690dbc0 VA: 0x7598f25bc0
	public Void set_defaultColorGradientPresetsPath(String value) { }
	// RVA: 0x690dbc8 VA: 0x7598f25bc8
	public UnicodeLineBreakingRules get_lineBreakingRules() { }
	// RVA: 0x690dfb0 VA: 0x7598f25fb0
	public Void set_lineBreakingRules(UnicodeLineBreakingRules value) { }
	// RVA: 0x690dfb8 VA: 0x7598f25fb8
	public Boolean get_displayWarnings() { }
	// RVA: 0x690dfc0 VA: 0x7598f25fc0
	public Void set_displayWarnings(Boolean value) { }
	// RVA: 0x690dfcc VA: 0x7598f25fcc
	protected Void InitializeFontReferenceLookup() { }
	// RVA: 0x690e214 VA: 0x7598f26214
	protected FontAsset GetCachedFontAssetInternal(Font font) { }
	// RVA: 0x690e5b4 VA: 0x7598f265b4
	public Void .ctor() { }
}
```