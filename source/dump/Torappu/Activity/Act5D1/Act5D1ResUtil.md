# Act5D1ResUtil

**Namespace:** `Torappu.Activity.Act5D1`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ResUtil
{
	public static String CHARACTER_BATTLE_RESULT_ASSIST; // 0x0
	public static String CHARACTER_BATTLE_RESULT_NONE; // 0x8
	public static String CHARACTER_BATTLE_RESULT_BG; // 0x10
	private const String HUB_PATH; // 0x0
	private const String ENTRY_IMG_PATH; // 0x0
	private const String STAGE_GROUP_ICON_PATH; // 0x0
	private const String MAP_PREVIEW; // 0x0
	public const String ACT5D1_ID; // 0x0

	public static PlayerAct5D1Activity playerInfo { get; }
	public static List`1 missionGroup { get; }
	public static List`1 missionData { get; }
	public static Act5D1Data act5d1Data { get; }
	public static BasicData basicData { get; }
	public static CommonTopMenu commonTopMenu { get; }
	public static SpriteHub act5d1SpriteHub { get; }
	public static SpriteHub act5d1SpriteHubForBattleFinish { get; }

	// RVA: 0x31c34b4 VA: 0x75957db4b4
	public static PlayerAct5D1Activity get_playerInfo() { }
	// RVA: 0x31c3db8 VA: 0x75957dbdb8
	public static List`1 get_missionGroup() { }
	// RVA: 0x31c3e10 VA: 0x75957dbe10
	public static List`1 get_missionData() { }
	// RVA: 0x31c3e68 VA: 0x75957dbe68
	public static Boolean IsPermanent(MissionGroup grp) { }
	// RVA: 0x31c3e9c VA: 0x75957dbe9c
	public static Boolean IsRuneMission(MissionData mission) { }
	// RVA: 0x31c3ff8 VA: 0x75957dbff8
	public static MissionData GetMissionData(String missionId) { }
	// RVA: 0x31c40f4 VA: 0x75957dc0f4
	public static Void CheckActiveAndRun(Action action) { }
	// RVA: 0x31c3f2c VA: 0x75957dbf2c
	public static Act5D1Data get_act5d1Data() { }
	// RVA: 0x31c41a4 VA: 0x75957dc1a4
	public static BasicData get_basicData() { }
	// RVA: 0x31c3d34 VA: 0x75957dbd34
	public static PlayerAct5D1Activity GetAct5D1PlayerInfo(String actId) { }
	// RVA: 0x31c4234 VA: 0x75957dc234
	public static PlayerAct5D1Activity GetAct5D1PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x31c42b8 VA: 0x75957dc2b8
	public static Int32 GetGoodBoughtCnt(String goodId) { }
	// RVA: 0x31c439c VA: 0x75957dc39c
	public static ProgressInfo GetProgressGoodInfo(String prgId) { }
	// RVA: 0x31c4480 VA: 0x75957dc480
	public static CommonTopMenu get_commonTopMenu() { }
	// RVA: 0x31c44a0 VA: 0x75957dc4a0
	public static Sprite GetMapImg(String stageId, ILoadAsset assetLoader) { }
	// RVA: 0x31c44a8 VA: 0x75957dc4a8
	public static Sprite GetEntryImg(String stageId) { }
	// RVA: 0x31c46e8 VA: 0x75957dc6e8
	public static RuneStageData GetStageInfo(String stageId) { }
	// RVA: 0x31c4834 VA: 0x75957dc834
	public static BattleStageInfo GenerateBattleStageInfo(String stageId) { }
	// RVA: 0x31c4974 VA: 0x75957dc974
	public static Sprite GetIconImg(String stageId) { }
	// RVA: 0x31c45fc VA: 0x75957dc5fc
	public static SpriteHub get_act5d1SpriteHub() { }
	// RVA: 0x31c4ac8 VA: 0x75957dcac8
	public static Sprite GetIconImgForBattleFinish(String stageId) { }
	// RVA: 0x31c4d28 VA: 0x75957dcd28
	public static Sprite GetEntryImgForBattleFinish(String stageId) { }
	// RVA: 0x31c4c20 VA: 0x75957dcc20
	public static SpriteHub get_act5d1SpriteHubForBattleFinish() { }
	// RVA: 0x31c4e80 VA: 0x75957dce80
	public static RuneStageData GetStageInfoFromBattleFinish(String stageId) { }
	// RVA: 0x31c501c VA: 0x75957dd01c
	public Void .ctor() { }
	// RVA: 0x31c5024 VA: 0x75957dd024
	private static Void .cctor() { }
}
```