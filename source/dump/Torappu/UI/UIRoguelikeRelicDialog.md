# UIRoguelikeRelicDialog

**Namespace:** `Torappu.UI`


## Fields

- `RoguelikeCustomizableItemIcon _itemIconPrefab`

- `RectTransform _itemIconHolder`

- `Single _itemIconScale`

- `Text _textTitle`

- `Text _textUsage`

- `Text _textDesc`

- `GameObject _pnlClose`

- `GameObject _pnlNext`

- `CanvasGroup _imgBlack`

- `Single _imgBlackFadeInDuration`

- `UIAnimationLocation _fadeInAnim`

- `UIAnimationLocation _popAnim`

- `String m_cachedTopicId`

- `RoguelikeCustomizableItemIcon m_itemIcon`

- `Int32 m_index`

- `Boolean m_inited`

- `Boolean m_isNormalFadeIn`

- `Tween m_animTween`

- `FadeSwitchTween m_imgBlackTween`

- `Action m_onConfirmed`


## Methods

- `Void _InitIfNot()`

- `Void _RenderSingle()`

- `Void _OnSingleCanceled()`

- `Void OnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIRoguelikeRelicDialog : UICustomDialog`1
{
	private RoguelikeCustomizableItemIcon _itemIconPrefab; // 0x58
	private RectTransform _itemIconHolder; // 0x60
	private Single _itemIconScale; // 0x68
	private Text _textTitle; // 0x70
	private Text _textUsage; // 0x78
	private Text _textDesc; // 0x80
	private GameObject _pnlClose; // 0x88
	private GameObject _pnlNext; // 0x90
	private CanvasGroup _imgBlack; // 0x98
	private Single _imgBlackFadeInDuration; // 0xa0
	private UIAnimationLocation _fadeInAnim; // 0xa8
	private UIAnimationLocation _popAnim; // 0xb8
	private String m_cachedTopicId; // 0xc8
	private List`1 m_cachedRelicIds; // 0xd0
	private RoguelikeCustomizableItemIcon m_itemIcon; // 0xd8
	private Int32 m_index; // 0xe0
	private Boolean m_inited; // 0xe4
	private Boolean m_isNormalFadeIn; // 0xe5
	private Tween m_animTween; // 0xe8
	private FadeSwitchTween m_imgBlackTween; // 0xf0
	private Action m_onConfirmed; // 0xf8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RenderSingle; // 0x8
	private static DelegateBridge __Hotfix0__OnSingleCanceled; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2268cc8 VA: 0x7594880cc8
	private Void _InitIfNot() { }
	// RVA: 0x2268de0 VA: 0x7594880de0
	private Void _RenderSingle() { }
	// RVA: 0x22691e4 VA: 0x75948811e4
	private Void _OnSingleCanceled() { }
	// RVA: 0x22692a4 VA: 0x75948812a4
	protected override Void OnRender(Options options) { }
	// RVA: 0x2269378 VA: 0x7594881378
	public Void OnCancelClicked() { }
	// RVA: 0x22693e0 VA: 0x75948813e0
	public Void .ctor() { }
}
```