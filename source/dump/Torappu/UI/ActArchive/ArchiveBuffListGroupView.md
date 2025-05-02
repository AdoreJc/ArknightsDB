# ArchiveBuffListGroupView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _itemContent`

- `UIAtlasImage _title`

- `UIAtlasObject _titleAtlas`

- `GameObject _panelLine`

- `Boolean m_isInited`

- `ArchiveBuffItemAdapter m_adapter`

- `Int32 m_cachedGroupIndex`

- `ActArchiveController m_controller`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void Render(ArchiveBuffGroupModel, String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveBuffListGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemContent; // 0x18
	private UIAtlasImage _title; // 0x20
	private List`1 _titleName; // 0x28
	private UIAtlasObject _titleAtlas; // 0x30
	private GameObject _panelLine; // 0x38
	private Boolean m_isInited; // 0x40
	private ArchiveBuffItemAdapter m_adapter; // 0x48
	private Int32 m_cachedGroupIndex; // 0x50
	private ActArchiveController m_controller; // 0x58
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ActArchiveController controller { get; set; }

	// RVA: 0x30389a8 VA: 0x75956509a8
	private ActArchiveController get_controller() { }
	// RVA: 0x3038760 VA: 0x7595650760
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x30387ec VA: 0x75956507ec
	public Void Render(ArchiveBuffGroupModel viewModel, String selectedBuffId) { }
	// RVA: 0x3038a10 VA: 0x7595650a10
	private Void _InitIfNot() { }
	// RVA: 0x3038bbc VA: 0x7595650bbc
	public Void .ctor() { }
}
```