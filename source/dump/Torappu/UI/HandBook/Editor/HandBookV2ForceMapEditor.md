# HandBookV2ForceMapEditor

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `HandBookV2ForceMapDB _forceMapDB`

- `HandBookV2ForceMapEditorView _mapView`

- `HandBookV2ForceMapData m_forceMapData`

- `HandBookV2ForceMapEditorModel m_editorModel`

- `HandBookV2ForceMapEditorProperty m_editorProperty`

- `OpEnum m_op`


## Properties

- `OpEnum currentOp`

- `Boolean isConfirmState`


## Methods

- `OpEnum get_currentOp()`

- `Boolean get_isConfirmState()`

- `Void Update()`

- `Void _InitData()`

- `Void _SaveDataToFile()`

- `Void EnterConfirm(OpEnum)`

- `Void SelectForce(Int32)`

- `Void SelectPoint(Int32)`

- `Void SetPosInput(Vector2)`

- `Void SetSliderVal(Single)`

- `Void QuitConfirm()`

- `Void ChangeOp(OpEnum)`

- `Void OnCancelClick()`

- `Void OnSureClick()`

- `Void OnDeleteForceLineClick()`

- `Void OnDeletePointLineClick()`

- `Void OnAddForceClick()`

- `Void OnDeleteForceClick()`

- `Void OnAddForceLineClick()`

- `Void OnZoomChanged(Single)`

- `Void OnOpChanged(Int32)`

- `Void OnSaveClick()`

- `Void OnBgStyleToggle(Boolean)`

- `Void OnXInputChanged(String)`

- `Void OnYInputChanged(String)`

- `Void OnColorChanged(String)`

- `Void OnCardColorChanged(String)`

- `Void OnScaleChanged(String)`

- `Void OnBtnAlignClick()`

- `Void _OnInputChanged(String, Boolean)`

- `Void _OnColorChanged()`

- `Int32 GetMaxForceIndex()`

