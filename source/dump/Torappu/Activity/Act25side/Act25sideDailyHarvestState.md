# Act25sideDailyHarvestState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Act25sideDailyHarvestView _view`

- `UIAnimationLocation _enterAnim`

- `Act25sideDailyHarvestStateBean m_cachedBean`

- `Boolean m_inited`

- `Act25SideData m_cachedData`

- `ItemVoucherData m_cachedItemData`

- `AnimationSwitchTween m_enterAnim`


## Methods

- `Void _InitIfNot()`

- `Void _Refresh()`

- `Void EventClose()`

- `Void OnRewardClick()`

- `Void OnRuleClick()`

- `Void _AddTopState()`

- `Void _SendGetItem()`

- `Void _ProcessGetItemResp(VoucherItemDetailResponse)`

- `Void _DataToHarvestRule(IStateBean)`

- `Void _DataToRewardState(IStateBean)`

- `Void _EventOnHarvest()`

- `AnimationSwitchTween _EnsureAnim()`

- `Void OnMessage(Int32, ValueBundle)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_SendGetItem>b__20_0(VoucherItemDetailResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideDailyHarvestState : PopupFloatState, IValueMsgReceiver
{
	private Act25sideDailyHarvestView _view; // 0x70
	private UIAnimationLocation _enterAnim; // 0x78
	public const Int32 ON_PROGRESS_TIMEOUT; // 0x0
	private Act25sideDailyHarvestStateBean m_cachedBean; // 0x88
	private Boolean m_inited; // 0x90
	private Act25SideData m_cachedData; // 0x98
	private ItemVoucherData m_cachedItemData; // 0xa0
	private AnimationSwitchTween m_enterAnim; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__Refresh; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x38
	private static DelegateBridge __Hotfix0_EventClose; // 0x40
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x48
	private static DelegateBridge __Hotfix0_OnRuleClick; // 0x50
	private static DelegateBridge __Hotfix0__AddTopState; // 0x58
	private static DelegateBridge __Hotfix0__SendGetItem; // 0x60
	private static DelegateBridge __Hotfix0__ProcessGetItemResp; // 0x68
	private static DelegateBridge __Hotfix0__DataToHarvestRule; // 0x70
	private static DelegateBridge __Hotfix0__DataToRewardState; // 0x78
	private static DelegateBridge __Hotfix0__EventOnHarvest; // 0x80
	private static DelegateBridge __Hotfix0__EnsureAnim; // 0x88
	private static DelegateBridge __Hotfix0_OnMessage; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x32771a4 VA: 0x759588f1a4
	protected override Void OnEnter() { }
	// RVA: 0x32776e8 VA: 0x759588f6e8
	protected override Void OnResume() { }
	// RVA: 0x3277778 VA: 0x759588f778
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32772cc VA: 0x759588f2cc
	private Void _InitIfNot() { }
	// RVA: 0x3277534 VA: 0x759588f534
	private Void _Refresh() { }
	// RVA: 0x3277af8 VA: 0x759588faf8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3277b60 VA: 0x759588fb60
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3277cf4 VA: 0x759588fcf4
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x3277e10 VA: 0x759588fe10
	public Void EventClose() { }
	// RVA: 0x3277e84 VA: 0x759588fe84
	public Void OnRewardClick() { }
	// RVA: 0x32780f8 VA: 0x75958900f8
	public Void OnRuleClick() { }
	// RVA: 0x VA: 0x0
	private Void _AddTopState() { }
	// RVA: 0x3277f04 VA: 0x759588ff04
	private Void _SendGetItem() { }
	// RVA: 0x3278178 VA: 0x7595890178
	private Void _ProcessGetItemResp(VoucherItemDetailResponse resp) { }
	// RVA: 0x3278240 VA: 0x7595890240
	private Void _DataToHarvestRule(IStateBean stateBean) { }
	// RVA: 0x3278328 VA: 0x7595890328
	private Void _DataToRewardState(IStateBean stateBean) { }
	// RVA: 0x3278408 VA: 0x7595890408
	private Void _EventOnHarvest() { }
	// RVA: 0x3277604 VA: 0x759588f604
	private AnimationSwitchTween _EnsureAnim() { }
	// RVA: 0x32785d0 VA: 0x75958905d0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3278674 VA: 0x7595890674
	public Void .ctor() { }
	// RVA: 0x3278720 VA: 0x7595890720
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x3278748 VA: 0x7595890748
	private Void <_SendGetItem>b__20_0(VoucherItemDetailResponse response) { }
	// RVA: 0x327874c VA: 0x759589074c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3278754 VA: 0x7595890754
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x327875c VA: 0x759589075c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3278764 VA: 0x7595890764
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x327878c VA: 0x759589078c
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
}
```