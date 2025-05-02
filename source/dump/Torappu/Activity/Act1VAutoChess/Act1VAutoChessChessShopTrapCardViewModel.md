# Act1VAutoChessChessShopTrapCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <chessId>k__BackingField`

- `String <trapId>k__BackingField`

- `Int32 <chessLevel>k__BackingField`

- `Act1VAutoChessTrapChessType <trapChessType>k__BackingField`

- `String <trapItemName>k__BackingField`

- `String <trapItemDesc>k__BackingField`

- `Int32 m_sortId`


## Properties

- `String chessId`

- `String trapId`

- `Int32 chessLevel`

- `Act1VAutoChessTrapChessType trapChessType`

- `String trapItemName`

- `String trapItemDesc`


## Methods

- `String get_chessId()`

- `Void set_chessId(String)`

- `String get_trapId()`

- `Void set_trapId(String)`

- `Int32 get_chessLevel()`

- `Void set_chessLevel(Int32)`

- `Act1VAutoChessTrapChessType get_trapChessType()`

- `Void set_trapChessType(Act1VAutoChessTrapChessType)`

- `String get_trapItemName()`

- `Void set_trapItemName(String)`

- `String get_trapItemDesc()`

- `Void set_trapItemDesc(String)`

- `Void LoadData(Act1VAutoChessTrapShopChessData, ActivityAutoChessVerify1Data)`

- `Int32 CompareTo(Act1VAutoChessChessShopTrapCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopTrapCardViewModel : IHotfixable, IComparable`1
{
	private String <chessId>k__BackingField; // 0x10
	private String <trapId>k__BackingField; // 0x18
	private Int32 <chessLevel>k__BackingField; // 0x20
	private Act1VAutoChessTrapChessType <trapChessType>k__BackingField; // 0x24
	private String <trapItemName>k__BackingField; // 0x28
	private String <trapItemDesc>k__BackingField; // 0x30
	private Int32 m_sortId; // 0x38
	private static DelegateBridge __Hotfix0_get_chessId; // 0x0
	private static DelegateBridge __Hotfix0_set_chessId; // 0x8
	private static DelegateBridge __Hotfix0_get_trapId; // 0x10
	private static DelegateBridge __Hotfix0_set_trapId; // 0x18
	private static DelegateBridge __Hotfix0_get_chessLevel; // 0x20
	private static DelegateBridge __Hotfix0_set_chessLevel; // 0x28
	private static DelegateBridge __Hotfix0_get_trapChessType; // 0x30
	private static DelegateBridge __Hotfix0_set_trapChessType; // 0x38
	private static DelegateBridge __Hotfix0_get_trapItemName; // 0x40
	private static DelegateBridge __Hotfix0_set_trapItemName; // 0x48
	private static DelegateBridge __Hotfix0_get_trapItemDesc; // 0x50
	private static DelegateBridge __Hotfix0_set_trapItemDesc; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_CompareTo; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String chessId { get; set; }
	public String trapId { get; set; }
	public Int32 chessLevel { get; set; }
	public Act1VAutoChessTrapChessType trapChessType { get; set; }
	public String trapItemName { get; set; }
	public String trapItemDesc { get; set; }

	// RVA: 0x3324904 VA: 0x759593c904
	public String get_chessId() { }
	// RVA: 0x3328dcc VA: 0x7595940dcc
	private Void set_chessId(String value) { }
	// RVA: 0x3324aa4 VA: 0x759593caa4
	public String get_trapId() { }
	// RVA: 0x3328e50 VA: 0x7595940e50
	private Void set_trapId(String value) { }
	// RVA: 0x3324b0c VA: 0x759593cb0c
	public Int32 get_chessLevel() { }
	// RVA: 0x3328ed4 VA: 0x7595940ed4
	private Void set_chessLevel(Int32 value) { }
	// RVA: 0x332496c VA: 0x759593c96c
	public Act1VAutoChessTrapChessType get_trapChessType() { }
	// RVA: 0x3328f50 VA: 0x7595940f50
	private Void set_trapChessType(Act1VAutoChessTrapChessType value) { }
	// RVA: 0x33249d4 VA: 0x759593c9d4
	public String get_trapItemName() { }
	// RVA: 0x3328fcc VA: 0x7595940fcc
	private Void set_trapItemName(String value) { }
	// RVA: 0x3324a3c VA: 0x759593ca3c
	public String get_trapItemDesc() { }
	// RVA: 0x3329050 VA: 0x7595941050
	private Void set_trapItemDesc(String value) { }
	// RVA: 0x33290d4 VA: 0x75959410d4
	public Void LoadData(Act1VAutoChessTrapShopChessData trapShopChessData, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x332922c VA: 0x759594122c
	public Int32 CompareTo(Act1VAutoChessChessShopTrapCardViewModel other) { }
	// RVA: 0x33292f4 VA: 0x75959412f4
	public Void .ctor() { }
}
```