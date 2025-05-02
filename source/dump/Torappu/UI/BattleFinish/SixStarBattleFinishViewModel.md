# SixStarBattleFinishViewModel

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `BattleInfoViewModel battleInfoViewModel`

- `FinishBattleRespExtraSixStarData m_sixStarData`

- `Int32 <runeRankBeforeBattle>k__BackingField`

- `Int32 <runeRankAfterBattle>k__BackingField`


## Properties

- `Int32 runeRankBeforeBattle`

- `Int32 runeRankAfterBattle`

- `Int32 totalScoreBeforeBattle`

- `Int32 totalScoreAfterBattle`

- `String stageName`

- `String stageCode`


## Methods

- `Int32 get_runeRankBeforeBattle()`

- `Void set_runeRankBeforeBattle(Int32)`

- `Int32 get_runeRankAfterBattle()`

- `Void set_runeRankAfterBattle(Int32)`

- `Int32 get_totalScoreBeforeBattle()`

- `Int32 get_totalScoreAfterBattle()`

- `String get_stageName()`

- `String get_stageCode()`

- `Void LoadData(CommonFinishBattleResponse)`

- `Void _UpdateRuneData(String)`

- `Void _UpdateBattleInfoViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class SixStarBattleFinishViewModel : IHotfixable
{
	public BattleInfoViewModel battleInfoViewModel; // 0x10
	private FinishBattleRespExtraSixStarData m_sixStarData; // 0x18
	private Int32 <runeRankBeforeBattle>k__BackingField; // 0x20
	private Int32 <runeRankAfterBattle>k__BackingField; // 0x24
	private static DelegateBridge __Hotfix0_get_runeRankBeforeBattle; // 0x0
	private static DelegateBridge __Hotfix0_set_runeRankBeforeBattle; // 0x8
	private static DelegateBridge __Hotfix0_get_runeRankAfterBattle; // 0x10
	private static DelegateBridge __Hotfix0_set_runeRankAfterBattle; // 0x18
	private static DelegateBridge __Hotfix0_get_totalScoreBeforeBattle; // 0x20
	private static DelegateBridge __Hotfix0_get_totalScoreAfterBattle; // 0x28
	private static DelegateBridge __Hotfix0_get_stageName; // 0x30
	private static DelegateBridge __Hotfix0_get_stageCode; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__UpdateRuneData; // 0x48
	private static DelegateBridge __Hotfix0__UpdateBattleInfoViewModel; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int32 runeRankBeforeBattle { get; set; }
	public Int32 runeRankAfterBattle { get; set; }
	public Int32 totalScoreBeforeBattle { get; }
	public Int32 totalScoreAfterBattle { get; }
	public String stageName { get; }
	public String stageCode { get; }

	// RVA: 0x2e94ad4 VA: 0x75954acad4
	public Int32 get_runeRankBeforeBattle() { }
	// RVA: 0x2e9615c VA: 0x75954ae15c
	private Void set_runeRankBeforeBattle(Int32 value) { }
	// RVA: 0x2e94b3c VA: 0x75954acb3c
	public Int32 get_runeRankAfterBattle() { }
	// RVA: 0x2e961d8 VA: 0x75954ae1d8
	private Void set_runeRankAfterBattle(Int32 value) { }
	// RVA: 0x2e94ed0 VA: 0x75954aced0
	public Int32 get_totalScoreBeforeBattle() { }
	// RVA: 0x2e94f48 VA: 0x75954acf48
	public Int32 get_totalScoreAfterBattle() { }
	// RVA: 0x2e95ad8 VA: 0x75954adad8
	public String get_stageName() { }
	// RVA: 0x2e95a44 VA: 0x75954ada44
	public String get_stageCode() { }
	// RVA: 0x2e95588 VA: 0x75954ad588
	public Void LoadData(CommonFinishBattleResponse outputFinishResponse) { }
	// RVA: 0x2e96254 VA: 0x75954ae254
	private Void _UpdateRuneData(String stageId) { }
	// RVA: 0x2e96398 VA: 0x75954ae398
	private Void _UpdateBattleInfoViewModel(String stageId) { }
	// RVA: 0x2e95fd0 VA: 0x75954adfd0
	public Void .ctor() { }
}
```