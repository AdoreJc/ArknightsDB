# Act3D0StageController

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Act3D0EntryZoneGroupBinder _entryZoneBinder`

- `Act3D0MapZoneGroupBinder _mapZoneBinder`

- `Boolean _useFloat`

- `Act3D0ZoneDescGroupViewProperty m_zoneDescGroupProperty`

- `String m_fakeCampForBGM`


## Methods

- `Void _OnCampConfirmed(Object)`

- `Void TriggerBGMForCampManually(String)`

- `Void _TriggerCampConfirmedAudioSignal()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnRewardTimeout()`

- `String <>xLuaBaseProxy_GetBGMSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0StageController : ActivityStageController
{
	private Act3D0EntryZoneGroupBinder _entryZoneBinder; // 0x60
	private Act3D0MapZoneGroupBinder _mapZoneBinder; // 0x68
	private Boolean _useFloat; // 0x70
	private Act3D0ZoneDescGroupViewProperty m_zoneDescGroupProperty; // 0x78
	private String m_fakeCampForBGM; // 0x80
	private EventPool`1 m_eventPool; // 0x88
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x0
	private static DelegateBridge __Hotfix0_get_staticActivityId; // 0x8
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfCampSelected; // 0x18
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x20
	private static DelegateBridge __Hotfix0__OnCampConfirmed; // 0x28
	private static DelegateBridge __Hotfix0__TryShowCampSelectState; // 0x30
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x38
	private static DelegateBridge __Hotfix0_OnRewardTimeout; // 0x40
	private static DelegateBridge __Hotfix0_GetBGMSignal; // 0x48
	private static DelegateBridge __Hotfix0_TriggerBGMForCampManually; // 0x50
	private static DelegateBridge __Hotfix0__TriggerCampConfirmedAudioSignal; // 0x58
	private static DelegateBridge __Hotfix0_GetAct3D0PlayerInfo; // 0x60
	private static DelegateBridge __Hotfix0_GetAct3D0PlayerInfoFromPlayerData; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public EventPool`1 eventPool { get; }
	public static String staticActivityId { get; }

	// RVA: 0x3228f44 VA: 0x7595840f44
	public EventPool`1 get_eventPool() { }
	// RVA: 0x3228924 VA: 0x7595840924
	public static String get_staticActivityId() { }
	// RVA: 0x3228fac VA: 0x7595840fac
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x3229084 VA: 0x7595841084
	public static Boolean CheckIfCampSelected() { }
	// RVA: 0x3229280 VA: 0x7595841280
	protected override Void OnLoaded() { }
	// RVA: 0x32294a4 VA: 0x75958414a4
	private Void _OnCampConfirmed(Object _) { }
	// RVA: 0x32291ec VA: 0x75958411ec
	private static IEnumerator _TryShowCampSelectState() { }
	// RVA: 0x3229690 VA: 0x7595841690
	protected override Void OnStageTimeout() { }
	// RVA: 0x32297d4 VA: 0x75958417d4
	protected override Void OnRewardTimeout() { }
	// RVA: 0x32298f4 VA: 0x75958418f4
	protected override String GetBGMSignal() { }
	// RVA: 0x3229a00 VA: 0x7595841a00
	public Void TriggerBGMForCampManually(String fakeCampId) { }
	// RVA: 0x322952c VA: 0x759584152c
	private Void _TriggerCampConfirmedAudioSignal() { }
	// RVA: 0x3228a00 VA: 0x7595840a00
	public static PlayerAct3D0Activity GetAct3D0PlayerInfo(String actId) { }
	// RVA: 0x3229a90 VA: 0x7595841a90
	public static PlayerAct3D0Activity GetAct3D0PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x3229b58 VA: 0x7595841b58
	public Void .ctor() { }
	// RVA: 0x3229c90 VA: 0x7595841c90
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x3229c98 VA: 0x7595841c98
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x3229ca0 VA: 0x7595841ca0
	private Void <>xLuaBaseProxy_OnRewardTimeout() { }
	// RVA: 0x3229ca8 VA: 0x7595841ca8
	private String <>xLuaBaseProxy_GetBGMSignal() { }
}
```