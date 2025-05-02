# BuildingWorkshopBonusItem

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `Image _icon`

- `Image _imgProgress`

- `Text _textProgress`

- `BonusItemModel m_curModel`


## Methods

- `Void Render(BonusItemModel)`

- `Sprite _LoadIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopBonusItem : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Image _imgProgress; // 0x20
	private Text _textProgress; // 0x28
	private BonusItemModel m_curModel; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadIcon; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d6b7cc VA: 0x75963837cc
	public Void Render(BonusItemModel model) { }
	// RVA: 0x3d6ba10 VA: 0x7596383a10
	private Sprite _LoadIcon(String bonusId) { }
	// RVA: 0x3d6bcb0 VA: 0x7596383cb0
	public Void .ctor() { }
}
```