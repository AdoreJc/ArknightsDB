# ShopDetailFurnGroupView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _itemName`

- `GameObject _timeLimitGameObject`

- `Text _timeLimitText`

- `Image _itemButton`

- `Text _itemButtonText`

- `Image _itemButtonIcon`

- `UnityEvent _disMissEvent`

- `Text _atmosCount`

- `ShopFurnDetailGroupText _groupText`

- `ShopFurnDetailFurnInfo _furnInfo`

- `Transform _textContainer`

- `Text _desc`

- `ScrollViewPager _viewPager`

- `Toggle _viewToggle`

- `Transform _toggleContainer`

- `Image _viewImg`

- `Transform _viewImgContainer`

- `ThreeStateToggle _coinPart`

- `ThreeStateToggle _diamPart`

- `Image _priceIcon`

- `Text _totalPrice`

- `Text _currentGroupCount`

- `Image _currentGroupColor`

- `GameObject _bothPricePart`

- `GameObject _diamPricePart`

- `GameObject _coinPricePart`

- `FurnGroupViewModel m_cacheViewModel`

- `SpriteHub m_priceTypeHub`

- `SelectClass m_selectPriceFlag`

- `Int32 currentMaxCount`

- `Single m_switchCountDown`


## Methods

- `Void _InitPriceObj(FurnGroupViewModel)`

- `Void ApplyData(FurnGroupViewModel, SpriteHub)`

- `Void _ApplyImgInfo(FurnGroupViewModel)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void _PageSwitchCallback(Int32)`

- `Void Update()`

- `Void _TryTweenToPage(Int32)`

- `Void ApplyPriceState()`

- `Void TurnCoinFurn()`

- `Void TurnCoinDiam()`

- `Void DismissSelf()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailFurnGroupView : MonoBehaviour, IHotfixable
{
	private const Single PAUSE_DURATION_WHEN_ACTION; // 0x0
	private const Single SWITCH_PAGE_PERIOD; // 0x0
	protected Text _itemName; // 0x18
	protected GameObject _timeLimitGameObject; // 0x20
	protected Text _timeLimitText; // 0x28
	protected Image _itemButton; // 0x30
	protected Text _itemButtonText; // 0x38
	protected Image _itemButtonIcon; // 0x40
	protected UnityEvent _disMissEvent; // 0x48
	protected Text _atmosCount; // 0x50
	private ShopFurnDetailGroupText _groupText; // 0x58
	private ShopFurnDetailFurnInfo _furnInfo; // 0x60
	private Transform _textContainer; // 0x68
	private Text _desc; // 0x70
	private ScrollViewPager _viewPager; // 0x78
	private Toggle _viewToggle; // 0x80
	private Transform _toggleContainer; // 0x88
	private Image _viewImg; // 0x90
	private Transform _viewImgContainer; // 0x98
	private ThreeStateToggle _coinPart; // 0xa0
	private ThreeStateToggle _diamPart; // 0xa8
	private Image _priceIcon; // 0xb0
	private Image[] _whiteFurniIcons; // 0xb8
	private Image[] _whiteDiamondIcons; // 0xc0
	private Text _totalPrice; // 0xc8
	private Text _currentGroupCount; // 0xd0
	private Image _currentGroupColor; // 0xd8
	private GameObject _bothPricePart; // 0xe0
	private GameObject _diamPricePart; // 0xe8
	private GameObject _coinPricePart; // 0xf0
	private FurnGroupViewModel m_cacheViewModel; // 0xf8
	private SpriteHub m_priceTypeHub; // 0x100
	private SelectClass m_selectPriceFlag; // 0x108
	private List`1 m_switchToggles; // 0x110
	private List`1 m_imgList; // 0x118
	private Int32 currentMaxCount; // 0x120
	private List`1 m_furnInfoList; // 0x128
	private List`1 m_furnTextList; // 0x130
	private Single m_switchCountDown; // 0x138
	private static DelegateBridge __Hotfix0__InitPriceObj; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0__ApplyImgInfo; // 0x10
	private static DelegateBridge __Hotfix0_Awake; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__PageSwitchCallback; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0__TryTweenToPage; // 0x38
	private static DelegateBridge __Hotfix0_ApplyPriceState; // 0x40
	private static DelegateBridge __Hotfix0_TurnCoinFurn; // 0x48
	private static DelegateBridge __Hotfix0_TurnCoinDiam; // 0x50
	private static DelegateBridge __Hotfix0_DismissSelf; // 0x58
	private static DelegateBridge __Hotfix0_OnClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x242d5a4 VA: 0x7594a455a4
	private Void _InitPriceObj(FurnGroupViewModel viewModel) { }
	// RVA: 0x242cc88 VA: 0x7594a44c88
	public Void ApplyData(FurnGroupViewModel viewModel, SpriteHub priceTypeHub) { }
	// RVA: 0x242db98 VA: 0x7594a45b98
	private Void _ApplyImgInfo(FurnGroupViewModel viewModel) { }
	// RVA: 0x242dfd4 VA: 0x7594a45fd4
	private Void Awake() { }
	// RVA: 0x242e0e0 VA: 0x7594a460e0
	private Void OnDestroy() { }
	// RVA: 0x242e1ec VA: 0x7594a461ec
	private Void _PageSwitchCallback(Int32 index) { }
	// RVA: 0x242e2d4 VA: 0x7594a462d4
	private Void Update() { }
	// RVA: 0x242e3e8 VA: 0x7594a463e8
	private Void _TryTweenToPage(Int32 pageIndex) { }
	// RVA: 0x242e47c VA: 0x7594a4647c
	public Void ApplyPriceState() { }
	// RVA: 0x242db08 VA: 0x7594a45b08
	public Void TurnCoinFurn() { }
	// RVA: 0x242eb10 VA: 0x7594a46b10
	public Void TurnCoinDiam() { }
	// RVA: 0x242eba4 VA: 0x7594a46ba4
	public Void DismissSelf() { }
	// RVA: 0x242ec20 VA: 0x7594a46c20
	public Void OnClick() { }
	// RVA: 0x242ed70 VA: 0x7594a46d70
	public Void .ctor() { }
}
```