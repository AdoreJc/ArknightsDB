# FontAsset

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `Font m_SourceFontFile`

- `AtlasPopulationMode m_AtlasPopulationMode`

- `Int32 m_FamilyNameHashCode`

- `Int32 m_StyleNameHashCode`

- `Boolean m_IsMultiAtlasTexturesEnabled`

- `Boolean m_ClearDynamicDataOnBuild`


## Properties

- `Font sourceFontFile`

- `AtlasPopulationMode atlasPopulationMode`

- `FaceInfo faceInfo`

- `Texture2D atlasTexture`

- `Int32 atlasTextureCount`

- `Boolean isMultiAtlasTexturesEnabled`

- `Int32 atlasWidth`

- `Int32 atlasHeight`

- `Int32 atlasPadding`

- `GlyphRenderMode atlasRenderMode`

- `FontFeatureTable fontFeatureTable`

- `FontAssetCreationEditorSettings fontAssetCreationEditorSettings`

- `Single regularStyleWeight`

- `Single regularStyleSpacing`

- `Single boldStyleWeight`

- `Single boldStyleSpacing`

- `Byte italicStyleSlant`

- `Byte tabMultiple`


## Methods

- `Font get_sourceFontFile()`

- `AtlasPopulationMode get_atlasPopulationMode()`

- `Void set_atlasPopulationMode(AtlasPopulationMode)`

- `FaceInfo get_faceInfo()`

- `Void set_faceInfo(FaceInfo)`

- `Texture2D get_atlasTexture()`

- `Void set_atlasTextures(Texture2D[])`

- `Int32 get_atlasTextureCount()`

- `Boolean get_isMultiAtlasTexturesEnabled()`

- `Void set_isMultiAtlasTexturesEnabled(Boolean)`

- `Int32 get_atlasWidth()`

- `Int32 get_atlasHeight()`

- `Int32 get_atlasPadding()`

- `GlyphRenderMode get_atlasRenderMode()`

- `FontFeatureTable get_fontFeatureTable()`

