# ActMultiV3PrepareMainEntranceShowViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String <actId>k__BackingField`

- `STPlayerStatus <selfStatus>k__BackingField`

- `STPlayerStatus <partnerStatus>k__BackingField`

- `Boolean <isFlipMode>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Single <playerShowTime>k__BackingField`

- `CharUISkinStruct <selfAssitSkin>k__BackingField`

- `CharUISkinStruct <partnerAssitSkin>k__BackingField`

- `ActMultiV3StageDetailViewModel <stageDetailViewModel>k__BackingField`

- `String <selfEffectIconId>k__BackingField`

- `String <selfEffectName>k__BackingField`

- `String <partnerEffectIconId>k__BackingField`

- `String <partnerEffectName>k__BackingField`

- `Boolean <isShow>k__BackingField`

- `Boolean <isPlayerDataReady>k__BackingField`


## Properties

- `String actId`

- `STPlayerStatus selfStatus`

- `STPlayerStatus partnerStatus`

- `Boolean isSelfReady`

- `Boolean isPartnerReady`

- `Boolean isFlipMode`

- `Int32 enterSeqNum`

- `Single playerShowTime`

- `CharUISkinStruct selfAssitSkin`

- `CharUISkinStruct partnerAssitSkin`

- `ActMultiV3StageDetailViewModel stageDetailViewModel`

- `String selfEffectIconId`

- `String selfEffectName`

- `String partnerEffectIconId`

- `String partnerEffectName`

- `Boolean isShow`

- `Boolean isPlayerDataReady`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `STPlayerStatus get_selfStatus()`

- `Void set_selfStatus(STPlayerStatus)`

- `STPlayerStatus get_partnerStatus()`

- `Void set_partnerStatus(STPlayerStatus)`

- `Boolean get_isSelfReady()`

- `Boolean get_isPartnerReady()`

- `Boolean get_isFlipMode()`

- `Void set_isFlipMode(Boolean)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Single get_playerShowTime()`

- `Void set_playerShowTime(Single)`

- `CharUISkinStruct get_selfAssitSkin()`

- `Void set_selfAssitSkin(CharUISkinStruct)`

- `CharUISkinStruct get_partnerAssitSkin()`

- `Void set_partnerAssitSkin(CharUISkinStruct)`

- `ActMultiV3StageDetailViewModel get_stageDetailViewModel()`

- `Void set_stageDetailViewModel(ActMultiV3StageDetailViewModel)`

- `String get_selfEffectIconId()`

- `Void set_selfEffectIconId(String)`

- `String get_selfEffectName()`

- `Void set_selfEffectName(String)`

- `String get_partnerEffectIconId()`

- `Void set_partnerEffectIconId(String)`

- `String get_partnerEffectName()`

