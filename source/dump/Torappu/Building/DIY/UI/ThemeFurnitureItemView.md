# ThemeFurnitureItemView

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

- `DIYThemeItemViewData m_themeItemData`


## Methods

- `Void add_buttonPressed(Action`2)`

- `Void remove_buttonPressed(Action`2)`

- `Void _SetupIcon(Image, Sprite)`

- `Void Setup(DIYThemeItemViewData)`

- `Void _OnButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class ThemeFurnitureItemView : MonoBehaviour, IHotfixable
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
	private DIYThemeItemViewData m_themeItemData; // 0x60
	private Action`2 buttonPressed; // 0x68
	private static DelegateBridge __Hotfix0_add_buttonPressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_buttonPressed; // 0x8
	private static DelegateBridge __Hotfix0__SetupIcon; // 0x10
	private static DelegateBridge __Hotfix0_Setup; // 0x18
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3839e54 VA: 0x7595e51e54
	public Void add_buttonPressed(Action`2 value) { }
	// RVA: 0x3839f48 VA: 0x7595e51f48
	public Void remove_buttonPressed(Action`2 value) { }
	// RVA: 0x383a03c VA: 0x7595e5203c
	private Void _SetupIcon(Image img, Sprite sp) { }
	// RVA: 0x383a170 VA: 0x7595e52170
	public Void Setup(DIYThemeItemViewData data) { }
	// RVA: 0x383a894 VA: 0x7595e52894
	private Void _OnButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x383a944 VA: 0x7595e52944
	private Void OnDestroy() { }
	// RVA: 0x383aa60 VA: 0x7595e52a60
	public Void .ctor() { }
}
```