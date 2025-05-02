# UIMedalDIYManager

**Namespace:** `Torappu.UI.Medal`


## Fields

- `UIMedalDIYTokenLayouter _tokenLayout`

- `UIMedalDIYCardList _cardList`

- `UIMedalDIYValidPosView _validPosView`

- `GameObject _tokenBlocker`

- `DIYContext m_context`

- `DragStatus m_dragStatus`

- `MedalDIYViewModel m_model`


## Properties

- `MedalDIYViewModel model`


## Methods

- `MedalDIYViewModel get_model()`

- `Void NotifyDataChanged()`

- `Void Init(UIPage)`

- `Void OnDisable()`

- `Void Update()`

- `Void _BeginDragFromToken(String)`

- `Void _DragCardFromList(String, PointerEventData)`

- `Void _EndDragFromToken(String)`

- `Void _PointDownFromToken(String, PointerEventData)`

- `Void _OnMedalTokenReleased()`

- `DragStatus _CreateDragStatus(String, PointerEventData)`

- `Void _ClearDraggingAndResetStatus(Boolean)`

- `Void _ResetAllStatus(Boolean)`

- `Void _UpdateStatus()`

- `PosValidateResult _UpdateStatusLastValidPos(UIMedalDIYFrame)`

- `PosValidateResult _UpdateLastValidPosOnRoute(HexPoint, HexPoint, MedalPosInfo, List`1, UIMedalDIYFrame)`

- `Void _UpdateValidPosView(Boolean)`

- `Void _CalcHexPosLerpInCardList(ListDict`2, ref)`

- `Void _UpdateDataAndNotify(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYManager : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_STEP_COUNT; // 0x0
	private const Int32 REMOVE_TOKEN_DIST; // 0x0
	private const Int32 REMOVE_TOKEN_VERTICE_NUM; // 0x0
	private UIMedalDIYTokenLayouter _tokenLayout; // 0x18
	private UIMedalDIYCardList _cardList; // 0x20
	private UIMedalDIYValidPosView _validPosView; // 0x28
	private GameObject _tokenBlocker; // 0x30
	private DIYContext m_context; // 0x38
	private DragStatus m_dragStatus; // 0x40
	private MedalDIYViewModel m_model; // 0x98
	private ListDict`2 m_sharedMedalPos; // 0xa0
	private List`1 m_sharedPosInfo; // 0xa8
	private ListDict`2 m_sharedLerpInfo; // 0xb0
	private static DelegateBridge __Hotfix0_get_model; // 0x0
	private static DelegateBridge __Hotfix0_NotifyDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__BeginDragFromToken; // 0x28
	private static DelegateBridge __Hotfix0__DragCardFromList; // 0x30
	private static DelegateBridge __Hotfix0__EndDragFromToken; // 0x38
	private static DelegateBridge __Hotfix0__PointDownFromToken; // 0x40
	private static DelegateBridge __Hotfix0__OnMedalTokenReleased; // 0x48
	private static DelegateBridge __Hotfix0__CreateDragStatus; // 0x50
	private static DelegateBridge __Hotfix0__GetLocalCursorPoint; // 0x58
	private static DelegateBridge __Hotfix0__ClearDraggingAndResetStatus; // 0x60
	private static DelegateBridge __Hotfix0__ResetAllStatus; // 0x68
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x70
	private static DelegateBridge __Hotfix0__UpdateStatusLastValidPos; // 0x78
	private static DelegateBridge __Hotfix0__UpdateLastValidPosOnRoute; // 0x80
	private static DelegateBridge __Hotfix0__LoadOtherMedalPosInfoToValidate; // 0x88
	private static DelegateBridge __Hotfix0__UpdateValidPosView; // 0x90
	private static DelegateBridge __Hotfix0__CalcHexPosLerpInCardList; // 0x98
	private static DelegateBridge __Hotfix0__UpdateDataAndNotify; // 0xa0
	private static DelegateBridge __Hotfix0__CheckIfToRemoveLastValidPos; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public MedalDIYViewModel model { get; }

	// RVA: 0x2764450 VA: 0x7594d7c450
	public MedalDIYViewModel get_model() { }
	// RVA: 0x2764f64 VA: 0x7594d7cf64
	public Void NotifyDataChanged() { }
	// RVA: 0x2763d94 VA: 0x7594d7bd94
	public Void Init(UIPage page) { }
	// RVA: 0x2769e34 VA: 0x7594d81e34
	private Void OnDisable() { }
	// RVA: 0x2769ea0 VA: 0x7594d81ea0
	private Void Update() { }
	// RVA: 0x276a16c VA: 0x7594d8216c
	private Void _BeginDragFromToken(String medalId) { }
	// RVA: 0x276a210 VA: 0x7594d82210
	private Void _DragCardFromList(String medalId, PointerEventData eventData) { }
	// RVA: 0x276a718 VA: 0x7594d82718
	private Void _EndDragFromToken(String medalId) { }
	// RVA: 0x276a790 VA: 0x7594d82790
	private Void _PointDownFromToken(String medalId, PointerEventData eventData) { }
	// RVA: 0x276a908 VA: 0x7594d82908
	private Void _OnMedalTokenReleased() { }
	// RVA: 0x276a3cc VA: 0x7594d823cc
	private DragStatus _CreateDragStatus(String medalId, PointerEventData eventData) { }
	// RVA: 0x276ab14 VA: 0x7594d82b14
	private static Boolean _GetLocalCursorPoint(Int32 pointerId, RectTransform local, Camera eventCam, out Vector2 localPos) { }
	// RVA: 0x27698d4 VA: 0x7594d818d4
	private Void _ClearDraggingAndResetStatus(Boolean immediately) { }
	// RVA: 0x2769cf0 VA: 0x7594d81cf0
	private Void _ResetAllStatus(Boolean immediately) { }
	// RVA: 0x2769f4c VA: 0x7594d81f4c
	private Void _UpdateStatus() { }
	// RVA: 0x276af08 VA: 0x7594d82f08
	private PosValidateResult _UpdateStatusLastValidPos(UIMedalDIYFrame frame) { }
	// RVA: 0x276b3dc VA: 0x7594d833dc
	private PosValidateResult _UpdateLastValidPosOnRoute(HexPoint srcPos, HexPoint dstPos, MedalPosInfo targetPos, List`1 otherPos, UIMedalDIYFrame frame) { }
	// RVA: 0x276b17c VA: 0x7594d8317c
	private List`1 _LoadOtherMedalPosInfoToValidate() { }
	// RVA: 0x276a644 VA: 0x7594d82644
	private Void _UpdateValidPosView(Boolean immediately) { }
	// RVA: 0x276ba10 VA: 0x7594d83a10
	private Void _CalcHexPosLerpInCardList(ListDict`2 medalPosList, ref ListDict`2 lerpList) { }
	// RVA: 0x276addc VA: 0x7594d82ddc
	private Void _UpdateDataAndNotify(Boolean immediately) { }
	// RVA: 0x276b7f4 VA: 0x7594d837f4
	private static Boolean _CheckIfToRemoveLastValidPos(HexPoint curPos, HexPoint lastValidPos, PosValidateResult validRet) { }
	// RVA: 0x276c24c VA: 0x7594d8424c
	public Void .ctor() { }
}
```