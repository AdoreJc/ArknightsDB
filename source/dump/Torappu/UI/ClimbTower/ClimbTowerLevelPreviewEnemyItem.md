# ClimbTowerLevelPreviewEnemyItem

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNormal`

- `Image _viewPart`

- `GameObject _bossLogo`

- `Text _idText`

- `String m_cachedEnemyId`

- `Int32 m_cachedIndex`


## Methods

- `Void Render(EnemyHandBookEverViewModel, Int32)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLevelPreviewEnemyItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelNormal; // 0x20
	private Image _viewPart; // 0x28
	private GameObject _bossLogo; // 0x30
	private Text _idText; // 0x38
	public Action`1 OnJumpToEnemyHandbook; // 0x40
	private String m_cachedEnemyId; // 0x48
	private Int32 m_cachedIndex; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c73748 VA: 0x759528b748
	public Void Render(EnemyHandBookEverViewModel viewModel, Int32 index) { }
	// RVA: 0x2c738a8 VA: 0x759528b8a8
	public Void OnBtnClicked() { }
	// RVA: 0x2c73938 VA: 0x759528b938
	public Void .ctor() { }
}
```