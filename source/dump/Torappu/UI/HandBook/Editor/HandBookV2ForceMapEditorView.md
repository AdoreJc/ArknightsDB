# HandBookV2ForceMapEditorView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `HandBookV2EditorForceView _forceViewTemplate`

- `Transform _forceViewContainer`

- `HandBookV2EditorForceCardView _forceCardTemplate`

- `Transform _forceCardContainer`

- `HandBookV2EditorForceLineView _forceLineTemplate`

- `Transform _forceLineContainer`

- `HandBookV2EditorPointLineView _pointLineTemplate`

- `Transform _pointLineContainer`

- `RectTransform _contentRt`

- `NonDrawingGraphic _contentRaycast`

- `GameObject _confirmPanelGo`

- `InputField _scaleInput`

- `Dropdown _opDropdown`

- `GameObject _savePanelGo`

- `GameObject _positionInputPanel`

- `GameObject _colorInputPanel`

- `InputField _xInput`

- `InputField _yInput`

- `InputField _colorInput`

- `InputField _cardColorInput`

- `GameObject _forceLineListPanel`

- `SimpleLayoutContent _forceLineList`

- `GameObject _pointLineListPanel`

- `SimpleLayoutContent _pointLineList`

- `GameObject _addForceLinePanel`

- `Text _textPoint1`

- `Text _textPoint2`

- `HandBookV2EditorForceLineView _previewLine`

- `GameObject _forceListPanel`

- `SimpleLayoutContent _forceList`

- `GameObject _forceSelectPanel`

- `Dropdown _forceDropdown`

- `Boolean m_hasInited`

- `Boolean m_isConfirmState`

- `HandBookV2ForceMapData m_forceMapData`

- `Adapter m_forceLineListAdapter`

- `Adapter m_pointLineListAdapter`

- `Adapter m_forceListAdapter`

- `Int32 m_selectForceLineIndex`

- `Int32 m_selectPointLineIndex`

- `Int32 m_selectPointIdx1`

- `Int32 m_selectPointIdx2`

- `Int32 m_selectForceIndex`

- `Int32 m_selectForceIndex2`


## Properties

- `Int32 selectForceIndex`

- `Boolean isConfirmState`


## Methods

- `Int32 get_selectForceIndex()`

- `Boolean get_isConfirmState()`

- `Void _UpdateForceDropDown()`

- `Void _InitIfNot()`

- `Void _RenderForce(HandBookV2ForceData, Boolean)`

- `Void _RenderCard(HandBookV2ForceData)`

- `Void _RenderForceLine(Int32, HandBookV2ForceLineData)`

- `Void _RenderPointLine(Int32, HandBookV2PointLineData)`

- `Vector2 _GetPointPos(Int32)`

- `Void _SetPreviewLineActive(Boolean)`

- `Void _SetOpDropdownActive(Boolean)`

- `Void _SetConfirmPanelActive(Boolean)`

- `Void _SetSavePanelActive(Boolean)`

- `Void _SetScaleSliderActive(Boolean)`

- `Void _SetPosInputActive(Boolean)`

- `Void _SetColorInputActive(Boolean)`

- `Void _SetAddForceLinePanelActive(Boolean)`

- `Void _ResetTextPoint()`

- `Void SetForceLineListPanelActive(Boolean)`

- `Void SetPointLineListPanelActive(Boolean)`

- `Void SetForceListPanelActive(Boolean)`

- `Void SetForceSelectPanelActive(Boolean)`

- `Void SetSliderVal(Single)`

- `Void SetPosInput(Vector2)`

- `Void SetColorVal(String, String)`

- `Void QuitConfirm(OpEnum)`

- `Void EnterConfirm(OpEnum)`

- `Void _ClearLineMap()`

- `Void _ClearForceMap()`

- `Void SelectForceLine(Int32)`

- `Void ClearSelectForceLine()`

- `Void ClearSelectPointLine()`

- `Void ClearSelectForce()`

- `Void SelectPointLine(Int32)`

- `Void SelectPoint(Int32)`

- `Void _SelectPoint(Int32, Boolean)`

- `Void _SetPointLineVertText(Int32, Boolean)`

