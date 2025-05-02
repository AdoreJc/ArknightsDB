# EnemyDuelBetEnemyItemView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _imgEnemyIcon`

- `Text _textEnemyCountLeft`

- `Text _textEnemyCountRight`

- `GameObject _pnlEnemyCountLeft`

- `GameObject _pnlEnemyCountRight`

- `GameObject _pnlNormal`

- `GameObject _pnlEmpty`

- `UIColorGraphic _colorGraphic`

- `UIStateFinder m_stateFinder`

- `String m_cachedEnemyId`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void Render(EnemyDuelBetEnemyViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetEnemyItemView : MonoBehaviour, IHotfixable
{
	private Image _imgEnemyIcon; // 0x18
	private Text _textEnemyCountLeft; // 0x20
	private Text _textEnemyCountRight; // 0x28
	private GameObject _pnlEnemyCountLeft; // 0x30
	private GameObject _pnlEnemyCountRight; // 0x38
	private GameObject _pnlNormal; // 0x40
	private GameObject _pnlEmpty; // 0x48
	private UIColorGraphic _colorGraphic; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private String m_cachedEnemyId; // 0x68
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x2979d0c VA: 0x7594f91d0c
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2979d74 VA: 0x7594f91d74
	public Void Render(EnemyDuelBetEnemyViewModel enemyViewModel, Boolean isLeft) { }
	// RVA: 0x2979f48 VA: 0x7594f91f48
	public Void .ctor() { }
}
```