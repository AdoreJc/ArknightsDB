# EmoticonPagerPanelView

**Namespace:** `Torappu.UI.Emoticon`


## Fields

- `ScrollViewMoveToughPager _pager`

- `RectTransform _bgRect`

- `Text _themeName`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `SimpleLayoutContent _emojiGroupContent`

- `SimpleLayoutContent _dotContent`

- `RectTransform _rectPos`

- `UIAnimationLocation _switchAnimLocation`

- `EmoticonPagerPanelPlugin _panelPlugin`

- `RectTransform _backRect`

- `CanvasGroup _panelGroup`

- `Boolean m_isInited`

- `EmoticonPagerPanelModel m_cachedModel`

- `EmojiGroupAdapter m_emojiGroupAdapter`

- `DotAdapter m_dotAdapter`

- `AnimationSwitchTween m_showTween`

- `Int32 m_showSeqNum`

- `Int32 m_hideFastModeSeqNum`

- `EmojiSceneType m_cachedSceneType`

- `Action onClickLeftButton`

- `Action onClickRightButton`

- `Action onClosePanel`


## Methods

- `Void _InitIfNot()`

- `Void _OnPageValueChanged(Single)`

- `Void _OnPageIndexChanged(Int32)`

- `Void OnClickLeftButton()`

- `Void OnClickRightButton()`

- `Void OnClosePanel()`

- `Void <>xLuaBaseProxy_Init(ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonPagerPanelView : EmoticonPanelBaseView
{
	private ScrollViewMoveToughPager _pager; // 0x28
	private RectTransform _bgRect; // 0x30
	private Text _themeName; // 0x38
	private GameObject _leftArrow; // 0x40
	private GameObject _rightArrow; // 0x48
	private SimpleLayoutContent _emojiGroupContent; // 0x50
	private SimpleLayoutContent _dotContent; // 0x58
	private RectTransform _rectPos; // 0x60
	private UIAnimationLocation _switchAnimLocation; // 0x68
	private EmoticonPagerPanelPlugin _panelPlugin; // 0x78
	private RectTransform _backRect; // 0x80
	private CanvasGroup _panelGroup; // 0x88
	private Boolean m_isInited; // 0x90
	private EmoticonPagerPanelModel m_cachedModel; // 0x98
	private EmojiGroupAdapter m_emojiGroupAdapter; // 0xa0
	private DotAdapter m_dotAdapter; // 0xa8
	private AnimationSwitchTween m_showTween; // 0xb0
	private Int32 m_showSeqNum; // 0xb8
	private Int32 m_hideFastModeSeqNum; // 0xbc
	private EmojiSceneType m_cachedSceneType; // 0xc0
	public Action onClickLeftButton; // 0xc8
	public Action onClickRightButton; // 0xd0
	public Action`1 onPagerIndexChanged; // 0xd8
	public Action`2 onClickEmojiItem; // 0xe0
	public Action onClosePanel; // 0xe8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnPageValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnPageIndexChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnClickLeftButton; // 0x28
	private static DelegateBridge __Hotfix0_OnClickRightButton; // 0x30
	private static DelegateBridge __Hotfix0_OnClosePanel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x29b83a4 VA: 0x7594fd03a4
	public override Void Init(ILoadAsset iLoadAsset) { }
	// RVA: 0x29b874c VA: 0x7594fd074c
	protected override Void _Render(EmoticonPanelBaseModel baseModel) { }
	// RVA: 0x29b842c VA: 0x7594fd042c
	private Void _InitIfNot() { }
	// RVA: 0x29b8dc8 VA: 0x7594fd0dc8
	private Void _OnPageValueChanged(Single value) { }
	// RVA: 0x29b8e50 VA: 0x7594fd0e50
	private Void _OnPageIndexChanged(Int32 index) { }
	// RVA: 0x29b8ef0 VA: 0x7594fd0ef0
	public Void OnClickLeftButton() { }
	// RVA: 0x29b8f74 VA: 0x7594fd0f74
	public Void OnClickRightButton() { }
	// RVA: 0x29b8ff8 VA: 0x7594fd0ff8
	public Void OnClosePanel() { }
	// RVA: 0x29b907c VA: 0x7594fd107c
	public Void .ctor() { }
	// RVA: 0x29b90e8 VA: 0x7594fd10e8
	private Void <>xLuaBaseProxy_Init(ILoadAsset P0) { }
}
```