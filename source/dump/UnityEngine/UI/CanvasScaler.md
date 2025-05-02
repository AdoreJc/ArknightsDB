# CanvasScaler

**Namespace:** `UnityEngine.UI`


## Fields

- `ScaleMode m_UiScaleMode`

- `Single m_ReferencePixelsPerUnit`

- `Single m_ScaleFactor`

- `Vector2 m_ReferenceResolution`

- `ScreenMatchMode m_ScreenMatchMode`

- `Single m_MatchWidthOrHeight`

- `Unit m_PhysicalUnit`

- `Single m_FallbackScreenDPI`

- `Single m_DefaultSpriteDPI`

- `Single m_DynamicPixelsPerUnit`

- `Canvas m_Canvas`

- `Single m_PrevScaleFactor`

- `Single m_PrevReferencePixelsPerUnit`

- `Boolean m_PresetInfoIsWorld`


## Properties

- `ScaleMode uiScaleMode`

- `Single referencePixelsPerUnit`

- `Single scaleFactor`

- `Vector2 referenceResolution`

- `ScreenMatchMode screenMatchMode`

- `Single matchWidthOrHeight`

- `Unit physicalUnit`

- `Single fallbackScreenDPI`

- `Single defaultSpriteDPI`

- `Single dynamicPixelsPerUnit`


## Methods

- `ScaleMode get_uiScaleMode()`

- `Void set_uiScaleMode(ScaleMode)`

- `Single get_referencePixelsPerUnit()`

- `Void set_referencePixelsPerUnit(Single)`

- `Single get_scaleFactor()`

- `Void set_scaleFactor(Single)`

- `Vector2 get_referenceResolution()`

- `Void set_referenceResolution(Vector2)`

- `ScreenMatchMode get_screenMatchMode()`

- `Void set_screenMatchMode(ScreenMatchMode)`

- `Single get_matchWidthOrHeight()`

- `Void set_matchWidthOrHeight(Single)`

- `Unit get_physicalUnit()`

- `Void set_physicalUnit(Unit)`

- `Single get_fallbackScreenDPI()`

- `Void set_fallbackScreenDPI(Single)`

- `Single get_defaultSpriteDPI()`

- `Void set_defaultSpriteDPI(Single)`

- `Single get_dynamicPixelsPerUnit()`

- `Void set_dynamicPixelsPerUnit(Single)`

- `Void Canvas_preWillRenderCanvases()`

- `Void SetScaleFactor(Single)`