- `Void SelectForce(Int32, OpEnum)`

- `Void _SetSelectForce(Int32, OpEnum, Boolean)`

- `Void _SetLineVertText(Int32, Boolean)`

- `Void UpdateLogoScale(Single)`

- `Void UpdateCardScale(Single)`

- `Void _UpdateBgPos(Single, Boolean)`

- `Void _UpdateCardPos(Single, Boolean)`

- `Void _UpdateLogoPos(Single, Boolean)`

- `Void UpdatePos(OpEnum, Single, Boolean)`

- `Void UpdateColor()`

- `Void AlignInputPos(OpEnum)`

- `Void ToggleBgStyle(Boolean)`

- `Void ZoomView(Single)`

- `Void ChangeOpMode(OpEnum)`

- `Void FocusOnPos(Vector2)`

- `Void SetBgRaycast(Boolean)`

- `Void SetLogoRaycast(Boolean)`

- `Void SetCardRaycast(Boolean)`

- `Void SetViewportRaycast(Boolean)`

- `Void SetAllCardVisible(Boolean)`

- `Void SetAllForceLineVisible(Boolean)`

- `Void SetAllPointLineVisible(Boolean)`

- `Void SaveBgModified()`

- `Void SaveLogoModified()`

- `Void SaveColorModified()`

- `Void SaveCardModified()`

- `Void SaveForceShapeModified()`

- `Void AddForceLine()`

- `Void RemoveForceLine()`

- `Void AddPointLine()`

- `Void RemovePointLine()`

- `Void RemoveForce()`

- `Void AddNewForce()`

- `Vector2 GetClickPos()`

- `Void OnClick()`

- `Void <_InitIfNot>b__54_0(Int32)`

- `Void <_InitIfNot>b__54_1(Int32)`

