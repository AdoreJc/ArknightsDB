# AutoChessCharacterMenuButton

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _btnText`

- `Image _icon`

- `Text _coinText`

- `Image _displayBg`

- `Image _coinBg`

- `Transform _utilBtn`

- `Transform _utilBtnRoot`

- `Transform _coinRoot`

- `Transform _rotateRoot`

- `Sprite _iconBgEnough`

- `Sprite _bgNotValid`

- `Sprite _iconBgNotEnough`

- `Color _defaultIconColor`

- `Color _notValidIconColor`

- `Color _defaultTextColor`

- `Color _notValidTextColor`

- `Color _defaultPriceTextColor`

- `Color _notValidPriceTextColor`

- `Button _button`

- `Follower2D _follower`

- `Transform _maskRoot`

- `GameObject _tutorialOnlyCoinPanel`

- `GameObject _tutorialOnlyButton`

- `Boolean m_inited`

- `Boolean m_hasRotated`

- `Boolean m_isShowed`

- `Param m_param`


## Methods

- `Void Render(Param)`

- `Void Hide()`

- `Void InitIfNot()`

- `Void OnClick()`

- `Void TutorialOnly_RegisterCharacterShopMenuCoinPanel()`

- `Void TutorialOnly_RegisterShopCharacterMenuBtn()`

- `Void _RevertRotateIfNeed()`

- `Void _RotateIfNeed(Param)`

- `Void _RenderCoin(Param)`

- `Void _UpdateValid(Boolean, DisplayTypeSetting)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessCharacterMenuButton : MonoBehaviour, IHotfixable
{
	private DisplayTypeSetting[] _settings; // 0x18
	private LiteTextIconPairSetting[] _liteSettings; // 0x20
	private Text _btnText; // 0x28
	private Image _icon; // 0x30
	private Text _coinText; // 0x38
	private Image _displayBg; // 0x40
	private Image _coinBg; // 0x48
	private Transform _utilBtn; // 0x50
	private Transform _utilBtnRoot; // 0x58
	private Transform _coinRoot; // 0x60
	private Transform _rotateRoot; // 0x68
	private Sprite _iconBgEnough; // 0x70
	private Sprite _bgNotValid; // 0x78
	private Sprite _iconBgNotEnough; // 0x80
	private Color _defaultIconColor; // 0x88
	private Color _notValidIconColor; // 0x98
	private Color _defaultTextColor; // 0xa8
	private Color _notValidTextColor; // 0xb8
	private Color _defaultPriceTextColor; // 0xc8
	private Color _notValidPriceTextColor; // 0xd8
	private Button _button; // 0xe8
	private Follower2D _follower; // 0xf0
	private Transform _maskRoot; // 0xf8
	private GameObject _tutorialOnlyCoinPanel; // 0x100
	private GameObject _tutorialOnlyButton; // 0x108
	private Boolean m_inited; // 0x110
	private Boolean m_hasRotated; // 0x111
	private Boolean m_isShowed; // 0x112
	private ListDict`2 m_displayTypeSettings; // 0x118
	private Param m_param; // 0x120
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterCharacterShopMenuCoinPanel; // 0x20
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterShopCharacterMenuBtn; // 0x28
	private static DelegateBridge __Hotfix0__RevertRotateIfNeed; // 0x30
	private static DelegateBridge __Hotfix0__RotateIfNeed; // 0x38
	private static DelegateBridge __Hotfix0__RenderCoin; // 0x40
	private static DelegateBridge __Hotfix0__UpdateValid; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2029228 VA: 0x7594641228
	public Void Render(Param param) { }
	// RVA: 0x2029b8c VA: 0x7594641b8c
	public Void Hide() { }
	// RVA: 0x2029448 VA: 0x7594641448
	private Void InitIfNot() { }
	// RVA: 0x2029d88 VA: 0x7594641d88
	public Void OnClick() { }
	// RVA: 0x2029e08 VA: 0x7594641e08
	public Void TutorialOnly_RegisterCharacterShopMenuCoinPanel() { }
	// RVA: 0x2029ef4 VA: 0x7594641ef4
	public Void TutorialOnly_RegisterShopCharacterMenuBtn() { }
	// RVA: 0x2029bfc VA: 0x7594641bfc
	private Void _RevertRotateIfNeed() { }
	// RVA: 0x2029534 VA: 0x7594641534
	private Void _RotateIfNeed(Param param) { }
	// RVA: 0x2029798 VA: 0x7594641798
	private Void _RenderCoin(Param param) { }
	// RVA: 0x20299e0 VA: 0x75946419e0
	private Void _UpdateValid(Boolean isValid, DisplayTypeSetting setting) { }
	// RVA: 0x2029fe0 VA: 0x7594641fe0
	public Void .ctor() { }
}
```