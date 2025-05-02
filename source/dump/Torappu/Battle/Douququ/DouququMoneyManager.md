# DouququMoneyManager

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `Int64 m_currentMoney`

- `Int64 m_betMoney`

- `Int64 m_rewardMoney`

- `Int32 m_lastBetCnt`

- `Choice m_currentChoice`

- `Selection m_currentSelection`

- `DouququGameMode m_gameMode`

- `Boolean m_isWin`

- `Int64 m_maxMoney`


## Properties

- `Int64 currentMoney`

- `Boolean isMoneyFull`

- `Int64 betMoney`

- `Int64 rewardMoney`

- `Int32 lastBetCnt`

- `Choice currentChoice`

- `Selection currentSelection`

- `Boolean win`


## Methods

- `Int64 get_currentMoney()`

- `Void set_currentMoney(Int64)`

- `Boolean get_isMoneyFull()`

- `Int64 get_betMoney()`

- `Void set_betMoney(Int64)`

- `Int64 get_rewardMoney()`

- `Void set_rewardMoney(Int64)`

- `Int32 get_lastBetCnt()`

- `Choice get_currentChoice()`

- `Selection get_currentSelection()`

- `Boolean get_win()`

- `Void Init(DouququGameMode)`

- `Void OnGameOver()`

- `Void OnChooseStart(Boolean)`

- `Void OnBetPreStart(Selection)`

- `Void OnBetStart()`

- `Void OnRoundEnd(RoundResult)`

- `Single GetOdds()`

- `Void _LogRoundPlayerResult()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class DouququMoneyManager : IHotfixable
{
	private Int64 m_currentMoney; // 0x10
	private Int64 m_betMoney; // 0x18
	private Int64 m_rewardMoney; // 0x20
	private Int32 m_lastBetCnt; // 0x28
	private Choice m_currentChoice; // 0x2c
	private Selection m_currentSelection; // 0x30
	private DouququGameMode m_gameMode; // 0x38
	private Boolean m_isWin; // 0x40
	private Int64 m_maxMoney; // 0x48
	private static DelegateBridge __Hotfix0_get_currentMoney; // 0x0
	private static DelegateBridge __Hotfix0_set_currentMoney; // 0x8
	private static DelegateBridge __Hotfix0_get_isMoneyFull; // 0x10
	private static DelegateBridge __Hotfix0_get_betMoney; // 0x18
	private static DelegateBridge __Hotfix0_set_betMoney; // 0x20
	private static DelegateBridge __Hotfix0_get_rewardMoney; // 0x28
	private static DelegateBridge __Hotfix0_set_rewardMoney; // 0x30
	private static DelegateBridge __Hotfix0_get_lastBetCnt; // 0x38
	private static DelegateBridge __Hotfix0_get_currentChoice; // 0x40
	private static DelegateBridge __Hotfix0_get_currentSelection; // 0x48
	private static DelegateBridge __Hotfix0_get_win; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x58
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x60
	private static DelegateBridge __Hotfix0_OnChooseStart; // 0x68
	private static DelegateBridge __Hotfix0_OnBetPreStart; // 0x70
	private static DelegateBridge __Hotfix0_OnBetStart; // 0x78
	private static DelegateBridge __Hotfix0_OnRoundEnd; // 0x80
	private static DelegateBridge __Hotfix0_GetOdds; // 0x88
	private static DelegateBridge __Hotfix0__LogRoundPlayerResult; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Int64 currentMoney { get; set; }
	public Boolean isMoneyFull { get; }
	public Int64 betMoney { get; set; }
	public Int64 rewardMoney { get; set; }
	public Int32 lastBetCnt { get; }
	public Choice currentChoice { get; }
	public Selection currentSelection { get; }
	public Boolean win { get; }

	// RVA: 0x1dca030 VA: 0x75943e2030
	public Int64 get_currentMoney() { }
	// RVA: 0x1dca098 VA: 0x75943e2098
	private Void set_currentMoney(Int64 value) { }
	// RVA: 0x1dca164 VA: 0x75943e2164
	public Boolean get_isMoneyFull() { }
	// RVA: 0x1dca1dc VA: 0x75943e21dc
	public Int64 get_betMoney() { }
	// RVA: 0x1dca244 VA: 0x75943e2244
	private Void set_betMoney(Int64 value) { }
	// RVA: 0x1dca310 VA: 0x75943e2310
	public Int64 get_rewardMoney() { }
	// RVA: 0x1dca378 VA: 0x75943e2378
	private Void set_rewardMoney(Int64 value) { }
	// RVA: 0x1dca440 VA: 0x75943e2440
	public Int32 get_lastBetCnt() { }
	// RVA: 0x1dca4a8 VA: 0x75943e24a8
	public Choice get_currentChoice() { }
	// RVA: 0x1dca510 VA: 0x75943e2510
	public Selection get_currentSelection() { }
	// RVA: 0x1dca578 VA: 0x75943e2578
	public Boolean get_win() { }
	// RVA: 0x1dca5e0 VA: 0x75943e25e0
	public Void Init(DouququGameMode gameMode) { }
	// RVA: 0x1dca6ec VA: 0x75943e26ec
	public Void OnGameOver() { }
	// RVA: 0x1dca80c VA: 0x75943e280c
	public Void OnChooseStart(Boolean isLeft) { }
	// RVA: 0x1dca898 VA: 0x75943e2898
	public Void OnBetPreStart(Selection selection) { }
	// RVA: 0x1dcaaa0 VA: 0x75943e2aa0
	public Void OnBetStart() { }
	// RVA: 0x1dcab20 VA: 0x75943e2b20
	public Void OnRoundEnd(RoundResult result) { }
	// RVA: 0x1dcadb8 VA: 0x75943e2db8
	public Single GetOdds() { }
	// RVA: 0x1dcac44 VA: 0x75943e2c44
	private Void _LogRoundPlayerResult() { }
	// RVA: 0x1dcae58 VA: 0x75943e2e58
	public Void .ctor() { }
}
```