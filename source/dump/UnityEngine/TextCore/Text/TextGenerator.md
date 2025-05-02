# TextGenerator

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `Single m_MarginWidth`

- `Single m_MarginHeight`

- `Single m_PreferredWidth`

- `Single m_PreferredHeight`

- `FontAsset m_CurrentFontAsset`

- `Material m_CurrentMaterial`

- `Int32 m_CurrentMaterialIndex`

- `Single m_Padding`

- `SpriteAsset m_CurrentSpriteAsset`

- `Int32 m_TotalCharacterCount`

- `Single m_FontScale`

- `Single m_FontSize`

- `Single m_FontScaleMultiplier`

- `Single m_CurrentFontSize`

- `FontStyles m_FontStyleInternal`

- `FontStyleStack m_FontStyleStack`

- `TextFontWeight m_FontWeightInternal`

- `TextAlignment m_LineJustification`

- `Single m_BaselineOffset`

- `Color32 m_FontColor32`

- `Color32 m_HtmlColor`

- `Color32 m_UnderlineColor`

- `Color32 m_StrikethroughColor`

- `TextColorGradient m_ColorGradientPreset`

- `Boolean m_IsFxMatrixSet`

- `Single m_LineOffset`

- `Single m_LineHeight`

- `Single m_CSpacing`

- `Single m_MonoSpacing`

- `Single m_XAdvance`

- `Single m_TagLineIndent`

- `Single m_TagIndent`

- `Boolean m_TagNoParsing`

- `Int32 m_CharacterCount`

- `Int32 m_FirstCharacterOfLine`

- `Int32 m_LastCharacterOfLine`

- `Int32 m_FirstVisibleCharacterOfLine`

- `Int32 m_LastVisibleCharacterOfLine`

- `Single m_MaxLineAscender`

- `Single m_MaxLineDescender`

- `Int32 m_LineNumber`

- `Int32 m_LineVisibleCharacterCount`

- `Int32 m_FirstOverflowCharacterIndex`

- `Int32 m_PageNumber`

- `Single m_MarginLeft`

- `Single m_MarginRight`

- `Single m_Width`

- `Extents m_MeshExtents`

- `Single m_MaxCapHeight`

- `Single m_MaxAscender`

- `Single m_MaxDescender`

- `Boolean m_IsNewPage`

- `Boolean m_IsNonBreakingSpace`

- `WordWrapState m_SavedWordWrapState`

- `WordWrapState m_SavedLineState`

- `Int32 m_LoopCountA`

- `TextElementType m_TextElementType`

- `Boolean m_IsParsingText`

- `Int32 m_SpriteIndex`

- `Color32 m_SpriteColor`

- `TextElement m_CachedTextElement`

- `Color32 m_HighlightColor`

- `Single m_CharWidthAdjDelta`

- `Matrix4x4 m_FxMatrix`

- `Single m_MaxFontSize`

- `Single m_MinFontSize`

- `Boolean m_IsCharacterWrappingEnabled`

- `Single m_StartOfLineAscender`

- `Single m_LineSpacingDelta`

- `Boolean m_IsMaskingEnabled`

- `Int32 m_SpriteCount`

- `Int32 m_SpriteAnimationId`

- `Boolean m_IsCalculatingPreferredValues`

- `SpriteAsset m_DefaultSpriteAsset`

- `Boolean m_TintSprite`

- `SpecialCharacter m_Ellipsis`

- `SpecialCharacter m_Underline`

- `Boolean m_IsUsingBold`

- `Boolean m_IsSdfShader`

- `Int32 m_RecursiveCount`


## Methods

- `Void Prepare(TextGenerationSettings, TextInfo)`

- `Void GenerateTextMesh(TextGenerationSettings, TextInfo)`

- `Void SaveWordWrappingState(ref, Int32, Int32, TextInfo)`

- `Int32 RestoreWordWrappingState(ref, TextInfo)`

