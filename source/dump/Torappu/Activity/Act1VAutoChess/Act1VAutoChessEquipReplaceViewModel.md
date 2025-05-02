# Act1VAutoChessEquipReplaceViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <mainDesc>k__BackingField`

- `Boolean <fastMode>k__BackingField`

- `Int32 <selectedIndex>k__BackingField`


## Properties

- `String mainDesc`

- `Boolean fastMode`

- `Int32 selectedIndex`


## Methods

- `String get_mainDesc()`

- `Void set_mainDesc(String)`

- `Boolean get_fastMode()`

- `Void set_fastMode(Boolean)`

- `Int32 get_selectedIndex()`

- `Void set_selectedIndex(Int32)`

- `Void LoadData(Input)`

- `Void Select(Int32)`

- `AutoChessChar _GetTargetChessChar(PlayerAutoChessV1Activity, Int32)`

- `Act1VAutoChessEquipReplaceItemViewModel _LoadTrapModel(ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity, AutoChessTrap)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEquipReplaceViewModel : IHotfixable
{
	private const String EQUIP_COUNTER_FORMAT; // 0x0
	private readonly List`1 m_items; // 0x10
	private String <mainDesc>k__BackingField; // 0x18
	private Boolean <fastMode>k__BackingField; // 0x20
	private Int32 <selectedIndex>k__BackingField; // 0x24
	private static DelegateBridge __Hotfix0_get_mainDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_mainDesc; // 0x8
	private static DelegateBridge __Hotfix0_get_items; // 0x10
	private static DelegateBridge __Hotfix0_get_fastMode; // 0x18
	private static DelegateBridge __Hotfix0_set_fastMode; // 0x20
	private static DelegateBridge __Hotfix0_get_selectedIndex; // 0x28
	private static DelegateBridge __Hotfix0_set_selectedIndex; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_Select; // 0x40
	private static DelegateBridge __Hotfix0__GetTargetChessChar; // 0x48
	private static DelegateBridge __Hotfix0__LoadTrapModel; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String mainDesc { get; set; }
	public List`1 items { get; }
	public Boolean fastMode { get; set; }
	public Int32 selectedIndex { get; set; }

	// RVA: 0x336f2f4 VA: 0x75959872f4
	public String get_mainDesc() { }
	// RVA: 0x336f694 VA: 0x7595987694
	private Void set_mainDesc(String value) { }
	// RVA: 0x336f42c VA: 0x759598742c
	public List`1 get_items() { }
	// RVA: 0x336f35c VA: 0x759598735c
	public Boolean get_fastMode() { }
	// RVA: 0x336f718 VA: 0x7595987718
	private Void set_fastMode(Boolean value) { }
	// RVA: 0x336f3c4 VA: 0x75959873c4
	public Int32 get_selectedIndex() { }
	// RVA: 0x336f798 VA: 0x7595987798
	private Void set_selectedIndex(Int32 value) { }
	// RVA: 0x336f814 VA: 0x7595987814
	public Void LoadData(Input input) { }
	// RVA: 0x336fd94 VA: 0x7595987d94
	public Void Select(Int32 index) { }
	// RVA: 0x336fa90 VA: 0x7595987a90
	private AutoChessChar _GetTargetChessChar(PlayerAutoChessV1Activity playerData, Int32 charInstId) { }
	// RVA: 0x336fb98 VA: 0x7595987b98
	private Act1VAutoChessEquipReplaceItemViewModel _LoadTrapModel(ActivityAutoChessVerify1Data gameData, PlayerAutoChessV1Activity playerData, AutoChessTrap trap) { }
	// RVA: 0x336fe64 VA: 0x7595987e64
	public Void .ctor() { }
}
```