- `Void SetReferencePixelsPerUnit(Single)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class CanvasScaler : UIBehaviour
{
	private ScaleMode m_UiScaleMode; // 0x18
	protected Single m_ReferencePixelsPerUnit; // 0x1c
	protected Single m_ScaleFactor; // 0x20
	protected Vector2 m_ReferenceResolution; // 0x24
	protected ScreenMatchMode m_ScreenMatchMode; // 0x2c
	protected Single m_MatchWidthOrHeight; // 0x30
	private const Single kLogBase; // 0x0
	protected Unit m_PhysicalUnit; // 0x34
	protected Single m_FallbackScreenDPI; // 0x38
	protected Single m_DefaultSpriteDPI; // 0x3c
	protected Single m_DynamicPixelsPerUnit; // 0x40
	private Canvas m_Canvas; // 0x48
	private Single m_PrevScaleFactor; // 0x50
	private Single m_PrevReferencePixelsPerUnit; // 0x54
	protected Boolean m_PresetInfoIsWorld; // 0x58

	public ScaleMode uiScaleMode { get; set; }
	public Single referencePixelsPerUnit { get; set; }
	public Single scaleFactor { get; set; }
	public Vector2 referenceResolution { get; set; }
	public ScreenMatchMode screenMatchMode { get; set; }
	public Single matchWidthOrHeight { get; set; }
	public Unit physicalUnit { get; set; }
	public Single fallbackScreenDPI { get; set; }
	public Single defaultSpriteDPI { get; set; }
	public Single dynamicPixelsPerUnit { get; set; }

	// RVA: 0x6a523e4 VA: 0x759906a3e4
	public ScaleMode get_uiScaleMode() { }
	// RVA: 0x6a523ec VA: 0x759906a3ec
	public Void set_uiScaleMode(ScaleMode value) { }
	// RVA: 0x6a523f4 VA: 0x759906a3f4
	public Single get_referencePixelsPerUnit() { }
	// RVA: 0x6a523fc VA: 0x759906a3fc
	public Void set_referencePixelsPerUnit(Single value) { }
	// RVA: 0x6a52404 VA: 0x759906a404
	public Single get_scaleFactor() { }
	// RVA: 0x6a5240c VA: 0x759906a40c
	public Void set_scaleFactor(Single value) { }
	// RVA: 0x6a52420 VA: 0x759906a420
	public Vector2 get_referenceResolution() { }
	// RVA: 0x6a52428 VA: 0x759906a428
	public Void set_referenceResolution(Vector2 value) { }
	// RVA: 0x6a5248c VA: 0x759906a48c
	public ScreenMatchMode get_screenMatchMode() { }
	// RVA: 0x6a52494 VA: 0x759906a494
	public Void set_screenMatchMode(ScreenMatchMode value) { }
	// RVA: 0x6a5249c VA: 0x759906a49c
	public Single get_matchWidthOrHeight() { }
	// RVA: 0x6a524a4 VA: 0x759906a4a4
	public Void set_matchWidthOrHeight(Single value) { }
	// RVA: 0x6a524ac VA: 0x759906a4ac
	public Unit get_physicalUnit() { }
	// RVA: 0x6a524b4 VA: 0x759906a4b4
	public Void set_physicalUnit(Unit value) { }
	// RVA: 0x6a524bc VA: 0x759906a4bc
	public Single get_fallbackScreenDPI() { }
	// RVA: 0x6a524c4 VA: 0x759906a4c4
	public Void set_fallbackScreenDPI(Single value) { }
	// RVA: 0x6a524cc VA: 0x759906a4cc
	public Single get_defaultSpriteDPI() { }
	// RVA: 0x6a524d4 VA: 0x759906a4d4
	public Void set_defaultSpriteDPI(Single value) { }
	// RVA: 0x6a524e4 VA: 0x759906a4e4
	public Single get_dynamicPixelsPerUnit() { }
	// RVA: 0x6a524ec VA: 0x759906a4ec
	public Void set_dynamicPixelsPerUnit(Single value) { }
	// RVA: 0x6a524f4 VA: 0x759906a4f4
	protected Void .ctor() { }
	// RVA: 0x6a5253c VA: 0x759906a53c
	protected override Void OnEnable() { }
	// RVA: 0x6a52614 VA: 0x759906a614
	private Void Canvas_preWillRenderCanvases() { }
	// RVA: 0x6a52624 VA: 0x759906a624
	protected override Void OnDisable() { }
	// RVA: 0x6a5274c VA: 0x759906a74c
	protected virtual Void Handle() { }
	// RVA: 0x6a52848 VA: 0x759906a848
	protected virtual Void HandleWorldCanvas() { }
	// RVA: 0x6a52868 VA: 0x759906a868
	protected virtual Void HandleConstantPixelSize() { }
	// RVA: 0x6a52888 VA: 0x759906a888
	protected virtual Void HandleScaleWithScreenSize() { }
	// RVA: 0x6a52abc VA: 0x759906aabc
	protected virtual Void HandleConstantPhysicalSize() { }
	// RVA: 0x6a526cc VA: 0x759906a6cc
	protected Void SetScaleFactor(Single scaleFactor) { }
	// RVA: 0x6a5270c VA: 0x759906a70c
	protected Void SetReferencePixelsPerUnit(Single referencePixelsPerUnit) { }
}
```