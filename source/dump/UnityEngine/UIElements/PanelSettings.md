# PanelSettings

**Namespace:** `UnityEngine.UIElements`


## Fields

- `ThemeStyleSheet themeUss`

- `RenderTexture m_TargetTexture`

- `PanelScaleMode m_ScaleMode`

- `Single m_Scale`

- `Single m_ReferenceDpi`

- `Single m_FallbackDpi`

- `Vector2Int m_ReferenceResolution`

- `PanelScreenMatchMode m_ScreenMatchMode`

- `Single m_Match`

- `Single m_SortingOrder`

- `Int32 m_TargetDisplay`

- `Boolean m_ClearDepthStencil`

- `Boolean m_ClearColor`

- `Color m_ColorClearValue`

- `RuntimePanelAccess m_PanelAccess`

- `DynamicAtlasSettings m_DynamicAtlasSettings`

- `Shader m_AtlasBlitShader`

- `Shader m_RuntimeShader`

- `Shader m_RuntimeWorldShader`

- `PanelTextSettings textSettings`

- `Rect m_TargetRect`

- `Single m_ResolvedScale`

- `StyleSheet m_OldThemeUss`

- `Single <ScreenDPI>k__BackingField`


## Properties

- `ThemeStyleSheet themeStyleSheet`

- `RenderTexture targetTexture`

- `PanelScaleMode scaleMode`

- `Single scale`

- `Single referenceDpi`

- `Single fallbackDpi`

- `Vector2Int referenceResolution`

- `PanelScreenMatchMode screenMatchMode`

- `Single match`

- `Single sortingOrder`

- `Int32 targetDisplay`

- `Boolean clearDepthStencil`

- `Single depthClearValue`

- `Boolean clearColor`

- `Color colorClearValue`

- `DynamicAtlasSettings dynamicAtlasSettings`

- `Single ScreenDPI`


## Methods

- `ThemeStyleSheet get_themeStyleSheet()`

- `Void set_themeStyleSheet(ThemeStyleSheet)`

- `RenderTexture get_targetTexture()`

- `Void set_targetTexture(RenderTexture)`

- `PanelScaleMode get_scaleMode()`

