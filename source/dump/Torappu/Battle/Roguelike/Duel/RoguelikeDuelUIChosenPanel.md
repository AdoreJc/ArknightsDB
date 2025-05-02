# RoguelikeDuelUIChosenPanel

**Namespace:** `Torappu.Battle.Roguelike.Duel`


## Fields

- `GameObject _refreshEnabledComponent`

- `GameObject _refreshDisabledComponent`

- `GameObject _battleInfoComponent`

- `Text _deployInfoComponent`

- `GameObject _startBattleComponent`

- `GameObject m_refreshEnabled`

- `GameObject m_refreshDisabled`

- `GameObject m_battleInfo`

- `Text m_deployInfo`

- `GameObject m_startBattle`

- `Boolean m_refreshFlag`

- `Single m_refreshTimer`

- `RoguelikeDuelGameMode m_gameMode`


## Methods

- `Void InitData(RoguelikeDuelUIPlugin)`

- `Void UpdateData()`

- `Void _UpdateRefreshState()`

- `Void _UpdateBattleInfoText()`

- `Void OnRefreshBtnClick()`

- `Void OnStartBtnClick()`

- `Void _OnConfirmPanelTrueClick()`

- `Void _OnConfirmPanelFalseClick()`

- `Void _SetRefreshBtnReady()`

- `Void _SetRefreshBtnState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike.Duel
public class RoguelikeDuelUIChosenPanel : MonoBehaviour, IHotfixable
{
	private GameObject _refreshEnabledComponent; // 0x18
	private GameObject _refreshDisabledComponent; // 0x20
	private GameObject _battleInfoComponent; // 0x28
	private Text _deployInfoComponent; // 0x30
	private GameObject _startBattleComponent; // 0x38
	private GameObject m_refreshEnabled; // 0x40
	private GameObject m_refreshDisabled; // 0x48
	private GameObject m_battleInfo; // 0x50
	private Text m_deployInfo; // 0x58
	private GameObject m_startBattle; // 0x60
	private Boolean m_refreshFlag; // 0x68
	private const Single m_refreshCoolDownTime; // 0x0
	private Single m_refreshTimer; // 0x6c
	private RoguelikeDuelGameMode m_gameMode; // 0x70
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__UpdateRefreshState; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBattleInfoText; // 0x18
	private static DelegateBridge __Hotfix0_OnRefreshBtnClick; // 0x20
	private static DelegateBridge __Hotfix0_OnStartBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmPanelTrueClick; // 0x30
	private static DelegateBridge __Hotfix0__OnConfirmPanelFalseClick; // 0x38
	private static DelegateBridge __Hotfix0__SetRefreshBtnReady; // 0x40
	private static DelegateBridge __Hotfix0__SetRefreshBtnState; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1d4bd5c VA: 0x7594363d5c
	public Void InitData(RoguelikeDuelUIPlugin plugin) { }
	// RVA: 0x1d4c130 VA: 0x7594364130
	public Void UpdateData() { }
	// RVA: 0x1d4c1a0 VA: 0x75943641a0
	private Void _UpdateRefreshState() { }
	// RVA: 0x1d4c018 VA: 0x7594364018
	private Void _UpdateBattleInfoText() { }
	// RVA: 0x1d4c2d8 VA: 0x75943642d8
	public Void OnRefreshBtnClick() { }
	// RVA: 0x1d4c43c VA: 0x759436443c
	public Void OnStartBtnClick() { }
	// RVA: 0x1d4c71c VA: 0x759436471c
	private Void _OnConfirmPanelTrueClick() { }
	// RVA: 0x1d4c7f4 VA: 0x75943647f4
	private Void _OnConfirmPanelFalseClick() { }
	// RVA: 0x1d4c3c8 VA: 0x75943643c8
	private Void _SetRefreshBtnReady() { }
	// RVA: 0x1d4c240 VA: 0x7594364240
	private Void _SetRefreshBtnState(Boolean flag) { }
	// RVA: 0x1d4c88c VA: 0x759436488c
	public Void .ctor() { }
}
```