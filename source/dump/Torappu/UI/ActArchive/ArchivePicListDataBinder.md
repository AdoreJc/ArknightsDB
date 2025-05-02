# ArchivePicListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String IMG_ITEM_TYPE_FORMAT`

- `SimpleLayoutContent _viewContainer`

- `AutoFocusScrollView _scrollView`

- `Adapter m_listAdapter`

- `Boolean m_hasInited`

- `String m_cachedPicItem`

- `ArchivePicModel m_cachedModel`

- `ActArchiveController m_controller`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchivePicListDataBinder : DataBinder`1
{
	private String IMG_ITEM_TYPE_FORMAT; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private AutoFocusScrollView _scrollView; // 0x30
	private List`1 _imgListItemTitleGroup; // 0x38
	private Adapter m_listAdapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private String m_cachedPicItem; // 0x50
	private ArchivePicModel m_cachedModel; // 0x58
	private ActArchiveController m_controller; // 0x60
	private Dictionary`2 m_imgListItemTitleMap; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ActArchiveController controller { get; set; }

	// RVA: 0x306ab64 VA: 0x7595682b64
	private ActArchiveController get_controller() { }
	// RVA: 0x3067ed8 VA: 0x759567fed8
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x306abcc VA: 0x7595682bcc
	private Void _InitIfNot() { }
	// RVA: 0x306af8c VA: 0x7595682f8c
	public override Void OnValueChanged(PicProperty property) { }
	// RVA: 0x3068554 VA: 0x7595680554
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x306b14c VA: 0x759568314c
	public Void .ctor() { }
}
```