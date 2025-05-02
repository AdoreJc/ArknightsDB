# SandboxV2AdminMainCookPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainCookTypeSelectorView _leftTypeView`

- `SandboxV2CookDrinkView _drinkView`

- `SandboxV2CookFoodListView _foodListView`

- `SandboxV2CookFreeCookView _freeCookView`

- `SandboxV2AdminMainCookPanelModelProperty m_prop`

- `Int32 m_dialogInstId`


## Methods

- `Void _InitIfNot()`

- `Void _InitDrinkEvents()`

- `Void _InitFoodListEvents()`

- `Void _InitFreeCookEvents()`

- `Boolean _CheckDrinkPanelInvalid(SandboxV2AdminMainCookPanelModel)`

- `Void _DrinkSwitchModeEvent()`

- `Void _DrinkClearEvent()`

- `Boolean _DrinkSelectMaterialsToFillOneBottleEvent()`

- `Void _DrinkMakeEvent()`

- `Boolean _DrinkItemSelectEvent(Int32, Int32)`

- `Boolean _CheckFoodListPanelInvalid(SandboxV2AdminMainCookPanelModel)`

- `Void _FoodListSelectItemEvent(Int32)`

- `Boolean _CheckFreeCookPanelInvalid(SandboxV2AdminMainCookPanelModel)`

- `Void _FreeCookSelectMainMatEvent(Int32)`

- `Void _FreeCookDeselectMainMatEvent(Int32)`

- `Void _FreeCookSelectSubMatEvent(Int32)`

- `Void _FreeCookDeselectSubMatEvent(Int32)`

- `Void _FreeCookClearMatEvent()`

- `Void _FreeCookMakeEvent()`

- `Void _OnCookDrinkRespond(SandboxV2CookDrinkResponse)`

- `Void _OnCookFoodRespond(SandboxV2CookFoodResponse)`

- `Void _RefreshIfCan()`

