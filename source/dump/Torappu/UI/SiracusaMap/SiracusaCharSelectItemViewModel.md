# SiracusaCharSelectItemViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String <charCardId>k__BackingField`

- `Int32 <sortIndex>k__BackingField`

- `String <charCardIconName>k__BackingField`

- `Color <charThemeColor>k__BackingField`

- `CharCardData <charCardData>k__BackingField`

- `Boolean <isAllRewardClear>k__BackingField`

- `CharCardStatus <charCardState>k__BackingField`

- `Int32 <taskRingCompleteCount>k__BackingField`

- `Int32 <taskRingTotalCount>k__BackingField`

- `Boolean <isSelecting>k__BackingField`


## Properties

- `String charCardId`

- `Int32 sortIndex`

- `String charCardIconName`

- `Color charThemeColor`

- `CharCardData charCardData`

- `Boolean isAllRewardClear`

- `CharCardStatus charCardState`

- `Int32 taskRingCompleteCount`

- `Int32 taskRingTotalCount`

- `Boolean isSelecting`


## Methods

- `String get_charCardId()`

- `Void set_charCardId(String)`

- `Int32 get_sortIndex()`

- `Void set_sortIndex(Int32)`

- `String get_charCardIconName()`

- `Void set_charCardIconName(String)`

- `Color get_charThemeColor()`

- `Void set_charThemeColor(Color)`

- `CharCardData get_charCardData()`

- `Void set_charCardData(CharCardData)`

- `Boolean get_isAllRewardClear()`

- `Void set_isAllRewardClear(Boolean)`

- `CharCardStatus get_charCardState()`

- `Void set_charCardState(CharCardStatus)`

- `Int32 get_taskRingCompleteCount()`

- `Void set_taskRingCompleteCount(Int32)`

- `Int32 get_taskRingTotalCount()`

- `Void set_taskRingTotalCount(Int32)`

- `Boolean get_isSelecting()`

- `Void set_isSelecting(Boolean)`

