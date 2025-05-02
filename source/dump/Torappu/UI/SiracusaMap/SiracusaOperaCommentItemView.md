# SiracusaOperaCommentItemView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _commentTitle`

- `Text _charName`

- `Text _score`

- `Text _textContent`

- `LayoutElement _layoutElement`

- `UIAtlasImage _frame`

- `GameObject _panelFrame`

- `Button _likeBtn`

- `Button _confirmLikeBtn`

- `GameObject _panelHotpot`

- `GameObject _panelLike`

- `GameObject _currLike`

- `Image _charCardAvatar`

- `UIAnimationLocation _selectedAnim`

- `Boolean m_isInited`

- `OperaCommentSeletedSwitchTween m_selectedTween`

- `TextGenerator m_textGenerator`

- `TextGenerationSettings m_textGeneratorSettings`

- `String m_cachedCommentId`


## Methods

- `Void Render(SiracusaOperaCommentItemViewModel, Single, Boolean, Boolean)`

- `Sprite _LoadAvartar(String)`

- `Void _InitIfNot()`

- `Single GetPreferedHeight(String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaCommentItemView : MonoBehaviour, IHotfixable
{
	private Text _commentTitle; // 0x18
	private Text _charName; // 0x20
	private Text _score; // 0x28
	private Text _textContent; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private UIAtlasImage _frame; // 0x40
	private GameObject _panelFrame; // 0x48
	private Button _likeBtn; // 0x50
	private Button _confirmLikeBtn; // 0x58
	private GameObject _panelHotpot; // 0x60
	private GameObject _panelLike; // 0x68
	private GameObject _currLike; // 0x70
	private Image _charCardAvatar; // 0x78
	private UIAnimationLocation _selectedAnim; // 0x80
	public Action`1 onCommentClicked; // 0x90
	private Boolean m_isInited; // 0x98
	private OperaCommentSeletedSwitchTween m_selectedTween; // 0xa0
	private TextGenerator m_textGenerator; // 0xa8
	private TextGenerationSettings m_textGeneratorSettings; // 0xb0
	private String m_cachedCommentId; // 0x110
	private const Single REMAIN_HEIGHT; // 0x0
	private const Single MIN_HEIGHT; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadAvartar; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_GetPreferedHeight; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23f64ec VA: 0x7594a0e4ec
	public Void Render(SiracusaOperaCommentItemViewModel viewModel, Single preferedHeight, Boolean isSelected, Boolean isInit) { }
	// RVA: 0x23f6894 VA: 0x7594a0e894
	public Sprite _LoadAvartar(String charId) { }
	// RVA: 0x23f677c VA: 0x7594a0e77c
	private Void _InitIfNot() { }
	// RVA: 0x23f638c VA: 0x7594a0e38c
	public Single GetPreferedHeight(String textContent) { }
	// RVA: 0x23f6b54 VA: 0x7594a0eb54
	public Void OnClick() { }
	// RVA: 0x23f6bdc VA: 0x7594a0ebdc
	public Void .ctor() { }
}
```