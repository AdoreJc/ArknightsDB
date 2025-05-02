# Act1VAutoChessShopCharChessDiyCardViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <firstDiyChessId>k__BackingField`

- `Int32 <chessShopLv>k__BackingField`

- `Int32 <curDiyCount>k__BackingField`

- `Int32 <maxDiyCount>k__BackingField`

- `Boolean <canShow>k__BackingField`


## Properties

- `String firstDiyChessId`

- `Int32 chessShopLv`

- `Int32 curDiyCount`

- `Int32 maxDiyCount`

- `Boolean canShow`


## Methods

- `String get_firstDiyChessId()`

- `Void set_firstDiyChessId(String)`

- `Int32 get_chessShopLv()`

- `Void set_chessShopLv(Int32)`

- `Int32 get_curDiyCount()`

- `Void set_curDiyCount(Int32)`

- `Int32 get_maxDiyCount()`

- `Void set_maxDiyCount(Int32)`

- `Boolean get_canShow()`

- `Void set_canShow(Boolean)`

- `Void LoadData(String, Int32, Int32)`

- `Void RefreshInfos(Int32, Act1VAutoChessShopStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessShopCharChessDiyCardViewModel : IHotfixable
{
	private String <firstDiyChessId>k__BackingField; // 0x10
	private Int32 <chessShopLv>k__BackingField; // 0x18
	private Int32 <curDiyCount>k__BackingField; // 0x1c
	private Int32 <maxDiyCount>k__BackingField; // 0x20
	private Boolean <canShow>k__BackingField; // 0x24
	private static DelegateBridge __Hotfix0_get_firstDiyChessId; // 0x0
	private static DelegateBridge __Hotfix0_set_firstDiyChessId; // 0x8
	private static DelegateBridge __Hotfix0_get_chessShopLv; // 0x10
	private static DelegateBridge __Hotfix0_set_chessShopLv; // 0x18
	private static DelegateBridge __Hotfix0_get_curDiyCount; // 0x20
	private static DelegateBridge __Hotfix0_set_curDiyCount; // 0x28
	private static DelegateBridge __Hotfix0_get_maxDiyCount; // 0x30
	private static DelegateBridge __Hotfix0_set_maxDiyCount; // 0x38
	private static DelegateBridge __Hotfix0_get_canShow; // 0x40
	private static DelegateBridge __Hotfix0_set_canShow; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_RefreshInfos; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String firstDiyChessId { get; set; }
	public Int32 chessShopLv { get; set; }
	public Int32 curDiyCount { get; set; }
	public Int32 maxDiyCount { get; set; }
	public Boolean canShow { get; set; }

	// RVA: 0x331d7f8 VA: 0x75959357f8
	public String get_firstDiyChessId() { }
	// RVA: 0x3329364 VA: 0x7595941364
	private Void set_firstDiyChessId(String value) { }
	// RVA: 0x33293e8 VA: 0x75959413e8
	public Int32 get_chessShopLv() { }
	// RVA: 0x3329450 VA: 0x7595941450
	private Void set_chessShopLv(Int32 value) { }
	// RVA: 0x331d860 VA: 0x7595935860
	public Int32 get_curDiyCount() { }
	// RVA: 0x33294cc VA: 0x75959414cc
	private Void set_curDiyCount(Int32 value) { }
	// RVA: 0x331d8c8 VA: 0x75959358c8
	public Int32 get_maxDiyCount() { }
	// RVA: 0x3329548 VA: 0x7595941548
	private Void set_maxDiyCount(Int32 value) { }
	// RVA: 0x33295c4 VA: 0x75959415c4
	public Boolean get_canShow() { }
	// RVA: 0x332962c VA: 0x759594162c
	private Void set_canShow(Boolean value) { }
	// RVA: 0x33296ac VA: 0x75959416ac
	public Void LoadData(String baseChessId, Int32 shopLv, Int32 maxDiyCnt) { }
	// RVA: 0x332976c VA: 0x759594176c
	public Void RefreshInfos(Int32 curDiyCnt, Act1VAutoChessShopStatus shopStatus) { }
	// RVA: 0x3329844 VA: 0x7595941844
	public Void .ctor() { }
}
```