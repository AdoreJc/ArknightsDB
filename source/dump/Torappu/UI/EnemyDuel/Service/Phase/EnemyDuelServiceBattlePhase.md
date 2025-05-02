# EnemyDuelServiceBattlePhase

**Namespace:** `Torappu.UI.EnemyDuel.Service.Phase`


## Fields

- `Int32 m_preserveCnt`

- `UInt32 m_receivedStep`

- `UInt32 m_receivedStepNotified`

- `Single m_playSpeed`

- `Single m_playFramesPerTime`

- `Int32 m_stride`

- `Int32 m_leftFrameInStep`

- `Int32 m_leftFrameInStepInFast`

- `Single m_idleStartTime`

- `IEnemyDuelServiceCore <serviceCore>k__BackingField`

- `Setting m_setting`

- `EnemyDuelServiceBattleNetState m_battleNetState`

- `EnemyDuelGameMode m_gameMode`


## Properties

- `IEnemyDuelServiceCore serviceCore`

- `EnemyDuelGameMode gameMode`


## Methods

- `IEnemyDuelServiceCore get_serviceCore()`

- `Void set_serviceCore(IEnemyDuelServiceCore)`

- `EnemyDuelGameMode get_gameMode()`

- `Single _GetWaiteFrameTime()`

- `Void _HandleRoundChanged(Object)`

- `Void _HandleStateChanged(Object)`

- `Void _ClearCachedSteps()`

- `Void _NotifyLoadComplete()`

- `Void RevStepDate(EnemyDuelServiceStepData)`

- `Void _PreserveTo(Int32)`

- `Void _ChangeStatus(EnemyDuelServiceBattleNetState)`

- `Void _AdjustPlaySpeed(Single)`

- `Void _RefreshPlaySpeed()`

- `Int32 _CalculateRemainFrame()`

- `Void _ApplyStepSetting(EnemyDuelServiceStepData)`

- `Boolean _DoBattleStart(StageData, BattleStageInfo, EnemyDuelServiceParam, EnemyDuelServiceBattleInfo, GameModeMeta, Boolean)`

