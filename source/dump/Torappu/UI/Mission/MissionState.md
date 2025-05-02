# MissionState

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionModel _stateBean`

- `MissionBookViewBase _bookView`


## Methods

- `Void InitData(Nullable`1)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionState : State
{
	private MissionModel _stateBean; // 0x50
	private MissionBookViewBase _bookView; // 0x58
	private static Boolean m_lockFlag; // 0x0
	private const Int32 AUTO_BREAK_MAX; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0__PlayStampSeIfNeed; // 0x20
	private static DelegateBridge __Hotfix0_SendConfirmMissionRequest; // 0x28
	private static DelegateBridge __Hotfix0_SendConfirmMissionGroupRequest; // 0x30
	private static DelegateBridge __Hotfix0_SendExchangeMissionRewardsRequest; // 0x38
	private static DelegateBridge __Hotfix0_SendAutoConfirmMissionsRequest; // 0x40
	private static DelegateBridge __Hotfix0__ShowGain; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x273888c VA: 0x7594d5088c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27388f4 VA: 0x7594d508f4
	protected override Void OnResume() { }
	// RVA: 0x2738968 VA: 0x7594d50968
	public Void InitData(Nullable`1 initMissionType) { }
	// RVA: 0x2738a58 VA: 0x7594d50a58
	private static Void _PlayStampSeIfNeed(MissionType type) { }
	// RVA: 0x2738b18 VA: 0x7594d50b18
	public static Void SendConfirmMissionRequest(String missionID_, MissionType type_) { }
	// RVA: 0x2738d9c VA: 0x7594d50d9c
	public static Void SendConfirmMissionGroupRequest(String missionGroupID_) { }
	// RVA: 0x2738fd8 VA: 0x7594d50fd8
	public static Void SendExchangeMissionRewardsRequest(String missionID_, MissionType type_) { }
	// RVA: 0x2739244 VA: 0x7594d51244
	public static Void SendAutoConfirmMissionsRequest(MissionType type) { }
	// RVA: 0x27394a4 VA: 0x7594d514a4
	private static IEnumerator _ShowGain(List`1 rewardList, MissionType type) { }
	// RVA: 0x2739590 VA: 0x7594d51590
	public Void .ctor() { }
	// RVA: 0x2739600 VA: 0x7594d51600
	private Void <>xLuaBaseProxy_OnResume() { }
}
```