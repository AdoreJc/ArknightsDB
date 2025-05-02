# ArchiveChaosListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _iconImage`

- `CanvasGroup _selectedGroup`

- `GameObject _newPanel`

- `Button _button`

- `Boolean m_hasInited`

- `ArchiveChaosListItemSwitchTween m_switchTween`

- `String m_cachedId`

- `ArchiveChaosController <controller>k__BackingField`


## Properties

- `ArchiveChaosController controller`


## Methods

- `ArchiveChaosController get_controller()`

- `Void set_controller(ArchiveChaosController)`

- `Void ItemClickEvent()`

- `Void Render(ChaosItemModel, String, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChaosListItemView : MonoBehaviour
{
	private static readonly Color ATTAINED_COLOR; // 0x0
	private static readonly Color UNATTAINED_COLOR; // 0x10
	private Image _iconImage; // 0x18
	private CanvasGroup _selectedGroup; // 0x20
	private GameObject _newPanel; // 0x28
	private Button _button; // 0x30
	private Boolean m_hasInited; // 0x38
	private ArchiveChaosListItemSwitchTween m_switchTween; // 0x40
	private String m_cachedId; // 0x48
	private ArchiveChaosController <controller>k__BackingField; // 0x50

	private ArchiveChaosController controller { get; set; }

	// RVA: 0x304114c VA: 0x759565914c
	private ArchiveChaosController get_controller() { }
	// RVA: 0x3041154 VA: 0x7595659154
	public Void set_controller(ArchiveChaosController value) { }
	// RVA: 0x304115c VA: 0x759565915c
	public Void ItemClickEvent() { }
	// RVA: 0x3040f74 VA: 0x7595658f74
	public Void Render(ChaosItemModel model, String selectedItemId, Boolean showSwitchAnim) { }
	// RVA: 0x30411e8 VA: 0x75956591e8
	private Void _InitIfNot() { }
	// RVA: 0x3041314 VA: 0x7595659314
	public Void .ctor() { }
	// RVA: 0x304131c VA: 0x759565931c
	private static Void .cctor() { }
}
```