# ArchiveDisasterListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _iconImage`

- `CanvasGroup _selectedGroup`

- `GameObject _newPanel`

- `Button _button`

- `Boolean m_hasInited`

- `UISwitchTween m_switchTween`

- `String m_cachedDisasterTypeId`

- `ArchiveDisasterController <controller>k__BackingField`


## Properties

- `ArchiveDisasterController controller`


## Methods

- `ArchiveDisasterController get_controller()`

- `Void set_controller(ArchiveDisasterController)`

- `Void ItemClickEvent()`

- `Void Render(DisasterTypeModel, String, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterListItemView : MonoBehaviour, IHotfixable
{
	private static readonly Color ATTAINED_COLOR; // 0x0
	private static readonly Color UNATTAINED_COLOR; // 0x10
	private Image _iconImage; // 0x18
	private CanvasGroup _selectedGroup; // 0x20
	private GameObject _newPanel; // 0x28
	private Button _button; // 0x30
	private Boolean m_hasInited; // 0x38
	private UISwitchTween m_switchTween; // 0x40
	private String m_cachedDisasterTypeId; // 0x48
	private ArchiveDisasterController <controller>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_controller; // 0x20
	private static DelegateBridge __Hotfix0_set_controller; // 0x28
	private static DelegateBridge __Hotfix0_ItemClickEvent; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ArchiveDisasterController controller { get; set; }

	// RVA: 0x3049300 VA: 0x7595661300
	private ArchiveDisasterController get_controller() { }
	// RVA: 0x3049378 VA: 0x7595661378
	public Void set_controller(ArchiveDisasterController value) { }
	// RVA: 0x304940c VA: 0x759566140c
	public Void ItemClickEvent() { }
	// RVA: 0x30494f0 VA: 0x75956614f0
	public Void Render(DisasterTypeModel typeModel, String selectedTypeId, Boolean showSwitchAnim) { }
	// RVA: 0x3049734 VA: 0x7595661734
	private Void _InitIfNot() { }
	// RVA: 0x304999c VA: 0x759566199c
	public Void .ctor() { }
	// RVA: 0x3049a1c VA: 0x7595661a1c
	private static Void .cctor() { }
}
```