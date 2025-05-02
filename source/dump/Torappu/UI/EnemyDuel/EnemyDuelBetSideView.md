# EnemyDuelBetSideView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `PnlBetOperation _pnlBetOperation`

- `PnlBetStand _pnlBetStand`

- `Text _textPlayerNumDesc`

- `EnemyDuelBetSidePlayerListView _playerListView`

- `SimpleLayoutContent _layoutEnemyList`

- `UIColorGraphic _enemyDetailBtnColorGraphic`

- `EnemyDuelBetEnemyDetailPanel _enemyDetailPanel`

- `Boolean m_cachedIsLeft`

- `Adapter m_adapter`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedRefreshPlayerListSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void Render(EnemyDuelBetViewModel, Boolean, Boolean)`

- `Void OnEnemyDetailBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetSideView : MonoBehaviour, IHotfixable
{
	private PnlBetOperation _pnlBetOperation; // 0x18
	private PnlBetStand _pnlBetStand; // 0x20
	private Text _textPlayerNumDesc; // 0x28
	private EnemyDuelBetSidePlayerListView _playerListView; // 0x30
	private SimpleLayoutContent _layoutEnemyList; // 0x38
	private UIColorGraphic _enemyDetailBtnColorGraphic; // 0x40
	private EnemyDuelBetEnemyDetailPanel _enemyDetailPanel; // 0x48
	private List`1 m_cachedEnemyList; // 0x50
	private Boolean m_cachedIsLeft; // 0x58
	private Adapter m_adapter; // 0x60
	private Boolean m_inited; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private Int32 m_cachedRefreshPlayerListSeqNum; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnEnemyDetailBtnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x297ba54 VA: 0x7594f93a54
	private Void _InitIfNot() { }
	// RVA: 0x297bbb8 VA: 0x7594f93bb8
	public Void Render(EnemyDuelBetViewModel model, Boolean isLeft, Boolean isInit) { }
	// RVA: 0x297c04c VA: 0x7594f9404c
	public Void OnEnemyDetailBtnClicked() { }
	// RVA: 0x297c100 VA: 0x7594f94100
	public Void .ctor() { }
}
```