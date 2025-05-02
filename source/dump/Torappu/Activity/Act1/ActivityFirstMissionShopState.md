# ActivityFirstMissionShopState

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstStateBean _stateBean`

- `TwoStateToggle _missionButton`

- `TwoStateToggle _shopButton`

- `ActivityFirstMissionView _missionView`

- `ActivityFirstShopView _shopView`

- `GameObject _topMenu`

- `Text _coinRemain`

- `ActivityFirstMissionShopEnum m_currentState`


## Methods

- `Void _ApplyState()`

- `Void TweenToMission()`

- `Void TweenToShop()`

- `Void RefreshCoinState()`

- `Void TweenToMap()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator _ReceiveItemsCoroutine(RewardItemModel)`

- `Void SendShopListRequest()`

- `Void AddShopTop(ActivityShopData)`

- `Void SendMissionRequest(String)`

- `Void <SendShopListRequest>b__18_0(ActivityGetShopListResponse)`

- `Void <SendMissionRequest>b__20_0(ActivityConfirmMissionResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMissionShopState : PopupFloatState, IHotfixable
{
	private ActivityFirstStateBean _stateBean; // 0x70
	private TwoStateToggle _missionButton; // 0x78
	private TwoStateToggle _shopButton; // 0x80
	private ActivityFirstMissionView _missionView; // 0x88
	private ActivityFirstShopView _shopView; // 0x90
	private GameObject _topMenu; // 0x98
	private Text _coinRemain; // 0xa0
	private ActivityFirstMissionShopEnum m_currentState; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__ApplyState; // 0x18
	private static DelegateBridge __Hotfix0_TweenToMission; // 0x20
	private static DelegateBridge __Hotfix0_TweenToShop; // 0x28
	private static DelegateBridge __Hotfix0_RefreshCoinState; // 0x30
	private static DelegateBridge __Hotfix0_TweenToMap; // 0x38
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x40
	private static DelegateBridge __Hotfix1__ReceiveItemsCoroutine; // 0x48
	private static DelegateBridge __Hotfix0_SendShopListRequest; // 0x50
	private static DelegateBridge __Hotfix0_AddShopTop; // 0x58
	private static DelegateBridge __Hotfix0_SendMissionRequest; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x348df50 VA: 0x7595aa5f50
	public override IStateBean GetCacheBean() { }
	// RVA: 0x348dfb8 VA: 0x7595aa5fb8
	protected override Void OnEnter() { }
	// RVA: 0x348e254 VA: 0x7595aa6254
	protected override Void OnResume() { }
	// RVA: 0x348e044 VA: 0x7595aa6044
	private Void _ApplyState() { }
	// RVA: 0x348e790 VA: 0x7595aa6790
	public Void TweenToMission() { }
	// RVA: 0x348e7fc VA: 0x7595aa67fc
	public Void TweenToShop() { }
	// RVA: 0x348e1b0 VA: 0x7595aa61b0
	private Void RefreshCoinState() { }
	// RVA: 0x348e86c VA: 0x7595aa686c
	public Void TweenToMap() { }
	// RVA: 0x348e92c VA: 0x7595aa692c
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x348ea14 VA: 0x7595aa6a14
	private IEnumerator _ReceiveItemsCoroutine(RewardItemModel rewarditem) { }
	// RVA: 0x348e300 VA: 0x7595aa6300
	public Void SendShopListRequest() { }
	// RVA: 0x348eb0c VA: 0x7595aa6b0c
	public Void AddShopTop(ActivityShopData shopData) { }
	// RVA: 0x348eca0 VA: 0x7595aa6ca0
	public Void SendMissionRequest(String missionId) { }
	// RVA: 0x348eecc VA: 0x7595aa6ecc
	public Void .ctor() { }
	// RVA: 0x348ef44 VA: 0x7595aa6f44
	private Void <SendShopListRequest>b__18_0(ActivityGetShopListResponse response) { }
	// RVA: 0x348ef88 VA: 0x7595aa6f88
	private Void <SendMissionRequest>b__20_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x348f2f4 VA: 0x7595aa72f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x348f2fc VA: 0x7595aa72fc
	private Void <>xLuaBaseProxy_OnResume() { }
}
```