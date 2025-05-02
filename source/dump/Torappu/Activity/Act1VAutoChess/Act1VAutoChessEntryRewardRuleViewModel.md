# Act1VAutoChessEntryRewardRuleViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <basicRewardDesc>k__BackingField`

- `String <extraRewardDesc>k__BackingField`

- `String <extraRewardNum0>k__BackingField`

- `String <extraRewardNum1>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Int32 <jumpSeqNum>k__BackingField`

- `Single <showJumpThreshold>k__BackingField`


## Properties

- `String basicRewardDesc`

- `String extraRewardDesc`

- `String extraRewardNum0`

- `String extraRewardNum1`

- `Int32 enterSeqNum`

- `Int32 jumpSeqNum`

- `Single showJumpThreshold`


## Methods

- `Void set_itemViewModels(List`1)`

- `Void set_listTitles(List`1)`

- `String get_basicRewardDesc()`

- `Void set_basicRewardDesc(String)`

- `String get_extraRewardDesc()`

- `Void set_extraRewardDesc(String)`

- `String get_extraRewardNum0()`

- `Void set_extraRewardNum0(String)`

- `String get_extraRewardNum1()`

- `Void set_extraRewardNum1(String)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Int32 get_jumpSeqNum()`

- `Void set_jumpSeqNum(Int32)`

- `Single get_showJumpThreshold()`

- `Void set_showJumpThreshold(Single)`

- `Void LoadData(String, String[])`

- `Void NotifyJump()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryRewardRuleViewModel : IHotfixable
{
	private List`1 <itemViewModels>k__BackingField; // 0x10
	private List`1 <listTitles>k__BackingField; // 0x18
	private String <basicRewardDesc>k__BackingField; // 0x20
	private String <extraRewardDesc>k__BackingField; // 0x28
	private String <extraRewardNum0>k__BackingField; // 0x30
	private String <extraRewardNum1>k__BackingField; // 0x38
	private Int32 <enterSeqNum>k__BackingField; // 0x40
	private Int32 <jumpSeqNum>k__BackingField; // 0x44
	private Single <showJumpThreshold>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_itemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_set_itemViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_listTitles; // 0x10
	private static DelegateBridge __Hotfix0_set_listTitles; // 0x18
	private static DelegateBridge __Hotfix0_get_basicRewardDesc; // 0x20
	private static DelegateBridge __Hotfix0_set_basicRewardDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_extraRewardDesc; // 0x30
	private static DelegateBridge __Hotfix0_set_extraRewardDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_extraRewardNum0; // 0x40
	private static DelegateBridge __Hotfix0_set_extraRewardNum0; // 0x48
	private static DelegateBridge __Hotfix0_get_extraRewardNum1; // 0x50
	private static DelegateBridge __Hotfix0_set_extraRewardNum1; // 0x58
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x60
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x68
	private static DelegateBridge __Hotfix0_get_jumpSeqNum; // 0x70
	private static DelegateBridge __Hotfix0_set_jumpSeqNum; // 0x78
	private static DelegateBridge __Hotfix0_get_showJumpThreshold; // 0x80
	private static DelegateBridge __Hotfix0_set_showJumpThreshold; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_NotifyJump; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public List`1 itemViewModels { get; set; }
	public List`1 listTitles { get; set; }
	public String basicRewardDesc { get; set; }
	public String extraRewardDesc { get; set; }
	public String extraRewardNum0 { get; set; }
	public String extraRewardNum1 { get; set; }
	public Int32 enterSeqNum { get; set; }
	public Int32 jumpSeqNum { get; set; }
	public Single showJumpThreshold { get; set; }

	// RVA: 0x3342f70 VA: 0x759595af70
	public List`1 get_itemViewModels() { }
	// RVA: 0x3343330 VA: 0x759595b330
	private Void set_itemViewModels(List`1 value) { }
	// RVA: 0x3342fd8 VA: 0x759595afd8
	public List`1 get_listTitles() { }
	// RVA: 0x33433b4 VA: 0x759595b3b4
	private Void set_listTitles(List`1 value) { }
	// RVA: 0x3342dd0 VA: 0x759595add0
	public String get_basicRewardDesc() { }
	// RVA: 0x3343438 VA: 0x759595b438
	private Void set_basicRewardDesc(String value) { }
	// RVA: 0x3342e38 VA: 0x759595ae38
	public String get_extraRewardDesc() { }
	// RVA: 0x33434bc VA: 0x759595b4bc
	private Void set_extraRewardDesc(String value) { }
	// RVA: 0x3342ea0 VA: 0x759595aea0
	public String get_extraRewardNum0() { }
	// RVA: 0x3343540 VA: 0x759595b540
	private Void set_extraRewardNum0(String value) { }
	// RVA: 0x3342f08 VA: 0x759595af08
	public String get_extraRewardNum1() { }
	// RVA: 0x33435c4 VA: 0x759595b5c4
	private Void set_extraRewardNum1(String value) { }
	// RVA: 0x3342d68 VA: 0x759595ad68
	public Int32 get_enterSeqNum() { }
	// RVA: 0x3343648 VA: 0x759595b648
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x3342aa4 VA: 0x759595aaa4
	public Int32 get_jumpSeqNum() { }
	// RVA: 0x33436c4 VA: 0x759595b6c4
	private Void set_jumpSeqNum(Int32 value) { }
	// RVA: 0x3343740 VA: 0x759595b740
	public Single get_showJumpThreshold() { }
	// RVA: 0x33437a8 VA: 0x759595b7a8
	private Void set_showJumpThreshold(Single value) { }
	// RVA: 0x3341cf4 VA: 0x7595959cf4
	public Void LoadData(String actId, String[] displayModeIdOrder) { }
	// RVA: 0x3341728 VA: 0x7595959728
	public Void NotifyJump() { }
	// RVA: 0x3341c84 VA: 0x7595959c84
	public Void .ctor() { }
}
```