- `Boolean ValidateHtmlTag(Int32[], Int32, out, TextGenerationSettings, TextInfo)`

- `Void SaveGlyphVertexInfo(Single, Single, Color32, TextGenerationSettings, TextInfo)`

- `Void SaveSpriteVertexInfo(Color32, TextGenerationSettings, TextInfo)`

- `Void DrawUnderlineMesh(Vector3, Vector3, ref, Single, Single, Single, Single, Color32, TextGenerationSettings, TextInfo)`

- `Void DrawTextHighlight(Vector3, Vector3, ref, Color32, TextGenerationSettings, TextInfo)`

- `Void EnableMasking()`

- `Void DisableMasking()`

- `Void SetArraySizes(Int32[], TextGenerationSettings, TextInfo)`

- `Void ComputeMarginSize(Rect, Vector4)`

- `Void GetSpecialCharacters(TextGenerationSettings)`

- `Void GetEllipsisSpecialCharacter(TextGenerationSettings)`

- `Void GetUnderlineSpecialCharacter(TextGenerationSettings)`

- `Single GetPaddingForMaterial(Material, Boolean)`

- `Vector2 GetPreferredValuesInternal(TextGenerationSettings, TextInfo)`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
internal class TextGenerator
{
	private static TextGenerator s_TextGenerator; // 0x0
	private Vector3[] m_RectTransformCorners; // 0x10
	private Single m_MarginWidth; // 0x18
	private Single m_MarginHeight; // 0x1c
	private Int32[] m_CharBuffer; // 0x20
	private Single m_PreferredWidth; // 0x28
	private Single m_PreferredHeight; // 0x2c
	private FontAsset m_CurrentFontAsset; // 0x30
	private Material m_CurrentMaterial; // 0x38
	private Int32 m_CurrentMaterialIndex; // 0x40
	private TextProcessingStack`1 m_MaterialReferenceStack; // 0x48
	private Single m_Padding; // 0xa0
	private SpriteAsset m_CurrentSpriteAsset; // 0xa8
	private Int32 m_TotalCharacterCount; // 0xb0
	private Single m_FontScale; // 0xb4
	private Single m_FontSize; // 0xb8
	private Single m_FontScaleMultiplier; // 0xbc
	private Single m_CurrentFontSize; // 0xc0
	private TextProcessingStack`1 m_SizeStack; // 0xc8
	private FontStyles m_FontStyleInternal; // 0xe8
	private FontStyleStack m_FontStyleStack; // 0xec
	private TextFontWeight m_FontWeightInternal; // 0xf8
	private TextProcessingStack`1 m_FontWeightStack; // 0x100
	private TextAlignment m_LineJustification; // 0x120
	private TextProcessingStack`1 m_LineJustificationStack; // 0x128
	private Single m_BaselineOffset; // 0x148
	private TextProcessingStack`1 m_BaselineOffsetStack; // 0x150
	private Color32 m_FontColor32; // 0x170
	private Color32 m_HtmlColor; // 0x174
	private Color32 m_UnderlineColor; // 0x178
	private Color32 m_StrikethroughColor; // 0x17c
	private TextProcessingStack`1 m_ColorStack; // 0x180
	private TextProcessingStack`1 m_UnderlineColorStack; // 0x1a0
	private TextProcessingStack`1 m_StrikethroughColorStack; // 0x1c0
	private TextProcessingStack`1 m_HighlightColorStack; // 0x1e0
	private TextColorGradient m_ColorGradientPreset; // 0x200
	private TextProcessingStack`1 m_ColorGradientStack; // 0x208
	private TextProcessingStack`1 m_ActionStack; // 0x230
	private Boolean m_IsFxMatrixSet; // 0x250
	private Single m_LineOffset; // 0x254
	private Single m_LineHeight; // 0x258
	private Single m_CSpacing; // 0x25c
	private Single m_MonoSpacing; // 0x260
	private Single m_XAdvance; // 0x264
	private Single m_TagLineIndent; // 0x268
	private Single m_TagIndent; // 0x26c
	private TextProcessingStack`1 m_IndentStack; // 0x270
	private Boolean m_TagNoParsing; // 0x290
	private Int32 m_CharacterCount; // 0x294
	private Int32 m_FirstCharacterOfLine; // 0x298
	private Int32 m_LastCharacterOfLine; // 0x29c
	private Int32 m_FirstVisibleCharacterOfLine; // 0x2a0
	private Int32 m_LastVisibleCharacterOfLine; // 0x2a4
	private Single m_MaxLineAscender; // 0x2a8
	private Single m_MaxLineDescender; // 0x2ac
	private Int32 m_LineNumber; // 0x2b0
	private Int32 m_LineVisibleCharacterCount; // 0x2b4
	private Int32 m_FirstOverflowCharacterIndex; // 0x2b8
	private Int32 m_PageNumber; // 0x2bc
	private Single m_MarginLeft; // 0x2c0
	private Single m_MarginRight; // 0x2c4
	private Single m_Width; // 0x2c8
	private Extents m_MeshExtents; // 0x2cc
	private Single m_MaxCapHeight; // 0x2dc
	private Single m_MaxAscender; // 0x2e0
	private Single m_MaxDescender; // 0x2e4
	private Boolean m_IsNewPage; // 0x2e8
	private Boolean m_IsNonBreakingSpace; // 0x2e9
	private WordWrapState m_SavedWordWrapState; // 0x2f0
	private WordWrapState m_SavedLineState; // 0x600
	private Int32 m_LoopCountA; // 0x910
	private TextElementType m_TextElementType; // 0x914
	private Boolean m_IsParsingText; // 0x915
	private Int32 m_SpriteIndex; // 0x918
	private Color32 m_SpriteColor; // 0x91c
	private TextElement m_CachedTextElement; // 0x920
	private Color32 m_HighlightColor; // 0x928
	private Single m_CharWidthAdjDelta; // 0x92c
	private Matrix4x4 m_FxMatrix; // 0x930
	private Single m_MaxFontSize; // 0x970
	private Single m_MinFontSize; // 0x974
	private Boolean m_IsCharacterWrappingEnabled; // 0x978
	private Single m_StartOfLineAscender; // 0x97c
	private Single m_LineSpacingDelta; // 0x980
	private Boolean m_IsMaskingEnabled; // 0x984
	private MaterialReference[] m_MaterialReferences; // 0x988
	private Int32 m_SpriteCount; // 0x990
	private TextProcessingStack`1 m_StyleStack; // 0x998
	private Int32 m_SpriteAnimationId; // 0x9b8
	private UInt32[] m_InternalTextParsingBuffer; // 0x9c0
	private RichTextTagAttribute[] m_Attributes; // 0x9c8
	private XmlTagAttribute[] m_XmlAttribute; // 0x9d0
	private Char[] m_RichTextTag; // 0x9d8
	private Dictionary`2 m_MaterialReferenceIndexLookup; // 0x9e0
	private Boolean m_IsCalculatingPreferredValues; // 0x9e8
	private SpriteAsset m_DefaultSpriteAsset; // 0x9f0
	private Boolean m_TintSprite; // 0x9f8
	protected SpecialCharacter m_Ellipsis; // 0xa00
	protected SpecialCharacter m_Underline; // 0xa20
	private Boolean m_IsUsingBold; // 0xa40
	private Boolean m_IsSdfShader; // 0xa41
	private TextElementInfo[] m_InternalTextElementInfo; // 0xa48
	private Int32 m_RecursiveCount; // 0xa50


