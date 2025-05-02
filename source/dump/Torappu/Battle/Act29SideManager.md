# Act29SideManager

**Namespace:** `Torappu.Battle`


## Fields

- `BuffData _portalTrapsActiveBuff`

- `String _enthuCamEff`

- `String _depressedCamEff`

- `PeriodicTimer m_switchTimer`

- `PeriodicTimer m_audioBuffDurationTimer`

- `PeriodicTimer m_portalTrapActiveTimer`

- `PeriodicTimer m_audioBuffDurationTimer_bossCtrl`

- `Int32 m_currentStage`

- `AudioType m_currentAudioType`

- `Single m_durationPortalActive`

- `Single m_durationBossAudioBuff`

- `Int32 m_currentActivePortalTrapIndex`

- `Boolean m_uiSignalTriggeredSkillManually`

- `Boolean m_isControlledByBoss`

- `Boolean m_isBossDead`

- `AudioType m_lastAudioType`

- `AudioType m_lastAudioTypeNormal`

- `CameraEffect m_enthEff`

- `CameraEffect m_depEff`

- `Act29sideAudioController m_audioController`


## Properties

- `AudioType currentAudioType`

- `Single audioBuffRamainingTime`

- `Single audioTypeRamainingTime`

- `Int32 currentStage`

- `Boolean isControlledByBoss`

- `Boolean uiSignalTriggeredSkillManually`

- `Boolean isBossDead`

- `Single bossAudioBuffTime`

- `Single bossAudioBuffProgress`


## Methods

- `AudioType get_currentAudioType()`

- `Single get_audioBuffRamainingTime()`

- `Single get_audioTypeRamainingTime()`

- `Int32 get_currentStage()`

- `Boolean get_isControlledByBoss()`

- `Boolean get_uiSignalTriggeredSkillManually()`

- `Void set_uiSignalTriggeredSkillManually(Boolean)`

- `Boolean get_isBossDead()`

- `Single get_bossAudioBuffTime()`

- `Single get_bossAudioBuffProgress()`

- `Void RegisterPortalTraps(Trap)`

- `Void SwitchAudioTypeManually()`

- `Void SwitchAudioByBoss(AudioType, Single, Boolean, Boolean)`

- `Void MuteAll()`

- `Void OnDestroy()`

- `Void _OnUnitBorn(Object)`

- `Void _OnGameStart(Object)`

- `Void _OnGameOver(Object)`

- `Void _ProcessBlackboard()`

- `AudioType _NextSwitchSide(Int32)`

- `Void _ResetSwitchTimer(Int32)`

- `Void _ResetAudioBuffDurationTimer(Int32)`

