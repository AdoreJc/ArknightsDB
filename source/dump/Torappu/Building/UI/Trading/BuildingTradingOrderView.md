# BuildingTradingOrderView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `BuildingTradingGainedOrderView _gainedPrefab`

- `BuildingTradingGainingOrderView _gainingPrefab`

- `GameObject _emptyPrefab`

- `RectTransform _container`

- `UIAnimationLocation _hideAnim`

- `UIAnimationLocation _showAnim`

- `UIAnimationLocation _reloadAnim`

- `GameObject m_emptyInst`

- `BuildingTradingGainedOrderView m_gainedInst`

- `BuildingTradingGainingOrderView m_gainingInst`

- `Action onLaborAccelClicked`

- `Int64 m_orderId`

- `Boolean <isInited>k__BackingField`

- `OrderStatus <orderStatus>k__BackingField`

- `Tween m_destroyInstTween`

- `CanvasGroup m_destroyAlpha`

- `Tween m_instantInstTween`

- `CanvasGroup m_instantAlpha`

- `UIAnimationTween m_hideViewAnim`

- `UIAnimationTween m_showViewAnim`

- `Coroutine m_reloadCoroutine`


## Properties

- `Boolean isInited`

- `Int64 orderId`

- `OrderStatus orderStatus`

- `Boolean isVisible`

- `Boolean isActing`


## Methods

- `Boolean get_isInited()`

- `Void set_isInited(Boolean)`

- `Int64 get_orderId()`

- `Void set_orderId(Int64)`

- `OrderStatus get_orderStatus()`

- `Void set_orderStatus(OrderStatus)`

- `Boolean get_isVisible()`

- `Boolean get_isActing()`

- `Void DoAction(OrderViewAction, TOrderSlotStruct, TradingInfoViewStruct)`

- `Void RenderImmediately(TOrderSlotStruct, TradingInfoViewStruct)`

- `Void Recycle()`

- `Boolean ValidationCheck(TOrderSlotStruct)`

- `Void _Render(TOrderSlotStruct, TradingInfoViewStruct, Boolean)`

- `Void _UpdateOrderStatus(OrderStatus, Boolean)`

- `Void _HaltAllEffects()`

- `Void _HideAnim()`

- `Void _HideImmediately()`

- `Void _ShowAnim()`

- `Void _ReloadWithAnim(TOrderSlotStruct, TradingInfoViewStruct)`

- `IEnumerator _ReloadCoroutine(TOrderSlotStruct, TradingInfoViewStruct)`

- `Void _DestroyInst(ref, Boolean)`

- `Void _InitContentIfNeeded(PrefabType, ref, Boolean)`

- `CanvasGroup _EnsureCanvasGroup(TargetType)`

- `PrefabType _AllocInstFromPool(PrefabType)`

- `Void _RecycleInstFromPool(PrefabType)`

- `Void _OnDeleteClicked()`

- `Void _OnFinishClicked()`

- `Void _OnLaborAccelClicked()`

- `Void <_HideAnim>b__50_0()`

- `Void <_ShowAnim>b__52_0()`

- `Void <_DestroyInst>b__55_0()`

