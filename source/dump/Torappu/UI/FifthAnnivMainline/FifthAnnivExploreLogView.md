# FifthAnnivExploreLogView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _textEventTitle`

- `Text _textEventTypeDesc`

- `Text _textEventDesc`

- `Text _textChoiceTitle`

- `Text _textChoiceDesc`

- `Text _textResultTitle`

- `Text _textResultDesc`

- `UIAtlasObject _atlasObject`

- `String _spriteNameSuccess`

- `String _spriteNameFail`

- `UIAtlasImage _imgResultSprite`

- `ScrollRect _scrollRect`

- `RectTransform _viewport`

- `RectTransform _content`

- `RectTransform _firstDialogContent`

- `Single _loadingDialogHeight`

- `VerticalLayoutGroup _verticalLayout`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _animLoop`

- `UIAnimationLocation _animExpand`

- `Single _firstFocusOffset`

- `Single _expandFocusOffset`

- `Single _focusTweenDur`

- `GameObject _pnlDotSuccess`

- `GameObject _pnlDotFailed`

- `GameObject _pnlBkgSuccess`

- `GameObject _pnlBkgFailed`

- `UIAtlasObject _commonAtlas`

- `Color _colorValueDecrease`

- `UIAtlasObject _eventIconAtlas`

- `UIAtlasImage _imgEventIcon`

- `Boolean m_inited`

- `UILayoutDimensionListener m_dimensionListener`

- `Tween m_effectTween`

- `Int32 m_cachedSeqNum`

- `FifthAnnivExploreLogModel m_cachedLogModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void _Render()`

- `Void _OnPostLayout()`

- `Void OnContinueClicked()`

- `Void <_OnPostLayout>b__47_1()`

- `Void <_OnPostLayout>b__47_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreLogView : FifthAnnivExploreDetailViewBase
{
	private const Int32 MAX_LOOP_COUNT; // 0x0
	private const String CHOICE_VALUE_ADD_FORMAT; // 0x0
	private Text _textEventTitle; // 0x38
	private Text _textEventTypeDesc; // 0x40
	private Text _textEventDesc; // 0x48
	private Text _textChoiceTitle; // 0x50
	private Text _textChoiceDesc; // 0x58
	private Text _textResultTitle; // 0x60
	private Text _textResultDesc; // 0x68
	private UIAtlasObject _atlasObject; // 0x70
	private String _spriteNameSuccess; // 0x78
	private String _spriteNameFail; // 0x80
	private UIAtlasImage _imgResultSprite; // 0x88
	private ScrollRect _scrollRect; // 0x90
	private RectTransform _viewport; // 0x98
	private RectTransform _content; // 0xa0
	private RectTransform _firstDialogContent; // 0xa8
	private Single _loadingDialogHeight; // 0xb0
	private VerticalLayoutGroup _verticalLayout; // 0xb8
	private UIAnimationLocation _animEnter; // 0xc0
	private UIAnimationLocation _animLoop; // 0xd0
	private UIAnimationLocation _animExpand; // 0xe0
	private Single _firstFocusOffset; // 0xf0
	private Single _expandFocusOffset; // 0xf4
	private Single _focusTweenDur; // 0xf8
	private GameObject _pnlDotSuccess; // 0x100
	private GameObject _pnlDotFailed; // 0x108
	private GameObject _pnlBkgSuccess; // 0x110
	private GameObject _pnlBkgFailed; // 0x118
	private Text[] _textValues; // 0x120
	private UIAtlasImage[] _spriteValues; // 0x128
	private UIColorGraphic[] _graphicValues; // 0x130
	private UIAtlasObject _commonAtlas; // 0x138
	private Color _colorValueDecrease; // 0x140
	private UIAtlasObject _eventIconAtlas; // 0x150
	private UIAtlasImage _imgEventIcon; // 0x158
	private Boolean m_inited; // 0x160
	private UILayoutDimensionListener m_dimensionListener; // 0x168
	private Tween m_effectTween; // 0x170
	private Int32 m_cachedSeqNum; // 0x178
	private FifthAnnivExploreLogModel m_cachedLogModel; // 0x180
	private UIStateFinder m_stateFinder; // 0x188
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_status; // 0x8
	private static DelegateBridge __Hotfix0_OnDataUpdate; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x20
	private static DelegateBridge __Hotfix0_OnContinueClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override DecisionStatus status { get; }

	// RVA: 0x2913b30 VA: 0x7594f2bb30
	private Void _InitIfNot() { }
	// RVA: 0x2913bec VA: 0x7594f2bbec
	protected override DecisionStatus get_status() { }
	// RVA: 0x2913c54 VA: 0x7594f2bc54
	protected override Void OnDataUpdate() { }
	// RVA: 0x2913d0c VA: 0x7594f2bd0c
	private Void _Render() { }
	// RVA: 0x291441c VA: 0x7594f2c41c
	private Void _OnPostLayout() { }
	// RVA: 0x29149bc VA: 0x7594f2c9bc
	public Void OnContinueClicked() { }
	// RVA: 0x2914a70 VA: 0x7594f2ca70
	public Void .ctor() { }
	// RVA: 0x2914adc VA: 0x7594f2cadc
	private Void <_OnPostLayout>b__47_1() { }
	// RVA: 0x2914b7c VA: 0x7594f2cb7c
	private Void <_OnPostLayout>b__47_2() { }
}
```