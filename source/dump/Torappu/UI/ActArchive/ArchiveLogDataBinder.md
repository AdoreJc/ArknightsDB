# ArchiveLogDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _viewContainer`

- `SimpleLayoutContent _logItemContainer`

- `ArchiveLogModel m_cachedModel`

- `ItemListAdapter m_itemListAdapter`

- `LogItemAdapter m_logItemAdapter`

- `LogTitleParam m_cachedTitleParam`

- `Boolean m_isInited`

- `ActArchiveController <controller>k__BackingField`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveLogDataBinder : DataBinder`1
{
	private List`1 _itemIconConfig; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private SimpleLayoutContent _logItemContainer; // 0x30
	private ArchiveLogModel m_cachedModel; // 0x38
	private ItemListAdapter m_itemListAdapter; // 0x40
	private LogItemAdapter m_logItemAdapter; // 0x48
	private LogTitleParam m_cachedTitleParam; // 0x50
	private Dictionary`2 m_iconMap; // 0x60
	private Boolean m_isInited; // 0x68
	private ActArchiveController <controller>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ActArchiveController controller { get; set; }

	// RVA: 0x3059450 VA: 0x7595671450
	private ActArchiveController get_controller() { }
	// RVA: 0x3059354 VA: 0x7595671354
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x30594b8 VA: 0x75956714b8
	public override Void OnValueChanged(LogProperty property) { }
	// RVA: 0x3059698 VA: 0x7595671698
	private Void _InitIfNot() { }
	// RVA: 0x3059998 VA: 0x7595671998
	public Void .ctor() { }
}
```