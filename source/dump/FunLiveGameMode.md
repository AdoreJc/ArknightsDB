# FunLiveGameMode

**Namespace:** ` `


## Fields

- `FP m_maxPlayTime`

- `Int32 m_normalEventCnt`

- `Int32 m_normalEventCntPerCast`

- `Int32 m_rareEventCnt`

- `Int32 m_rareEventCntPerCast`

- `Boolean m_haveDangerousEv`

- `String m_levelId`

- `Int32 m_attribIconDiffNum`

- `Boolean m_isTrainingLevel`

- `FunLiveInput m_input`


## Properties

- `Boolean HaveDangerousEvent`

- `Int32 AttribIconDiffNum`

- `Boolean isTrainingLevel`


## Methods

- `Int32 GetFarmRemainingTime()`

- `Int32 GetFarmMaxTime()`

- `Int32 GetEventTotalCnt()`

- `Boolean get_HaveDangerousEvent()`

- `Int32 get_AttribIconDiffNum()`

- `Boolean get_isTrainingLevel()`

- `Int32 GetDefaultEventTotalCnt()`

- `Int32 GetCurrentLevelIndex()`

- `Void _CheckGameFinish()`

- `Void SetRareAndDangerousEventData(String, Int32)`

- `Void CollectTargetInfo(Unit, String)`

- `Boolean ProcessTargetsInfo()`

- `Void ResetData()`

- `Void FunLiveLogEvent()`

- `Void UpdateNormalAndRareEventCnt()`

- `GameModeType <>xLuaBaseProxy_get_gameModeType()`

- `Void <>xLuaBaseProxy_Init(ref, ref, BattlePlayerData, LevelData)`

- `Void <>xLuaBaseProxy_Tick(Action)`

