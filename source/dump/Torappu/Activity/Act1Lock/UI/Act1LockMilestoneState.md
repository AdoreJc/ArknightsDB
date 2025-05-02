# Act1LockMilestoneState

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `RectTransform _topMenuContainer`

- `Act1LockMilestoneItem _milestoneItemPrefab`

- `RectTransform _listRoot`

- `Text _pointCntText`

- `Button _getBtn`


## Methods

- `Void _InitIfNot()`

- `Void _Refresh(Boolean)`

- `Void EventOnGetAll()`

- `Void _Get(String)`

- `Void _GotThem(List`1)`

- `Void <_InitIfNot>b__8_0()`

- `Void <EventOnGetAll>b__10_0(Act1LockGetMilestoneBatchRespone)`

- `Void <_Get>b__11_0(Act1LockGetMilestoneRespone)`

- `Void <_GotThem>b__12_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMilestoneState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private Act1LockMilestoneItem _milestoneItemPrefab; // 0x78
	private RectTransform _listRoot; // 0x80
	private Text _pointCntText; // 0x88
	private Button _getBtn; // 0x90
	private List`1 m_items; // 0x98
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__Refresh; // 0x18
	private static DelegateBridge __Hotfix0_EventOnGetAll; // 0x20
	private static DelegateBridge __Hotfix0__Get; // 0x28
	private static DelegateBridge __Hotfix0__GotThem; // 0x30
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x339fc28 VA: 0x75959b7c28
	protected override Void OnEnter() { }
	// RVA: 0x33a0204 VA: 0x75959b8204
	protected override Void OnResume() { }
	// RVA: 0x339fc9c VA: 0x75959b7c9c
	private Void _InitIfNot() { }
	// RVA: 0x339ffb8 VA: 0x75959b7fb8
	private Void _Refresh(Boolean afterGet) { }
	// RVA: 0x33a0270 VA: 0x75959b8270
	public Void EventOnGetAll() { }
	// RVA: 0x33a0544 VA: 0x75959b8544
	private Void _Get(String milestoneId) { }
	// RVA: 0x33a0830 VA: 0x75959b8830
	private Void _GotThem(List`1 items) { }
	// RVA: 0x33a0a50 VA: 0x75959b8a50
	public static IEnumerator ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x33a0b54 VA: 0x75959b8b54
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33a0bb8 VA: 0x75959b8bb8
	public Void .ctor() { }
	// RVA: 0x33a0c28 VA: 0x75959b8c28
	private Void <_InitIfNot>b__8_0() { }
	// RVA: 0x33a0c38 VA: 0x75959b8c38
	private Void <EventOnGetAll>b__10_0(Act1LockGetMilestoneBatchRespone response) { }
	// RVA: 0x33a0c50 VA: 0x75959b8c50
	private Void <_Get>b__11_0(Act1LockGetMilestoneRespone response) { }
	// RVA: 0x33a0c68 VA: 0x75959b8c68
	private Void <_GotThem>b__12_0() { }
	// RVA: 0x33a0c70 VA: 0x75959b8c70
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x33a0c78 VA: 0x75959b8c78
	private Void <>xLuaBaseProxy_OnResume() { }
}
```