- `Void <_InitContentIfNeeded>b__56_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingOrderView : MonoBehaviour
{
	private const Single CONTENT_ANIM_DUR; // 0x0
	private const Single RELOAD_ANIM_HIDE_DUR; // 0x0
	private const Single RELOAD_ANIM_SHOW_DUR; // 0x0
	private const Single RELOAD_ANIM_HOLD_DUR; // 0x0
	public const Single RELOAD_ANIM_DELAY_UNIT; // 0x0
	private const Single RELOAD_ANIM_DELAY_MAX_COUNT; // 0x0
	private BuildingTradingGainedOrderView _gainedPrefab; // 0x18
	private BuildingTradingGainingOrderView _gainingPrefab; // 0x20
	private GameObject _emptyPrefab; // 0x28
	private RectTransform _container; // 0x30
	private UIAnimationLocation _hideAnim; // 0x38
	private UIAnimationLocation _showAnim; // 0x48
	private UIAnimationLocation _reloadAnim; // 0x58
	private GameObject m_emptyInst; // 0x68
	private BuildingTradingGainedOrderView m_gainedInst; // 0x70
	private BuildingTradingGainingOrderView m_gainingInst; // 0x78
	public Action`1 onDeleteClicked; // 0x80
	public Action`1 onFinishClicked; // 0x88
	public Action onLaborAccelClicked; // 0x90
	private ListDict`2 m_instPool; // 0x98
	private Int64 m_orderId; // 0xa0
	private Boolean <isInited>k__BackingField; // 0xa8
	private OrderStatus <orderStatus>k__BackingField; // 0xac
	private Tween m_destroyInstTween; // 0xb0
	private CanvasGroup m_destroyAlpha; // 0xb8
	private Tween m_instantInstTween; // 0xc0
	private CanvasGroup m_instantAlpha; // 0xc8
	private UIAnimationTween m_hideViewAnim; // 0xd0
	private UIAnimationTween m_showViewAnim; // 0xd8
	private Coroutine m_reloadCoroutine; // 0xe0

	public Boolean isInited { get; set; }
	public Int64 orderId { get; set; }
	public OrderStatus orderStatus { get; set; }
	public Boolean isVisible { get; }
	public Boolean isActing { get; }

	// RVA: 0x3d886d0 VA: 0x75963a06d0
	public Boolean get_isInited() { }
	// RVA: 0x3d886d8 VA: 0x75963a06d8
	private Void set_isInited(Boolean value) { }
	// RVA: 0x3d886e4 VA: 0x75963a06e4
	public Int64 get_orderId() { }
	// RVA: 0x3d886ec VA: 0x75963a06ec
	public Void set_orderId(Int64 value) { }
	// RVA: 0x3d886f4 VA: 0x75963a06f4
	public OrderStatus get_orderStatus() { }
	// RVA: 0x3d886fc VA: 0x75963a06fc
	private Void set_orderStatus(OrderStatus value) { }
	// RVA: 0x3d87598 VA: 0x759639f598
	public Boolean get_isVisible() { }
	// RVA: 0x3d885fc VA: 0x75963a05fc
	public Boolean get_isActing() { }
	// RVA: 0x3d85ba8 VA: 0x759639dba8
	public Void DoAction(OrderViewAction action, TOrderSlotStruct slotStruct, TradingInfoViewStruct tradingModel) { }
	// RVA: 0x3d8791c VA: 0x759639f91c
	public Void RenderImmediately(TOrderSlotStruct slotStruct, TradingInfoViewStruct tradingModel) { }
	// RVA: 0x3d88df8 VA: 0x75963a0df8
	public Void Recycle() { }
	// RVA: 0x3d878e4 VA: 0x759639f8e4
	public Boolean ValidationCheck(TOrderSlotStruct slotStruct) { }
	// RVA: 0x3d8887c VA: 0x75963a087c
	private Void _Render(TOrderSlotStruct slotStruct, TradingInfoViewStruct tradingModel, Boolean withTransition) { }
	// RVA: 0x3d88e10 VA: 0x75963a0e10
	private Void _UpdateOrderStatus(OrderStatus newStatus, Boolean withTransition) { }
	// RVA: 0x3d88c94 VA: 0x75963a0c94
	private Void _HaltAllEffects() { }
	// RVA: 0x3d88704 VA: 0x75963a0704
	private Void _HideAnim() { }
	// RVA: 0x3d88840 VA: 0x75963a0840
	private Void _HideImmediately() { }
	// RVA: 0x3d88a54 VA: 0x75963a0a54
	private Void _ShowAnim() { }
	// RVA: 0x3d88bbc VA: 0x75963a0bbc
	private Void _ReloadWithAnim(TOrderSlotStruct slotStruct, TradingInfoViewStruct tradingModel) { }
	// RVA: 0x3d88ecc VA: 0x75963a0ecc
	private IEnumerator _ReloadCoroutine(TOrderSlotStruct slotStruct, TradingInfoViewStruct tradingModel) { }
	// RVA: 0x VA: 0x0
	private Void _DestroyInst(ref InstType inst, Boolean withTransition) { }
	// RVA: 0x VA: 0x0
	private Void _InitContentIfNeeded(PrefabType prefab, ref PrefabType inst, Boolean withTransition) { }
	// RVA: 0x VA: 0x0
	private CanvasGroup _EnsureCanvasGroup(TargetType inst) { }
	// RVA: 0x VA: 0x0
	private PrefabType _AllocInstFromPool(PrefabType prefab) { }
	// RVA: 0x VA: 0x0
	private Void _RecycleInstFromPool(PrefabType inst) { }
	// RVA: 0x3d88f80 VA: 0x75963a0f80
	private Void _OnDeleteClicked() { }
	// RVA: 0x3d88fa0 VA: 0x75963a0fa0
	private Void _OnFinishClicked() { }
	// RVA: 0x3d890ec VA: 0x75963a10ec
	private Void _OnLaborAccelClicked() { }
	// RVA: 0x3d89108 VA: 0x75963a1108
	public Void .ctor() { }
	// RVA: 0x3d89198 VA: 0x75963a1198
	private Void <_HideAnim>b__50_0() { }
	// RVA: 0x3d891c8 VA: 0x75963a11c8
	private Void <_ShowAnim>b__52_0() { }
	// RVA: 0x VA: 0x0
	private Void <_DestroyInst>b__55_0() { }
	// RVA: 0x VA: 0x0
	private Void <_InitContentIfNeeded>b__56_0() { }
}
```