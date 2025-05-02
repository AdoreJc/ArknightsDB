# CharacterInfoPotentialView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `RectTransform _illustContainer`

- `CharacterInfoPotentialIconLayout _potentialIconLayout`

- `SimpleLayoutContent _potentialTextContent`

- `TwoStateToggle _toggleFullVoucher`

- `TwoStateToggle _toggleCommonItem`

- `CharacterInfoPotentialLevelUpItem _charItem`

- `CharacterInfoPotentialLevelUpItem _commonItem`

- `CharacterInfoPotentialLevelUpItem _voucherItem`

- `UIStringEvent _onItemClick`

- `UIStringEvent _onVoucherClick`

- `Text _textItemDesc`

- `CharacterInfoActivityPotentialItemView _activityItem`

- `GameObject _panelPotentialBtn`

- `GameObject _mixedHintPanel`

- `Text _textPotentialLvlCurr`

- `Text _textPotentialLvlPrev`

- `Image _imgPotentialCurrent`

- `Image _imgPotentialPrev`

- `AnimationWrapper _animationWrapper`

- `UICharacterIllust m_illust`

- `Adapter m_potentialTextAdapter`

- `Int32 m_index`

- `Int32 m_rank`

- `TweenWrapper m_tweenWrapper`

- `Boolean m_hasInited`


## Methods

- `Void Render(CharacterInfoPotentialViewModel, UIPage)`

- `Void ShowPotentialLvlUpAnim(CharacterInfoPotentialViewModel)`

- `Void OnSelect(Int32)`

- `Void OnClick()`

- `Void _RefreshPotentialImg()`

- `Void _RefreshLvlUpView(CharacterInfoPotentialViewModel)`

- `Void _RenderItemDesc()`

- `CharacterInfoPotentialLevelUpItem _GetSelectItem()`

- `Void _InitIfNot()`

- `Void _ShowActivityPotential(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialView : MonoBehaviour, IHotfixable
{
	private const String ANIM_SHOW_KEY; // 0x0
	private RectTransform _illustContainer; // 0x18
	private CharacterInfoPotentialIconLayout _potentialIconLayout; // 0x20
	private SimpleLayoutContent _potentialTextContent; // 0x28
	private TwoStateToggle _toggleFullVoucher; // 0x30
	private TwoStateToggle _toggleCommonItem; // 0x38
	private CharacterInfoPotentialLevelUpItem _charItem; // 0x40
	private CharacterInfoPotentialLevelUpItem _commonItem; // 0x48
	private CharacterInfoPotentialLevelUpItem _voucherItem; // 0x50
	private UIStringEvent _onItemClick; // 0x58
	private UIStringEvent _onVoucherClick; // 0x60
	private Text _textItemDesc; // 0x68
	private CharacterInfoActivityPotentialItemView _activityItem; // 0x70
	private GameObject _panelPotentialBtn; // 0x78
	private GameObject _mixedHintPanel; // 0x80
	private Text _textPotentialLvlCurr; // 0x88
	private Text _textPotentialLvlPrev; // 0x90
	private Image _imgPotentialCurrent; // 0x98
	private Image _imgPotentialPrev; // 0xa0
	private AnimationWrapper _animationWrapper; // 0xa8
	private UICharacterIllust m_illust; // 0xb0
	private Adapter m_potentialTextAdapter; // 0xb8
	private Int32 m_index; // 0xc0
	private Int32 m_rank; // 0xc4
	private TweenWrapper m_tweenWrapper; // 0xc8
	private Boolean m_hasInited; // 0xd0
	private PotentialRank[] m_potentialRanks; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ShowPotentialLvlUpAnim; // 0x8
	private static DelegateBridge __Hotfix0_OnSelect; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__RefreshPotentialImg; // 0x20
	private static DelegateBridge __Hotfix0__GenerateIconRankList; // 0x28
	private static DelegateBridge __Hotfix0__RefreshLvlUpView; // 0x30
	private static DelegateBridge __Hotfix0__RenderItemDesc; // 0x38
	private static DelegateBridge __Hotfix0__GetSelectItem; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__ShowActivityPotential; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2d7fa68 VA: 0x7595397a68
	public Void Render(CharacterInfoPotentialViewModel model, UIPage page) { }
	// RVA: 0x2d800bc VA: 0x75953980bc
	public Void ShowPotentialLvlUpAnim(CharacterInfoPotentialViewModel model) { }
	// RVA: 0x2d801fc VA: 0x75953981fc
	public Void OnSelect(Int32 index) { }
	// RVA: 0x2d8043c VA: 0x759539843c
	public Void OnClick() { }
	// RVA: 0x2d7fe08 VA: 0x7595397e08
	private Void _RefreshPotentialImg() { }
	// RVA: 0x2d80668 VA: 0x7595398668
	private List`1 _GenerateIconRankList() { }
	// RVA: 0x2d7ff54 VA: 0x7595397f54
	private Void _RefreshLvlUpView(CharacterInfoPotentialViewModel model) { }
	// RVA: 0x2d802d4 VA: 0x75953982d4
	private Void _RenderItemDesc() { }
	// RVA: 0x2d805c4 VA: 0x75953985c4
	private CharacterInfoPotentialLevelUpItem _GetSelectItem() { }
	// RVA: 0x2d7fd34 VA: 0x7595397d34
	private Void _InitIfNot() { }
	// RVA: 0x2d80854 VA: 0x7595398854
	private Void _ShowActivityPotential(Boolean isShow) { }
	// RVA: 0x2d808fc VA: 0x75953988fc
	public Void .ctor() { }
}
```