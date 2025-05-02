# Act1VAutoChessEntryModeChoiceViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <selectedModeId>k__BackingField`

- `String <focusingModeId>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`


## Properties

- `String selectedModeId`

- `String focusingModeId`

- `Int32 enterSeqNum`


## Methods

- `Void set_itemViewModels(ListDict`2)`

- `String get_selectedModeId()`

- `Void set_selectedModeId(String)`

- `String get_focusingModeId()`

- `Void set_focusingModeId(String)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Void SetFocusingModeId(String, Boolean)`

- `Void NotifyEnter()`

- `Void _RefreshModeItems(Dictionary`2)`

- `Void _RefreshSelectedId()`

- `Void _RefreshTrackPoint()`

- `Void <>xLuaBaseProxy_LoadData(String, ActivityAutoChessVerify1Data)`

- `Void <>xLuaBaseProxy_RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryModeChoiceViewModel : Act1VAutoChessEntryBaseSubViewModel
{
	private ListDict`2 <itemViewModels>k__BackingField; // 0x28
	private String <selectedModeId>k__BackingField; // 0x30
	private String <focusingModeId>k__BackingField; // 0x38
	private Int32 <enterSeqNum>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_itemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_set_itemViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedModeId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedModeId; // 0x18
	private static DelegateBridge __Hotfix0_get_focusingModeId; // 0x20
	private static DelegateBridge __Hotfix0_set_focusingModeId; // 0x28
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x30
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x48
	private static DelegateBridge __Hotfix0_SetFocusingModeId; // 0x50
	private static DelegateBridge __Hotfix0_NotifyEnter; // 0x58
	private static DelegateBridge __Hotfix0__RefreshModeItems; // 0x60
	private static DelegateBridge __Hotfix0__RefreshSelectedId; // 0x68
	private static DelegateBridge __Hotfix0__RefreshTrackPoint; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public ListDict`2 itemViewModels { get; set; }
	public String selectedModeId { get; set; }
	public String focusingModeId { get; set; }
	public Int32 enterSeqNum { get; set; }

	// RVA: 0x3351464 VA: 0x7595969464
	public ListDict`2 get_itemViewModels() { }
	// RVA: 0x33514cc VA: 0x75959694cc
	private Void set_itemViewModels(ListDict`2 value) { }
	// RVA: 0x3351550 VA: 0x7595969550
	public String get_selectedModeId() { }
	// RVA: 0x33515b8 VA: 0x75959695b8
	private Void set_selectedModeId(String value) { }
	// RVA: 0x335163c VA: 0x759596963c
	public String get_focusingModeId() { }
	// RVA: 0x33516a4 VA: 0x75959696a4
	private Void set_focusingModeId(String value) { }
	// RVA: 0x3351728 VA: 0x7595969728
	public Int32 get_enterSeqNum() { }
	// RVA: 0x3351790 VA: 0x7595969790
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x335180c VA: 0x759596980c
	public override Void LoadData(String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x3351f64 VA: 0x7595969f64
	public override Void RefreshData() { }
	// RVA: 0x3352550 VA: 0x759596a550
	public Void SetFocusingModeId(String modeId, Boolean isFromItemClick) { }
	// RVA: 0x3352944 VA: 0x759596a944
	public Void NotifyEnter() { }
	// RVA: 0x335202c VA: 0x759596a02c
	private Void _RefreshModeItems(Dictionary`2 modeRecordMap) { }
	// RVA: 0x33522e0 VA: 0x759596a2e0
	private Void _RefreshSelectedId() { }
	// RVA: 0x3352380 VA: 0x759596a380
	private Void _RefreshTrackPoint() { }
	// RVA: 0x3352c6c VA: 0x759596ac6c
	public Void .ctor() { }
	// RVA: 0x3352cd8 VA: 0x759596acd8
	private Void <>xLuaBaseProxy_LoadData(String P0, ActivityAutoChessVerify1Data P1) { }
	// RVA: 0x3352cdc VA: 0x759596acdc
	private Void <>xLuaBaseProxy_RefreshData() { }
}
```