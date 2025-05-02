# ArchiveChaosSideView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _iconImage`

- `Text _nameText`

- `Text _fixedNameText`

- `CanvasGroup _levelGroup`

- `Text _usageText`

- `Text _descText`

- `GameObject _attainedPanel`

- `GameObject _unattainedPanel`

- `ArchiveChaosController <controller>k__BackingField`


## Properties

- `ArchiveChaosController controller`


## Methods

- `ArchiveChaosController get_controller()`

- `Void set_controller(ArchiveChaosController)`

- `Void Render(ChaosItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChaosSideView : MonoBehaviour
{
	private static readonly Color ICON_ATTAINED_COLOR; // 0x0
	private static readonly Color ICON_UNATTAINED_COLOR; // 0x10
	private static readonly Color NAME_ATTAINED_COLOR; // 0x20
	private static readonly Color NAME_UNATTAINED_COLOR; // 0x30
	private Image _iconImage; // 0x18
	private Text _nameText; // 0x20
	private Text _fixedNameText; // 0x28
	private CanvasGroup _levelGroup; // 0x30
	private Text _usageText; // 0x38
	private Text _descText; // 0x40
	private GameObject _attainedPanel; // 0x48
	private GameObject _unattainedPanel; // 0x50
	private ArchiveChaosController <controller>k__BackingField; // 0x58

	private ArchiveChaosController controller { get; set; }

	// RVA: 0x3042d10 VA: 0x759565ad10
	private ArchiveChaosController get_controller() { }
	// RVA: 0x3042d18 VA: 0x759565ad18
	public Void set_controller(ArchiveChaosController value) { }
	// RVA: 0x304089c VA: 0x759565889c
	public Void Render(ChaosItemModel model) { }
	// RVA: 0x3042d20 VA: 0x759565ad20
	public Void .ctor() { }
	// RVA: 0x3042d28 VA: 0x759565ad28
	private static Void .cctor() { }
}
```