- `Int32 GetMaxPointIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2ForceMapEditor : SingletonMonoBehaviour`1
{
	private HandBookV2ForceMapDB _forceMapDB; // 0x18
	private HandBookV2ForceMapEditorView _mapView; // 0x20
	private HandBookV2ForceMapData m_forceMapData; // 0x28
	private HandBookV2ForceMapEditorModel m_editorModel; // 0x30
	private HandBookV2ForceMapEditorProperty m_editorProperty; // 0x38
	private OpEnum m_op; // 0x40
	private static DelegateBridge __Hotfix0_get_currentOp; // 0x0
	private static DelegateBridge __Hotfix0_get_isConfirmState; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0__InitData; // 0x20
	private static DelegateBridge __Hotfix0__SaveDataToFile; // 0x28
	private static DelegateBridge __Hotfix0_EnterConfirm; // 0x30
	private static DelegateBridge __Hotfix0_SelectForce; // 0x38
	private static DelegateBridge __Hotfix0_SelectPoint; // 0x40
	private static DelegateBridge __Hotfix0_SetPosInput; // 0x48
	private static DelegateBridge __Hotfix0_SetSliderVal; // 0x50
	private static DelegateBridge __Hotfix0_QuitConfirm; // 0x58
	private static DelegateBridge __Hotfix0_ChangeOp; // 0x60
	private static DelegateBridge __Hotfix0_OnCancelClick; // 0x68
	private static DelegateBridge __Hotfix0_OnSureClick; // 0x70
	private static DelegateBridge __Hotfix0_OnDeleteForceLineClick; // 0x78
	private static DelegateBridge __Hotfix0_OnDeletePointLineClick; // 0x80
	private static DelegateBridge __Hotfix0_OnAddForceClick; // 0x88
	private static DelegateBridge __Hotfix0_OnDeleteForceClick; // 0x90
	private static DelegateBridge __Hotfix0_OnAddForceLineClick; // 0x98
	private static DelegateBridge __Hotfix0_OnZoomChanged; // 0xa0
	private static DelegateBridge __Hotfix0_OnOpChanged; // 0xa8
	private static DelegateBridge __Hotfix0_OnSaveClick; // 0xb0
	private static DelegateBridge __Hotfix0_OnBgStyleToggle; // 0xb8
	private static DelegateBridge __Hotfix0_OnXInputChanged; // 0xc0
	private static DelegateBridge __Hotfix0_OnYInputChanged; // 0xc8
	private static DelegateBridge __Hotfix0_OnColorChanged; // 0xd0
	private static DelegateBridge __Hotfix0_OnCardColorChanged; // 0xd8
	private static DelegateBridge __Hotfix0_OnScaleChanged; // 0xe0
	private static DelegateBridge __Hotfix0_OnBtnAlignClick; // 0xe8
	private static DelegateBridge __Hotfix0__OnInputChanged; // 0xf0
	private static DelegateBridge __Hotfix0__OnColorChanged; // 0xf8
	private static DelegateBridge __Hotfix0_GetMaxForceIndex; // 0x100
	private static DelegateBridge __Hotfix0_GetMaxPointIndex; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public OpEnum currentOp { get; }
	public Boolean isConfirmState { get; }

	// RVA: 0x2ee3058 VA: 0x75954fb058
	public OpEnum get_currentOp() { }
	// RVA: 0x2ee3400 VA: 0x75954fb400
	public Boolean get_isConfirmState() { }
	// RVA: 0x2ee4578 VA: 0x75954fc578
	protected Void Update() { }
	// RVA: 0x2ee4798 VA: 0x75954fc798
	protected override Void OnInit() { }
	// RVA: 0x2ee4850 VA: 0x75954fc850
	private Void _InitData() { }
	// RVA: 0x2ee4a10 VA: 0x75954fca10
	private Void _SaveDataToFile() { }
	// RVA: 0x2ee30c0 VA: 0x75954fb0c0
	public Void EnterConfirm(OpEnum opEnum) { }
	// RVA: 0x2ee3164 VA: 0x75954fb164
	public Void SelectForce(Int32 forceIndex) { }
	// RVA: 0x2ee3a38 VA: 0x75954fba38
	public Void SelectPoint(Int32 pointIndex) { }
	// RVA: 0x2ee32b8 VA: 0x75954fb2b8
	public Void SetPosInput(Vector2 pos) { }
	// RVA: 0x2ee5150 VA: 0x75954fd150
	public Void SetSliderVal(Single val) { }
	// RVA: 0x2ee527c VA: 0x75954fd27c
	public Void QuitConfirm() { }
	// RVA: 0x2ee5470 VA: 0x75954fd470
	public Void ChangeOp(OpEnum opEnum) { }
	// RVA: 0x2ee4708 VA: 0x75954fc708
	public Void OnCancelClick() { }
	// RVA: 0x2ee5e6c VA: 0x75954fde6c
	public Void OnSureClick() { }
	// RVA: 0x2ee74e8 VA: 0x75954ff4e8
	public Void OnDeleteForceLineClick() { }
	// RVA: 0x2ee7644 VA: 0x75954ff644
	public Void OnDeletePointLineClick() { }
	// RVA: 0x2ee77a0 VA: 0x75954ff7a0
	public Void OnAddForceClick() { }
	// RVA: 0x2ee7898 VA: 0x75954ff898
	public Void OnDeleteForceClick() { }
	// RVA: 0x2ee7c7c VA: 0x75954ffc7c
	public Void OnAddForceLineClick() { }
	// RVA: 0x2ee7cf0 VA: 0x75954ffcf0
	public Void OnZoomChanged(Single zoomVal) { }
	// RVA: 0x2ee7e0c VA: 0x75954ffe0c
	public Void OnOpChanged(Int32 opVal) { }
	// RVA: 0x2ee7e8c VA: 0x75954ffe8c
	public Void OnSaveClick() { }
	// RVA: 0x2ee7ef4 VA: 0x75954ffef4
	public Void OnBgStyleToggle(Boolean isSolid) { }
	// RVA: 0x2ee8128 VA: 0x7595500128
	public Void OnXInputChanged(String text) { }
	// RVA: 0x2ee8260 VA: 0x7595500260
	public Void OnYInputChanged(String text) { }
	// RVA: 0x2ee82e4 VA: 0x75955002e4
	public Void OnColorChanged(String text) { }
	// RVA: 0x2ee83d0 VA: 0x75955003d0
	public Void OnCardColorChanged(String text) { }
	// RVA: 0x2ee844c VA: 0x759550044c
	public Void OnScaleChanged(String text) { }
	// RVA: 0x2ee8698 VA: 0x7595500698
	public Void OnBtnAlignClick() { }
	// RVA: 0x2ee81ac VA: 0x75955001ac
	private Void _OnInputChanged(String text, Boolean isXInput) { }
	// RVA: 0x2ee8360 VA: 0x7595500360
	private Void _OnColorChanged() { }
	// RVA: 0x2ee8b4c VA: 0x7595500b4c
	public Int32 GetMaxForceIndex() { }
	// RVA: 0x2ee24d8 VA: 0x75954fa4d8
	public Int32 GetMaxPointIndex() { }
	// RVA: 0x2ee8c4c VA: 0x7595500c4c
	public Void .ctor() { }
}
```