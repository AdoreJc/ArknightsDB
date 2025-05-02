# ArchiveTrapListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _imgIcon`

- `GameObject _panelLocked`

- `GameObject _panelUnattained`

- `GameObject _panelIcon`

- `GameObject _panelLockedIcon`

- `Image _imgSmallIcon`

- `Text _textOrder`

- `Text _textTitle`

- `Text _textUsage`

- `Text _textDesc`

- `Text _trapDesc`

- `TrapItemModel m_cachedModel`

- `Boolean m_hasInited`

- `ArchiveTrapController <controller>k__BackingField`


## Properties

- `ArchiveTrapController controller`


## Methods

- `ArchiveTrapController get_controller()`

- `Void set_controller(ArchiveTrapController)`

- `Void _InitIfNot()`

- `Void OnTrapItemClicked()`

- `Void Render(TrapItemModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTrapListItemView : MonoBehaviour, IHotfixable
{
	private Image _imgIcon; // 0x18
	private GameObject _panelLocked; // 0x20
	private GameObject _panelUnattained; // 0x28
	private GameObject _panelIcon; // 0x30
	private GameObject _panelLockedIcon; // 0x38
	private Image _imgSmallIcon; // 0x40
	private Text _textOrder; // 0x48
	private Text _textTitle; // 0x50
	private Text _textUsage; // 0x58
	private Text _textDesc; // 0x60
	private Text _trapDesc; // 0x68
	private TrapItemModel m_cachedModel; // 0x70
	private Boolean m_hasInited; // 0x78
	private ArchiveTrapController <controller>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnTrapItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ArchiveTrapController controller { get; set; }

	// RVA: 0x308f414 VA: 0x75956a7414
	private ArchiveTrapController get_controller() { }
	// RVA: 0x308f47c VA: 0x75956a747c
	public Void set_controller(ArchiveTrapController value) { }
	// RVA: 0x308f500 VA: 0x75956a7500
	private Void _InitIfNot() { }
	// RVA: 0x308f574 VA: 0x75956a7574
	public Void OnTrapItemClicked() { }
	// RVA: 0x308f658 VA: 0x75956a7658
	public Void Render(TrapItemModel itemModel, String selectItemId) { }
	// RVA: 0x308fa94 VA: 0x75956a7a94
	public Void .ctor() { }
}
```