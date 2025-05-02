# Act1BossRushMileStoneState

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `Act1BossRushMileStoneView _view`

- `RectTransform _topMenu`

- `Act1BossRushMileStoneStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _OnItemClick(String)`

- `Void _OnGetAllClick()`

- `Void _InitIfNot()`

- `Void _RefreshView()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_OnItemClick>b__7_0(BossRushRewardMileStoneResponse)`

- `Void <_OnGetAllClick>b__8_0(BossRushRewardAllMileStoneResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMileStoneState : PopupFadeState, IHotfixable
{
	private Act1BossRushMileStoneView _view; // 0x70
	private RectTransform _topMenu; // 0x78
	private Act1BossRushMileStoneStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0__OnGetAllClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__RefreshView; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31925ac VA: 0x75957aa5ac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3192614 VA: 0x75957aa614
	protected override Void OnEnter() { }
	// RVA: 0x3192988 VA: 0x75957aa988
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3192b1c VA: 0x75957aab1c
	private Void _OnItemClick(String mileStoneId) { }
	// RVA: 0x3192e58 VA: 0x75957aae58
	private Void _OnGetAllClick() { }
	// RVA: 0x3192690 VA: 0x75957aa690
	private Void _InitIfNot() { }
	// RVA: 0x3192840 VA: 0x75957aa840
	private Void _RefreshView() { }
	// RVA: 0x31932dc VA: 0x75957ab2dc
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x31933e0 VA: 0x75957ab3e0
	public Void .ctor() { }
	// RVA: 0x3193538 VA: 0x75957ab538
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x3193560 VA: 0x75957ab560
	private Void <_OnItemClick>b__7_0(BossRushRewardMileStoneResponse response) { }
	// RVA: 0x31935e4 VA: 0x75957ab5e4
	private Void <_OnGetAllClick>b__8_0(BossRushRewardAllMileStoneResponse response) { }
	// RVA: 0x3193668 VA: 0x75957ab668
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3193670 VA: 0x75957ab670
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```