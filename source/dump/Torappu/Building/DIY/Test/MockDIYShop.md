# MockDIYShop

**Namespace:** `Torappu.Building.DIY.Test`


## Fields

- `Int32 _cash`

- `Int32 _furnitureCoin`

- `MockFurnitureStorage _furnitureStorage`

- `Single _fakeDelayTime`

- `Single m_timeCnt`

- `Int32 m_resultCode`


## Properties

- `Int32 currentCash`

- `Int32 currentFurnitureCoin`


## Methods

- `Void Update()`

- `Void RefreshData(Action`1)`

- `Void Setup(IFurnitureDataProvider, IDIYRoomModifierDataProvider)`

- `Int32 get_currentCash()`

- `Int32 get_currentFurnitureCoin()`

- `Void _StartResultHandleCountDown(Action`1, Int32)`

- `Void TryBuyShopItem(IDIYShopItem, Int32, Int32, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.Test
public class MockDIYShop : MonoBehaviour, IDIYShop
{
	private Item[] _items; // 0x18
	private Int32 _cash; // 0x20
	private Int32 _furnitureCoin; // 0x24
	private MockFurnitureStorage _furnitureStorage; // 0x28
	private Single _fakeDelayTime; // 0x30
	private Single m_timeCnt; // 0x34
	private Int32 m_resultCode; // 0x38
	private Action`1 m_handler; // 0x40

	public Int32 currentCash { get; }
	public Int32 currentFurnitureCoin { get; }

	// RVA: 0x37f6100 VA: 0x7595e0e100
	private Void Update() { }
	// RVA: 0x37f6164 VA: 0x7595e0e164
	public Void RefreshData(Action`1 resultHandler) { }
	// RVA: 0x37f61b8 VA: 0x7595e0e1b8
	public IEnumerable`1 EnumShopItems() { }
	// RVA: 0x37f2ffc VA: 0x7595e0affc
	public Void Setup(IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider) { }
	// RVA: 0x37f64f4 VA: 0x7595e0e4f4
	public Int32 get_currentCash() { }
	// RVA: 0x37f64fc VA: 0x7595e0e4fc
	public Int32 get_currentFurnitureCoin() { }
	// RVA: 0x37f6190 VA: 0x7595e0e190
	private Void _StartResultHandleCountDown(Action`1 handler, Int32 resultCode) { }
	// RVA: 0x37f6504 VA: 0x7595e0e504
	public Void TryBuyShopItem(IDIYShopItem item, Int32 cashBuyCount, Int32 furnitureCoinBuyCount, Action`1 resultHandler) { }
	// RVA: 0x37f6c00 VA: 0x7595e0ec00
	public Void .ctor() { }
}
```