	// RVA: 0x68ebed0 VA: 0x7598f03ed0
	private static TextGenerator GetTextGenerator() { }
	// RVA: 0x68ec52c VA: 0x7598f0452c
	public static Void GenerateText(TextGenerationSettings settings, TextInfo textInfo) { }
	// RVA: 0x68ec914 VA: 0x7598f04914
	public static Vector2 GetCursorPosition(TextInfo textInfo, Rect screenRect, Int32 index, Boolean inverseYAxis) { }
	// RVA: 0x68eca4c VA: 0x7598f04a4c
	public static Vector2 GetPreferredValues(TextGenerationSettings settings, TextInfo textInfo) { }
	// RVA: 0x68ec744 VA: 0x7598f04744
	private Void Prepare(TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68e52e0 VA: 0x7598efd2e0
	private Void GenerateTextMesh(TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68edddc VA: 0x7598f05ddc
	private Void SaveWordWrappingState(ref WordWrapState state, Int32 index, Int32 count, TextInfo textInfo) { }
	// RVA: 0x68ee0a4 VA: 0x7598f060a4
	protected Int32 RestoreWordWrappingState(ref WordWrapState state, TextInfo textInfo) { }
	// RVA: 0x68ee390 VA: 0x7598f06390
	protected Boolean ValidateHtmlTag(Int32[] chars, Int32 startIndex, out Int32 endIndex, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f273c VA: 0x7598f0a73c
	private Void SaveGlyphVertexInfo(Single padding, Single stylePadding, Color32 vertexColor, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f4550 VA: 0x7598f0c550
	private Void SaveSpriteVertexInfo(Color32 vertexColor, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f602c VA: 0x7598f0e02c
	private Void DrawUnderlineMesh(Vector3 start, Vector3 end, ref Int32 index, Single startScale, Single endScale, Single maxScale, Single sdfScale, Color32 underlineColor, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f7120 VA: 0x7598f0f120
	private Void DrawTextHighlight(Vector3 start, Vector3 end, ref Int32 index, Color32 highlightColor, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f7724 VA: 0x7598f0f724
	private static Void ClearMesh(Boolean updateMesh, TextInfo textInfo) { }
	// RVA: 0x68f7744 VA: 0x7598f0f744
	private Void EnableMasking() { }
	// RVA: 0x68f7750 VA: 0x7598f0f750
	private Void DisableMasking() { }
	// RVA: 0x68ecdf4 VA: 0x7598f04df4
	private Void SetArraySizes(Int32[] chars, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f7758 VA: 0x7598f0f758
	internal TextElement GetTextElement(TextGenerationSettings generationSettings, UInt32 unicode, FontAsset fontAsset, FontStyles fontStyle, TextFontWeight fontWeight, out Boolean isUsingAlternativeTypeface) { }
	// RVA: 0x68eccb4 VA: 0x7598f04cb4
	private Void ComputeMarginSize(Rect rect, Vector4 margins) { }
	// RVA: 0x68ecc8c VA: 0x7598f04c8c
	protected Void GetSpecialCharacters(TextGenerationSettings generationSettings) { }
	// RVA: 0x68f7a4c VA: 0x7598f0fa4c
	protected Void GetEllipsisSpecialCharacter(TextGenerationSettings generationSettings) { }
	// RVA: 0x68f6fdc VA: 0x7598f0efdc
	protected Void GetUnderlineSpecialCharacter(TextGenerationSettings generationSettings) { }
	// RVA: 0x68f7be4 VA: 0x7598f0fbe4
	private Single GetPaddingForMaterial(Material material, Boolean extraPadding) { }
	// RVA: 0x68ecb78 VA: 0x7598f04b78
	private Vector2 GetPreferredValuesInternal(TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68f7cf8 VA: 0x7598f0fcf8
	protected virtual Vector2 CalculatePreferredValues(Single defaultFontSize, Vector2 marginSize, Boolean ignoreTextAutoSizing, TextGenerationSettings generationSettings, TextInfo textInfo) { }
	// RVA: 0x68ebf58 VA: 0x7598f03f58
	public Void .ctor() { }
}
```