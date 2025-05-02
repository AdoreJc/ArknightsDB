# Act1LockMissionsState

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `RectTransform _topMenuContainer`

- `Act1LockMissionItem _itemPrefab`

- `Transform _listRoot`

- `Text _pointText`

- `Button _getBtn`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateStatus()`

- `Void _Get(String)`

- `Void EventOnGetAll()`

- `Void _HandleGet(List`1)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void <_InitIfNot>b__9_0()`

- `Void <_HandleGet>b__13_0(ActivityMissionCheckResponse)`

- `Void <_HandleGet>b__13_2()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMissionsState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private Act1LockMissionItem _itemPrefab; // 0x78
	private Transform _listRoot; // 0x80
	private Text _pointText; // 0x88
	private Button _getBtn; // 0x90
	private List`1 m_items; // 0x98
	private List`1 m_missions; // 0xa0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x18
	private static DelegateBridge __Hotfix0__Get; // 0x20
	private static DelegateBridge __Hotfix0_EventOnGetAll; // 0x28
	private static DelegateBridge __Hotfix0__HandleGet; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x33a0fa4 VA: 0x75959b8fa4
	protected override Void OnEnter() { }
	// RVA: 0x33a18f4 VA: 0x75959b98f4
	protected override Void OnResume() { }
	// RVA: 0x33a1014 VA: 0x75959b9014
	private Void _InitIfNot() { }
	// RVA: 0x33a14c8 VA: 0x75959b94c8
	private Void _UpdateStatus() { }
	// RVA: 0x33a195c VA: 0x75959b995c
	private Void _Get(String missionId) { }
	// RVA: 0x33a1da0 VA: 0x75959b9da0
	public Void EventOnGetAll() { }
	// RVA: 0x33a1ab4 VA: 0x75959b9ab4
	private Void _HandleGet(List`1 msIds) { }
	// RVA: 0x33a1f68 VA: 0x75959b9f68
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x33a2068 VA: 0x75959ba068
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33a20cc VA: 0x75959ba0cc
	public Void .ctor() { }
	// RVA: 0x33a213c VA: 0x75959ba13c
	private Void <_InitIfNot>b__9_0() { }
	// RVA: 0x33a214c VA: 0x75959ba14c
	private Void <_HandleGet>b__13_0(ActivityMissionCheckResponse response) { }
	// RVA: 0x33a22ec VA: 0x75959ba2ec
	private Void <_HandleGet>b__13_2() { }
	// RVA: 0x33a22f0 VA: 0x75959ba2f0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x33a22f8 VA: 0x75959ba2f8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```