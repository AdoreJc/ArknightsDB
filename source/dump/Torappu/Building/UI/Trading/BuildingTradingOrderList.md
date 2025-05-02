# BuildingTradingOrderList

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `RectTransform _orderContainer`

- `BuildingTradingOrderView _orderPrefab`

- `ScrollRect _orderScroll`

- `Text _textOrderNum`

- `Text _textOrderLimit`

- `RectTransform _orderNumLine`

- `ScrollRectSoftMask _scrollMask`

- `Boolean m_isTransiting`

- `Tween m_scrollTween`

- `TOrderSlotGroupViewModel m_pendingChanges`

- `Boolean m_isInited`

- `String m_roomIdCache`

- `ViewModelCache m_curModelCache`

- `Boolean m_focusCompleteOrderFlag`

- `Options <options>k__BackingField`


## Properties

- `Options options`


## Methods

- `Options get_options()`

- `Void set_options(Options)`

- `Void _OnOrderDeleteClicked(Int64)`

- `Void _OnOrderFinishClicked(Int64)`

- `Void _OnLaborAccelClicked()`

- `Void OnEnable()`

- `Void NotifyOrdersDeletedOrDelivered()`

- `Void _InitIfNot()`

- `Void _TransitWhenDataChanged(TOrderSlotGroupViewModel)`

- `Void _RenderInfo()`

- `IEnumerator _UpdateLayoutCoroutine()`

- `Void _TryRegisterAVGFirstOrder()`

- `Void _UpdateViaDeformation()`

- `Void _UpdateViaDeltaWithActionList()`

- `Void _ParseActionList()`

- `Void _ApplyActionsToViews()`

- `Void _RemoveRedunentViews()`

