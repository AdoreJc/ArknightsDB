# ClimbTowerRewardDetailColumnItem

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textLayer`

- `Text _textLowerItem`

- `Text _textHigherItem`

- `GameObject _pnlHigherItemNoDrop`

- `GameObject _pnlHigherItemDrop`


## Methods

- `Void Render(ClimbTowerRewardInfo, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardDetailColumnItem : MonoBehaviour, IHotfixable
{
	private Text _textLayer; // 0x18
	private Text _textLowerItem; // 0x20
	private Text _textHigherItem; // 0x28
	private GameObject _pnlHigherItemNoDrop; // 0x30
	private GameObject _pnlHigherItemDrop; // 0x38
	private GameObject[] _separators; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c6a1e0 VA: 0x75952821e0
	public Void Render(ClimbTowerRewardInfo rewardInfo, Boolean isLastItem) { }
	// RVA: 0x2c6a390 VA: 0x7595282390
	public Void .ctor() { }
}
```