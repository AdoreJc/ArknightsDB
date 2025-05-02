# ShopFurnitureItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `FurnitureItemView _innerFurnitureItemView`

- `Text _countLabel`

- `Text _comfortLabel`

- `GameObject _cashCostPanel`

- `Text _cashCostLabel`

- `GameObject _furnitureCoinCostPanel`

- `Text _furnitureCoinCostLabel`

- `GameObject _discountPanel`

- `Text _discountLabel`

- `GameObject _rarityPanel`

- `MeetingClueRestTimeLabel _restTimeLabel`

- `DIYShopItemViewData m_shopItemData`


## Methods

- `Void add_buttonPressed(Action`2)`

- `Void remove_buttonPressed(Action`2)`

- `Void _SetupIcon(Image, Sprite)`

- `Void Setup(DIYShopItemViewData)`

- `Void Refresh()`

- `Void _OnButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class ShopFurnitureItemView : MonoBehaviour, IHotfixable
{
	private FurnitureItemView _innerFurnitureItemView; // 0x18
	private Text _countLabel; // 0x20
	private Text _comfortLabel; // 0x28
	private GameObject _cashCostPanel; // 0x30
	private Text _cashCostLabel; // 0x38
	private GameObject _furnitureCoinCostPanel; // 0x40
	private Text _furnitureCoinCostLabel; // 0x48
	private GameObject _discountPanel; // 0x50
	private Text _discountLabel; // 0x58
	private GameObject _rarityPanel; // 0x60
	private MeetingClueRestTimeLabel _restTimeLabel; // 0x68
	private DIYShopItemViewData m_shopItemData; // 0x70
	private Action`2 buttonPressed; // 0x78
	private static DelegateBridge __Hotfix0_add_buttonPressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_buttonPressed; // 0x8
	private static DelegateBridge __Hotfix0__SetupIcon; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x18
	private static DelegateBridge __Hotfix0_Refresh; // 0x20
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x382d50c VA: 0x7595e4550c
	public Void add_buttonPressed(Action`2 value) { }
	// RVA: 0x382d600 VA: 0x7595e45600
	public Void remove_buttonPressed(Action`2 value) { }
	// RVA: 0x382d6f4 VA: 0x7595e456f4
	private Void _SetupIcon(Image img, Sprite sp) { }
	// RVA: 0x382d828 VA: 0x7595e45828
	public Void Setup(DIYShopItemViewData data) { }
	// RVA: 0x382d8b4 VA: 0x7595e458b4
	public Void Refresh() { }
	// RVA: 0x382e244 VA: 0x7595e46244
	private Void _OnButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x382e2f4 VA: 0x7595e462f4
	private Void OnDestroy() { }
	// RVA: 0x382e410 VA: 0x7595e46410
	public Void .ctor() { }
}
```