- `Void set_scaleMode(PanelScaleMode)`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Single get_referenceDpi()`

- `Void set_referenceDpi(Single)`

- `Single get_fallbackDpi()`

- `Void set_fallbackDpi(Single)`

- `Vector2Int get_referenceResolution()`

- `Void set_referenceResolution(Vector2Int)`

- `PanelScreenMatchMode get_screenMatchMode()`

- `Void set_screenMatchMode(PanelScreenMatchMode)`

- `Single get_match()`

- `Void set_match(Single)`

- `Single get_sortingOrder()`

- `Void set_sortingOrder(Single)`

- `Int32 get_targetDisplay()`

- `Void set_targetDisplay(Int32)`

- `Boolean get_clearDepthStencil()`

- `Void set_clearDepthStencil(Boolean)`

- `Single get_depthClearValue()`

- `Boolean get_clearColor()`

- `Void set_clearColor(Boolean)`

- `Color get_colorClearValue()`

- `Void set_colorClearValue(Color)`

- `DynamicAtlasSettings get_dynamicAtlasSettings()`

- `Void set_dynamicAtlasSettings(DynamicAtlasSettings)`

- `Void Reset()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Single get_ScreenDPI()`

- `Void set_ScreenDPI(Single)`

- `Void ApplyThemeStyleSheet(VisualElement)`

- `Void InitializeShaders()`

- `Void SetScreenToPanelSpaceFunction(Func`2)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class PanelSettings : ScriptableObject
{
	private const Int32 k_DefaultSortingOrder; // 0x0
	private const Single k_DefaultScaleValue; // 0x0
	internal const String k_DefaultStyleSheetPath; // 0x0
	private ThemeStyleSheet themeUss; // 0x18
	private RenderTexture m_TargetTexture; // 0x20
	private PanelScaleMode m_ScaleMode; // 0x28
	private Single m_Scale; // 0x2c
	private const Single DefaultDpi; // 0x0
	private Single m_ReferenceDpi; // 0x30
	private Single m_FallbackDpi; // 0x34
	private Vector2Int m_ReferenceResolution; // 0x38
	private PanelScreenMatchMode m_ScreenMatchMode; // 0x40
	private Single m_Match; // 0x44
	private Single m_SortingOrder; // 0x48
	private Int32 m_TargetDisplay; // 0x4c
	private Boolean m_ClearDepthStencil; // 0x50
	private Boolean m_ClearColor; // 0x51
	private Color m_ColorClearValue; // 0x54
	private RuntimePanelAccess m_PanelAccess; // 0x68
	internal UIDocumentList m_AttachedUIDocumentsList; // 0x70
	private DynamicAtlasSettings m_DynamicAtlasSettings; // 0x78
	private Shader m_AtlasBlitShader; // 0x80
	private Shader m_RuntimeShader; // 0x88
	private Shader m_RuntimeWorldShader; // 0x90
	public PanelTextSettings textSettings; // 0x98
	private Rect m_TargetRect; // 0xa0
	private Single m_ResolvedScale; // 0xb0
	private StyleSheet m_OldThemeUss; // 0xb8
	internal Int32 m_EmptyPanelCounter; // 0xc0
	private Single <ScreenDPI>k__BackingField; // 0xc4
	private Func`2 m_AssignedScreenToPanel; // 0xc8

	public ThemeStyleSheet themeStyleSheet { get; set; }
	public RenderTexture targetTexture { get; set; }
	public PanelScaleMode scaleMode { get; set; }
	public Single scale { get; set; }
	public Single referenceDpi { get; set; }
	public Single fallbackDpi { get; set; }
	public Vector2Int referenceResolution { get; set; }
	public PanelScreenMatchMode screenMatchMode { get; set; }
	public Single match { get; set; }
	public Single sortingOrder { get; set; }
	public Int32 targetDisplay { get; set; }
	public Boolean clearDepthStencil { get; set; }
	public Single depthClearValue { get; }
	public Boolean clearColor { get; set; }
	public Color colorClearValue { get; set; }
	internal BaseRuntimePanel panel { get; }
	internal VisualElement visualTree { get; }
	public DynamicAtlasSettings dynamicAtlasSettings { get; set; }
	private Single ScreenDPI { get; set; }

	// RVA: 0x6a00bb8 VA: 0x7599018bb8
	public ThemeStyleSheet get_themeStyleSheet() { }
	// RVA: 0x6a00bc0 VA: 0x7599018bc0
	public Void set_themeStyleSheet(ThemeStyleSheet value) { }
	// RVA: 0x6a00d48 VA: 0x7599018d48
	public RenderTexture get_targetTexture() { }
	// RVA: 0x6a00d50 VA: 0x7599018d50
	public Void set_targetTexture(RenderTexture value) { }
	// RVA: 0x6a00dac VA: 0x7599018dac
	public PanelScaleMode get_scaleMode() { }
	// RVA: 0x6a00db4 VA: 0x7599018db4
	public Void set_scaleMode(PanelScaleMode value) { }
	// RVA: 0x6a00dbc VA: 0x7599018dbc
	public Single get_scale() { }
	// RVA: 0x6a00dc4 VA: 0x7599018dc4
	public Void set_scale(Single value) { }
	// RVA: 0x6a00dcc VA: 0x7599018dcc
	public Single get_referenceDpi() { }
	// RVA: 0x6a00dd4 VA: 0x7599018dd4
	public Void set_referenceDpi(Single value) { }
	// RVA: 0x6a00e00 VA: 0x7599018e00
	public Single get_fallbackDpi() { }
	// RVA: 0x6a00e08 VA: 0x7599018e08
	public Void set_fallbackDpi(Single value) { }
	// RVA: 0x6a00e34 VA: 0x7599018e34
	public Vector2Int get_referenceResolution() { }
	// RVA: 0x6a00e3c VA: 0x7599018e3c
	public Void set_referenceResolution(Vector2Int value) { }
	// RVA: 0x6a00e44 VA: 0x7599018e44
	public PanelScreenMatchMode get_screenMatchMode() { }
	// RVA: 0x6a00e4c VA: 0x7599018e4c
	public Void set_screenMatchMode(PanelScreenMatchMode value) { }
	// RVA: 0x6a00e54 VA: 0x7599018e54
	public Single get_match() { }
	// RVA: 0x6a00e5c VA: 0x7599018e5c
	public Void set_match(Single value) { }
	// RVA: 0x6a00e64 VA: 0x7599018e64
	public Single get_sortingOrder() { }
	// RVA: 0x6a00e6c VA: 0x7599018e6c
	public Void set_sortingOrder(Single value) { }
	// RVA: 0x6a00e8c VA: 0x7599018e8c
	internal Void ApplySortingOrder() { }
	// RVA: 0x6a00ed8 VA: 0x7599018ed8
	public Int32 get_targetDisplay() { }
	// RVA: 0x6a00ee0 VA: 0x7599018ee0
	public Void set_targetDisplay(Int32 value) { }
	// RVA: 0x6a00f3c VA: 0x7599018f3c
	public Boolean get_clearDepthStencil() { }
	// RVA: 0x6a00f44 VA: 0x7599018f44
	public Void set_clearDepthStencil(Boolean value) { }
	// RVA: 0x6a00f50 VA: 0x7599018f50
	public Single get_depthClearValue() { }
	// RVA: 0x6a00f5c VA: 0x7599018f5c
	public Boolean get_clearColor() { }
	// RVA: 0x6a00f64 VA: 0x7599018f64
	public Void set_clearColor(Boolean value) { }
	// RVA: 0x6a00f70 VA: 0x7599018f70
	public Color get_colorClearValue() { }
	// RVA: 0x6a00f7c VA: 0x7599018f7c
	public Void set_colorClearValue(Color value) { }
	// RVA: 0x6a00f88 VA: 0x7599018f88
	internal BaseRuntimePanel get_panel() { }
	// RVA: 0x6a010f0 VA: 0x75990190f0
	internal VisualElement get_visualTree() { }
	// RVA: 0x6a0111c VA: 0x759901911c
	public DynamicAtlasSettings get_dynamicAtlasSettings() { }
	// RVA: 0x6a01124 VA: 0x7599019124
	public Void set_dynamicAtlasSettings(DynamicAtlasSettings value) { }
	// RVA: 0x6a0112c VA: 0x759901912c
	private Void .ctor() { }
	// RVA: 0x6a01230 VA: 0x7599019230
	private Void Reset() { }
	// RVA: 0x6a01234 VA: 0x7599019234
	private Void OnEnable() { }
	// RVA: 0x6a014e0 VA: 0x75990194e0
	private Void OnDisable() { }
	// RVA: 0x6a01538 VA: 0x7599019538
	internal Void DisposePanel() { }
	// RVA: 0x6a01550 VA: 0x7599019550
	private Single get_ScreenDPI() { }
	// RVA: 0x6a01558 VA: 0x7599019558
	private Void set_ScreenDPI(Single value) { }
	// RVA: 0x6a0133c VA: 0x759901933c
	internal Void UpdateScreenDPI() { }
	// RVA: 0x6a00be0 VA: 0x7599018be0
	private Void ApplyThemeStyleSheet(VisualElement root) { }
	// RVA: 0x6a01358 VA: 0x7599019358
	private Void InitializeShaders() { }
	// RVA: 0x6a01570 VA: 0x7599019570
	internal Void ApplyPanelSettings() { }
	// RVA: 0x6a01e4c VA: 0x7599019e4c
	public Void SetScreenToPanelSpaceFunction(Func`2 screentoPanelSpaceFunction) { }
	// RVA: 0x6a01d34 VA: 0x7599019d34
	internal Single ResolveScale(Rect targetRect, Single screenDpi) { }
	// RVA: 0x6a01b78 VA: 0x7599019b78
	internal Rect GetDisplayRect() { }
	// RVA: 0x6a01e84 VA: 0x7599019e84
	internal Void AttachAndInsertUIDocumentToVisualTree(UIDocument uiDocument) { }
	// RVA: 0x6a0238c VA: 0x759901a38c
	internal Void DetachUIDocument(UIDocument uiDocument) { }
}
```