# CrisisShopWrapped

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `SeasonFlag seasonFlag`

- `CrisisLongTermShopWrapped longTermViewModel`

- `CrisisSeasonShopWrapped seasonViewModel`


## Properties

- `Int32 buyCount`

- `CrisisShopVer shopVer`

- `Int32 ableBuyCount`

- `Boolean isTimeLimited`

- `Boolean isUnique`

- `PlayerGoodProgressData progressInfo`

- `CrisisCommonShopItemData commonViewModel`


## Methods

- `Int32 get_buyCount()`

- `CrisisShopVer get_shopVer()`

- `Int32 get_ableBuyCount()`

- `Boolean get_isTimeLimited()`

- `Boolean get_isUnique()`

- `PlayerGoodProgressData get_progressInfo()`

- `CrisisCommonShopItemData get_commonViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopWrapped
{
	public SeasonFlag seasonFlag; // 0x10
	public CrisisLongTermShopWrapped longTermViewModel; // 0x18
	public CrisisSeasonShopWrapped seasonViewModel; // 0x20

	public List`1 progressViewModelList { get; }
	public Int32 buyCount { get; }
	public CrisisShopVer shopVer { get; }
	public Int32 ableBuyCount { get; }
	public Boolean isTimeLimited { get; }
	public Boolean isUnique { get; }
	public PlayerGoodProgressData progressInfo { get; }
	public CrisisCommonShopItemData commonViewModel { get; }

	// RVA: 0x2c35f50 VA: 0x759524df50
	public static CrisisProgressShopItemViewModel GetProgressItem(List`1 list, Int32 order) { }
	// RVA: 0x2c36060 VA: 0x759524e060
	public List`1 get_progressViewModelList() { }
	// RVA: 0x2c36090 VA: 0x759524e090
	public Int32 get_buyCount() { }
	// RVA: 0x2c360c0 VA: 0x759524e0c0
	public CrisisShopVer get_shopVer() { }
	// RVA: 0x2c360f0 VA: 0x759524e0f0
	public Int32 get_ableBuyCount() { }
	// RVA: 0x2c36120 VA: 0x759524e120
	public Boolean get_isTimeLimited() { }
	// RVA: 0x2c36158 VA: 0x759524e158
	public Boolean get_isUnique() { }
	// RVA: 0x2c36188 VA: 0x759524e188
	public PlayerGoodProgressData get_progressInfo() { }
	// RVA: 0x2c361b8 VA: 0x759524e1b8
	public CrisisCommonShopItemData get_commonViewModel() { }
	// RVA: 0x2c361e8 VA: 0x759524e1e8
	public Void .ctor() { }
}
```