- `Void set_partnerEffectName(String)`

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Boolean get_isPlayerDataReady()`

- `Void set_isPlayerDataReady(Boolean)`

- `Void LoadData(String)`

- `Void UpdatePlayerShowData()`

- `Void NotifyEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PrepareMainEntranceShowViewModel : IHotfixable
{
	private String <actId>k__BackingField; // 0x10
	private STPlayerStatus <selfStatus>k__BackingField; // 0x18
	private STPlayerStatus <partnerStatus>k__BackingField; // 0x20
	private Boolean <isFlipMode>k__BackingField; // 0x28
	private Int32 <enterSeqNum>k__BackingField; // 0x2c
	private Single <playerShowTime>k__BackingField; // 0x30
	private CharUISkinStruct <selfAssitSkin>k__BackingField; // 0x38
	private CharUISkinStruct <partnerAssitSkin>k__BackingField; // 0x48
	private ActMultiV3StageDetailViewModel <stageDetailViewModel>k__BackingField; // 0x58
	private String <selfEffectIconId>k__BackingField; // 0x60
	private String <selfEffectName>k__BackingField; // 0x68
	private String <partnerEffectIconId>k__BackingField; // 0x70
	private String <partnerEffectName>k__BackingField; // 0x78
	private Boolean <isShow>k__BackingField; // 0x80
	private Boolean <isPlayerDataReady>k__BackingField; // 0x81
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_selfStatus; // 0x10
	private static DelegateBridge __Hotfix0_set_selfStatus; // 0x18
	private static DelegateBridge __Hotfix0_get_partnerStatus; // 0x20
	private static DelegateBridge __Hotfix0_set_partnerStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_isSelfReady; // 0x30
	private static DelegateBridge __Hotfix0_get_isPartnerReady; // 0x38
	private static DelegateBridge __Hotfix0_get_isFlipMode; // 0x40
	private static DelegateBridge __Hotfix0_set_isFlipMode; // 0x48
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x50
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x58
	private static DelegateBridge __Hotfix0_get_playerShowTime; // 0x60
	private static DelegateBridge __Hotfix0_set_playerShowTime; // 0x68
	private static DelegateBridge __Hotfix0_get_selfAssitSkin; // 0x70
	private static DelegateBridge __Hotfix0_set_selfAssitSkin; // 0x78
	private static DelegateBridge __Hotfix0_get_partnerAssitSkin; // 0x80
	private static DelegateBridge __Hotfix0_set_partnerAssitSkin; // 0x88
	private static DelegateBridge __Hotfix0_get_stageDetailViewModel; // 0x90
	private static DelegateBridge __Hotfix0_set_stageDetailViewModel; // 0x98
	private static DelegateBridge __Hotfix0_get_selfEffectIconId; // 0xa0
	private static DelegateBridge __Hotfix0_set_selfEffectIconId; // 0xa8
	private static DelegateBridge __Hotfix0_get_selfEffectName; // 0xb0
	private static DelegateBridge __Hotfix0_set_selfEffectName; // 0xb8
	private static DelegateBridge __Hotfix0_get_partnerEffectIconId; // 0xc0
	private static DelegateBridge __Hotfix0_set_partnerEffectIconId; // 0xc8
	private static DelegateBridge __Hotfix0_get_partnerEffectName; // 0xd0
	private static DelegateBridge __Hotfix0_set_partnerEffectName; // 0xd8
	private static DelegateBridge __Hotfix0_get_isShow; // 0xe0
	private static DelegateBridge __Hotfix0_set_isShow; // 0xe8
	private static DelegateBridge __Hotfix0_get_isPlayerDataReady; // 0xf0
	private static DelegateBridge __Hotfix0_set_isPlayerDataReady; // 0xf8
	private static DelegateBridge __Hotfix0_LoadData; // 0x100
	private static DelegateBridge __Hotfix0_UpdatePlayerShowData; // 0x108
	private static DelegateBridge __Hotfix0_NotifyEnter; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	public String actId { get; set; }
	public STPlayerStatus selfStatus { get; set; }
	public STPlayerStatus partnerStatus { get; set; }
	public Boolean isSelfReady { get; }
	public Boolean isPartnerReady { get; }
	public Boolean isFlipMode { get; set; }
	public Int32 enterSeqNum { get; set; }
	public Single playerShowTime { get; set; }
	public CharUISkinStruct selfAssitSkin { get; set; }
	public CharUISkinStruct partnerAssitSkin { get; set; }
	public ActMultiV3StageDetailViewModel stageDetailViewModel { get; set; }
	public String selfEffectIconId { get; set; }
	public String selfEffectName { get; set; }
	public String partnerEffectIconId { get; set; }
	public String partnerEffectName { get; set; }
	public Boolean isShow { get; set; }
	public Boolean isPlayerDataReady { get; set; }

	// RVA: 0x3124480 VA: 0x759573c480
	public String get_actId() { }
	// RVA: 0x31244e8 VA: 0x759573c4e8
	private Void set_actId(String value) { }
	// RVA: 0x312456c VA: 0x759573c56c
	public STPlayerStatus get_selfStatus() { }
	// RVA: 0x31245d4 VA: 0x759573c5d4
	public Void set_selfStatus(STPlayerStatus value) { }
	// RVA: 0x3124658 VA: 0x759573c658
	public STPlayerStatus get_partnerStatus() { }
	// RVA: 0x31246c0 VA: 0x759573c6c0
	public Void set_partnerStatus(STPlayerStatus value) { }
	// RVA: 0x3124744 VA: 0x759573c744
	public Boolean get_isSelfReady() { }
	// RVA: 0x31247d0 VA: 0x759573c7d0
	public Boolean get_isPartnerReady() { }
	// RVA: 0x312485c VA: 0x759573c85c
	public Boolean get_isFlipMode() { }
	// RVA: 0x31248c4 VA: 0x759573c8c4
	private Void set_isFlipMode(Boolean value) { }
	// RVA: 0x3124944 VA: 0x759573c944
	public Int32 get_enterSeqNum() { }
	// RVA: 0x31249ac VA: 0x759573c9ac
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x3124a28 VA: 0x759573ca28
	public Single get_playerShowTime() { }
	// RVA: 0x3124a90 VA: 0x759573ca90
	private Void set_playerShowTime(Single value) { }
	// RVA: 0x3124b0c VA: 0x759573cb0c
	public CharUISkinStruct get_selfAssitSkin() { }
	// RVA: 0x3124b70 VA: 0x759573cb70
	private Void set_selfAssitSkin(CharUISkinStruct value) { }
	// RVA: 0x3124c00 VA: 0x759573cc00
	public CharUISkinStruct get_partnerAssitSkin() { }
	// RVA: 0x3124c64 VA: 0x759573cc64
	private Void set_partnerAssitSkin(CharUISkinStruct value) { }
	// RVA: 0x3124cf4 VA: 0x759573ccf4
	public ActMultiV3StageDetailViewModel get_stageDetailViewModel() { }
	// RVA: 0x3124d5c VA: 0x759573cd5c
	public Void set_stageDetailViewModel(ActMultiV3StageDetailViewModel value) { }
	// RVA: 0x3124de0 VA: 0x759573cde0
	public String get_selfEffectIconId() { }
	// RVA: 0x3124e48 VA: 0x759573ce48
	private Void set_selfEffectIconId(String value) { }
	// RVA: 0x3124ecc VA: 0x759573cecc
	public String get_selfEffectName() { }
	// RVA: 0x3124f34 VA: 0x759573cf34
	private Void set_selfEffectName(String value) { }
	// RVA: 0x3124fb8 VA: 0x759573cfb8
	public String get_partnerEffectIconId() { }
	// RVA: 0x3125020 VA: 0x759573d020
	private Void set_partnerEffectIconId(String value) { }
	// RVA: 0x31250a4 VA: 0x759573d0a4
	public String get_partnerEffectName() { }
	// RVA: 0x312510c VA: 0x759573d10c
	private Void set_partnerEffectName(String value) { }
	// RVA: 0x3125190 VA: 0x759573d190
	public Boolean get_isShow() { }
	// RVA: 0x31251f8 VA: 0x759573d1f8
	private Void set_isShow(Boolean value) { }
	// RVA: 0x3125278 VA: 0x759573d278
	public Boolean get_isPlayerDataReady() { }
	// RVA: 0x31252e0 VA: 0x759573d2e0
	private Void set_isPlayerDataReady(Boolean value) { }
	// RVA: 0x3125360 VA: 0x759573d360
	public Void LoadData(String actId) { }
	// RVA: 0x31254bc VA: 0x759573d4bc
	public Void UpdatePlayerShowData() { }
	// RVA: 0x3125870 VA: 0x759573d870
	public Void NotifyEnter() { }
	// RVA: 0x31258e4 VA: 0x759573d8e4
	public Void .ctor() { }
}
```