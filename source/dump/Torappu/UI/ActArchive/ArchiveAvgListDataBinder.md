# ArchiveAvgListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SimpleLayoutContent _listViewContainer`

- `AutoFocusScrollView _scrollView`

- `CanvasGroup _titleCanvas`

- `CanvasGroup _contentCanvas`

- `CanvasGroup _spriteCanvas`

- `Text _title`

- `Text _content`

- `Image _sprite`

- `Sprite _defaultListIcon`

- `ListAdapter m_listAdapter`

- `Boolean m_hasInited`

- `String m_cachedItemId`

- `ArchiveAvgModel m_cachedModel`

- `String m_cachedAvgItem`

- `ArchiveAvgController m_controller`

- `Sequence m_tween`


## Properties

- `ArchiveAvgController controller`


## Methods

- `ArchiveAvgController get_controller()`

- `Void set_controller(ArchiveAvgController)`

- `Void _InitIfNot()`

- `Void _RefreshLeftPanel()`

- `Void OnAvgCardItemClick()`

- `Void _SetContent(String, String, Sprite)`

- `Void _OnStoryClicked(String)`

- `DataBundle _ArchiveAvgDetailToDataBundle()`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAvgListDataBinder : DataBinder`1
{
	private const Single FADE_TIME; // 0x0
	private SimpleLayoutContent _listViewContainer; // 0x20
	private AutoFocusScrollView _scrollView; // 0x28
	private CanvasGroup _titleCanvas; // 0x30
	private CanvasGroup _contentCanvas; // 0x38
	private CanvasGroup _spriteCanvas; // 0x40
	private Text _title; // 0x48
	private Text _content; // 0x50
	private Image _sprite; // 0x58
	private List`1 _imgListItemTitleGroup; // 0x60
	private Sprite _defaultListIcon; // 0x68
	private ListAdapter m_listAdapter; // 0x70
	private Boolean m_hasInited; // 0x78
	private String m_cachedItemId; // 0x80
	private ArchiveAvgModel m_cachedModel; // 0x88
	private String m_cachedAvgItem; // 0x90
	private ArchiveAvgController m_controller; // 0x98
	private Sequence m_tween; // 0xa0
	private Dictionary`2 m_imgListItemTitleMap; // 0xa8
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__RefreshLeftPanel; // 0x20
	private static DelegateBridge __Hotfix0_OnAvgCardItemClick; // 0x28
	private static DelegateBridge __Hotfix0__SetContent; // 0x30
	private static DelegateBridge __Hotfix0__OnStoryClicked; // 0x38
	private static DelegateBridge __Hotfix0__ArchiveAvgDetailToDataBundle; // 0x40
	private static DelegateBridge __Hotfix0__GetStoryBriefPath; // 0x48
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ArchiveAvgController controller { get; set; }

	// RVA: 0x3034a24 VA: 0x759564ca24
	private ArchiveAvgController get_controller() { }
	// RVA: 0x3034494 VA: 0x759564c494
	public Void set_controller(ArchiveAvgController value) { }
	// RVA: 0x3034a8c VA: 0x759564ca8c
	private Void _InitIfNot() { }
	// RVA: 0x3034e20 VA: 0x759564ce20
	public override Void OnValueChanged(AvgProperty property) { }
	// RVA: 0x3034fe4 VA: 0x759564cfe4
	private Void _RefreshLeftPanel() { }
	// RVA: 0x3035b40 VA: 0x759564db40
	public Void OnAvgCardItemClick() { }
	// RVA: 0x3035a60 VA: 0x759564da60
	private Void _SetContent(String title, String content, Sprite sprite) { }
	// RVA: 0x3035df0 VA: 0x759564ddf0
	private Void _OnStoryClicked(String storyId) { }
	// RVA: 0x3035f80 VA: 0x759564df80
	private DataBundle _ArchiveAvgDetailToDataBundle() { }
	// RVA: 0x303598c VA: 0x759564d98c
	private static String _GetStoryBriefPath(String key) { }
	// RVA: 0x30348f4 VA: 0x759564c8f4
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x303609c VA: 0x759564e09c
	public Void .ctor() { }
}
```