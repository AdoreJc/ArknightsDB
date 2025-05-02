# EnemyDuelOperationRankItemView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Color _defaultRankCol`

- `Color _playerRankCol`

- `Color _defaultNameCol`

- `Color _playerNameCol`

- `Color _outNameCol`

- `Color _loseMoneyCol`

- `Color _outMoneyCol`

- `Color _losePlayerMoneyCol`

- `Color _winDefaultMoneyCol`

- `Color _winPlayerMoneyCol`

- `ThreeStateToggle _bgToggle`

- `TwoStateToggle _outToggle`

- `Text _winCnt`

- `GameObject _winStreakPanel`

- `Image _avatar`

- `Text _rank`

- `Text _name`

- `Text _moneyChange`

- `Text _currMoney`

- `Tween m_arrowTween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(OperationRoundRankItemModel)`

- `Void _RenderPlayer(OperationRoundRankItemModel)`

- `Void _RenderOut(OperationRoundRankItemModel)`

- `Void _RenderDefault(OperationRoundRankItemModel)`

- `Void _RenderAvatar(OperationRoundRankItemModel)`

- `Void _PlayMoneyTween(Text, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelOperationRankItemView : MonoBehaviour, IHotfixable
{
	private const String NO_CHANGE_TEXT; // 0x0
	private const Single MONEY_TWEEN_START_TIME; // 0x0
	private const Single MONEY_TWEEN_DURATION; // 0x0
	private Color _defaultRankCol; // 0x18
	private Color _playerRankCol; // 0x28
	private Color _defaultNameCol; // 0x38
	private Color _playerNameCol; // 0x48
	private Color _outNameCol; // 0x58
	private Color _loseMoneyCol; // 0x68
	private Color _outMoneyCol; // 0x78
	private Color _losePlayerMoneyCol; // 0x88
	private Color _winDefaultMoneyCol; // 0x98
	private Color _winPlayerMoneyCol; // 0xa8
	private ThreeStateToggle _bgToggle; // 0xb8
	private TwoStateToggle _outToggle; // 0xc0
	private Text _winCnt; // 0xc8
	private GameObject _winStreakPanel; // 0xd0
	private Image _avatar; // 0xd8
	private Text _rank; // 0xe0
	private Text _name; // 0xe8
	private Text _moneyChange; // 0xf0
	private Text _currMoney; // 0xf8
	private Tween m_arrowTween; // 0x100
	private UIPageFinder m_pageFinder; // 0x108
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderPlayer; // 0x8
	private static DelegateBridge __Hotfix0__RenderOut; // 0x10
	private static DelegateBridge __Hotfix0__RenderDefault; // 0x18
	private static DelegateBridge __Hotfix0__RenderAvatar; // 0x20
	private static DelegateBridge __Hotfix0__PlayMoneyTween; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x298c770 VA: 0x7594fa4770
	public Void Render(OperationRoundRankItemModel model) { }
	// RVA: 0x298c8f4 VA: 0x7594fa48f4
	private Void _RenderPlayer(OperationRoundRankItemModel model) { }
	// RVA: 0x298cbd0 VA: 0x7594fa4bd0
	private Void _RenderOut(OperationRoundRankItemModel model) { }
	// RVA: 0x298cdfc VA: 0x7594fa4dfc
	private Void _RenderDefault(OperationRoundRankItemModel model) { }
	// RVA: 0x298d364 VA: 0x7594fa5364
	private Void _RenderAvatar(OperationRoundRankItemModel model) { }
	// RVA: 0x298d0f8 VA: 0x7594fa50f8
	private Void _PlayMoneyTween(Text moneyText, Int32 startNum, Int32 endNum) { }
	// RVA: 0x298d49c VA: 0x7594fa549c
	public Void .ctor() { }
}
```