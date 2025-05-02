# Act1VAutoChessChessShopMenuLevelItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <shopLevel>k__BackingField`

- `Boolean <showDiyCharInfo>k__BackingField`

- `Int32 <levelCurDiyCharCnt>k__BackingField`

- `Act1VAutoChessShopStatus <shopStatus>k__BackingField`

- `Boolean <isSelected>k__BackingField`

- `Int32 <index>k__BackingField`

- `String m_actId`

- `Boolean m_isLevelCharChessEmpty`

- `Boolean m_isLevelTrapChessEmpty`

- `Int32 m_levelCanDiyCharCnt`


## Properties

- `Int32 shopLevel`

- `Boolean showDiyCharInfo`

- `Int32 levelCurDiyCharCnt`

- `Act1VAutoChessShopStatus shopStatus`

- `Boolean isSelected`

- `Int32 index`


## Methods

- `Int32 get_shopLevel()`

- `Void set_shopLevel(Int32)`

- `Boolean get_showDiyCharInfo()`

- `Void set_showDiyCharInfo(Boolean)`

- `Int32 get_levelCurDiyCharCnt()`

- `Void set_levelCurDiyCharCnt(Int32)`

- `Act1VAutoChessShopStatus get_shopStatus()`

- `Void set_shopStatus(Act1VAutoChessShopStatus)`

- `Boolean get_isSelected()`

- `Void set_isSelected(Boolean)`

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Void LoadData(String, Act1VAutoChessShopLevelDisplayData, ListDict`2, Act1VAutoChessShopStatus, Int32)`

- `Void RefreshShopStatus(Act1VAutoChessShopStatus)`

- `Void RefreshLevelCurDiyCharCnt(Int32)`

- `Void RefreshSelectState(Boolean)`

- `Boolean IsMenuItemHasLevelInfo()`

- `Boolean CheckChessPoolChessShopLevelCharsHasNew()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopMenuLevelItemViewModel : IHotfixable
{
	private Int32 <shopLevel>k__BackingField; // 0x10
	private Boolean <showDiyCharInfo>k__BackingField; // 0x14
	private Int32 <levelCurDiyCharCnt>k__BackingField; // 0x18
	private Act1VAutoChessShopStatus <shopStatus>k__BackingField; // 0x1c
	private Boolean <isSelected>k__BackingField; // 0x20
	private Int32 <index>k__BackingField; // 0x24
	private String m_actId; // 0x28
	private Boolean m_isLevelCharChessEmpty; // 0x30
	private Boolean m_isLevelTrapChessEmpty; // 0x31
	private Int32 m_levelCanDiyCharCnt; // 0x34
	private ListDict`2 m_charChessDataListDict; // 0x38
	private static DelegateBridge __Hotfix0_get_shopLevel; // 0x0
	private static DelegateBridge __Hotfix0_set_shopLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_showDiyCharInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_showDiyCharInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_levelCurDiyCharCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_levelCurDiyCharCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_shopStatus; // 0x30
	private static DelegateBridge __Hotfix0_set_shopStatus; // 0x38
	private static DelegateBridge __Hotfix0_get_isSelected; // 0x40
	private static DelegateBridge __Hotfix0_set_isSelected; // 0x48
	private static DelegateBridge __Hotfix0_get_index; // 0x50
	private static DelegateBridge __Hotfix0_set_index; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_RefreshShopStatus; // 0x68
	private static DelegateBridge __Hotfix0_RefreshLevelCurDiyCharCnt; // 0x70
	private static DelegateBridge __Hotfix0_RefreshSelectState; // 0x78
	private static DelegateBridge __Hotfix0_IsMenuItemHasLevelInfo; // 0x80
	private static DelegateBridge __Hotfix0_CheckChessPoolChessShopLevelCharsHasNew; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Int32 shopLevel { get; set; }
	public Boolean showDiyCharInfo { get; set; }
	public Int32 levelCurDiyCharCnt { get; set; }
	public Act1VAutoChessShopStatus shopStatus { get; set; }
	public Boolean isSelected { get; set; }
	public Int32 index { get; set; }

	// RVA: 0x332aa10 VA: 0x7595942a10
	public Int32 get_shopLevel() { }
	// RVA: 0x332aa78 VA: 0x7595942a78
	private Void set_shopLevel(Int32 value) { }
	// RVA: 0x332aaf4 VA: 0x7595942af4
	public Boolean get_showDiyCharInfo() { }
	// RVA: 0x332ab5c VA: 0x7595942b5c
	private Void set_showDiyCharInfo(Boolean value) { }
	// RVA: 0x332abdc VA: 0x7595942bdc
	public Int32 get_levelCurDiyCharCnt() { }
	// RVA: 0x332ac44 VA: 0x7595942c44
	private Void set_levelCurDiyCharCnt(Int32 value) { }
	// RVA: 0x332acc0 VA: 0x7595942cc0
	public Act1VAutoChessShopStatus get_shopStatus() { }
	// RVA: 0x332ad28 VA: 0x7595942d28
	private Void set_shopStatus(Act1VAutoChessShopStatus value) { }
	// RVA: 0x332ada4 VA: 0x7595942da4
	public Boolean get_isSelected() { }
	// RVA: 0x332ae0c VA: 0x7595942e0c
	private Void set_isSelected(Boolean value) { }
	// RVA: 0x332ae8c VA: 0x7595942e8c
	public Int32 get_index() { }
	// RVA: 0x332aef4 VA: 0x7595942ef4
	private Void set_index(Int32 value) { }
	// RVA: 0x332af70 VA: 0x7595942f70
	public Void LoadData(String activityId, Act1VAutoChessShopLevelDisplayData shopLevelData, ListDict`2 charChessDataListDict, Act1VAutoChessShopStatus status, Int32 viewIndex) { }
	// RVA: 0x332b0d4 VA: 0x75959430d4
	public Void RefreshShopStatus(Act1VAutoChessShopStatus status) { }
	// RVA: 0x332b1b8 VA: 0x75959431b8
	public Void RefreshLevelCurDiyCharCnt(Int32 curDiyCnt) { }
	// RVA: 0x332b238 VA: 0x7595943238
	public Void RefreshSelectState(Boolean isSelect) { }
	// RVA: 0x332b2b8 VA: 0x75959432b8
	public Boolean IsMenuItemHasLevelInfo() { }
	// RVA: 0x332b35c VA: 0x759594335c
	public Boolean CheckChessPoolChessShopLevelCharsHasNew() { }
	// RVA: 0x332b49c VA: 0x759594349c
	public Void .ctor() { }
}
```