# Act5D0StageController

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Act5D0EntryZoneGroupBinder _entryZoneBinder`

- `Act5D0MapZoneGroupBinder _mapZoneBinder`

- `Act5D0ZoneDescGroupViewProperty m_zoneDescGroupProperty`


## Methods

- `IEnumerator _TrySyncMissionStatus()`

- `IEnumerator <>n__0()`

- `IEnumerator <>xLuaBaseProxy_LoadCoroutine()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0StageController : ActivityStageController
{
	private Act5D0EntryZoneGroupBinder _entryZoneBinder; // 0x60
	private Act5D0MapZoneGroupBinder _mapZoneBinder; // 0x68
	private Act5D0ZoneDescGroupViewProperty m_zoneDescGroupProperty; // 0x70
	private static DelegateBridge __Hotfix0_LoadCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_get_staticActivityId; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x18
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x20
	private static DelegateBridge __Hotfix0__TrySyncMissionStatus; // 0x28
	private static DelegateBridge __Hotfix0_GetAct5D0PlayerInfo; // 0x30
	private static DelegateBridge __Hotfix0_GetAct5D0PlayerInfoFromPlayerData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public static String staticActivityId { get; }

	// RVA: 0x31bb4dc VA: 0x75957d34dc
	public override IEnumerator LoadCoroutine() { }
	// RVA: 0x31bb5b0 VA: 0x75957d35b0
	public static String get_staticActivityId() { }
	// RVA: 0x31bb68c VA: 0x75957d368c
	protected override Void OnLoaded() { }
	// RVA: 0x31bbb30 VA: 0x75957d3b30
	protected override Void OnStageTimeout() { }
	// RVA: 0x31bbc70 VA: 0x75957d3c70
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x31bbd48 VA: 0x75957d3d48
	private IEnumerator _TrySyncMissionStatus() { }
	// RVA: 0x31bbe1c VA: 0x75957d3e1c
	public static PlayerAct5D0Activity GetAct5D0PlayerInfo(String actId) { }
	// RVA: 0x31bbeb4 VA: 0x75957d3eb4
	public static PlayerAct5D0Activity GetAct5D0PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x31bbf74 VA: 0x75957d3f74
	public Void .ctor() { }
	// RVA: 0x31bc08c VA: 0x75957d408c
	private IEnumerator <>n__0() { }
	// RVA: 0x31bc094 VA: 0x75957d4094
	private IEnumerator <>xLuaBaseProxy_LoadCoroutine() { }
	// RVA: 0x31bc09c VA: 0x75957d409c
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x31bc0a4 VA: 0x75957d40a4
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
}
```