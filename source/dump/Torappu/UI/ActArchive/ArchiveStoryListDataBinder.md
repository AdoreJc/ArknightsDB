# ArchiveStoryListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `AutoFocusScrollView _scrollView`

- `SimpleLayoutContent _viewContainer`

- `Sprite _imgListItemTitleNormal`

- `RectTransform _leftContainer`

- `CanvasGroup _leftCanvas`

- `ScrollRect _leftScrollView`

- `FileItemView _fileItemView`

- `Boolean m_hasInited`

- `String m_cachedStoryItem`

- `ArchiveStoryListAdapter m_listAdapter`

- `ArchiveStoryController m_controller`

- `ArchiveStoryModel m_cachedModel`

- `Tween m_tween`


## Properties

- `ArchiveStoryController controller`


## Methods

- `ArchiveStoryController get_controller()`

- `Void set_controller(ArchiveStoryController)`

- `Void _InitIfNot()`

- `Void _RefreshLeftContent()`

- `Void _SetContent(StoryItemModel, Sprite, Sprite)`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveStoryListDataBinder : DataBinder`1
{
	private const Single ANIM_TIME; // 0x0
	private AutoFocusScrollView _scrollView; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private Sprite _imgListItemTitleNormal; // 0x30
	private RectTransform _leftContainer; // 0x38
	private CanvasGroup _leftCanvas; // 0x40
	private ScrollRect _leftScrollView; // 0x48
	private FileItemView _fileItemView; // 0x50
	private Boolean m_hasInited; // 0x58
	private String m_cachedStoryItem; // 0x60
	private Dictionary`2 m_cachedSprites; // 0x68
	private ArchiveStoryListAdapter m_listAdapter; // 0x70
	private ArchiveStoryController m_controller; // 0x78
	private ArchiveStoryModel m_cachedModel; // 0x80
	private Tween m_tween; // 0x88
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshLeftContent; // 0x20
	private static DelegateBridge __Hotfix0__SetContent; // 0x28
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveStoryController controller { get; set; }

	// RVA: 0x307ffc4 VA: 0x7595697fc4
	private ArchiveStoryController get_controller() { }
	// RVA: 0x307fa98 VA: 0x7595697a98
	public Void set_controller(ArchiveStoryController value) { }
	// RVA: 0x30800fc VA: 0x75956980fc
	public override Void OnValueChanged(StoryProperty property) { }
	// RVA: 0x308002c VA: 0x759569802c
	private Void _InitIfNot() { }
	// RVA: 0x30802a8 VA: 0x75956982a8
	private Void _RefreshLeftContent() { }
	// RVA: 0x30809b4 VA: 0x75956989b4
	private Void _SetContent(StoryItemModel storyModel, Sprite header, Sprite content) { }
	// RVA: 0x307fe94 VA: 0x7595697e94
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x3080bb8 VA: 0x7595698bb8
	public Void .ctor() { }
}
```