# CooperateDefenceModeManager

**Namespace:** ` `


## Fields

- `CooperateGameMode m_mode`

- `Boolean m_rechallengeCurWave`

- `Int32 m_waveIndexInDefenceMode`

- `Int32 m_waveFinishIndex`

- `CooperateFortressFixerBuildableChecker m_tileBuildableChecker`

- `Int32 m_mapWidth`

- `Int32 m_mapHeight`

- `FP m_bossCurHp`

- `FP m_bossMaxHp`

- `Boolean m_waveFinishEventOn`


## Properties

- `Boolean isLastWave`

- `Int32 curWave`

- `Int32 fortressFinishWave`

- `FP bossCurHp`

- `FP bossMaxHp`


## Methods

- `Boolean get_isLastWave()`

- `Int32 get_curWave()`

- `Int32 get_fortressFinishWave()`

- `FP get_bossCurHp()`

- `FP get_bossMaxHp()`

- `Void OnCardListChanged(Card)`

- `Void OnTryHookCheckWaveNotFinish(Boolean)`

- `Void OnRestingFinished()`

- `IEnumerator OnBeforeWaveStart()`

- `Void RecordBossStatus(FP, FP)`

- `Void _OnUnitBorn(Object)`

- `Boolean <>xLuaBaseProxy_HookGetNextWave()`

- `Void <>xLuaBaseProxy_Init(CooperateGameMode, LevelData)`

- `Void <>xLuaBaseProxy_OnWaveWillStart(WaveData)`

- `Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData)`

- `Int32 <>xLuaBaseProxy_OnGetHpForGameCheck()`

- `Void <>xLuaBaseProxy_RegisterEventListener()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CooperateDefenceModeManager : CooperateSubMode
{
	private CooperateGameMode m_mode; // 0x10
	private Boolean m_rechallengeCurWave; // 0x18
	private Int32 m_waveIndexInDefenceMode; // 0x1c
	private Int32 m_waveFinishIndex; // 0x20
	private CooperateFortressFixerBuildableChecker m_tileBuildableChecker; // 0x28
	private List`1 m_pinnedTiles; // 0x30
	private Int32 m_mapWidth; // 0x38
	private Int32 m_mapHeight; // 0x3c
	private FP m_bossCurHp; // 0x40
	private FP m_bossMaxHp; // 0x48
	private Boolean m_waveFinishEventOn; // 0x50
	private static DelegateBridge __Hotfix0_get_isLastWave; // 0x0
	private static DelegateBridge __Hotfix0_get_curWave; // 0x8
	private static DelegateBridge __Hotfix0_get_fortressFinishWave; // 0x10
	private static DelegateBridge __Hotfix0_get_bossCurHp; // 0x18
	private static DelegateBridge __Hotfix0_get_bossMaxHp; // 0x20
	private static DelegateBridge __Hotfix0_HookGetNextWave; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_OnWaveWillStart; // 0x38
	private static DelegateBridge __Hotfix0_OnWaveWillFinish; // 0x40
	private static DelegateBridge __Hotfix0_OnGetHpForGameCheck; // 0x48
	private static DelegateBridge __Hotfix0_RegisterEventListener; // 0x50
	private static DelegateBridge __Hotfix0_OnCardListChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnTryHookCheckWaveNotFinish; // 0x60
	private static DelegateBridge __Hotfix0_OnRestingFinished; // 0x68
	private static DelegateBridge __Hotfix0_OnBeforeWaveStart; // 0x70
	private static DelegateBridge __Hotfix0_RecordBossStatus; // 0x78
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean isLastWave { get; }
	public Int32 curWave { get; }
	public Int32 fortressFinishWave { get; }
	public FP bossCurHp { get; }
	public FP bossMaxHp { get; }

	// RVA: 0x1cc3170 VA: 0x75942db170
	public Boolean get_isLastWave() { }
	// RVA: 0x1cc9268 VA: 0x75942e1268
	public Int32 get_curWave() { }
	// RVA: 0x1cbe0d0 VA: 0x75942d60d0
	public Int32 get_fortressFinishWave() { }
	// RVA: 0x1cbe1a0 VA: 0x75942d61a0
	public FP get_bossCurHp() { }
	// RVA: 0x1cbe138 VA: 0x75942d6138
	public FP get_bossMaxHp() { }
	// RVA: 0x1cc92d0 VA: 0x75942e12d0
	public override Boolean HookGetNextWave() { }
	// RVA: 0x1cc9334 VA: 0x75942e1334
	public override Void Init(CooperateGameMode gameMode, LevelData levelData) { }
	// RVA: 0x1cc9704 VA: 0x75942e1704
	public override Void OnWaveWillStart(WaveData waveData) { }
	// RVA: 0x1cc97c8 VA: 0x75942e17c8
	public override Void OnWaveWillFinish(WaveData waveData) { }
	// RVA: 0x1cc9858 VA: 0x75942e1858
	public override Int32 OnGetHpForGameCheck() { }
	// RVA: 0x1cc9910 VA: 0x75942e1910
	public override Void RegisterEventListener() { }
	// RVA: 0x1cc1530 VA: 0x75942d9530
	public Void OnCardListChanged(Card card) { }
	// RVA: 0x1cc32c4 VA: 0x75942db2c4
	public Void OnTryHookCheckWaveNotFinish(Boolean schedulerResult) { }
	// RVA: 0x1cc667c VA: 0x75942de67c
	public Void OnRestingFinished() { }
	// RVA: 0x1cc9a18 VA: 0x75942e1a18
	public IEnumerator OnBeforeWaveStart() { }
	// RVA: 0x1cbeca8 VA: 0x75942d6ca8
	public Void RecordBossStatus(FP hp, FP maxHp) { }
	// RVA: 0x1cc9aec VA: 0x75942e1aec
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x1cbf970 VA: 0x75942d7970
	public Void .ctor() { }
	// RVA: 0x1cc9dc4 VA: 0x75942e1dc4
	private Boolean <>xLuaBaseProxy_HookGetNextWave() { }
	// RVA: 0x1cc9dc8 VA: 0x75942e1dc8
	private Void <>xLuaBaseProxy_Init(CooperateGameMode P0, LevelData P1) { }
	// RVA: 0x1cc9dcc VA: 0x75942e1dcc
	private Void <>xLuaBaseProxy_OnWaveWillStart(WaveData P0) { }
	// RVA: 0x1cc9dd0 VA: 0x75942e1dd0
	private Void <>xLuaBaseProxy_OnWaveWillFinish(WaveData P0) { }
	// RVA: 0x1cc9dd4 VA: 0x75942e1dd4
	private Int32 <>xLuaBaseProxy_OnGetHpForGameCheck() { }
	// RVA: 0x1cc9dd8 VA: 0x75942e1dd8
	private Void <>xLuaBaseProxy_RegisterEventListener() { }
}
```