- `SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FunLiveGameMode : DefaultGameMode
{
	public const String FUNLIVE_UI_PLUGIN_PATH; // 0x0
	private Dictionary`2 m_screenShotTargets; // 0x20
	private Dictionary`2 m_targetInfoCount; // 0x28
	private Dictionary`2 m_rareEvent; // 0x30
	private List`1 m_dangerousEventList; // 0x38
	private List`1 m_storedRareEventList; // 0x40
	private List`1 m_storedRareEventPerCastList; // 0x48
	private Dictionary`2 m_storedUnit; // 0x50
	private List`1 m_logEventIdList; // 0x58
	private FP m_maxPlayTime; // 0x60
	private Int32 m_normalEventCnt; // 0x68
	private Int32 m_normalEventCntPerCast; // 0x6c
	private Int32 m_rareEventCnt; // 0x70
	private Int32 m_rareEventCntPerCast; // 0x74
	private Boolean m_haveDangerousEv; // 0x78
	private String m_levelId; // 0x80
	private Int32 m_attribIconDiffNum; // 0x88
	private Boolean m_isTrainingLevel; // 0x8c
	private FunLiveInput m_input; // 0x90
	private static DelegateBridge __Hotfix0_GetFarmRemainingTime; // 0x0
	private static DelegateBridge __Hotfix0_GetFarmMaxTime; // 0x8
	private static DelegateBridge __Hotfix0_GetEventTotalCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_HaveDangerousEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_AttribIconDiffNum; // 0x20
	private static DelegateBridge __Hotfix0_get_isTrainingLevel; // 0x28
	private static DelegateBridge __Hotfix0_GetDefaultEventTotalCnt; // 0x30
	private static DelegateBridge __Hotfix0_GetCurrentLevelIndex; // 0x38
	private static DelegateBridge __Hotfix0_get_gameModeType; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0_get_StoredUnit; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x58
	private static DelegateBridge __Hotfix0_GatherPreloadAssets; // 0x60
	private static DelegateBridge __Hotfix0__GetPreGivenTokens; // 0x68
	private static DelegateBridge __Hotfix0_Tick; // 0x70
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x78
	private static DelegateBridge __Hotfix0__CheckGameFinish; // 0x80
	private static DelegateBridge __Hotfix0_SetRareAndDangerousEventData; // 0x88
	private static DelegateBridge __Hotfix0_CollectTargetInfo; // 0x90
	private static DelegateBridge __Hotfix0_ProcessTargetsInfo; // 0x98
	private static DelegateBridge __Hotfix0_ResetData; // 0xa0
	private static DelegateBridge __Hotfix0_GetEventIdList; // 0xa8
	private static DelegateBridge __Hotfix0_FunLiveLogEvent; // 0xb0
	private static DelegateBridge __Hotfix0_UpdateNormalAndRareEventCnt; // 0xb8

	public Boolean HaveDangerousEvent { get; }
	public Int32 AttribIconDiffNum { get; }
	public Boolean isTrainingLevel { get; }
	public override GameModeType gameModeType { get; }
	public Dictionary`2 StoredUnit { get; }

	// RVA: 0x1cd7e24 VA: 0x75942efe24
	public Int32 GetFarmRemainingTime() { }
	// RVA: 0x1cd7f58 VA: 0x75942eff58
	public Int32 GetFarmMaxTime() { }
	// RVA: 0x1cd7fec VA: 0x75942effec
	public Int32 GetEventTotalCnt() { }
	// RVA: 0x1cd805c VA: 0x75942f005c
	public Boolean get_HaveDangerousEvent() { }
	// RVA: 0x1cd80c4 VA: 0x75942f00c4
	public Int32 get_AttribIconDiffNum() { }
	// RVA: 0x1cd812c VA: 0x75942f012c
	public Boolean get_isTrainingLevel() { }
	// RVA: 0x1cd8194 VA: 0x75942f0194
	public Int32 GetDefaultEventTotalCnt() { }
	// RVA: 0x1cd81fc VA: 0x75942f01fc
	public Int32 GetCurrentLevelIndex() { }
	// RVA: 0x1cd8278 VA: 0x75942f0278
	public override GameModeType get_gameModeType() { }
	// RVA: 0x1cd82e0 VA: 0x75942f02e0
	public Void .ctor(ref GameModeMeta meta) { }
	// RVA: 0x1cd8678 VA: 0x75942f0678
	public Dictionary`2 get_StoredUnit() { }
	// RVA: 0x1cd86e0 VA: 0x75942f06e0
	public override Void Init(ref GameModeMeta meta, ref Int32 randomSeed, BattlePlayerData playerData, LevelData levelData) { }
	// RVA: 0x1cd8b1c VA: 0x75942f0b1c
	public static Dictionary`2 GatherPreloadAssets() { }
	// RVA: 0x1cd8938 VA: 0x75942f0938
	private static List`1 _GetPreGivenTokens(FunLiveInput input) { }
	// RVA: 0x1cd8cdc VA: 0x75942f0cdc
	public override Void Tick(Action doDefaultTick) { }
	// RVA: 0x1cd8ed0 VA: 0x75942f0ed0
	public override SchedulerPreprocessor GetSchedulerPreprocessor() { }
	// RVA: 0x1cd8d70 VA: 0x75942f0d70
	private Void _CheckGameFinish() { }
	// RVA: 0x1cd8f68 VA: 0x75942f0f68
	public Void SetRareAndDangerousEventData(String key, Int32 value) { }
	// RVA: 0x1cd91bc VA: 0x75942f11bc
	public Void CollectTargetInfo(Unit target, String targetInfo) { }
	// RVA: 0x1cd93ac VA: 0x75942f13ac
	public Boolean ProcessTargetsInfo() { }
	// RVA: 0x1cd9b60 VA: 0x75942f1b60
	public Void ResetData() { }
	// RVA: 0x1cd9c74 VA: 0x75942f1c74
	public List`1 GetEventIdList() { }
	// RVA: 0x1cd9f54 VA: 0x75942f1f54
	public Void FunLiveLogEvent() { }
	// RVA: 0x1cda34c VA: 0x75942f234c
	public Void UpdateNormalAndRareEventCnt() { }
	// RVA: 0x1cda400 VA: 0x75942f2400
	private GameModeType <>xLuaBaseProxy_get_gameModeType() { }
	// RVA: 0x1cda468 VA: 0x75942f2468
	private Void <>xLuaBaseProxy_Init(ref GameModeMeta P0, ref Int32 P1, BattlePlayerData P2, LevelData P3) { }
	// RVA: 0x1cda508 VA: 0x75942f2508
	private Void <>xLuaBaseProxy_Tick(Action P0) { }
	// RVA: 0x1cda5b0 VA: 0x75942f25b0
	private SchedulerPreprocessor <>xLuaBaseProxy_GetSchedulerPreprocessor() { }
}
```