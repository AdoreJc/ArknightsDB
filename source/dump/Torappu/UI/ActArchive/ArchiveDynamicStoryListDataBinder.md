# ArchiveDynamicStoryListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `AutoFocusScrollView _scrollView`

- `SimpleLayoutContent _viewContainer`

- `Sprite _imgListItemTitleNormal`

- `RectTransform _leftContainer`

- `CanvasGroup _leftCanvas`

- `ScrollRect _leftScrollView`

- `ArchiveDynamicStoryContentBaseView _contentView`

- `Single _selectTweenFromPos`

- `Single _selectTweenToPos`

- `Boolean m_hasInited`

- `String m_cachedStoryItem`

- `ArchiveStoryListAdapter m_listAdapter`

- `ArchiveDynamicStoryController m_controller`

- `ArchiveStoryModel m_cachedModel`

- `Tween m_tween`


## Properties

- `ArchiveDynamicStoryController controller`


## Methods

- `ArchiveDynamicStoryController get_controller()`

- `Void set_controller(ArchiveDynamicStoryController)`

- `Void _InitIfNot()`

- `Void _RefreshLeftContent()`

- `Void _SetContent(StoryItemModel, Sprite, Sprite)`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDynamicStoryListDataBinder : DataBinder`1
{
	private const Single ANIM_TIME; // 0x0
	private AutoFocusScrollView _scrollView; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private Sprite _imgListItemTitleNormal; // 0x30
	private RectTransform _leftContainer; // 0x38
	private CanvasGroup _leftCanvas; // 0x40
	private ScrollRect _leftScrollView; // 0x48
	private ArchiveDynamicStoryContentBaseView _contentView; // 0x50
	private Single _selectTweenFromPos; // 0x58
	private Single _selectTweenToPos; // 0x5c
	private Boolean m_hasInited; // 0x60
	private String m_cachedStoryItem; // 0x68
	private Dictionary`2 m_cachedSprites; // 0x70
	private ArchiveStoryListAdapter m_listAdapter; // 0x78
	private ArchiveDynamicStoryController m_controller; // 0x80
	private ArchiveStoryModel m_cachedModel; // 0x88
	private Tween m_tween; // 0x90
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshLeftContent; // 0x20
	private static DelegateBridge __Hotfix0__SetContent; // 0x28
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveDynamicStoryController controller { get; set; }

	// RVA: 0x307e758 VA: 0x7595696758
	private ArchiveDynamicStoryController get_controller() { }
	// RVA: 0x307e3c8 VA: 0x75956963c8
	public Void set_controller(ArchiveDynamicStoryController value) { }
	// RVA: 0x307e890 VA: 0x7595696890
	public override Void OnValueChanged(StoryProperty property) { }
	// RVA: 0x307e7c0 VA: 0x75956967c0
	private Void _InitIfNot() { }
	// RVA: 0x307ea3c VA: 0x7595696a3c
	private Void _RefreshLeftContent() { }
	// RVA: 0x307f178 VA: 0x7595697178
	private Void _SetContent(StoryItemModel storyModel, Sprite header, Sprite content) { }
	// RVA: 0x307e628 VA: 0x7595696628
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x307f298 VA: 0x7595697298
	public Void .ctor() { }
}
```