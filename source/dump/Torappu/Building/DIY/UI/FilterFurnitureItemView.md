# FilterFurnitureItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `FurnitureItemView _innerFurnitureItemView`

- `GameObject _selectBackground`

- `Text _descriptionLabel`

- `GameObject _descriptionPanel`

- `DIYShopFilterViewData m_shopItemData`


## Methods

- `Void add_buttonPressed(Action`1)`

- `Void remove_buttonPressed(Action`1)`

- `Void add_infoPressed(Action`1)`

- `Void remove_infoPressed(Action`1)`

- `Void add_descPressed(Action`1)`

- `Void remove_descPressed(Action`1)`

- `Void _SetupIcon(Image, Sprite)`

- `Void Setup(DIYShopFilterViewData)`

- `Void OnBackgroundButtonPressed()`

- `Void _OnButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void _OnInfoButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class FilterFurnitureItemView : MonoBehaviour, IHotfixable
{
	private FurnitureItemView _innerFurnitureItemView; // 0x18
	private GameObject _selectBackground; // 0x20
	private Text _descriptionLabel; // 0x28
	private GameObject _descriptionPanel; // 0x30
	private DIYShopFilterViewData m_shopItemData; // 0x38
	private Action`1 buttonPressed; // 0x40
	private Action`1 infoPressed; // 0x48
	private Action`1 descPressed; // 0x50
	private static DelegateBridge __Hotfix0_add_buttonPressed; // 0x0
	private static DelegateBridge __Hotfix0_remove_buttonPressed; // 0x8
	private static DelegateBridge __Hotfix0_add_infoPressed; // 0x10
	private static DelegateBridge __Hotfix0_remove_infoPressed; // 0x18
	private static DelegateBridge __Hotfix0_add_descPressed; // 0x20
	private static DelegateBridge __Hotfix0_remove_descPressed; // 0x28
	private static DelegateBridge __Hotfix0__SetupIcon; // 0x30
	private static DelegateBridge __Hotfix0_Setup; // 0x38
	private static DelegateBridge __Hotfix0_OnBackgroundButtonPressed; // 0x40
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0__OnInfoButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x382a42c VA: 0x7595e4242c
	public Void add_buttonPressed(Action`1 value) { }
	// RVA: 0x382a520 VA: 0x7595e42520
	public Void remove_buttonPressed(Action`1 value) { }
	// RVA: 0x382a614 VA: 0x7595e42614
	public Void add_infoPressed(Action`1 value) { }
	// RVA: 0x382a708 VA: 0x7595e42708
	public Void remove_infoPressed(Action`1 value) { }
	// RVA: 0x382a7fc VA: 0x7595e427fc
	public Void add_descPressed(Action`1 value) { }
	// RVA: 0x382a8f0 VA: 0x7595e428f0
	public Void remove_descPressed(Action`1 value) { }
	// RVA: 0x382a9e4 VA: 0x7595e429e4
	private Void _SetupIcon(Image img, Sprite sp) { }
	// RVA: 0x382ab18 VA: 0x7595e42b18
	public Void Setup(DIYShopFilterViewData data) { }
	// RVA: 0x382adac VA: 0x7595e42dac
	public Void OnBackgroundButtonPressed() { }
	// RVA: 0x382ae38 VA: 0x7595e42e38
	private Void _OnButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x382aee4 VA: 0x7595e42ee4
	private Void _OnInfoButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x382af90 VA: 0x7595e42f90
	private Void OnDestroy() { }
	// RVA: 0x382b100 VA: 0x7595e43100
	public Void .ctor() { }
}
```