# ArchiveNewsListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `AutoFocusScrollView _scrollView`

- `SimpleLayoutContent _viewContainer`

- `Image _imgBorderBg`

- `Image _imgBorderTitle`

- `Image _imgMainTitle`

- `ScrollRect _detailContent`

- `ArchiveNewsDetailObjView _titleObj`

- `ArchiveNewsDetailObjView _textObj`

- `ArchiveNewsDetailObjView _imgObj`

- `Boolean m_hasInited`

- `String m_cachedNewsItem`

- `ArchiveNewsListAdapter m_listAdapter`

- `ArchiveNewsController m_controller`

- `ArchiveNewsModel m_cachedModel`

- `String m_cachedNewsType`

- `String m_cachedNewsId`


## Properties

- `ArchiveNewsController controller`


## Methods

- `ArchiveNewsController get_controller()`

- `Void set_controller(ArchiveNewsController)`

- `Void _InitIfNot()`

- `Void _RefreshLeftContent()`

- `Void _RenderDetail(NewsItemModel, ArchiveNewsModel)`

- `Void _ClearContent()`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveNewsListDataBinder : DataBinder`1
{
	private AutoFocusScrollView _scrollView; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private Image _imgBorderBg; // 0x30
	private Image _imgBorderTitle; // 0x38
	private Image _imgMainTitle; // 0x40
	private ScrollRect _detailContent; // 0x48
	private ArchiveNewsDetailObjView _titleObj; // 0x50
	private ArchiveNewsDetailObjView _textObj; // 0x58
	private ArchiveNewsDetailObjView _imgObj; // 0x60
	private Boolean m_hasInited; // 0x68
	private String m_cachedNewsItem; // 0x70
	private ArchiveNewsListAdapter m_listAdapter; // 0x78
	private ArchiveNewsController m_controller; // 0x80
	private ArchiveNewsModel m_cachedModel; // 0x88
	private String m_cachedNewsType; // 0x90
	private String m_cachedNewsId; // 0x98
	private Dictionary`2 m_cachedSprites; // 0xa0
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshLeftContent; // 0x20
	private static DelegateBridge __Hotfix0__RenderDetail; // 0x28
	private static DelegateBridge __Hotfix0__ClearContent; // 0x30
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private ArchiveNewsController controller { get; set; }

	// RVA: 0x3064674 VA: 0x759567c674
	private ArchiveNewsController get_controller() { }
	// RVA: 0x30637bc VA: 0x759567b7bc
	public Void set_controller(ArchiveNewsController value) { }
	// RVA: 0x30647ac VA: 0x759567c7ac
	public override Void OnValueChanged(NewsProperty property) { }
	// RVA: 0x30646dc VA: 0x759567c6dc
	private Void _InitIfNot() { }
	// RVA: 0x3064958 VA: 0x759567c958
	private Void _RefreshLeftContent() { }
	// RVA: 0x3064d88 VA: 0x759567cd88
	private Void _RenderDetail(NewsItemModel itemModel, ArchiveNewsModel newsModel) { }
	// RVA: 0x3065154 VA: 0x759567d154
	private Void _ClearContent() { }
	// RVA: 0x3063c1c VA: 0x759567bc1c
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x3065278 VA: 0x759567d278
	public Void .ctor() { }
}
```