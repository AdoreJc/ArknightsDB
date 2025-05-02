# Act1VAutoChessEntryModeChoiceItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <modeId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <modeName>k__BackingField`

- `String <modeDesc>k__BackingField`

- `String <modeUnlockDesc>k__BackingField`

- `Boolean <isUnlocked>k__BackingField`

- `Boolean <isFocusing>k__BackingField`

- `Boolean <needShowAlreadySelect>k__BackingField`

- `Boolean <modeFinish>k__BackingField`

- `Int32 <modeEffectDescListSeqNum>k__BackingField`

- `Boolean <showTrackPoint>k__BackingField`

- `String <actId>k__BackingField`


## Properties

- `String modeId`

- `Int32 sortId`

- `String modeName`

- `String modeDesc`

- `String modeUnlockDesc`

- `Boolean isUnlocked`

- `Boolean isFocusing`

- `Boolean needShowAlreadySelect`

- `Boolean modeFinish`

- `Int32 modeEffectDescListSeqNum`

- `Boolean showTrackPoint`

- `String actId`


## Methods

- `String get_modeId()`

- `Void set_modeId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_modeName()`

- `Void set_modeName(String)`

- `String get_modeDesc()`

- `Void set_modeDesc(String)`

- `String get_modeUnlockDesc()`

- `Void set_modeUnlockDesc(String)`

