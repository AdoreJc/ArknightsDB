# DIYShopBuyPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _furnitureNameLabel`

- `Text _originPriceLabel`

- `GameObject _originPriceStrike`

- `GameObject _discountPanel`

- `Text _discountLabel`

- `Text _priceLabel`

- `Text _hasFurnitureCountLabel`

- `Text _themeLabel`

- `Text _groupLabel`

- `GameObject _themeGroupPanel`

- `UsageDescGroup _lowerGroup`

- `UsageDescGroup _upperGroup`

- `Image _furnitureIcon`

- `GameObject _buyLimitPanel`

- `Text _buyLimitLabel`

- `Text _comfortLabel`

- `GameObjectArrayCountControl _rarityStarArray`

- `DIYShopBuyItemLine _buyItemLine`

- `GameObject _paySwitchObject`

- `Button _okButton`

- `Color _originPriceValidColor`

- `Color _originPriceInvalidColor`

- `CanvasGroup _panelCanvasGroup`

- `Image _background`

- `Argument m_currentArgument`

- `SwitchState m_currentSwitchState`


## Methods

- `Void add_commandButtonPressed(Action`3)`

- `Void remove_commandButtonPressed(Action`3)`

- `IEnumerator _LayoutCoroutine()`

- `Void Setup(Argument)`

- `Void _SetupAsPart(Int32, Int32, Int32, Int32, GameObject[], GameObject[])`

- `Void _SetupAsCash()`

- `Void _SetupAsFurnitureCoin()`

- `Void Show()`

- `Void Hide()`

- `Void OnBuyButtonPressed()`

- `Void OnCancelButtonPressed()`

- `Void OnCashSwitchPressed()`

- `Void OnFurnitureCoinSwitchPressed()`

- `Void _OnLineCountChanged(Int32)`

- `Void OnDestroy()`

- `Void <Hide>b__40_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopBuyPanel : MonoBehaviour, IHotfixable
{
	private Text _furnitureNameLabel; // 0x18
	private Text _originPriceLabel; // 0x20
	private GameObject _originPriceStrike; // 0x28
	private GameObject _discountPanel; // 0x30
	private Text _discountLabel; // 0x38
	private Text _priceLabel; // 0x40
	private Text _hasFurnitureCountLabel; // 0x48
	private Text _themeLabel; // 0x50
	private Text _groupLabel; // 0x58
	private GameObject _themeGroupPanel; // 0x60
	private UsageDescGroup _lowerGroup; // 0x68
	private UsageDescGroup _upperGroup; // 0x70
	private Image _furnitureIcon; // 0x78
	private GameObject _buyLimitPanel; // 0x80
	private Text _buyLimitLabel; // 0x88
	private Text _comfortLabel; // 0x90
	private GameObjectArrayCountControl _rarityStarArray; // 0x98
	private DIYShopBuyItemLine _buyItemLine; // 0xa0
	private GameObject _paySwitchObject; // 0xa8
	private GameObject[] _cashOnlyObjects; // 0xb0
	private GameObject[] _furnitureCoinOnlyObjects; // 0xb8
	private Button _okButton; // 0xc0
	private Color _originPriceValidColor; // 0xc8
	private Color _originPriceInvalidColor; // 0xd8
	private CanvasGroup _panelCanvasGroup; // 0xe8
	private Image _background; // 0xf0
	private Argument m_currentArgument; // 0xf8
	private SwitchState m_currentSwitchState; // 0x100
	private Action`3 commandButtonPressed; // 0x108
	private static DelegateBridge __Hotfix0_add_commandButtonPressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_commandButtonPressed; // 0x8
	private static DelegateBridge __Hotfix0__LayoutCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x18
	private static DelegateBridge __Hotfix0__SetupAsPart; // 0x20
	private static DelegateBridge __Hotfix0__SetupAsCash; // 0x28
	private static DelegateBridge __Hotfix0__SetupAsFurnitureCoin; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x38
	private static DelegateBridge __Hotfix0_Hide; // 0x40
	private static DelegateBridge __Hotfix0_OnBuyButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnCancelButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnCashSwitchPressed; // 0x58
	private static DelegateBridge __Hotfix0_OnFurnitureCoinSwitchPressed; // 0x60
	private static DelegateBridge __Hotfix0__OnLineCountChanged; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x37ffff4 VA: 0x7595e17ff4
	public Void add_commandButtonPressed(Action`3 value) { }
	// RVA: 0x38000ec VA: 0x7595e180ec
	public Void remove_commandButtonPressed(Action`3 value) { }
	// RVA: 0x38001e4 VA: 0x7595e181e4
	private IEnumerator _LayoutCoroutine() { }
	// RVA: 0x38002b8 VA: 0x7595e182b8
	public Void Setup(Argument arg) { }
	// RVA: 0x3801700 VA: 0x7595e19700
	private Void _SetupAsPart(Int32 originPrice, Int32 discount, Int32 price, Int32 maxBuyCount, GameObject[] activeObjects, GameObject[] inactiveObjects) { }
	// RVA: 0x38014f4 VA: 0x7595e194f4
	private Void _SetupAsCash() { }
	// RVA: 0x38012e8 VA: 0x7595e192e8
	private Void _SetupAsFurnitureCoin() { }
	// RVA: 0x3801bb0 VA: 0x7595e19bb0
	public Void Show() { }
	// RVA: 0x3801d38 VA: 0x7595e19d38
	public Void Hide() { }
	// RVA: 0x3801eac VA: 0x7595e19eac
	public Void OnBuyButtonPressed() { }
	// RVA: 0x3801fb0 VA: 0x7595e19fb0
	public Void OnCancelButtonPressed() { }
	// RVA: 0x3802018 VA: 0x7595e1a018
	public Void OnCashSwitchPressed() { }
	// RVA: 0x3802080 VA: 0x7595e1a080
	public Void OnFurnitureCoinSwitchPressed() { }
	// RVA: 0x3801ad4 VA: 0x7595e19ad4
	private Void _OnLineCountChanged(Int32 count) { }
	// RVA: 0x38020e8 VA: 0x7595e1a0e8
	private Void OnDestroy() { }
	// RVA: 0x38021f0 VA: 0x7595e1a1f0
	public Void .ctor() { }
	// RVA: 0x3802260 VA: 0x7595e1a260
	private Void <Hide>b__40_0() { }
}
```