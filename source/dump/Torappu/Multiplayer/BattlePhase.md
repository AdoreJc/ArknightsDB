# BattlePhase

**Namespace:** `Torappu.Multiplayer`


## Fields

- `Int32 m_preserveCnt`

- `UInt32 m_receivedStep`

- `UInt32 m_receivedStepNotified`

- `Single m_playSpeed`

- `Single m_playFramesOnce`

- `Int32 m_stride`

- `Int32 m_leftFrameInStep`

- `Int32 m_leftFrameInStepInFast`

- `Single m_idleStartTime`

- `MultiplayerSetting m_setting`

- `IMultiplayerGameMode m_gameMode`

- `CooperateGameMode m_coopGameMode`

- `GameBattleStatus m_status`


## Methods

- `Single _GetWaiteFrameTime()`

- `Void _RealBattleStart(StageData, MultiplayerInput, BattleStageInfo, MultiplayerActParam, BattleInfo, GameModeMeta)`

- `Void _ReplayBattleStart(StageData, BattleStageInfo, MultiplayerActParam, GameModeMeta)`

- `MultiplayerSquadData _TryParsePlayerData(UserInfo)`

- `Void _NotifyLoadComplete()`

- `Void RevStepDate(StepData)`

- `Void _PreserveTo(Int32)`

- `Void _ChangeStatus(GameBattleStatus)`

- `Void _AdjustPlaySpeed(Single)`

- `Void _RefreshPlaySpeed()`

- `Int32 _CalculateRemainFrame()`

- `Void _ApplyStepSetting(StepData)`

- `Void <>xLuaBaseProxy_FixedUpdate()`

- `Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class BattlePhase : MultiBattlePhase
{
	private const Int32 INITIAL_PRESERVE_CNT; // 0x0
	private Queue`1 m_cachedSteps; // 0x10
	private Int32 m_preserveCnt; // 0x18
	private UInt32 m_receivedStep; // 0x1c
	private UInt32 m_receivedStepNotified; // 0x20
	private Single m_playSpeed; // 0x24
	private Single m_playFramesOnce; // 0x28
	private Int32 m_stride; // 0x2c
	private Int32 m_leftFrameInStep; // 0x30
	private Int32 m_leftFrameInStepInFast; // 0x34
	private Single m_idleStartTime; // 0x38
	private MultiplayerSetting m_setting; // 0x40
	private IMultiplayerGameMode m_gameMode; // 0x60
	private CooperateGameMode m_coopGameMode; // 0x68
	private GameBattleStatus m_status; // 0x70
	private static DelegateBridge __Hotfix0__GetWaiteFrameTime; // 0x0
	private static DelegateBridge __Hotfix0_Enter; // 0x8
	private static DelegateBridge __Hotfix0__RealBattleStart; // 0x10
	private static DelegateBridge __Hotfix0__ReplayBattleStart; // 0x18
	private static DelegateBridge __Hotfix0_Leave; // 0x20
	private static DelegateBridge __Hotfix0__CreatePackedRuneData; // 0x28
	private static DelegateBridge __Hotfix0__TryParsePlayerData; // 0x30
	private static DelegateBridge __Hotfix0__NotifyLoadComplete; // 0x38
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x40
	private static DelegateBridge __Hotfix0_OnNetStateChanged; // 0x48
	private static DelegateBridge __Hotfix0_RevStepDate; // 0x50
	private static DelegateBridge __Hotfix0__PreserveTo; // 0x58
	private static DelegateBridge __Hotfix0__ChangeStatus; // 0x60
	private static DelegateBridge __Hotfix0__AdjustPlaySpeed; // 0x68
	private static DelegateBridge __Hotfix0__RefreshPlaySpeed; // 0x70
	private static DelegateBridge __Hotfix0__CalculateRemainFrame; // 0x78
	private static DelegateBridge __Hotfix0__ApplyStepSetting; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x3587e78 VA: 0x7595b9fe78
	private Single _GetWaiteFrameTime() { }
	// RVA: 0x3587efc VA: 0x7595b9fefc
	public override Void Enter() { }
	// RVA: 0x35890f0 VA: 0x7595ba10f0
	private Void _RealBattleStart(StageData stageData, MultiplayerInput multiplayerInput, BattleStageInfo overrideStageInfo, MultiplayerActParam actParam, BattleInfo battle, GameModeMeta gameModeMeta) { }
	// RVA: 0x358955c VA: 0x7595ba155c
	private Void _ReplayBattleStart(StageData stageData, BattleStageInfo stageInfo, MultiplayerActParam actParam, GameModeMeta gameModeMeta) { }
	// RVA: 0x3589d24 VA: 0x7595ba1d24
	public override Void Leave() { }
	// RVA: 0x35899a0 VA: 0x7595ba19a0
	private List`1 _CreatePackedRuneData(MultiplayerInput multiplayerInput, MultiplayerActParam actParam) { }
	// RVA: 0x3588c38 VA: 0x7595ba0c38
	private MultiplayerSquadData _TryParsePlayerData(UserInfo player) { }
	// RVA: 0x3589f2c VA: 0x7595ba1f2c
	private Void _NotifyLoadComplete() { }
	// RVA: 0x358a0ac VA: 0x7595ba20ac
	public override Void FixedUpdate() { }
	// RVA: 0x358b0cc VA: 0x7595ba30cc
	public override Void OnNetStateChanged(ConnectionState state) { }
	// RVA: 0x358b14c VA: 0x7595ba314c
	public Void RevStepDate(StepData step) { }
	// RVA: 0x358ac1c VA: 0x7595ba2c1c
	private Void _PreserveTo(Int32 frameCount) { }
	// RVA: 0x358a98c VA: 0x7595ba298c
	private Void _ChangeStatus(GameBattleStatus cur) { }
	// RVA: 0x358b2d0 VA: 0x7595ba32d0
	private Void _AdjustPlaySpeed(Single speed) { }
	// RVA: 0x358ae0c VA: 0x7595ba2e0c
	private Void _RefreshPlaySpeed() { }
	// RVA: 0x358b364 VA: 0x7595ba3364
	private Int32 _CalculateRemainFrame() { }
	// RVA: 0x358aca4 VA: 0x7595ba2ca4
	private Void _ApplyStepSetting(StepData step) { }
	// RVA: 0x358b3f4 VA: 0x7595ba33f4
	public Void .ctor() { }
	// RVA: 0x358b4e8 VA: 0x7595ba34e8
	private Void <>xLuaBaseProxy_FixedUpdate() { }
	// RVA: 0x358b550 VA: 0x7595ba3550
	private Void <>xLuaBaseProxy_OnNetStateChanged(ConnectionState P0) { }
}
```