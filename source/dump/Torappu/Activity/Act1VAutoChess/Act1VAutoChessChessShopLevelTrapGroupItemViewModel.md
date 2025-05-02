# Act1VAutoChessChessShopLevelTrapGroupItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <groupLevel>k__BackingField`

- `Act1VAutoChessShopLevelTagViewModel <levelTagViewModel>k__BackingField`


## Properties

- `Int32 groupLevel`

- `Act1VAutoChessShopLevelTagViewModel levelTagViewModel`


## Methods

- `Int32 get_groupLevel()`

- `Void set_groupLevel(Int32)`

- `Act1VAutoChessShopLevelTagViewModel get_levelTagViewModel()`

- `Void set_levelTagViewModel(Act1VAutoChessShopLevelTagViewModel)`

- `Void LoadData(Act1VAutoChessShopLevelDisplayData, ActivityAutoChessVerify1Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelTrapGroupItemViewModel : IHotfixable
{
	private Int32 <groupLevel>k__BackingField; // 0x10
	private Act1VAutoChessShopLevelTagViewModel <levelTagViewModel>k__BackingField; // 0x18
	private List`1 m_levelTrapItemCardViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_get_groupLevel; // 0x0
	private static DelegateBridge __Hotfix0_set_groupLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_levelTagViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_levelTagViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_levelTrapItemCardViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 groupLevel { get; set; }
	public Act1VAutoChessShopLevelTagViewModel levelTagViewModel { get; set; }
	public List`1 levelTrapItemCardViewModelList { get; }

	// RVA: 0x332ca08 VA: 0x7595944a08
	public Int32 get_groupLevel() { }
	// RVA: 0x332ca70 VA: 0x7595944a70
	private Void set_groupLevel(Int32 value) { }
	// RVA: 0x3324294 VA: 0x759593c294
	public Act1VAutoChessShopLevelTagViewModel get_levelTagViewModel() { }
	// RVA: 0x332caec VA: 0x7595944aec
	private Void set_levelTagViewModel(Act1VAutoChessShopLevelTagViewModel value) { }
	// RVA: 0x33242fc VA: 0x759593c2fc
	public List`1 get_levelTrapItemCardViewModelList() { }
	// RVA: 0x332cb70 VA: 0x7595944b70
	public Void LoadData(Act1VAutoChessShopLevelDisplayData displayData, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x332ce5c VA: 0x7595944e5c
	public Void .ctor() { }
}
```