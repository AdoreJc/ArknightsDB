# DIYRecycleElementView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `FurnitureItemView _furnItemView`

- `GameObject _bgGrey`

- `GameObject _frameSelected`

- `GameObject _imgUpperBlue`

- `GameObject _coverGrey`

- `Int32 m_index`


## Properties

- `Int32 index`


## Methods

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Void _OnButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void _OnInfoButtonPressed(DIYItemViewData, FurnitureItemView)`

- `Void SetUpFurnItemView(DIYItemViewData, Int32, ElementType, Boolean)`

- `Void UpdateFurnItemView(DIYItemViewData, ElementType, Boolean)`

- `Void _UpdateFuncFurniFrame(DIYItemViewData, ElementType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYRecycleElementView : MonoBehaviour, IHotfixable
{
	private FurnitureItemView _furnItemView; // 0x18
	private GameObject _bgGrey; // 0x20
	private GameObject _frameSelected; // 0x28
	private GameObject _imgUpperBlue; // 0x30
	private GameObject _coverGrey; // 0x38
	public Func`2 furnitureSelected; // 0x40
	public Func`2 infoButtonPressed; // 0x48
	private Int32 m_index; // 0x50
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_set_index; // 0x8
	private static DelegateBridge __Hotfix0__OnButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0__OnInfoButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0_SetUpFurnItemView; // 0x20
	private static DelegateBridge __Hotfix0_UpdateFurnItemView; // 0x28
	private static DelegateBridge __Hotfix0__UpdateFuncFurniFrame; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 index { get; set; }

	// RVA: 0x382b170 VA: 0x7595e43170
	public Int32 get_index() { }
	// RVA: 0x382b1d8 VA: 0x7595e431d8
	public Void set_index(Int32 value) { }
	// RVA: 0x382b254 VA: 0x7595e43254
	private Void _OnButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x382b34c VA: 0x7595e4334c
	private Void _OnInfoButtonPressed(DIYItemViewData data, FurnitureItemView view) { }
	// RVA: 0x381c970 VA: 0x7595e34970
	public Void SetUpFurnItemView(DIYItemViewData viewData, Int32 idx, ElementType type, Boolean firstRow) { }
	// RVA: 0x381c80c VA: 0x7595e3480c
	public Void UpdateFurnItemView(DIYItemViewData viewData, ElementType type, Boolean firstRow) { }
	// RVA: 0x382b444 VA: 0x7595e43444
	private Void _UpdateFuncFurniFrame(DIYItemViewData viewData, ElementType type, Boolean firstRow) { }
	// RVA: 0x382b66c VA: 0x7595e4366c
	public Void .ctor() { }
}
```