- `Void LoadData(CharCardData, Dictionary`2, Boolean)`

- `Void _InitRewardList(CharCardData, Dictionary`2, Boolean)`

- `Void UpdateData(PlayerSiracusaMap)`

- `Void _UpdateRewardGetState(CharCard, List`1)`

- `Boolean _GetAllRewardClearState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectItemViewModel : IHotfixable
{
	private String <charCardId>k__BackingField; // 0x10
	private Int32 <sortIndex>k__BackingField; // 0x18
	private String <charCardIconName>k__BackingField; // 0x20
	private Color <charThemeColor>k__BackingField; // 0x28
	private CharCardData <charCardData>k__BackingField; // 0x38
	public List`1 specialTaskRingRewards; // 0x40
	public List`1 normalTaskRingRewards; // 0x48
	private Boolean <isAllRewardClear>k__BackingField; // 0x50
	private CharCardStatus <charCardState>k__BackingField; // 0x54
	private Int32 <taskRingCompleteCount>k__BackingField; // 0x58
	private Int32 <taskRingTotalCount>k__BackingField; // 0x5c
	private Boolean <isSelecting>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_charCardId; // 0x0
	private static DelegateBridge __Hotfix0_set_charCardId; // 0x8
	private static DelegateBridge __Hotfix0_get_sortIndex; // 0x10
	private static DelegateBridge __Hotfix0_set_sortIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_charCardIconName; // 0x20
	private static DelegateBridge __Hotfix0_set_charCardIconName; // 0x28
	private static DelegateBridge __Hotfix0_get_charThemeColor; // 0x30
	private static DelegateBridge __Hotfix0_set_charThemeColor; // 0x38
	private static DelegateBridge __Hotfix0_get_charCardData; // 0x40
	private static DelegateBridge __Hotfix0_set_charCardData; // 0x48
	private static DelegateBridge __Hotfix0_get_isAllRewardClear; // 0x50
	private static DelegateBridge __Hotfix0_set_isAllRewardClear; // 0x58
	private static DelegateBridge __Hotfix0_get_charCardState; // 0x60
	private static DelegateBridge __Hotfix0_set_charCardState; // 0x68
	private static DelegateBridge __Hotfix0_get_taskRingCompleteCount; // 0x70
	private static DelegateBridge __Hotfix0_set_taskRingCompleteCount; // 0x78
	private static DelegateBridge __Hotfix0_get_taskRingTotalCount; // 0x80
	private static DelegateBridge __Hotfix0_set_taskRingTotalCount; // 0x88
	private static DelegateBridge __Hotfix0_get_isSelecting; // 0x90
	private static DelegateBridge __Hotfix0_set_isSelecting; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0__InitRewardList; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateData; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateRewardGetState; // 0xb8
	private static DelegateBridge __Hotfix0__GetAllRewardClearState; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public String charCardId { get; set; }
	public Int32 sortIndex { get; set; }
	public String charCardIconName { get; set; }
	public Color charThemeColor { get; set; }
	public CharCardData charCardData { get; set; }
	public Boolean isAllRewardClear { get; set; }
	public CharCardStatus charCardState { get; set; }
	public Int32 taskRingCompleteCount { get; set; }
	public Int32 taskRingTotalCount { get; set; }
	public Boolean isSelecting { get; set; }

	// RVA: 0x23ee200 VA: 0x7594a06200
	public String get_charCardId() { }
	// RVA: 0x23f4090 VA: 0x7594a0c090
	private Void set_charCardId(String value) { }
	// RVA: 0x23f3ea8 VA: 0x7594a0bea8
	public Int32 get_sortIndex() { }
	// RVA: 0x23f4114 VA: 0x7594a0c114
	private Void set_sortIndex(Int32 value) { }
	// RVA: 0x23ee2d0 VA: 0x7594a062d0
	public String get_charCardIconName() { }
	// RVA: 0x23f4190 VA: 0x7594a0c190
	private Void set_charCardIconName(String value) { }
	// RVA: 0x23f1e34 VA: 0x7594a09e34
	public Color get_charThemeColor() { }
	// RVA: 0x23f4214 VA: 0x7594a0c214
	private Void set_charThemeColor(Color value) { }
	// RVA: 0x23f1e9c VA: 0x7594a09e9c
	public CharCardData get_charCardData() { }
	// RVA: 0x23f42b8 VA: 0x7594a0c2b8
	private Void set_charCardData(CharCardData value) { }
	// RVA: 0x23f2168 VA: 0x7594a0a168
	public Boolean get_isAllRewardClear() { }
	// RVA: 0x23f433c VA: 0x7594a0c33c
	private Void set_isAllRewardClear(Boolean value) { }
	// RVA: 0x23ee268 VA: 0x7594a06268
	public CharCardStatus get_charCardState() { }
	// RVA: 0x23f43bc VA: 0x7594a0c3bc
	private Void set_charCardState(CharCardStatus value) { }
	// RVA: 0x23ee338 VA: 0x7594a06338
	public Int32 get_taskRingCompleteCount() { }
	// RVA: 0x23f4438 VA: 0x7594a0c438
	private Void set_taskRingCompleteCount(Int32 value) { }
	// RVA: 0x23ee3a0 VA: 0x7594a063a0
	public Int32 get_taskRingTotalCount() { }
	// RVA: 0x23f44b4 VA: 0x7594a0c4b4
	private Void set_taskRingTotalCount(Int32 value) { }
	// RVA: 0x23ee408 VA: 0x7594a06408
	public Boolean get_isSelecting() { }
	// RVA: 0x23f4530 VA: 0x7594a0c530
	private Void set_isSelecting(Boolean value) { }
	// RVA: 0x23f3828 VA: 0x7594a0b828
	public Void LoadData(CharCardData cardData, Dictionary`2 taskRingDataMaps, Boolean isRetro) { }
	// RVA: 0x23f45b0 VA: 0x7594a0c5b0
	private Void _InitRewardList(CharCardData cardData, Dictionary`2 taskRingDataMaps, Boolean isRetro) { }
	// RVA: 0x23f3af8 VA: 0x7594a0baf8
	public Void UpdateData(PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x23f4838 VA: 0x7594a0c838
	private Void _UpdateRewardGetState(CharCard charCard, List`1 rewards) { }
	// RVA: 0x23f49b0 VA: 0x7594a0c9b0
	private Boolean _GetAllRewardClearState() { }
	// RVA: 0x23f37b8 VA: 0x7594a0b7b8
	public Void .ctor() { }
}
```