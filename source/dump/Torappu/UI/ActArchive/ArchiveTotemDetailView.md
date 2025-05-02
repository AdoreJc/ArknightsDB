# ArchiveTotemDetailView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Text _nameText`

- `Text _usageText`

- `Text _descText`

- `Image _iconImage`

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `GameObject _redTotemPanel`

- `GameObject _greenTotemPanel`

- `GameObject _blueTotemPanel`

- `GameObject _noneTotemPanel`

- `GameObject _affixPanel`

- `UIPageFinder m_finder`

- `ArchiveTotemController <controller>k__BackingField`


## Properties

- `ArchiveTotemController controller`


## Methods

- `ArchiveTotemController get_controller()`

- `Void set_controller(ArchiveTotemController)`

- `Void Render(TotemItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemDetailView : MonoBehaviour, IHotfixable
{
	private Text _nameText; // 0x18
	private Text _usageText; // 0x20
	private Text _descText; // 0x28
	private Image _iconImage; // 0x30
	private GameObject _normalPanel; // 0x38
	private GameObject _lockedPanel; // 0x40
	private GameObject _redTotemPanel; // 0x48
	private GameObject _greenTotemPanel; // 0x50
	private GameObject _blueTotemPanel; // 0x58
	private GameObject _noneTotemPanel; // 0x60
	private GameObject _affixPanel; // 0x68
	private UIPageFinder m_finder; // 0x70
	private ArchiveTotemController <controller>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ArchiveTotemController controller { get; set; }

	// RVA: 0x308a2b0 VA: 0x75956a22b0
	private ArchiveTotemController get_controller() { }
	// RVA: 0x308a318 VA: 0x75956a2318
	public Void set_controller(ArchiveTotemController value) { }
	// RVA: 0x308a39c VA: 0x75956a239c
	public Void Render(TotemItemModel model) { }
	// RVA: 0x308a768 VA: 0x75956a2768
	public Void .ctor() { }
}
```