- `Void <>xLuaBaseProxy_FixedUpdate()`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel.Service.Phase
public class EnemyDuelServiceBattlePhase : EnemyDuelServicePhase
{
	private const Int32 INITIAL_PRESERVE_CNT; // 0x0
	private Queue`1 m_cachedSteps; // 0x10
	private Int32 m_preserveCnt; // 0x18
	private UInt32 m_receivedStep; // 0x1c
	private UInt32 m_receivedStepNotified; // 0x20
	private Single m_playSpeed; // 0x24
	private Single m_playFramesPerTime; // 0x28
	private Int32 m_stride; // 0x2c
	private Int32 m_leftFrameInStep; // 0x30
	private Int32 m_leftFrameInStepInFast; // 0x34
	private Single m_idleStartTime; // 0x38
	private IEnemyDuelServiceCore <serviceCore>k__BackingField; // 0x40
	private Setting m_setting; // 0x48
	private EnemyDuelServiceBattleNetState m_battleNetState; // 0x68
	private EnemyDuelGameMode m_gameMode; // 0x70
	private static DelegateBridge __Hotfix0_get_serviceCore; // 0x0
	private static DelegateBridge __Hotfix0_set_serviceCore; // 0x8
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x10
	private static DelegateBridge __Hotfix0__GetWaiteFrameTime; // 0x18
	private static DelegateBridge __Hotfix0_Enter; // 0x20
	private static DelegateBridge __Hotfix0__HandleRoundChanged; // 0x28
	private static DelegateBridge __Hotfix0__HandleStateChanged; // 0x30
	private static DelegateBridge __Hotfix0_Leave; // 0x38
	private static DelegateBridge __Hotfix0__ClearCachedSteps; // 0x40
	private static DelegateBridge __Hotfix0__NotifyLoadComplete; // 0x48
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x50
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x58
	private static DelegateBridge __Hotfix0_RevStepDate; // 0x60
	private static DelegateBridge __Hotfix0__PreserveTo; // 0x68
	private static DelegateBridge __Hotfix0__ChangeStatus; // 0x70
	private static DelegateBridge __Hotfix0__AdjustPlaySpeed; // 0x78
	private static DelegateBridge __Hotfix0__RefreshPlaySpeed; // 0x80
	private static DelegateBridge __Hotfix0__CalculateRemainFrame; // 0x88
	private static DelegateBridge __Hotfix0__ApplyStepSetting; // 0x90
	private static DelegateBridge __Hotfix0__DoBattleStart; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	private IEnemyDuelServiceCore serviceCore { get; set; }
	private EnemyDuelGameMode gameMode { get; }

	// RVA: 0x29aade4 VA: 0x7594fc2de4
	private IEnemyDuelServiceCore get_serviceCore() { }
	// RVA: 0x29aae4c VA: 0x7594fc2e4c
	private Void set_serviceCore(IEnemyDuelServiceCore value) { }
	// RVA: 0x29aaed0 VA: 0x7594fc2ed0
	private EnemyDuelGameMode get_gameMode() { }
	// RVA: 0x29ab06c VA: 0x7594fc306c
	private Single _GetWaiteFrameTime() { }
	// RVA: 0x29ab0f0 VA: 0x7594fc30f0
	public override Void Enter(IEnemyDuelServiceCore core) { }
	// RVA: 0x29aba00 VA: 0x7594fc3a00
	private Void _HandleRoundChanged(Object args) { }
	// RVA: 0x29abc24 VA: 0x7594fc3c24
	private Void _HandleStateChanged(Object args) { }
	// RVA: 0x29abd08 VA: 0x7594fc3d08
	public override Void Leave() { }
	// RVA: 0x29abaf0 VA: 0x7594fc3af0
	private Void _ClearCachedSteps() { }
	// RVA: 0x29abe08 VA: 0x7594fc3e08
	private Void _NotifyLoadComplete() { }
	// RVA: 0x29abee8 VA: 0x7594fc3ee8
	public override Void FixedUpdate() { }
	// RVA: 0x29ac75c VA: 0x7594fc475c
	public override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x29a62a0 VA: 0x7594fbe2a0
	public Void RevStepDate(EnemyDuelServiceStepData step) { }
	// RVA: 0x29ac3c0 VA: 0x7594fc43c0
	private Void _PreserveTo(Int32 frameCount) { }
	// RVA: 0x29ac284 VA: 0x7594fc4284
	private Void _ChangeStatus(EnemyDuelServiceBattleNetState cur) { }
	// RVA: 0x29ac7dc VA: 0x7594fc47dc
	private Void _AdjustPlaySpeed(Single speed) { }
	// RVA: 0x29ac57c VA: 0x7594fc457c
	private Void _RefreshPlaySpeed() { }
	// RVA: 0x29ac870 VA: 0x7594fc4870
	private Int32 _CalculateRemainFrame() { }
	// RVA: 0x29ac448 VA: 0x7594fc4448
	private Void _ApplyStepSetting(EnemyDuelServiceStepData step) { }
	// RVA: 0x29ab52c VA: 0x7594fc352c
	private Boolean _DoBattleStart(StageData stageData, BattleStageInfo overrideStageInfo, EnemyDuelServiceParam actParam, EnemyDuelServiceBattleInfo battle, GameModeMeta gameModeMeta, Boolean isMulti) { }
	// RVA: 0x29ac8f8 VA: 0x7594fc48f8
	public Void .ctor() { }
	// RVA: 0x29ac9ec VA: 0x7594fc49ec
	private Void <>xLuaBaseProxy_FixedUpdate() { }
	// RVA: 0x29aca54 VA: 0x7594fc4a54
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
}
```