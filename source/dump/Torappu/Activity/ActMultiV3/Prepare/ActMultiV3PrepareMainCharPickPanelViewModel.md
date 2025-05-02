# ActMultiV3PrepareMainCharPickPanelViewModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `String <activityId>k__BackingField`

- `Boolean <reverse>k__BackingField`

- `Boolean <noNeedPick>k__BackingField`

- `Boolean <myTurn>k__BackingField`

- `Boolean <turnFromSkip>k__BackingField`

- `Boolean <canSkip>k__BackingField`

- `Int32 <pickCnt>k__BackingField`

- `Int32 <pickMax>k__BackingField`

- `Boolean <showReserveList>k__BackingField`


## Properties

- `String activityId`

- `Boolean reverse`

- `Boolean noNeedPick`

- `Boolean myTurn`

- `Boolean turnFromSkip`

- `Boolean canSkip`

- `Int32 pickCnt`

- `Int32 pickMax`

- `Boolean showReserveList`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Boolean get_reverse()`

- `Void set_reverse(Boolean)`

- `Void set_remainCharList(List`1)`

- `Void set_gotCharList(List`1)`

- `Boolean get_noNeedPick()`

- `Void set_noNeedPick(Boolean)`

- `Boolean get_myTurn()`

- `Void set_myTurn(Boolean)`

- `Boolean get_turnFromSkip()`

- `Void set_turnFromSkip(Boolean)`

- `Boolean get_canSkip()`

- `Void set_canSkip(Boolean)`

- `Int32 get_pickCnt()`

- `Void set_pickCnt(Int32)`

- `Int32 get_pickMax()`

- `Void set_pickMax(Int32)`

- `Boolean get_showReserveList()`

- `Void set_showReserveList(Boolean)`

- `Void LoadStableData(String)`

- `Void Update()`

- `Void Reset()`

- `Void _UpdateGotList(TeamInfo)`

- `ActMultiV3PrepareMainCharCardModel _FindOrLoadChar(String)`

- `Void _CacheAllDuplicateChar(STTurnPickStatus)`

- `ActMultiV3PrepareMainCharCardModel FindChar(Int32)`

- `Boolean SetReserveList(Boolean)`

- `Int32 _CompareChar(ActMultiV3PrepareMainCharCardModel, ActMultiV3PrepareMainCharCardModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharPickPanelViewModel : IHotfixable
{
	private String <activityId>k__BackingField; // 0x10
	private Boolean <reverse>k__BackingField; // 0x18
	private List`1 <remainCharList>k__BackingField; // 0x20
	private List`1 <gotCharList>k__BackingField; // 0x28
	private Boolean <noNeedPick>k__BackingField; // 0x30
	private Boolean <myTurn>k__BackingField; // 0x31
	private Boolean <turnFromSkip>k__BackingField; // 0x32
	private Boolean <canSkip>k__BackingField; // 0x33
	private Int32 <pickCnt>k__BackingField; // 0x34
	private Int32 <pickMax>k__BackingField; // 0x38
	private Boolean <showReserveList>k__BackingField; // 0x3c
	private Dictionary`2 m_allDumpChar; // 0x40
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_reverse; // 0x10
	private static DelegateBridge __Hotfix0_set_reverse; // 0x18
	private static DelegateBridge __Hotfix0_get_remainCharList; // 0x20
	private static DelegateBridge __Hotfix0_set_remainCharList; // 0x28
	private static DelegateBridge __Hotfix0_get_gotCharList; // 0x30
	private static DelegateBridge __Hotfix0_set_gotCharList; // 0x38
	private static DelegateBridge __Hotfix0_get_noNeedPick; // 0x40
	private static DelegateBridge __Hotfix0_set_noNeedPick; // 0x48
	private static DelegateBridge __Hotfix0_get_myTurn; // 0x50
	private static DelegateBridge __Hotfix0_set_myTurn; // 0x58
	private static DelegateBridge __Hotfix0_get_turnFromSkip; // 0x60
	private static DelegateBridge __Hotfix0_set_turnFromSkip; // 0x68
	private static DelegateBridge __Hotfix0_get_canSkip; // 0x70
	private static DelegateBridge __Hotfix0_set_canSkip; // 0x78
	private static DelegateBridge __Hotfix0_get_pickCnt; // 0x80
	private static DelegateBridge __Hotfix0_set_pickCnt; // 0x88
	private static DelegateBridge __Hotfix0_get_pickMax; // 0x90
	private static DelegateBridge __Hotfix0_set_pickMax; // 0x98
	private static DelegateBridge __Hotfix0_get_showReserveList; // 0xa0
	private static DelegateBridge __Hotfix0_set_showReserveList; // 0xa8
	private static DelegateBridge __Hotfix0_LoadStableData; // 0xb0
	private static DelegateBridge __Hotfix0_Update; // 0xb8
	private static DelegateBridge __Hotfix0_Reset; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateGotList; // 0xc8
	private static DelegateBridge __Hotfix0__FindOrLoadChar; // 0xd0
	private static DelegateBridge __Hotfix0__CacheAllDuplicateChar; // 0xd8
	private static DelegateBridge __Hotfix0_LoadCharCardViewModelFromPrefer; // 0xe0
	private static DelegateBridge __Hotfix0__FindCharFromSquadWithCharId; // 0xe8
	private static DelegateBridge __Hotfix0_FindChar; // 0xf0
	private static DelegateBridge __Hotfix0_SetReserveList; // 0xf8
	private static DelegateBridge __Hotfix0__CompareChar; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public String activityId { get; set; }
	public Boolean reverse { get; set; }
	public List`1 remainCharList { get; set; }
	public List`1 gotCharList { get; set; }
	public Boolean noNeedPick { get; set; }
	public Boolean myTurn { get; set; }
	public Boolean turnFromSkip { get; set; }
	public Boolean canSkip { get; set; }
	public Int32 pickCnt { get; set; }
	public Int32 pickMax { get; set; }
	public Boolean showReserveList { get; set; }

	// RVA: 0x3168270 VA: 0x7595780270
	public String get_activityId() { }
	// RVA: 0x31682d8 VA: 0x75957802d8
	private Void set_activityId(String value) { }
	// RVA: 0x316835c VA: 0x759578035c
	public Boolean get_reverse() { }
	// RVA: 0x31683c4 VA: 0x75957803c4
	private Void set_reverse(Boolean value) { }
	// RVA: 0x3168444 VA: 0x7595780444
	public List`1 get_remainCharList() { }
	// RVA: 0x31684ac VA: 0x75957804ac
	private Void set_remainCharList(List`1 value) { }
	// RVA: 0x3168530 VA: 0x7595780530
	public List`1 get_gotCharList() { }
	// RVA: 0x3168598 VA: 0x7595780598
	private Void set_gotCharList(List`1 value) { }
	// RVA: 0x3168150 VA: 0x7595780150
	public Boolean get_noNeedPick() { }
	// RVA: 0x316861c VA: 0x759578061c
	private Void set_noNeedPick(Boolean value) { }
	// RVA: 0x31681b8 VA: 0x75957801b8
	public Boolean get_myTurn() { }
	// RVA: 0x316869c VA: 0x759578069c
	private Void set_myTurn(Boolean value) { }
	// RVA: 0x316871c VA: 0x759578071c
	public Boolean get_turnFromSkip() { }
	// RVA: 0x3168784 VA: 0x7595780784
	private Void set_turnFromSkip(Boolean value) { }
	// RVA: 0x3168804 VA: 0x7595780804
	public Boolean get_canSkip() { }
	// RVA: 0x316886c VA: 0x759578086c
	private Void set_canSkip(Boolean value) { }
	// RVA: 0x31688ec VA: 0x75957808ec
	public Int32 get_pickCnt() { }
	// RVA: 0x3168954 VA: 0x7595780954
	private Void set_pickCnt(Int32 value) { }
	// RVA: 0x31689d0 VA: 0x75957809d0
	public Int32 get_pickMax() { }
	// RVA: 0x3168a38 VA: 0x7595780a38
	private Void set_pickMax(Int32 value) { }
	// RVA: 0x3168ab4 VA: 0x7595780ab4
	public Boolean get_showReserveList() { }
	// RVA: 0x3168b1c VA: 0x7595780b1c
	private Void set_showReserveList(Boolean value) { }
	// RVA: 0x31673d8 VA: 0x759577f3d8
	public Void LoadStableData(String actId) { }
	// RVA: 0x3166c5c VA: 0x759577ec5c
	public Void Update() { }
	// RVA: 0x316722c VA: 0x759577f22c
	public Void Reset() { }
	// RVA: 0x3168f40 VA: 0x7595780f40
	private Void _UpdateGotList(TeamInfo teaminfo) { }
	// RVA: 0x3168d88 VA: 0x7595780d88
	private ActMultiV3PrepareMainCharCardModel _FindOrLoadChar(String charId) { }
	// RVA: 0x3168b9c VA: 0x7595780b9c
	private Void _CacheAllDuplicateChar(STTurnPickStatus turnPick) { }
	// RVA: 0x31693b4 VA: 0x75957813b4
	public static ActMultiV3PrepareMainCharCardModel LoadCharCardViewModelFromPrefer(String charId) { }
	// RVA: 0x31694ec VA: 0x75957814ec
	private static STBasicChar _FindCharFromSquadWithCharId(List`1 squad, String charId) { }
	// RVA: 0x31678b4 VA: 0x759577f8b4
	public ActMultiV3PrepareMainCharCardModel FindChar(Int32 instId) { }
	// RVA: 0x3167cd0 VA: 0x759577fcd0
	public Boolean SetReserveList(Boolean v) { }
	// RVA: 0x3169630 VA: 0x7595781630
	private Int32 _CompareChar(ActMultiV3PrepareMainCharCardModel a, ActMultiV3PrepareMainCharCardModel b) { }
	// RVA: 0x3169784 VA: 0x7595781784
	public Void .ctor() { }
}
```