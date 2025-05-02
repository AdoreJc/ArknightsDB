# ArchiveTotemListGroupView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _itemContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_selectedItem`

- `Boolean m_showSwitchAnim`

- `ArchiveTotemController <controller>k__BackingField`


## Properties

- `ArchiveTotemController controller`


## Methods

- `ArchiveTotemController get_controller()`

- `Void set_controller(ArchiveTotemController)`

- `Void Render(ArchiveTotemGroupModel, String, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTotemListGroupView : MonoBehaviour, IHotfixable
{
	private List`1 _flagPanels; // 0x18
	private SimpleLayoutContent _itemContent; // 0x20
	private Boolean m_hasInited; // 0x28
	private Adapter m_adapter; // 0x30
	private List`1 m_cachedItems; // 0x38
	private String m_selectedItem; // 0x40
	private Boolean m_showSwitchAnim; // 0x48
	private ArchiveTotemController <controller>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveTotemController controller { get; set; }

	// RVA: 0x308aee4 VA: 0x75956a2ee4
	private ArchiveTotemController get_controller() { }
	// RVA: 0x308af4c VA: 0x75956a2f4c
	public Void set_controller(ArchiveTotemController value) { }
	// RVA: 0x308afd0 VA: 0x75956a2fd0
	public Void Render(ArchiveTotemGroupModel model, String selectedItem, Boolean showSwitchAnim) { }
	// RVA: 0x308b14c VA: 0x75956a314c
	private Void _InitIfNot() { }
	// RVA: 0x308b2b0 VA: 0x75956a32b0
	public Void .ctor() { }
}
```