- `Void _ActiveProperPortalTrap()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act29SideManager : EnvManager, IBuffSource, IHotfixable
{
	private BuffData _portalTrapsActiveBuff; // 0x28
	private String _enthuCamEff; // 0x30
	private String _depressedCamEff; // 0x38
	private const String m_none; // 0x0
	private const String m_enthusiasitc; // 0x0
	private const String m_depressed; // 0x0
	private const String m_durationAudioBuffStr; // 0x0
	private const String m_durationBossAudioBuffStr; // 0x0
	private const String m_durationPortalActiveStr; // 0x0
	private const String m_portalTrapActiveBuffName; // 0x0
	private const String m_portlexiId; // 0x0
	private const String m_playExtraAudioStr; // 0x0
	private PeriodicTimer m_switchTimer; // 0x40
	private PeriodicTimer m_audioBuffDurationTimer; // 0x48
	private PeriodicTimer m_portalTrapActiveTimer; // 0x50
	private PeriodicTimer m_audioBuffDurationTimer_bossCtrl; // 0x58
	private List`1 m_switchIntervalList; // 0x60
	private List`1 m_switchSideList; // 0x68
	private Int32 m_currentStage; // 0x70
	private AudioType m_currentAudioType; // 0x74
	private List`1 m_durationAudioBuff; // 0x78
	private Single m_durationPortalActive; // 0x80
	private Single m_durationBossAudioBuff; // 0x84
	private List`1 m_portalTraps; // 0x88
	private Int32 m_currentActivePortalTrapIndex; // 0x90
	private Boolean m_uiSignalTriggeredSkillManually; // 0x94
	private Boolean m_isControlledByBoss; // 0x95
	private Boolean m_isBossDead; // 0x96
	private AudioType m_lastAudioType; // 0x98
	private AudioType m_lastAudioTypeNormal; // 0x9c
	private CameraEffect m_enthEff; // 0xa0
	private CameraEffect m_depEff; // 0xa8
	private Act29sideAudioController m_audioController; // 0xb0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0_get_currentAudioType; // 0x8
	private static DelegateBridge __Hotfix0_get_audioBuffRamainingTime; // 0x10
	private static DelegateBridge __Hotfix0_get_audioTypeRamainingTime; // 0x18
	private static DelegateBridge __Hotfix0_get_currentStage; // 0x20
	private static DelegateBridge __Hotfix0_get_isControlledByBoss; // 0x28
	private static DelegateBridge __Hotfix0_get_switchIntervalList; // 0x30
	private static DelegateBridge __Hotfix0_get_durationAudioBuff; // 0x38
	private static DelegateBridge __Hotfix0_get_switchSideList; // 0x40
	private static DelegateBridge __Hotfix0_get_uiSignalTriggeredSkillManually; // 0x48
	private static DelegateBridge __Hotfix0_set_uiSignalTriggeredSkillManually; // 0x50
	private static DelegateBridge __Hotfix0_get_isBossDead; // 0x58
	private static DelegateBridge __Hotfix0_get_bossAudioBuffTime; // 0x60
	private static DelegateBridge __Hotfix0_get_bossAudioBuffProgress; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x70
	private static DelegateBridge __Hotfix0_OnTick; // 0x78
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x80
	private static DelegateBridge __Hotfix0_RegisterPortalTraps; // 0x88
	private static DelegateBridge __Hotfix0_SwitchAudioTypeManually; // 0x90
	private static DelegateBridge __Hotfix0_SwitchAudioByBoss; // 0x98
	private static DelegateBridge __Hotfix0_MuteAll; // 0xa0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa8
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0xb0
	private static DelegateBridge __Hotfix0__OnGameStart; // 0xb8
	private static DelegateBridge __Hotfix0__OnGameOver; // 0xc0
	private static DelegateBridge __Hotfix0__ProcessBlackboard; // 0xc8
	private static DelegateBridge __Hotfix0__NextSwitchSide; // 0xd0
	private static DelegateBridge __Hotfix0__ResetSwitchTimer; // 0xd8
	private static DelegateBridge __Hotfix0__ResetAudioBuffDurationTimer; // 0xe0
	private static DelegateBridge __Hotfix0__ActiveProperPortalTrap; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public override IEnumerable`1 eventGroups { get; }
	public AudioType currentAudioType { get; }
	public Single audioBuffRamainingTime { get; }
	public Single audioTypeRamainingTime { get; }
	public Int32 currentStage { get; }
	public Boolean isControlledByBoss { get; }
	public List`1 switchIntervalList { get; }
	public List`1 durationAudioBuff { get; }
	public List`1 switchSideList { get; }
	public Boolean uiSignalTriggeredSkillManually { get; set; }
	public Boolean isBossDead { get; }
	public Single bossAudioBuffTime { get; }
	public Single bossAudioBuffProgress { get; }

	// RVA: 0x402e41c VA: 0x759664641c
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x402e6bc VA: 0x75966466bc
	public AudioType get_currentAudioType() { }
	// RVA: 0x402e724 VA: 0x7596646724
	public Single get_audioBuffRamainingTime() { }
	// RVA: 0x402e7e8 VA: 0x75966467e8
	public Single get_audioTypeRamainingTime() { }
	// RVA: 0x402e8d0 VA: 0x75966468d0
	public Int32 get_currentStage() { }
	// RVA: 0x402e938 VA: 0x7596646938
	public Boolean get_isControlledByBoss() { }
	// RVA: 0x402e9a0 VA: 0x75966469a0
	public List`1 get_switchIntervalList() { }
	// RVA: 0x402ea08 VA: 0x7596646a08
	public List`1 get_durationAudioBuff() { }
	// RVA: 0x402ea70 VA: 0x7596646a70
	public List`1 get_switchSideList() { }
	// RVA: 0x402ead8 VA: 0x7596646ad8
	public Boolean get_uiSignalTriggeredSkillManually() { }
	// RVA: 0x402eb40 VA: 0x7596646b40
	public Void set_uiSignalTriggeredSkillManually(Boolean value) { }
	// RVA: 0x402ebc0 VA: 0x7596646bc0
	public Boolean get_isBossDead() { }
	// RVA: 0x402ec28 VA: 0x7596646c28
	public Single get_bossAudioBuffTime() { }
	// RVA: 0x402ec90 VA: 0x7596646c90
	public Single get_bossAudioBuffProgress() { }
	// RVA: 0x402ed58 VA: 0x7596646d58
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x402f9b4 VA: 0x75966479b4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40303c0 VA: 0x75966483c0
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x40304c0 VA: 0x75966484c0
	public Void RegisterPortalTraps(Trap trap) { }
	// RVA: 0x40305bc VA: 0x75966485bc
	public Void SwitchAudioTypeManually() { }
	// RVA: 0x403064c VA: 0x759664864c
	public Void SwitchAudioByBoss(AudioType audioType, Single audioBuffDuration, Boolean firstTime, Boolean toOpposite) { }
	// RVA: 0x4030928 VA: 0x7596648928
	public Void MuteAll() { }
	// RVA: 0x4030ad0 VA: 0x7596648ad0
	protected Void OnDestroy() { }
	// RVA: 0x4030b48 VA: 0x7596648b48
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x4030d0c VA: 0x7596648d0c
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x4030d88 VA: 0x7596648d88
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x402f150 VA: 0x7596647150
	private Void _ProcessBlackboard() { }
	// RVA: 0x40301f0 VA: 0x75966481f0
	private AudioType _NextSwitchSide(Int32 currentStage) { }
	// RVA: 0x402f88c VA: 0x759664788c
	private Void _ResetSwitchTimer(Int32 currentStage) { }
	// RVA: 0x4030290 VA: 0x7596648290
	private Void _ResetAudioBuffDurationTimer(Int32 currentStage) { }
	// RVA: 0x402ff08 VA: 0x7596647f08
	private Void _ActiveProperPortalTrap() { }
	// RVA: 0x4030e18 VA: 0x7596648e18
	public Void .ctor() { }
	// RVA: 0x4030f18 VA: 0x7596648f18
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x4030f1c VA: 0x7596648f1c
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4030f20 VA: 0x7596648f20
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x4030f24 VA: 0x7596648f24
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```