- `Void _TutorialOnly_RegisterObject()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainCookPanel : SandboxV2AdminMainTabPanel
{
	private SandboxV2AdminMainCookTypeSelectorView _leftTypeView; // 0x60
	private SandboxV2CookDrinkView _drinkView; // 0x68
	private SandboxV2CookFoodListView _foodListView; // 0x70
	private SandboxV2CookFreeCookView _freeCookView; // 0x78
	private SandboxV2AdminMainCookPanelModelProperty m_prop; // 0x80
	private Int32 m_dialogInstId; // 0x88
	private static DelegateBridge __Hotfix0_get_panelType; // 0x0
	private static DelegateBridge __Hotfix0_get_topTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitDrinkEvents; // 0x20
	private static DelegateBridge __Hotfix0__InitFoodListEvents; // 0x28
	private static DelegateBridge __Hotfix0__InitFreeCookEvents; // 0x30
	private static DelegateBridge __Hotfix0__CheckDrinkPanelInvalid; // 0x38
	private static DelegateBridge __Hotfix0__DrinkSwitchModeEvent; // 0x40
	private static DelegateBridge __Hotfix0__DrinkClearEvent; // 0x48
	private static DelegateBridge __Hotfix0__DrinkSelectMaterialsToFillOneBottleEvent; // 0x50
	private static DelegateBridge __Hotfix0__DrinkMakeEvent; // 0x58
	private static DelegateBridge __Hotfix0__DrinkItemSelectEvent; // 0x60
	private static DelegateBridge __Hotfix0__CheckFoodListPanelInvalid; // 0x68
	private static DelegateBridge __Hotfix0__FoodListSelectItemEvent; // 0x70
	private static DelegateBridge __Hotfix0__CheckFreeCookPanelInvalid; // 0x78
	private static DelegateBridge __Hotfix0__FreeCookSelectMainMatEvent; // 0x80
	private static DelegateBridge __Hotfix0__FreeCookDeselectMainMatEvent; // 0x88
	private static DelegateBridge __Hotfix0__FreeCookSelectSubMatEvent; // 0x90
	private static DelegateBridge __Hotfix0__FreeCookDeselectSubMatEvent; // 0x98
	private static DelegateBridge __Hotfix0__FreeCookClearMatEvent; // 0xa0
	private static DelegateBridge __Hotfix0__FreeCookMakeEvent; // 0xa8
	private static DelegateBridge __Hotfix0__OnCookDrinkRespond; // 0xb0
	private static DelegateBridge __Hotfix0__OnCookFoodRespond; // 0xb8
	private static DelegateBridge __Hotfix0__RefreshIfCan; // 0xc0
	private static DelegateBridge __Hotfix0__TutorialOnly_RegisterObject; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public override SandboxV2AdminMainPanelType panelType { get; }
	public override String topTitle { get; }

	// RVA: 0x24ca258 VA: 0x7594ae2258
	public override SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24ca2c0 VA: 0x7594ae22c0
	public override String get_topTitle() { }
	// RVA: 0x24ca34c VA: 0x7594ae234c
	protected override Void OnUpdate(SandboxV2AdminMainTabPanelUpdateCase updateCase) { }
	// RVA: 0x24ca438 VA: 0x7594ae2438
	private Void _InitIfNot() { }
	// RVA: 0x24caa60 VA: 0x7594ae2a60
	private Void _InitDrinkEvents() { }
	// RVA: 0x24cac74 VA: 0x7594ae2c74
	private Void _InitFoodListEvents() { }
	// RVA: 0x24cad34 VA: 0x7594ae2d34
	private Void _InitFreeCookEvents() { }
	// RVA: 0x24cb1d0 VA: 0x7594ae31d0
	private Boolean _CheckDrinkPanelInvalid(SandboxV2AdminMainCookPanelModel model) { }
	// RVA: 0x24cb324 VA: 0x7594ae3324
	private Void _DrinkSwitchModeEvent() { }
	// RVA: 0x24cb40c VA: 0x7594ae340c
	private Void _DrinkClearEvent() { }
	// RVA: 0x24cb4dc VA: 0x7594ae34dc
	private Boolean _DrinkSelectMaterialsToFillOneBottleEvent() { }
	// RVA: 0x24cb5b8 VA: 0x7594ae35b8
	private Void _DrinkMakeEvent() { }
	// RVA: 0x24cbc28 VA: 0x7594ae3c28
	private Boolean _DrinkItemSelectEvent(Int32 index, Int32 count) { }
	// RVA: 0x24cbd28 VA: 0x7594ae3d28
	private Boolean _CheckFoodListPanelInvalid(SandboxV2AdminMainCookPanelModel model) { }
	// RVA: 0x24cbe7c VA: 0x7594ae3e7c
	private Void _FoodListSelectItemEvent(Int32 index) { }
	// RVA: 0x24cbff4 VA: 0x7594ae3ff4
	private Boolean _CheckFreeCookPanelInvalid(SandboxV2AdminMainCookPanelModel model) { }
	// RVA: 0x24cc148 VA: 0x7594ae4148
	private Void _FreeCookSelectMainMatEvent(Int32 index) { }
	// RVA: 0x24cc358 VA: 0x7594ae4358
	private Void _FreeCookDeselectMainMatEvent(Int32 index) { }
	// RVA: 0x24cc448 VA: 0x7594ae4448
	private Void _FreeCookSelectSubMatEvent(Int32 index) { }
	// RVA: 0x24cc538 VA: 0x7594ae4538
	private Void _FreeCookDeselectSubMatEvent(Int32 index) { }
	// RVA: 0x24cc628 VA: 0x7594ae4628
	private Void _FreeCookClearMatEvent() { }
	// RVA: 0x24cc6f8 VA: 0x7594ae46f8
	private Void _FreeCookMakeEvent() { }
	// RVA: 0x24ccc0c VA: 0x7594ae4c0c
	private Void _OnCookDrinkRespond(SandboxV2CookDrinkResponse response) { }
	// RVA: 0x24cce8c VA: 0x7594ae4e8c
	private Void _OnCookFoodRespond(SandboxV2CookFoodResponse response) { }
	// RVA: 0x24cd2b8 VA: 0x7594ae52b8
	private Void _RefreshIfCan() { }
	// RVA: 0x24ca864 VA: 0x7594ae2864
	private Void _TutorialOnly_RegisterObject() { }
	// RVA: 0x24cd3bc VA: 0x7594ae53bc
	public Void .ctor() { }
}
```