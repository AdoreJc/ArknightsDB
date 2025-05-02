# ArchiveTotemListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _iconImage`

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `GameObject _newPanel`

- `CanvasGroup _selectedGroup`

- `Button _button`

- `Boolean m_hasInited`

- `ArchiveTotemListItemSwitchTween m_switchTween`

- `UIPageFinder m_finder`

- `String m_cachedId`

- `ArchiveTotemController <controller>k__BackingField`


## Properties

- `ArchiveTotemController controller`


## Methods

- `ArchiveTotemController get_controller()`

- `Void set_controller(ArchiveTotemController)`

- `Void ItemClickEvent()`

- `Void Render(TotemItemModel, String, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemListItemView : MonoBehaviour, IHotfixable
{
	public static readonly Color ATTAINED_COLOR; // 0x0
	public static readonly Color UNATTAINED_COLOR; // 0x10
	private Image _iconImage; // 0x18
	private GameObject _normalPanel; // 0x20
	private GameObject _lockedPanel; // 0x28
	private GameObject _newPanel; // 0x30
	private CanvasGroup _selectedGroup; // 0x38
	private Button _button; // 0x40
	private Boolean m_hasInited; // 0x48
	private ArchiveTotemListItemSwitchTween m_switchTween; // 0x50
	private UIPageFinder m_finder; // 0x58
	private String m_cachedId; // 0x68
	private ArchiveTotemController <controller>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_controller; // 0x20
	private static DelegateBridge __Hotfix0_set_controller; // 0x28
	private static DelegateBridge __Hotfix0_ItemClickEvent; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ArchiveTotemController controller { get; set; }

	// RVA: 0x308b86c VA: 0x75956a386c
	private ArchiveTotemController get_controller() { }
	// RVA: 0x308b590 VA: 0x75956a3590
	public Void set_controller(ArchiveTotemController value) { }
	// RVA: 0x308b8e4 VA: 0x75956a38e4
	public Void ItemClickEvent() { }
	// RVA: 0x308b624 VA: 0x75956a3624
	public Void Render(TotemItemModel model, String selectedItem, Boolean showSwitchAnim) { }
	// RVA: 0x308b9c8 VA: 0x75956a39c8
	private Void _InitIfNot() { }
	// RVA: 0x308bb3c VA: 0x75956a3b3c
	public Void .ctor() { }
	// RVA: 0x308bbbc VA: 0x75956a3bbc
	private static Void .cctor() { }
}
```