- `Void <_InitIfNot>b__54_2(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2ForceMapEditorView : DataBinder`1
{
	private HandBookV2EditorForceView _forceViewTemplate; // 0x20
	private Transform _forceViewContainer; // 0x28
	private HandBookV2EditorForceCardView _forceCardTemplate; // 0x30
	private Transform _forceCardContainer; // 0x38
	private HandBookV2EditorForceLineView _forceLineTemplate; // 0x40
	private Transform _forceLineContainer; // 0x48
	private HandBookV2EditorPointLineView _pointLineTemplate; // 0x50
	private Transform _pointLineContainer; // 0x58
	private RectTransform _contentRt; // 0x60
	private NonDrawingGraphic _contentRaycast; // 0x68
	private GameObject _confirmPanelGo; // 0x70
	private InputField _scaleInput; // 0x78
	private Dropdown _opDropdown; // 0x80
	private GameObject _savePanelGo; // 0x88
	private GameObject _positionInputPanel; // 0x90
	private GameObject _colorInputPanel; // 0x98
	private InputField _xInput; // 0xa0
	private InputField _yInput; // 0xa8
	private InputField _colorInput; // 0xb0
	private InputField _cardColorInput; // 0xb8
	private GameObject _forceLineListPanel; // 0xc0
	private SimpleLayoutContent _forceLineList; // 0xc8
	private GameObject _pointLineListPanel; // 0xd0
	private SimpleLayoutContent _pointLineList; // 0xd8
	private GameObject _addForceLinePanel; // 0xe0
	private Text _textPoint1; // 0xe8
	private Text _textPoint2; // 0xf0
	private HandBookV2EditorForceLineView _previewLine; // 0xf8
	private GameObject _forceListPanel; // 0x100
	private SimpleLayoutContent _forceList; // 0x108
	private GameObject _forceSelectPanel; // 0x110
	private Dropdown _forceDropdown; // 0x118
	private Boolean m_hasInited; // 0x120
	private Boolean m_isConfirmState; // 0x121
	private HandBookV2ForceMapData m_forceMapData; // 0x128
	private Dictionary`2 m_pointIdx2ForceIdMap; // 0x130
	private Dictionary`2 m_forceId2DataMap; // 0x138
	private Dictionary`2 m_forceIdx2ViewMap; // 0x140
	private Dictionary`2 m_forceIdx2CardMap; // 0x148
	private Dictionary`2 m_forceLineIdx2LineMap; // 0x150
	private Dictionary`2 m_pointLineIdx2LineMap; // 0x158
	private List`1 m_candidateForceList; // 0x160
	private Adapter m_forceLineListAdapter; // 0x168
	private Adapter m_pointLineListAdapter; // 0x170
	private Adapter m_forceListAdapter; // 0x178
	private List`1 m_forceLineDataSource; // 0x180
	private List`1 m_pointLineDataSource; // 0x188
	private List`1 m_forceDataSource; // 0x190
	private const String FORCE_NONE; // 0x0
	private Int32 m_selectForceLineIndex; // 0x198
	private Int32 m_selectPointLineIndex; // 0x19c
	private Int32 m_selectPointIdx1; // 0x1a0
	private Int32 m_selectPointIdx2; // 0x1a4
	private Int32 m_selectForceIndex; // 0x1a8
	private Int32 m_selectForceIndex2; // 0x1ac
	private static DelegateBridge __Hotfix0_get_selectForceIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_isConfirmState; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__UpdateForceDropDown; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__RenderForce; // 0x28
	private static DelegateBridge __Hotfix0__RenderCard; // 0x30
	private static DelegateBridge __Hotfix0__RenderForceLine; // 0x38
	private static DelegateBridge __Hotfix0__RenderPointLine; // 0x40
	private static DelegateBridge __Hotfix0__GetPointPos; // 0x48
	private static DelegateBridge __Hotfix0__SetPreviewLineActive; // 0x50
	private static DelegateBridge __Hotfix0__SetOpDropdownActive; // 0x58
	private static DelegateBridge __Hotfix0__SetConfirmPanelActive; // 0x60
	private static DelegateBridge __Hotfix0__SetSavePanelActive; // 0x68
	private static DelegateBridge __Hotfix0__SetScaleSliderActive; // 0x70
	private static DelegateBridge __Hotfix0__SetPosInputActive; // 0x78
	private static DelegateBridge __Hotfix0__SetColorInputActive; // 0x80
	private static DelegateBridge __Hotfix0__SetAddForceLinePanelActive; // 0x88
	private static DelegateBridge __Hotfix0__ResetTextPoint; // 0x90
	private static DelegateBridge __Hotfix0_SetForceLineListPanelActive; // 0x98
	private static DelegateBridge __Hotfix0_SetPointLineListPanelActive; // 0xa0
	private static DelegateBridge __Hotfix0_SetForceListPanelActive; // 0xa8
	private static DelegateBridge __Hotfix0_SetForceSelectPanelActive; // 0xb0
	private static DelegateBridge __Hotfix0_SetSliderVal; // 0xb8
	private static DelegateBridge __Hotfix0_SetPosInput; // 0xc0
	private static DelegateBridge __Hotfix0_SetColorVal; // 0xc8
	private static DelegateBridge __Hotfix0_QuitConfirm; // 0xd0
	private static DelegateBridge __Hotfix0_EnterConfirm; // 0xd8
	private static DelegateBridge __Hotfix0__ClearLineMap; // 0xe0
	private static DelegateBridge __Hotfix0__ClearForceMap; // 0xe8
	private static DelegateBridge __Hotfix0_SelectForceLine; // 0xf0
	private static DelegateBridge __Hotfix0_ClearSelectForceLine; // 0xf8
	private static DelegateBridge __Hotfix0_ClearSelectPointLine; // 0x100
	private static DelegateBridge __Hotfix0_ClearSelectForce; // 0x108
	private static DelegateBridge __Hotfix0_SelectPointLine; // 0x110
	private static DelegateBridge __Hotfix0_SelectPoint; // 0x118
	private static DelegateBridge __Hotfix0__SelectPoint; // 0x120
	private static DelegateBridge __Hotfix0__SetPointLineVertText; // 0x128
	private static DelegateBridge __Hotfix0_SelectForce; // 0x130
	private static DelegateBridge __Hotfix0__SetSelectForce; // 0x138
	private static DelegateBridge __Hotfix0__SetLineVertText; // 0x140
	private static DelegateBridge __Hotfix0_UpdateLogoScale; // 0x148
	private static DelegateBridge __Hotfix0_UpdateCardScale; // 0x150
	private static DelegateBridge __Hotfix0__UpdateBgPos; // 0x158
	private static DelegateBridge __Hotfix0__UpdateCardPos; // 0x160
	private static DelegateBridge __Hotfix0__UpdateLogoPos; // 0x168
	private static DelegateBridge __Hotfix0_UpdatePos; // 0x170
	private static DelegateBridge __Hotfix0_UpdateColor; // 0x178
	private static DelegateBridge __Hotfix0_AlignInputPos; // 0x180
	private static DelegateBridge __Hotfix0_ToggleBgStyle; // 0x188
	private static DelegateBridge __Hotfix0_ZoomView; // 0x190
	private static DelegateBridge __Hotfix0_ChangeOpMode; // 0x198
	private static DelegateBridge __Hotfix0_FocusOnPos; // 0x1a0
	private static DelegateBridge __Hotfix0_SetBgRaycast; // 0x1a8
	private static DelegateBridge __Hotfix0_SetLogoRaycast; // 0x1b0
	private static DelegateBridge __Hotfix0_SetCardRaycast; // 0x1b8
	private static DelegateBridge __Hotfix0_SetViewportRaycast; // 0x1c0
	private static DelegateBridge __Hotfix0_SetAllCardVisible; // 0x1c8
	private static DelegateBridge __Hotfix0_SetAllForceLineVisible; // 0x1d0
	private static DelegateBridge __Hotfix0_SetAllPointLineVisible; // 0x1d8
	private static DelegateBridge __Hotfix0_SaveBgModified; // 0x1e0
	private static DelegateBridge __Hotfix0_SaveLogoModified; // 0x1e8
	private static DelegateBridge __Hotfix0_SaveColorModified; // 0x1f0
	private static DelegateBridge __Hotfix0_SaveCardModified; // 0x1f8
	private static DelegateBridge __Hotfix0_SaveForceShapeModified; // 0x200
	private static DelegateBridge __Hotfix0_AddForceLine; // 0x208
	private static DelegateBridge __Hotfix0_RemoveForceLine; // 0x210
	private static DelegateBridge __Hotfix0_AddPointLine; // 0x218
	private static DelegateBridge __Hotfix0_RemovePointLine; // 0x220
	private static DelegateBridge __Hotfix0_RemoveForce; // 0x228
	private static DelegateBridge __Hotfix0_AddNewForce; // 0x230
	private static DelegateBridge __Hotfix0_GetClickPos; // 0x238
	private static DelegateBridge __Hotfix0_OnClick; // 0x240
	private static DelegateBridge _c__Hotfix0_ctor; // 0x248

	public Int32 selectForceIndex { get; }
	public Boolean isConfirmState { get; }

	// RVA: 0x2ee7830 VA: 0x75954ff830
	public Int32 get_selectForceIndex() { }
	// RVA: 0x2ee4510 VA: 0x75954fc510
	public Boolean get_isConfirmState() { }
	// RVA: 0x2ee8cdc VA: 0x7595500cdc
	public override Void OnValueChanged(HandBookV2ForceMapEditorProperty property) { }
	// RVA: 0x2eea188 VA: 0x7595502188
	private Void _UpdateForceDropDown() { }
	// RVA: 0x2ee9604 VA: 0x7595501604
	private Void _InitIfNot() { }
	// RVA: 0x2ee98c0 VA: 0x75955018c0
	private Void _RenderForce(HandBookV2ForceData forceData, Boolean isTemp) { }
	// RVA: 0x2ee9a28 VA: 0x7595501a28
	private Void _RenderCard(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee9b84 VA: 0x7595501b84
	private Void _RenderForceLine(Int32 index, HandBookV2ForceLineData lineData) { }
	// RVA: 0x2ee9da0 VA: 0x7595501da0
	private Void _RenderPointLine(Int32 index, HandBookV2PointLineData lineData) { }
	// RVA: 0x2eea9fc VA: 0x75955029fc
	private Vector2 _GetPointPos(Int32 pointIndex) { }
	// RVA: 0x2eea7e8 VA: 0x75955027e8
	private Void _SetPreviewLineActive(Boolean isActive) { }
	// RVA: 0x2eeab7c VA: 0x7595502b7c
	private Void _SetOpDropdownActive(Boolean isActive) { }
	// RVA: 0x2eea764 VA: 0x7595502764
	private Void _SetConfirmPanelActive(Boolean isActive) { }
	// RVA: 0x2eeac10 VA: 0x7595502c10
	private Void _SetSavePanelActive(Boolean isActive) { }
	// RVA: 0x2eeac94 VA: 0x7595502c94
	private Void _SetScaleSliderActive(Boolean isActive) { }
	// RVA: 0x2eead28 VA: 0x7595502d28
	private Void _SetPosInputActive(Boolean isActive) { }
	// RVA: 0x2eeadac VA: 0x7595502dac
	private Void _SetColorInputActive(Boolean isActive) { }
	// RVA: 0x2eeae30 VA: 0x7595502e30
	private Void _SetAddForceLinePanelActive(Boolean isActive) { }
	// RVA: 0x2eeaeb4 VA: 0x7595502eb4
	private Void _ResetTextPoint() { }
	// RVA: 0x2ee5b68 VA: 0x75954fdb68
	public Void SetForceLineListPanelActive(Boolean isActive) { }
	// RVA: 0x2ee5bec VA: 0x75954fdbec
	public Void SetPointLineListPanelActive(Boolean isActive) { }
	// RVA: 0x2ee5c70 VA: 0x75954fdc70
	public Void SetForceListPanelActive(Boolean isActive) { }
	// RVA: 0x2eeaf64 VA: 0x7595502f64
	public Void SetForceSelectPanelActive(Boolean isActive) { }
	// RVA: 0x2ee51d8 VA: 0x75954fd1d8
	public Void SetSliderVal(Single val) { }
	// RVA: 0x2ee506c VA: 0x75954fd06c
	public Void SetPosInput(Vector2 pos) { }
	// RVA: 0x2eeafe8 VA: 0x7595502fe8
	public Void SetColorVal(String colorStr, String cardColorStr) { }
	// RVA: 0x2ee52f0 VA: 0x75954fd2f0
	public Void QuitConfirm(OpEnum opEnum) { }
	// RVA: 0x2ee4a74 VA: 0x75954fca74
	public Void EnterConfirm(OpEnum opEnum) { }
	// RVA: 0x2eeb950 VA: 0x7595503950
	private Void _ClearLineMap() { }
	// RVA: 0x2eeb600 VA: 0x7595503600
	private Void _ClearForceMap() { }
	// RVA: 0x2eebca0 VA: 0x7595503ca0
	public Void SelectForceLine(Int32 lineIdx) { }
	// RVA: 0x2ee5cf4 VA: 0x75954fdcf4
	public Void ClearSelectForceLine() { }
	// RVA: 0x2ee5d70 VA: 0x75954fdd70
	public Void ClearSelectPointLine() { }
	// RVA: 0x2ee5dec VA: 0x75954fddec
	public Void ClearSelectForce() { }
	// RVA: 0x2eebe5c VA: 0x7595503e5c
	public Void SelectPointLine(Int32 lineIdx) { }
	// RVA: 0x2ee4ed4 VA: 0x75954fced4
	public Void SelectPoint(Int32 pointIndex) { }
	// RVA: 0x2eebf6c VA: 0x7595503f6c
	public Void _SelectPoint(Int32 pointIdx, Boolean isSelected) { }
	// RVA: 0x2eec0c4 VA: 0x75955040c4
	public Void _SetPointLineVertText(Int32 pointIndex, Boolean isPoint1) { }
	// RVA: 0x2ee4cc0 VA: 0x75954fccc0
	public Void SelectForce(Int32 forceIndex, OpEnum opEnum) { }
	// RVA: 0x2eec1f8 VA: 0x75955041f8
	private Void _SetSelectForce(Int32 forceIndex, OpEnum m_op, Boolean isSelected) { }
	// RVA: 0x2eec500 VA: 0x7595504500
	private Void _SetLineVertText(Int32 forceIndex, Boolean isPoint1) { }
	// RVA: 0x2ee8510 VA: 0x7595500510
	public Void UpdateLogoScale(Single scale) { }
	// RVA: 0x2ee85d4 VA: 0x75955005d4
	public Void UpdateCardScale(Single scaleVal) { }
	// RVA: 0x2eec63c VA: 0x759550463c
	private Void _UpdateBgPos(Single inputVal, Boolean isXInput) { }
	// RVA: 0x2eec72c VA: 0x759550472c
	private Void _UpdateCardPos(Single val, Boolean isX) { }
	// RVA: 0x2eec81c VA: 0x759550481c
	private Void _UpdateLogoPos(Single val, Boolean isX) { }
	// RVA: 0x2ee8824 VA: 0x7595500824
	public Void UpdatePos(OpEnum op, Single val, Boolean isXInput) { }
	// RVA: 0x2ee8930 VA: 0x7595500930
	public Void UpdateColor() { }
	// RVA: 0x2ee870c VA: 0x759550070c
	public Void AlignInputPos(OpEnum op) { }
	// RVA: 0x2ee7f7c VA: 0x75954fff7c
	public Void ToggleBgStyle(Boolean isSolid) { }
	// RVA: 0x2ee7d78 VA: 0x75954ffd78
	public Void ZoomView(Single zoomVal) { }
	// RVA: 0x2ee4638 VA: 0x75954fc638
	public Void ChangeOpMode(OpEnum opEnum) { }
	// RVA: 0x2eebdb0 VA: 0x7595503db0
	public Void FocusOnPos(Vector2 pos) { }
	// RVA: 0x2ee55cc VA: 0x75954fd5cc
	public Void SetBgRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee580c VA: 0x75954fd80c
	public Void SetLogoRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee59b8 VA: 0x75954fd9b8
	public Void SetCardRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee5778 VA: 0x75954fd778
	public Void SetViewportRaycast(Boolean canRaycast) { }
	// RVA: 0x2eeb090 VA: 0x7595503090
	public Void SetAllCardVisible(Boolean isVisible) { }
	// RVA: 0x2eeb230 VA: 0x7595503230
	public Void SetAllForceLineVisible(Boolean isVisible) { }
	// RVA: 0x2eeb3d0 VA: 0x75955033d0
	public Void SetAllPointLineVisible(Boolean isVisible) { }
	// RVA: 0x2ee5fa0 VA: 0x75954fdfa0
	public Void SaveBgModified() { }
	// RVA: 0x2ee6258 VA: 0x75954fe258
	public Void SaveLogoModified() { }
	// RVA: 0x2ee6744 VA: 0x75954fe744
	public Void SaveColorModified() { }
	// RVA: 0x2ee64c0 VA: 0x75954fe4c0
	public Void SaveCardModified() { }
	// RVA: 0x2ee7004 VA: 0x75954ff004
	public Void SaveForceShapeModified() { }
	// RVA: 0x2ee6aec VA: 0x75954feaec
	public Void AddForceLine() { }
	// RVA: 0x2ee757c VA: 0x75954ff57c
	public Void RemoveForceLine() { }
	// RVA: 0x2ee6dd8 VA: 0x75954fedd8
	public Void AddPointLine() { }
	// RVA: 0x2ee76d8 VA: 0x75954ff6d8
	public Void RemovePointLine() { }
	// RVA: 0x2ee792c VA: 0x75954ff92c
	public Void RemoveForce() { }
	// RVA: 0x2ee7274 VA: 0x75954ff274
	public Void AddNewForce() { }
	// RVA: 0x2eec974 VA: 0x7595504974
	private Vector2 GetClickPos() { }
	// RVA: 0x2eeca3c VA: 0x7595504a3c
	public Void OnClick() { }
	// RVA: 0x2eecf74 VA: 0x7595504f74
	public Void .ctor() { }
	// RVA: 0x2eed2bc VA: 0x75955052bc
	private Void <_InitIfNot>b__54_0(Int32 index) { }
	// RVA: 0x2eed2c0 VA: 0x75955052c0
	private Void <_InitIfNot>b__54_1(Int32 index) { }
	// RVA: 0x2eed2c4 VA: 0x75955052c4
	private Void <_InitIfNot>b__54_2(Int32 index) { }
}
```