- `Void set_fallbackFontAssetTable(List`1)`

- `FontAssetCreationEditorSettings get_fontAssetCreationEditorSettings()`

- `Void set_fontAssetCreationEditorSettings(FontAssetCreationEditorSettings)`

- `Single get_regularStyleWeight()`

- `Void set_regularStyleWeight(Single)`

- `Single get_regularStyleSpacing()`

- `Void set_regularStyleSpacing(Single)`

- `Single get_boldStyleWeight()`

- `Void set_boldStyleWeight(Single)`

- `Single get_boldStyleSpacing()`

- `Void set_boldStyleSpacing(Single)`

- `Byte get_italicStyleSlant()`

- `Void set_italicStyleSlant(Byte)`

- `Byte get_tabMultiple()`

- `Void set_tabMultiple(Byte)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void ReadFontAssetDefinition()`

- `Void AddSynthesizedCharacter(UInt32, Boolean, Boolean)`

- `FontEngineError LoadFontFace()`

- `Boolean HasCharacter(Int32)`

- `Boolean HasCharacter(Char, Boolean, Boolean)`

- `Boolean HasCharacter_Internal(UInt32, Boolean, Boolean)`

- `Boolean HasCharacters(String, out)`

- `Boolean HasCharacters(String, out, Boolean, Boolean)`

- `Boolean HasCharacters(String)`

- `Boolean TryAddCharacters(UInt32[], Boolean)`

- `Boolean TryAddCharacters(UInt32[], out, Boolean)`

- `Boolean TryAddCharacters(String, Boolean)`

- `Boolean TryAddCharacters(String, out, Boolean)`

- `Boolean TryAddGlyphsToNewAtlasTexture()`

- `Void SetupNewAtlasTexture()`

- `Void CopyListDataToArray(List`1, ref)`

- `Void ClearFontAssetData(Boolean)`

- `Void DestroyAtlasTextures()`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class FontAsset : TextAsset
{
	internal String m_SourceFontFileGUID; // 0x38
	private Font m_SourceFontFile; // 0x40
	private AtlasPopulationMode m_AtlasPopulationMode; // 0x48
	internal Boolean InternalDynamicOS; // 0x4c
	internal FaceInfo m_FaceInfo; // 0x50
	private Int32 m_FamilyNameHashCode; // 0xb0
	private Int32 m_StyleNameHashCode; // 0xb4
	private FontWeightPair[] m_FontWeightTable; // 0xb8
	internal List`1 m_GlyphTable; // 0xc0
	internal Dictionary`2 m_GlyphLookupDictionary; // 0xc8
	internal List`1 m_CharacterTable; // 0xd0
	internal Dictionary`2 m_CharacterLookupDictionary; // 0xd8
	internal Texture2D m_AtlasTexture; // 0xe0
	internal Texture2D[] m_AtlasTextures; // 0xe8
	internal Int32 m_AtlasTextureIndex; // 0xf0
	private Boolean m_IsMultiAtlasTexturesEnabled; // 0xf4
	private Boolean m_ClearDynamicDataOnBuild; // 0xf5
	internal Int32 m_AtlasWidth; // 0xf8
	internal Int32 m_AtlasHeight; // 0xfc
	internal Int32 m_AtlasPadding; // 0x100
	internal GlyphRenderMode m_AtlasRenderMode; // 0x104
	private List`1 m_UsedGlyphRects; // 0x108
	private List`1 m_FreeGlyphRects; // 0x110
	internal FontFeatureTable m_FontFeatureTable; // 0x118
	internal List`1 m_FallbackFontAssetTable; // 0x120
	internal FontAssetCreationEditorSettings m_fontAssetCreationEditorSettings; // 0x128
	internal Single m_RegularStyleWeight; // 0x178
	internal Single m_RegularStyleSpacing; // 0x17c
	internal Single m_BoldStyleWeight; // 0x180
	internal Single m_BoldStyleSpacing; // 0x184
	internal Byte m_ItalicStyleSlant; // 0x188
	internal Byte m_TabMultiple; // 0x189
	internal Boolean IsFontAssetLookupTablesDirty; // 0x18a
	private static ProfilerMarker k_ReadFontAssetDefinitionMarker; // 0x0
	private static ProfilerMarker k_AddSynthesizedCharactersMarker; // 0x8
	private static ProfilerMarker k_TryAddCharacterMarker; // 0x10
	private static ProfilerMarker k_TryAddCharactersMarker; // 0x18
	private static ProfilerMarker k_UpdateGlyphAdjustmentRecordsMarker; // 0x20
	private static ProfilerMarker k_ClearFontAssetDataMarker; // 0x28
	private static ProfilerMarker k_UpdateFontAssetDataMarker; // 0x30
	private static String s_DefaultMaterialSuffix; // 0x38
	private static HashSet`1 k_SearchedFontAssetLookup; // 0x40
	private static List`1 k_FontAssets_FontFeaturesUpdateQueue; // 0x48
	private static HashSet`1 k_FontAssets_FontFeaturesUpdateQueueLookup; // 0x50
	private static List`1 k_FontAssets_AtlasTexturesUpdateQueue; // 0x58
	private static HashSet`1 k_FontAssets_AtlasTexturesUpdateQueueLookup; // 0x60
	private List`1 m_GlyphsToRender; // 0x190
	private List`1 m_GlyphsRendered; // 0x198
	private List`1 m_GlyphIndexList; // 0x1a0
	private List`1 m_GlyphIndexListNewlyAdded; // 0x1a8
	internal List`1 m_GlyphsToAdd; // 0x1b0
	internal HashSet`1 m_GlyphsToAddLookup; // 0x1b8
	internal List`1 m_CharactersToAdd; // 0x1c0
	internal HashSet`1 m_CharactersToAddLookup; // 0x1c8
	internal List`1 s_MissingCharacterList; // 0x1d0
	internal HashSet`1 m_MissingUnicodesFromFontFile; // 0x1d8
	internal static UInt32[] k_GlyphIndexArray; // 0x68

	public Font sourceFontFile { get; set; }
	public AtlasPopulationMode atlasPopulationMode { get; set; }
	public FaceInfo faceInfo { get; set; }
	internal Int32 familyNameHashCode { get; set; }
	internal Int32 styleNameHashCode { get; set; }
	public FontWeightPair[] fontWeightTable { get; set; }
	public List`1 glyphTable { get; set; }
	public Dictionary`2 glyphLookupTable { get; }
	public List`1 characterTable { get; set; }
	public Dictionary`2 characterLookupTable { get; }
	public Texture2D atlasTexture { get; }
	public Texture2D[] atlasTextures { get; set; }
	public Int32 atlasTextureCount { get; }
	public Boolean isMultiAtlasTexturesEnabled { get; set; }
	internal Boolean clearDynamicDataOnBuild { get; set; }
	public Int32 atlasWidth { get; set; }
	public Int32 atlasHeight { get; set; }
	public Int32 atlasPadding { get; set; }
	public GlyphRenderMode atlasRenderMode { get; set; }
	internal List`1 usedGlyphRects { get; set; }
	internal List`1 freeGlyphRects { get; set; }
	public FontFeatureTable fontFeatureTable { get; set; }
	public List`1 fallbackFontAssetTable { get; set; }
	public FontAssetCreationEditorSettings fontAssetCreationEditorSettings { get; set; }
	public Single regularStyleWeight { get; set; }
	public Single regularStyleSpacing { get; set; }
	public Single boldStyleWeight { get; set; }
	public Single boldStyleSpacing { get; set; }
	public Byte italicStyleSlant { get; set; }
	public Byte tabMultiple { get; set; }

	// RVA: 0x68f9d48 VA: 0x7598f11d48
	public Font get_sourceFontFile() { }
	// RVA: 0x68f9d50 VA: 0x7598f11d50
	internal Void set_sourceFontFile(Font value) { }
	// RVA: 0x68f9d58 VA: 0x7598f11d58
	public AtlasPopulationMode get_atlasPopulationMode() { }
	// RVA: 0x68f9d60 VA: 0x7598f11d60
	public Void set_atlasPopulationMode(AtlasPopulationMode value) { }
	// RVA: 0x68f9d68 VA: 0x7598f11d68
	public FaceInfo get_faceInfo() { }
	// RVA: 0x68f9d84 VA: 0x7598f11d84
	public Void set_faceInfo(FaceInfo value) { }
	// RVA: 0x68f9da8 VA: 0x7598f11da8
	internal Int32 get_familyNameHashCode() { }
	// RVA: 0x68f9dd8 VA: 0x7598f11dd8
	internal Void set_familyNameHashCode(Int32 value) { }
	// RVA: 0x68f9de0 VA: 0x7598f11de0
	internal Int32 get_styleNameHashCode() { }
	// RVA: 0x68f9e10 VA: 0x7598f11e10
	internal Void set_styleNameHashCode(Int32 value) { }
	// RVA: 0x68f9e18 VA: 0x7598f11e18
	public FontWeightPair[] get_fontWeightTable() { }
	// RVA: 0x68f9e20 VA: 0x7598f11e20
	internal Void set_fontWeightTable(FontWeightPair[] value) { }
	// RVA: 0x68f9e28 VA: 0x7598f11e28
	public List`1 get_glyphTable() { }
	// RVA: 0x68f9e30 VA: 0x7598f11e30
	internal Void set_glyphTable(List`1 value) { }
	// RVA: 0x68f9e38 VA: 0x7598f11e38
	public Dictionary`2 get_glyphLookupTable() { }
	// RVA: 0x68fa22c VA: 0x7598f1222c
	public List`1 get_characterTable() { }
	// RVA: 0x68fa234 VA: 0x7598f12234
	internal Void set_characterTable(List`1 value) { }
	// RVA: 0x68fa23c VA: 0x7598f1223c
	public Dictionary`2 get_characterLookupTable() { }
	// RVA: 0x68fa260 VA: 0x7598f12260
	public Texture2D get_atlasTexture() { }
	// RVA: 0x68fa300 VA: 0x7598f12300
	public Texture2D[] get_atlasTextures() { }
	// RVA: 0x68fa308 VA: 0x7598f12308
	public Void set_atlasTextures(Texture2D[] value) { }
	// RVA: 0x68fa310 VA: 0x7598f12310
	public Int32 get_atlasTextureCount() { }
	// RVA: 0x68fa31c VA: 0x7598f1231c
	public Boolean get_isMultiAtlasTexturesEnabled() { }
	// RVA: 0x68fa324 VA: 0x7598f12324
	public Void set_isMultiAtlasTexturesEnabled(Boolean value) { }
	// RVA: 0x68fa330 VA: 0x7598f12330
	internal Boolean get_clearDynamicDataOnBuild() { }
	// RVA: 0x68fa338 VA: 0x7598f12338
	internal Void set_clearDynamicDataOnBuild(Boolean value) { }
	// RVA: 0x68fa344 VA: 0x7598f12344
	public Int32 get_atlasWidth() { }
	// RVA: 0x68fa34c VA: 0x7598f1234c
	internal Void set_atlasWidth(Int32 value) { }
	// RVA: 0x68fa354 VA: 0x7598f12354
	public Int32 get_atlasHeight() { }
	// RVA: 0x68fa35c VA: 0x7598f1235c
	internal Void set_atlasHeight(Int32 value) { }
	// RVA: 0x68fa364 VA: 0x7598f12364
	public Int32 get_atlasPadding() { }
	// RVA: 0x68fa36c VA: 0x7598f1236c
	internal Void set_atlasPadding(Int32 value) { }
	// RVA: 0x68fa374 VA: 0x7598f12374
	public GlyphRenderMode get_atlasRenderMode() { }
	// RVA: 0x68fa37c VA: 0x7598f1237c
	internal Void set_atlasRenderMode(GlyphRenderMode value) { }
	// RVA: 0x68fa384 VA: 0x7598f12384
	internal List`1 get_usedGlyphRects() { }
	// RVA: 0x68fa38c VA: 0x7598f1238c
	internal Void set_usedGlyphRects(List`1 value) { }
	// RVA: 0x68fa39c VA: 0x7598f1239c
	internal List`1 get_freeGlyphRects() { }
	// RVA: 0x68fa3a4 VA: 0x7598f123a4
	internal Void set_freeGlyphRects(List`1 value) { }
	// RVA: 0x68fa3b4 VA: 0x7598f123b4
	public FontFeatureTable get_fontFeatureTable() { }
	// RVA: 0x68fa3bc VA: 0x7598f123bc
	internal Void set_fontFeatureTable(FontFeatureTable value) { }
	// RVA: 0x68fa3cc VA: 0x7598f123cc
	public List`1 get_fallbackFontAssetTable() { }
	// RVA: 0x68fa3d4 VA: 0x7598f123d4
	public Void set_fallbackFontAssetTable(List`1 value) { }
	// RVA: 0x68fa3e4 VA: 0x7598f123e4
	public FontAssetCreationEditorSettings get_fontAssetCreationEditorSettings() { }
	// RVA: 0x68fa400 VA: 0x7598f12400
	public Void set_fontAssetCreationEditorSettings(FontAssetCreationEditorSettings value) { }
	// RVA: 0x68fa424 VA: 0x7598f12424
	public Single get_regularStyleWeight() { }
	// RVA: 0x68fa42c VA: 0x7598f1242c
	public Void set_regularStyleWeight(Single value) { }
	// RVA: 0x68fa434 VA: 0x7598f12434
	public Single get_regularStyleSpacing() { }
	// RVA: 0x68fa43c VA: 0x7598f1243c
	public Void set_regularStyleSpacing(Single value) { }
	// RVA: 0x68fa444 VA: 0x7598f12444
	public Single get_boldStyleWeight() { }
	// RVA: 0x68fa44c VA: 0x7598f1244c
	public Void set_boldStyleWeight(Single value) { }
	// RVA: 0x68fa454 VA: 0x7598f12454
	public Single get_boldStyleSpacing() { }
	// RVA: 0x68fa45c VA: 0x7598f1245c
	public Void set_boldStyleSpacing(Single value) { }
	// RVA: 0x68fa464 VA: 0x7598f12464
	public Byte get_italicStyleSlant() { }
	// RVA: 0x68fa46c VA: 0x7598f1246c
	public Void set_italicStyleSlant(Byte value) { }
	// RVA: 0x68fa474 VA: 0x7598f12474
	public Byte get_tabMultiple() { }
	// RVA: 0x68fa47c VA: 0x7598f1247c
	public Void set_tabMultiple(Byte value) { }
	// RVA: 0x68fa484 VA: 0x7598f12484
	public static FontAsset CreateFontAsset(String familyName, String styleName, Int32 pointSize) { }
	// RVA: 0x68fa764 VA: 0x7598f12764
	private static FontAsset CreateFontAsset(String fontFilePath, Int32 faceIndex, Int32 samplingPointSize, Int32 atlasPadding, GlyphRenderMode renderMode, Int32 atlasWidth, Int32 atlasHeight, AtlasPopulationMode atlasPopulationMode, Boolean enableMultiAtlasSupport) { }
	// RVA: 0x68fad98 VA: 0x7598f12d98
	public static FontAsset CreateFontAsset(Font font) { }
	// RVA: 0x68fae14 VA: 0x7598f12e14
	public static FontAsset CreateFontAsset(Font font, Int32 samplingPointSize, Int32 atlasPadding, GlyphRenderMode renderMode, Int32 atlasWidth, Int32 atlasHeight, AtlasPopulationMode atlasPopulationMode, Boolean enableMultiAtlasSupport) { }
	// RVA: 0x68faed4 VA: 0x7598f12ed4
	private static FontAsset CreateFontAsset(Font font, Int32 faceIndex, Int32 samplingPointSize, Int32 atlasPadding, GlyphRenderMode renderMode, Int32 atlasWidth, Int32 atlasHeight, AtlasPopulationMode atlasPopulationMode, Boolean enableMultiAtlasSupport) { }
	// RVA: 0x68fa8e0 VA: 0x7598f128e0
	private static FontAsset CreateFontAssetInstance(Font font, Int32 atlasPadding, GlyphRenderMode renderMode, Int32 atlasWidth, Int32 atlasHeight, AtlasPopulationMode atlasPopulationMode, Boolean enableMultiAtlasSupport) { }
	// RVA: 0x68fb0e8 VA: 0x7598f130e8
	private Void Awake() { }
	// RVA: 0x68fb0ec VA: 0x7598f130ec
	private Void OnDestroy() { }
	// RVA: 0x68f9e5c VA: 0x7598f11e5c
	public Void ReadFontAssetDefinition() { }
	// RVA: 0x68fb214 VA: 0x7598f13214
	internal Void InitializeDictionaryLookupTables() { }
	// RVA: 0x68fb470 VA: 0x7598f13470
	internal Void InitializeGlyphLookupDictionary() { }
	// RVA: 0x68fb730 VA: 0x7598f13730
	internal Void InitializeCharacterLookupDictionary() { }
	// RVA: 0x68fb8fc VA: 0x7598f138fc
	internal Void InitializeGlyphPaidAdjustmentRecordsLookupDictionary() { }
	// RVA: 0x68fb234 VA: 0x7598f13234
	internal Void AddSynthesizedCharactersAndFaceMetrics() { }
	// RVA: 0x68fbc54 VA: 0x7598f13c54
	private Void AddSynthesizedCharacter(UInt32 unicode, Boolean isFontFaceLoaded, Boolean addImmediately) { }
	// RVA: 0x68fbea8 VA: 0x7598f13ea8
	internal Void AddCharacterToLookupCache(UInt32 unicode, Character character) { }
	// RVA: 0x68fbb4c VA: 0x7598f13b4c
	private FontEngineError LoadFontFace() { }
	// RVA: 0x68fbf10 VA: 0x7598f13f10
	internal Void SortCharacterTable() { }
	// RVA: 0x68fc06c VA: 0x7598f1406c
	internal Void SortGlyphTable() { }
	// RVA: 0x68fc1c8 VA: 0x7598f141c8
	internal Void SortFontFeatureTable() { }
	// RVA: 0x68fc3f8 VA: 0x7598f143f8
	internal Void SortAllTables() { }
	// RVA: 0x68fc420 VA: 0x7598f14420
	public Boolean HasCharacter(Int32 character) { }
	// RVA: 0x68fc480 VA: 0x7598f14480
	public Boolean HasCharacter(Char character, Boolean searchFallbacks, Boolean tryAddCharacter) { }
	// RVA: 0x68fd21c VA: 0x7598f1521c
	private Boolean HasCharacter_Internal(UInt32 character, Boolean searchFallbacks, Boolean tryAddCharacter) { }
	// RVA: 0x68fd440 VA: 0x7598f15440
	public Boolean HasCharacters(String text, out List`1 missingCharacters) { }
	// RVA: 0x68fd600 VA: 0x7598f15600
	public Boolean HasCharacters(String text, out UInt32[] missingCharacters, Boolean searchFallbacks, Boolean tryAddCharacter) { }
	// RVA: 0x68fda54 VA: 0x7598f15a54
	public Boolean HasCharacters(String text) { }
	// RVA: 0x68fdb08 VA: 0x7598f15b08
	public static String GetCharacters(FontAsset fontAsset) { }
	// RVA: 0x68fdc14 VA: 0x7598f15c14
	public static Int32[] GetCharactersArray(FontAsset fontAsset) { }
	// RVA: 0x68fdcf8 VA: 0x7598f15cf8
	internal UInt32 GetGlyphIndex(UInt32 unicode) { }
	// RVA: 0x68fddd4 VA: 0x7598f15dd4
	internal static Void RegisterFontAssetForFontFeatureUpdate(FontAsset fontAsset) { }
	// RVA: 0x68fdf44 VA: 0x7598f15f44
	internal static Void UpdateFontFeaturesForFontAssetsInQueue() { }
	// RVA: 0x68fe480 VA: 0x7598f16480
	internal static Void RegisterAtlasTextureForApply(Texture2D texture) { }
	// RVA: 0x68fe5c0 VA: 0x7598f165c0
	internal static Void UpdateAtlasTexturesInQueue() { }
	// RVA: 0x68fe744 VA: 0x7598f16744
	internal static Void UpdateFontAssetInUpdateQueue() { }
	// RVA: 0x68fe794 VA: 0x7598f16794
	public Boolean TryAddCharacters(UInt32[] unicodes, Boolean includeFontFeatures) { }
	// RVA: 0x68fe7b4 VA: 0x7598f167b4
	public Boolean TryAddCharacters(UInt32[] unicodes, out UInt32[] missingUnicodes, Boolean includeFontFeatures) { }
	// RVA: 0x68ff99c VA: 0x7598f1799c
	public Boolean TryAddCharacters(String characters, Boolean includeFontFeatures) { }
	// RVA: 0x68ff9bc VA: 0x7598f179bc
	public Boolean TryAddCharacters(String characters, out String missingCharacters, Boolean includeFontFeatures) { }
	// RVA: 0x68fc7a4 VA: 0x7598f147a4
	internal Boolean TryAddCharacterInternal(UInt32 unicode, out Character character, Boolean shouldGetFontFeatures) { }
	// RVA: 0x69008dc VA: 0x7598f188dc
	internal Boolean TryGetCharacter_and_QueueRenderToTexture(UInt32 unicode, out Character character, Boolean shouldGetFontFeatures) { }
	// RVA: 0x6900f00 VA: 0x7598f18f00
	internal Void TryAddGlyphsToAtlasTextures() { }
	// RVA: 0x68ff4e0 VA: 0x7598f174e0
	private Boolean TryAddGlyphsToNewAtlasTexture() { }
	// RVA: 0x69006a4 VA: 0x7598f186a4
	private Void SetupNewAtlasTexture() { }
	// RVA: 0x6900f04 VA: 0x7598f18f04
	internal Void UpdateAtlasTexture() { }
	// RVA: 0x68fe0bc VA: 0x7598f160bc
	internal Void UpdateGlyphAdjustmentRecords() { }
	// RVA: 0x6901160 VA: 0x7598f19160
	internal Void UpdateGlyphAdjustmentRecords(UInt32[] glyphIndexes) { }
	// RVA: 0x69014fc VA: 0x7598f194fc
	internal Void UpdateGlyphAdjustmentRecords(List`1 glyphIndexes) { }
	// RVA: 0x6901500 VA: 0x7598f19500
	internal Void UpdateGlyphAdjustmentRecords(List`1 newGlyphIndexes, List`1 allGlyphIndexes) { }
	// RVA: 0x VA: 0x0
	private Void CopyListDataToArray(List`1 srcList, ref T[] dstArray) { }
	// RVA: 0x6901504 VA: 0x7598f19504
	public Void ClearFontAssetData(Boolean setAtlasSizeToZero) { }
	// RVA: 0x6901990 VA: 0x7598f19990
	internal Void ClearFontAssetDataInternal() { }
	// RVA: 0x69019ac VA: 0x7598f199ac
	internal Void UpdateFontAssetData() { }
	// RVA: 0x69015a0 VA: 0x7598f195a0
	internal Void ClearFontAssetTables() { }
	// RVA: 0x6901798 VA: 0x7598f19798
	internal Void ClearAtlasTextures(Boolean setAtlasSizeToZero) { }
	// RVA: 0x68fb150 VA: 0x7598f13150
	private Void DestroyAtlasTextures() { }
	// RVA: 0x6901b34 VA: 0x7598f19b34
	public Void .ctor() { }
	// RVA: 0x6901e8c VA: 0x7598f19e8c
	private static Void .cctor() { }
}
```