# Act1VAutoChessShopLevelTagViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <level>k__BackingField`

- `Act1VAutoChessShopStatus <shopStatus>k__BackingField`

- `Color <levelTagBgColor>k__BackingField`


## Properties

- `Int32 level`

- `Act1VAutoChessShopStatus shopStatus`

- `Color levelTagBgColor`


## Methods

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Act1VAutoChessShopStatus get_shopStatus()`

- `Void set_shopStatus(Act1VAutoChessShopStatus)`

- `Color get_levelTagBgColor()`

- `Void set_levelTagBgColor(Color)`

- `Void LoadData(Int32, Act1VAutoChessShopStatus, String)`

- `Void RefreshByShopStatusChanged(Act1VAutoChessShopStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessShopLevelTagViewModel : IHotfixable
{
	private Int32 <level>k__BackingField; // 0x10
	private Act1VAutoChessShopStatus <shopStatus>k__BackingField; // 0x14
	private Color <levelTagBgColor>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_level; // 0x0
	private static DelegateBridge __Hotfix0_set_level; // 0x8
	private static DelegateBridge __Hotfix0_get_shopStatus; // 0x10
	private static DelegateBridge __Hotfix0_set_shopStatus; // 0x18
	private static DelegateBridge __Hotfix0_get_levelTagBgColor; // 0x20
	private static DelegateBridge __Hotfix0_set_levelTagBgColor; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshByShopStatusChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 level { get; set; }
	public Act1VAutoChessShopStatus shopStatus { get; set; }
	public Color levelTagBgColor { get; set; }

	// RVA: 0x3328a78 VA: 0x7595940a78
	public Int32 get_level() { }
	// RVA: 0x3328ae0 VA: 0x7595940ae0
	private Void set_level(Int32 value) { }
	// RVA: 0x3328b5c VA: 0x7595940b5c
	public Act1VAutoChessShopStatus get_shopStatus() { }
	// RVA: 0x3328bc4 VA: 0x7595940bc4
	private Void set_shopStatus(Act1VAutoChessShopStatus value) { }
	// RVA: 0x3328c40 VA: 0x7595940c40
	public Color get_levelTagBgColor() { }
	// RVA: 0x3328ca8 VA: 0x7595940ca8
	private Void set_levelTagBgColor(Color value) { }
	// RVA: 0x332839c VA: 0x759594039c
	public Void LoadData(Int32 shopLevel, Act1VAutoChessShopStatus status, String levelColStr) { }
	// RVA: 0x3328d4c VA: 0x7595940d4c
	public Void RefreshByShopStatusChanged(Act1VAutoChessShopStatus status) { }
	// RVA: 0x332832c VA: 0x759594032c
	public Void .ctor() { }
}
```