- `Void set_modeEffectDescItemViewModels(List`1)`

- `Boolean get_isUnlocked()`

- `Void set_isUnlocked(Boolean)`

- `Boolean get_isFocusing()`

- `Void set_isFocusing(Boolean)`

- `Boolean get_needShowAlreadySelect()`

- `Void set_needShowAlreadySelect(Boolean)`

- `Boolean get_modeFinish()`

- `Void set_modeFinish(Boolean)`

- `Int32 get_modeEffectDescListSeqNum()`

- `Void set_modeEffectDescListSeqNum(Int32)`

- `Boolean get_showTrackPoint()`

- `Void set_showTrackPoint(Boolean)`

- `String get_actId()`

- `Void set_actId(String)`

- `Void LoadData(String, Act1VAutoChessModeData, Dictionary`2)`

- `Void RefreshData(Dictionary`2)`

- `Void NotifyModeEffectDescListUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryModeChoiceItemViewModel : IHotfixable
{
	private String <modeId>k__BackingField; // 0x10
	private Int32 <sortId>k__BackingField; // 0x18
	private String <modeName>k__BackingField; // 0x20
	private String <modeDesc>k__BackingField; // 0x28
	private String <modeUnlockDesc>k__BackingField; // 0x30
	private List`1 <modeEffectDescItemViewModels>k__BackingField; // 0x38
	private Boolean <isUnlocked>k__BackingField; // 0x40
	private Boolean <isFocusing>k__BackingField; // 0x41
	private Boolean <needShowAlreadySelect>k__BackingField; // 0x42
	private Boolean <modeFinish>k__BackingField; // 0x43
	private Int32 <modeEffectDescListSeqNum>k__BackingField; // 0x44
	private Boolean <showTrackPoint>k__BackingField; // 0x48
	private String <actId>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_modeId; // 0x0
	private static DelegateBridge __Hotfix0_set_modeId; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_set_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_modeName; // 0x20
	private static DelegateBridge __Hotfix0_set_modeName; // 0x28
	private static DelegateBridge __Hotfix0_get_modeDesc; // 0x30
	private static DelegateBridge __Hotfix0_set_modeDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_modeUnlockDesc; // 0x40
	private static DelegateBridge __Hotfix0_set_modeUnlockDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_modeEffectDescItemViewModels; // 0x50
	private static DelegateBridge __Hotfix0_set_modeEffectDescItemViewModels; // 0x58
	private static DelegateBridge __Hotfix0_get_isUnlocked; // 0x60
	private static DelegateBridge __Hotfix0_set_isUnlocked; // 0x68
	private static DelegateBridge __Hotfix0_get_isFocusing; // 0x70
	private static DelegateBridge __Hotfix0_set_isFocusing; // 0x78
	private static DelegateBridge __Hotfix0_get_needShowAlreadySelect; // 0x80
	private static DelegateBridge __Hotfix0_set_needShowAlreadySelect; // 0x88
	private static DelegateBridge __Hotfix0_get_modeFinish; // 0x90
	private static DelegateBridge __Hotfix0_set_modeFinish; // 0x98
	private static DelegateBridge __Hotfix0_get_modeEffectDescListSeqNum; // 0xa0
	private static DelegateBridge __Hotfix0_set_modeEffectDescListSeqNum; // 0xa8
	private static DelegateBridge __Hotfix0_get_showTrackPoint; // 0xb0
	private static DelegateBridge __Hotfix0_set_showTrackPoint; // 0xb8
	private static DelegateBridge __Hotfix0_get_actId; // 0xc0
	private static DelegateBridge __Hotfix0_set_actId; // 0xc8
	private static DelegateBridge __Hotfix0_LoadData; // 0xd0
	private static DelegateBridge __Hotfix0_RefreshData; // 0xd8
	private static DelegateBridge __Hotfix0_NotifyModeEffectDescListUpdate; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public String modeId { get; set; }
	public Int32 sortId { get; set; }
	public String modeName { get; set; }
	public String modeDesc { get; set; }
	public String modeUnlockDesc { get; set; }
	public List`1 modeEffectDescItemViewModels { get; set; }
	public Boolean isUnlocked { get; set; }
	public Boolean isFocusing { get; set; }
	public Boolean needShowAlreadySelect { get; set; }
	public Boolean modeFinish { get; set; }
	public Int32 modeEffectDescListSeqNum { get; set; }
	public Boolean showTrackPoint { get; set; }
	public String actId { get; set; }

	// RVA: 0x33527dc VA: 0x759596a7dc
	public String get_modeId() { }
	// RVA: 0x3352e20 VA: 0x759596ae20
	private Void set_modeId(String value) { }
	// RVA: 0x3352db8 VA: 0x759596adb8
	public Int32 get_sortId() { }
	// RVA: 0x3352ea4 VA: 0x759596aea4
	private Void set_sortId(Int32 value) { }
	// RVA: 0x3352f20 VA: 0x759596af20
	public String get_modeName() { }
	// RVA: 0x3352f88 VA: 0x759596af88
	private Void set_modeName(String value) { }
	// RVA: 0x335300c VA: 0x759596b00c
	public String get_modeDesc() { }
	// RVA: 0x3353074 VA: 0x759596b074
	private Void set_modeDesc(String value) { }
	// RVA: 0x33530f8 VA: 0x759596b0f8
	public String get_modeUnlockDesc() { }
	// RVA: 0x3353160 VA: 0x759596b160
	private Void set_modeUnlockDesc(String value) { }
	// RVA: 0x33531e4 VA: 0x759596b1e4
	public List`1 get_modeEffectDescItemViewModels() { }
	// RVA: 0x335324c VA: 0x759596b24c
	private Void set_modeEffectDescItemViewModels(List`1 value) { }
	// RVA: 0x3352774 VA: 0x759596a774
	public Boolean get_isUnlocked() { }
	// RVA: 0x33532d0 VA: 0x759596b2d0
	private Void set_isUnlocked(Boolean value) { }
	// RVA: 0x3353350 VA: 0x759596b350
	public Boolean get_isFocusing() { }
	// RVA: 0x3352844 VA: 0x759596a844
	public Void set_isFocusing(Boolean value) { }
	// RVA: 0x33533b8 VA: 0x759596b3b8
	public Boolean get_needShowAlreadySelect() { }
	// RVA: 0x33528c4 VA: 0x759596a8c4
	public Void set_needShowAlreadySelect(Boolean value) { }
	// RVA: 0x3353420 VA: 0x759596b420
	public Boolean get_modeFinish() { }
	// RVA: 0x3353488 VA: 0x759596b488
	private Void set_modeFinish(Boolean value) { }
	// RVA: 0x3353508 VA: 0x759596b508
	public Int32 get_modeEffectDescListSeqNum() { }
	// RVA: 0x3353570 VA: 0x759596b570
	private Void set_modeEffectDescListSeqNum(Int32 value) { }
	// RVA: 0x33535ec VA: 0x759596b5ec
	public Boolean get_showTrackPoint() { }
	// RVA: 0x3352bec VA: 0x759596abec
	public Void set_showTrackPoint(Boolean value) { }
	// RVA: 0x3353654 VA: 0x759596b654
	public String get_actId() { }
	// RVA: 0x33536bc VA: 0x759596b6bc
	private Void set_actId(String value) { }
	// RVA: 0x3351c94 VA: 0x7595969c94
	public Void LoadData(String actId, Act1VAutoChessModeData modeData, Dictionary`2 modeRecordMap) { }
	// RVA: 0x3352ae0 VA: 0x759596aae0
	public Void RefreshData(Dictionary`2 modeRecordMap) { }
	// RVA: 0x3351ef0 VA: 0x7595969ef0
	public Void NotifyModeEffectDescListUpdate() { }
	// RVA: 0x3351c24 VA: 0x7595969c24
	public Void .ctor() { }
}
```