# CrisisV2MissionState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MissionView _view`

- `CrisisV2MissionStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _TryDismissSelf()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnClaimSingleMission(Object)`

- `Void _OnClaimAllMissions()`

- `Void _OnJumpToSlot(Object)`

- `Void _ClaimMissionReward(String, List`1)`

- `Void _OnMissionClaimed(CrisisV2GetMissionRewardsResponse)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void _DataToMapState(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MissionState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 CLAIM_SINGLE_MISSION; // 0x0
	public const Int32 CLAIM_ALL_MISSION; // 0x0
	public const Int32 JUMP_TO_SLOT; // 0x0
	public const Int32 CLOSE_SELF; // 0x0
	private CrisisV2MissionView _view; // 0x70
	private CrisisV2MissionStateBean m_stateBean; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__TryDismissSelf; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnClaimSingleMission; // 0x28
	private static DelegateBridge __Hotfix0__OnClaimAllMissions; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToSlot; // 0x38
	private static DelegateBridge __Hotfix0__ClaimMissionReward; // 0x40
	private static DelegateBridge __Hotfix0__OnMissionClaimed; // 0x48
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x58
	private static DelegateBridge __Hotfix0__DataToMapState; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2bdf234 VA: 0x75951f7234
	private Void _InitIfNot() { }
	// RVA: 0x2bdf2e4 VA: 0x75951f72e4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2bdf34c VA: 0x75951f734c
	protected override Void OnEnter() { }
	// RVA: 0x2bdf458 VA: 0x75951f7458
	private Void _TryDismissSelf() { }
	// RVA: 0x2bdf56c VA: 0x75951f756c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2bdf67c VA: 0x75951f767c
	private Void _OnClaimSingleMission(Object msgObjVal) { }
	// RVA: 0x2bdf840 VA: 0x75951f7840
	private Void _OnClaimAllMissions() { }
	// RVA: 0x2bdf8f8 VA: 0x75951f78f8
	private Void _OnJumpToSlot(Object msgObjVal) { }
	// RVA: 0x2bdfa24 VA: 0x75951f7a24
	private Void _ClaimMissionReward(String mapId, List`1 missions) { }
	// RVA: 0x2bdfc5c VA: 0x75951f7c5c
	private Void _OnMissionClaimed(CrisisV2GetMissionRewardsResponse response) { }
	// RVA: 0x2bdfdac VA: 0x75951f7dac
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x2bdfe94 VA: 0x75951f7e94
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2be000c VA: 0x75951f800c
	private Void _DataToMapState(IStateBean stateBean) { }
	// RVA: 0x2be0130 VA: 0x75951f8130
	public Void .ctor() { }
	// RVA: 0x2be01e0 VA: 0x75951f81e0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2be01e8 VA: 0x75951f81e8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```