- `Void _ValidateOrderViews(List`1)`

- `Void _FocusCompleteIfNeeded()`

- `Boolean _CheckIfViewVisibleInScroll(BuildingTradingOrderView)`

- `Single _CalcScrollProgressOfOrder(BuildingTradingOrderView)`

- `Void _FocusToStart()`

- `Void _TweenScroll(Single, Single, Single)`

- `IEnumerator _WaitTrainsitionCoroutine()`

- `Void _OnDataChangedFinish()`

- `Void _LogErrorWhenUpdateActionList(String)`

- `BuildingTradingOrderView _AllocOrderView()`

- `Void _RecycleOrderView(BuildingTradingOrderView)`

- `Single <_TweenScroll>b__46_0()`

- `Void <_TweenScroll>b__46_1(Single)`

- `Void <_TweenScroll>b__46_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingOrderList : DataBinder`1, IHotfixable
{
	private const Single SCROLL_TWEEN_DUR; // 0x0
	private RectTransform _orderContainer; // 0x20
	private BuildingTradingOrderView _orderPrefab; // 0x28
	private ScrollRect _orderScroll; // 0x30
	private Text _textOrderNum; // 0x38
	private Text _textOrderLimit; // 0x40
	private RectTransform _orderNumLine; // 0x48
	private ScrollRectSoftMask _scrollMask; // 0x50
	private Boolean m_isTransiting; // 0x58
	private Tween m_scrollTween; // 0x60
	private TOrderSlotGroupViewModel m_pendingChanges; // 0x68
	private Boolean m_isInited; // 0x70
	private String m_roomIdCache; // 0x78
	private ViewModelCache m_curModelCache; // 0x80
	private List`1 m_orderViews; // 0x88
	private Boolean m_focusCompleteOrderFlag; // 0x90
	private List`1 m_actionList; // 0x98
	private List`1 m_sharedList; // 0xa0
	private Options <options>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_options; // 0x0
	private static DelegateBridge __Hotfix0_set_options; // 0x8
	private static DelegateBridge __Hotfix0__OnOrderDeleteClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnOrderFinishClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnLaborAccelClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_NotifyOrdersDeletedOrDelivered; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__TransitWhenDataChanged; // 0x48
	private static DelegateBridge __Hotfix0__RenderInfo; // 0x50
	private static DelegateBridge __Hotfix0__UpdateLayoutCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__TryRegisterAVGFirstOrder; // 0x60
	private static DelegateBridge __Hotfix0__UpdateViaDeformation; // 0x68
	private static DelegateBridge __Hotfix0__UpdateViaDeltaWithActionList; // 0x70
	private static DelegateBridge __Hotfix0__ParseActionList; // 0x78
	private static DelegateBridge __Hotfix0__ApplyActionsToViews; // 0x80
	private static DelegateBridge __Hotfix0__RemoveRedunentViews; // 0x88
	private static DelegateBridge __Hotfix0__ValidateOrderViews; // 0x90
	private static DelegateBridge __Hotfix0__FocusCompleteIfNeeded; // 0x98
	private static DelegateBridge __Hotfix0__CheckIfViewVisibleInScroll; // 0xa0
	private static DelegateBridge __Hotfix0__CalcScrollProgressOfOrder; // 0xa8
	private static DelegateBridge __Hotfix0__FocusToStart; // 0xb0
	private static DelegateBridge __Hotfix0__TweenScroll; // 0xb8
	private static DelegateBridge __Hotfix0__WaitTrainsitionCoroutine; // 0xc0
	private static DelegateBridge __Hotfix0__OnDataChangedFinish; // 0xc8
	private static DelegateBridge __Hotfix0__LogErrorWhenUpdateActionList; // 0xd0
	private static DelegateBridge __Hotfix0__AllocOrderView; // 0xd8
	private static DelegateBridge __Hotfix0__RecycleOrderView; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	private Options options { get; set; }

	// RVA: 0x3d84898 VA: 0x759639c898
	private Options get_options() { }
	// RVA: 0x3d7e630 VA: 0x7596396630
	public Void set_options(Options value) { }
	// RVA: 0x3d84928 VA: 0x759639c928
	private Void _OnOrderDeleteClicked(Int64 orderId) { }
	// RVA: 0x3d849fc VA: 0x759639c9fc
	private Void _OnOrderFinishClicked(Int64 orderId) { }
	// RVA: 0x3d84ad0 VA: 0x759639cad0
	private Void _OnLaborAccelClicked() { }
	// RVA: 0x3d84b88 VA: 0x759639cb88
	private Void OnEnable() { }
	// RVA: 0x3d84cac VA: 0x759639ccac
	public override Void OnValueChanged(TOrderSlotGroupViewProperty property) { }
	// RVA: 0x3d8109c VA: 0x759639909c
	public Void NotifyOrdersDeletedOrDelivered() { }
	// RVA: 0x3d84dbc VA: 0x759639cdbc
	private Void _InitIfNot() { }
	// RVA: 0x3d84e4c VA: 0x759639ce4c
	private Void _TransitWhenDataChanged(TOrderSlotGroupViewModel viewModel) { }
	// RVA: 0x3d850a0 VA: 0x759639d0a0
	private Void _RenderInfo() { }
	// RVA: 0x3d84c00 VA: 0x759639cc00
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x3d85a78 VA: 0x759639da78
	private Void _TryRegisterAVGFirstOrder() { }
	// RVA: 0x3d85214 VA: 0x759639d214
	private Void _UpdateViaDeformation() { }
	// RVA: 0x3d856a0 VA: 0x759639d6a0
	private Void _UpdateViaDeltaWithActionList() { }
	// RVA: 0x3d85ebc VA: 0x759639debc
	private Void _ParseActionList() { }
	// RVA: 0x3d864c0 VA: 0x759639e4c0
	private Void _ApplyActionsToViews() { }
	// RVA: 0x3d872c4 VA: 0x759639f2c4
	private Void _RemoveRedunentViews() { }
	// RVA: 0x3d87690 VA: 0x759639f690
	private Void _ValidateOrderViews(List`1 orderStatusList) { }
	// RVA: 0x3d857b8 VA: 0x759639d7b8
	private Void _FocusCompleteIfNeeded() { }
	// RVA: 0x3d8797c VA: 0x759639f97c
	private Boolean _CheckIfViewVisibleInScroll(BuildingTradingOrderView orderView) { }
	// RVA: 0x3d87b44 VA: 0x759639fb44
	private Single _CalcScrollProgressOfOrder(BuildingTradingOrderView orderView) { }
	// RVA: 0x3d85624 VA: 0x759639d624
	private Void _FocusToStart() { }
	// RVA: 0x3d87cf0 VA: 0x759639fcf0
	private Void _TweenScroll(Single progress, Single duration, Single delay) { }
	// RVA: 0x3d859a4 VA: 0x759639d9a4
	private IEnumerator _WaitTrainsitionCoroutine() { }
	// RVA: 0x3d88044 VA: 0x75963a0044
	private Void _OnDataChangedFinish() { }
	// RVA: 0x3d86e54 VA: 0x759639ee54
	private Void _LogErrorWhenUpdateActionList(String info) { }
	// RVA: 0x3d85cf8 VA: 0x759639dcf8
	private BuildingTradingOrderView _AllocOrderView() { }
	// RVA: 0x3d875b8 VA: 0x759639f5b8
	private Void _RecycleOrderView(BuildingTradingOrderView orderView) { }
	// RVA: 0x3d880f4 VA: 0x75963a00f4
	public Void .ctor() { }
	// RVA: 0x3d88310 VA: 0x75963a0310
	private Single <_TweenScroll>b__46_0() { }
	// RVA: 0x3d8832c VA: 0x75963a032c
	private Void <_TweenScroll>b__46_1(Single val) { }
	// RVA: 0x3d88348 VA: 0x75963a0348
	private Void <_TweenScroll>b__46_2() { }
}
```