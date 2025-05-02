# Act5D0ResUtil

**Namespace:** `Torappu.Activity.Act5D0`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0ResUtil : IHotfixable
{
	private const String PANEL_MISSION_RES_PATH; // 0x0
	private const String PANEL_MILESTONE_RES_PATH; // 0x0
	private const String HUB_PATH; // 0x0
	public static Single MILESTONE_HEIGHT; // 0x0
	public static Single MILESTONE_DELTA_HEIGHT; // 0x4
	public static Single MILESTONE_OFFSET; // 0x8
	private static DelegateBridge __Hotfix0_get_activityId; // 0x10
	private static DelegateBridge __Hotfix0_GetMissionResPath; // 0x18
	private static DelegateBridge __Hotfix0_GetMileStoneResPath; // 0x20
	private static DelegateBridge __Hotfix0_get_uiItemCard; // 0x28
	private static DelegateBridge __Hotfix0_get_commonTopMenu; // 0x30
	private static DelegateBridge __Hotfix0_get_playerInfo; // 0x38
	private static DelegateBridge __Hotfix0_get_act5d0Data; // 0x40
	private static DelegateBridge __Hotfix0_get_basicData; // 0x48
	private static DelegateBridge __Hotfix0_GetMissionGroup; // 0x50
	private static DelegateBridge __Hotfix0_getMissionData; // 0x58
	private static DelegateBridge __Hotfix0_GetAct5D0PlayerInfo; // 0x60
	private static DelegateBridge __Hotfix0_GetAct5D0PlayerInfoFromPlayerData; // 0x68
	private static DelegateBridge __Hotfix0_get_entrySpriteHub; // 0x70
	private static DelegateBridge __Hotfix0_GetMissionItemResHolder; // 0x78
	private static DelegateBridge __Hotfix0_GetMileStoneItemResHolder; // 0x80
	private static DelegateBridge __Hotfix0_get_mileStoneToken; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public static String activityId { get; }
	public static UIItemCard uiItemCard { get; }
	public static CommonTopMenu commonTopMenu { get; }
	public static PlayerAct5D0Activity playerInfo { get; }
	public static Act5D0Data act5d0Data { get; }
	public static BasicData basicData { get; }
	public static SpriteHub entrySpriteHub { get; }
	public static UIItemViewModel mileStoneToken { get; }

	// RVA: 0x31b92e0 VA: 0x75957d12e0
	public static String get_activityId() { }
	// RVA: 0x31b93dc VA: 0x75957d13dc
	public static String GetMissionResPath(DifficultyLevel level) { }
	// RVA: 0x31b94dc VA: 0x75957d14dc
	public static String GetMileStoneResPath(PartType part) { }
	// RVA: 0x31b9630 VA: 0x75957d1630
	public static UIItemCard get_uiItemCard() { }
	// RVA: 0x31b96ac VA: 0x75957d16ac
	public static CommonTopMenu get_commonTopMenu() { }
	// RVA: 0x31b9728 VA: 0x75957d1728
	public static PlayerAct5D0Activity get_playerInfo() { }
	// RVA: 0x31b97dc VA: 0x75957d17dc
	public static Act5D0Data get_act5d0Data() { }
	// RVA: 0x31b9970 VA: 0x75957d1970
	public static BasicData get_basicData() { }
	// RVA: 0x31b9a44 VA: 0x75957d1a44
	public static MissionGroup GetMissionGroup(String actId) { }
	// RVA: 0x31b9b88 VA: 0x75957d1b88
	public static MissionData getMissionData(String missionID, String activityID) { }
	// RVA: 0x31b9cec VA: 0x75957d1cec
	public static PlayerAct5D0Activity GetAct5D0PlayerInfo(String actId) { }
	// RVA: 0x31b9dac VA: 0x75957d1dac
	public static PlayerAct5D0Activity GetAct5D0PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x31b9e88 VA: 0x75957d1e88
	public static SpriteHub get_entrySpriteHub() { }
	// RVA: 0x31b9fb0 VA: 0x75957d1fb0
	public static Act5D0MissionResHolder GetMissionItemResHolder(DifficultyLevel level) { }
	// RVA: 0x31ba174 VA: 0x75957d2174
	public static Act5D0MileStoneResHolder GetMileStoneItemResHolder(PartType part) { }
	// RVA: 0x31ba338 VA: 0x75957d2338
	public static UIItemViewModel get_mileStoneToken() { }
	// RVA: 0x31ba404 VA: 0x75957d2404
	public Void .ctor() { }
	// RVA: 0x31ba484 VA: 0x75957d2484
	private static Void .cctor() { }
}
```