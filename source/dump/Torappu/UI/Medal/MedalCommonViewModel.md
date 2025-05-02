# MedalCommonViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalExpireStatus m_expireStatus`

- `MedalPerData <data>k__BackingField`

- `MedalGetState <getState>k__BackingField`

- `Boolean <hasAdvanced>k__BackingField`

- `MedalPerData <advancedData>k__BackingField`

- `Boolean <advancedGetFlag>k__BackingField`

- `Int64 <getTime>k__BackingField`

- `Int64 <advancedGetTime>k__BackingField`

- `Int32 <finishValue>k__BackingField`

- `Int32 <finishTarget>k__BackingField`

- `Int32 <advancedFinishValue>k__BackingField`

- `Int32 <advancedFinishTarget>k__BackingField`

- `MedalTypeData typeData`

- `Boolean isSelect`


## Properties

- `String medalId`

- `MedalPerData currentData`

- `MedalPerData data`

- `MedalGetState getState`

- `Boolean hasAdvanced`

- `MedalPerData advancedData`

- `Boolean advancedGetFlag`

- `Int64 getTime`

- `Int64 advancedGetTime`

- `Int32 finishValue`

- `Int32 finishTarget`

- `Int32 advancedFinishValue`

- `Int32 advancedFinishTarget`


## Methods

- `String get_medalId()`

- `MedalPerData get_currentData()`

- `MedalPerData get_data()`

- `Void set_data(MedalPerData)`

- `MedalGetState get_getState()`

- `Void set_getState(MedalGetState)`

- `Boolean get_hasAdvanced()`

- `Void set_hasAdvanced(Boolean)`

- `MedalPerData get_advancedData()`

- `Void set_advancedData(MedalPerData)`

- `Boolean get_advancedGetFlag()`

- `Void set_advancedGetFlag(Boolean)`

- `Int64 get_getTime()`

- `Void set_getTime(Int64)`

- `Int64 get_advancedGetTime()`

- `Void set_advancedGetTime(Int64)`

- `Int32 get_finishValue()`

- `Void set_finishValue(Int32)`

- `Int32 get_finishTarget()`

- `Void set_finishTarget(Int32)`

- `Int32 get_advancedFinishValue()`

- `Void set_advancedFinishValue(Int32)`

- `Int32 get_advancedFinishTarget()`

- `Void set_advancedFinishTarget(Int32)`

- `Void SyncPlayerMedalStatus(MedalPerData, Int64)`

- `Void SyncPlayerAdvancedStatus(MedalPerData)`

- `DisplayInfoCache GetDisplayInfo()`

- `Boolean IsAchieved()`

- `Boolean CheckIfMedalMatchShowType(MedalBarListShowType)`

- `Boolean IsExpired()`

- `Boolean IsPermExpired()`

- `Boolean IsMedalGotten()`

- `String GetProperExpireGetMethodDesc()`

- `MedalExpireType GetExpireType()`

- `Boolean IsHidden()`

- `Boolean CheckIfShowPreMedalListDuringNotGet()`

- `Boolean CheckIfShowRewardsDuringNotGet()`

- `Boolean CheckIfShowAdvMedalDuringNotGet()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalCommonViewModel : IHotfixable
{
	private MedalExpireStatus m_expireStatus; // 0x10
	private MedalPerData <data>k__BackingField; // 0x18
	private MedalGetState <getState>k__BackingField; // 0x20
	private Boolean <hasAdvanced>k__BackingField; // 0x24
	private MedalPerData <advancedData>k__BackingField; // 0x28
	private Boolean <advancedGetFlag>k__BackingField; // 0x30
	private Int64 <getTime>k__BackingField; // 0x38
	private Int64 <advancedGetTime>k__BackingField; // 0x40
	private Int32 <finishValue>k__BackingField; // 0x48
	private Int32 <finishTarget>k__BackingField; // 0x4c
	private Int32 <advancedFinishValue>k__BackingField; // 0x50
	private Int32 <advancedFinishTarget>k__BackingField; // 0x54
	public MedalTypeData typeData; // 0x58
	public Boolean isSelect; // 0x60
	private static DelegateBridge __Hotfix0_get_medalId; // 0x0
	private static DelegateBridge __Hotfix0_get_currentData; // 0x8
	private static DelegateBridge __Hotfix0_get_data; // 0x10
	private static DelegateBridge __Hotfix0_set_data; // 0x18
	private static DelegateBridge __Hotfix0_get_getState; // 0x20
	private static DelegateBridge __Hotfix0_set_getState; // 0x28
	private static DelegateBridge __Hotfix0_get_hasAdvanced; // 0x30
	private static DelegateBridge __Hotfix0_set_hasAdvanced; // 0x38
	private static DelegateBridge __Hotfix0_get_advancedData; // 0x40
	private static DelegateBridge __Hotfix0_set_advancedData; // 0x48
	private static DelegateBridge __Hotfix0_get_advancedGetFlag; // 0x50
	private static DelegateBridge __Hotfix0_set_advancedGetFlag; // 0x58
	private static DelegateBridge __Hotfix0_get_getTime; // 0x60
	private static DelegateBridge __Hotfix0_set_getTime; // 0x68
	private static DelegateBridge __Hotfix0_get_advancedGetTime; // 0x70
	private static DelegateBridge __Hotfix0_set_advancedGetTime; // 0x78
	private static DelegateBridge __Hotfix0_get_finishValue; // 0x80
	private static DelegateBridge __Hotfix0_set_finishValue; // 0x88
	private static DelegateBridge __Hotfix0_get_finishTarget; // 0x90
	private static DelegateBridge __Hotfix0_set_finishTarget; // 0x98
	private static DelegateBridge __Hotfix0_get_advancedFinishValue; // 0xa0
	private static DelegateBridge __Hotfix0_set_advancedFinishValue; // 0xa8
	private static DelegateBridge __Hotfix0_get_advancedFinishTarget; // 0xb0
	private static DelegateBridge __Hotfix0_set_advancedFinishTarget; // 0xb8
	private static DelegateBridge __Hotfix0_SyncPlayerMedalStatus; // 0xc0
	private static DelegateBridge __Hotfix0_SyncPlayerAdvancedStatus; // 0xc8
	private static DelegateBridge __Hotfix0_GetDisplayInfo; // 0xd0
	private static DelegateBridge __Hotfix0_IsAchieved; // 0xd8
	private static DelegateBridge __Hotfix0_CheckIfMedalMatchShowType; // 0xe0
	private static DelegateBridge __Hotfix0_IsExpired; // 0xe8
	private static DelegateBridge __Hotfix0_IsPermExpired; // 0xf0
	private static DelegateBridge __Hotfix0_IsMedalGotten; // 0xf8
	private static DelegateBridge __Hotfix0_GetProperExpireGetMethodDesc; // 0x100
	private static DelegateBridge __Hotfix0_GetExpireType; // 0x108
	private static DelegateBridge __Hotfix0_IsHidden; // 0x110
	private static DelegateBridge __Hotfix0_CheckIfShowPreMedalListDuringNotGet; // 0x118
	private static DelegateBridge __Hotfix0_CheckIfShowRewardsDuringNotGet; // 0x120
	private static DelegateBridge __Hotfix0_CheckIfShowAdvMedalDuringNotGet; // 0x128
	private static DelegateBridge __Hotfix0_CreateFromFriendMedal; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	public String medalId { get; }
	public MedalPerData currentData { get; }
	public MedalPerData data { get; set; }
	public MedalGetState getState { get; set; }
	public Boolean hasAdvanced { get; set; }
	public MedalPerData advancedData { get; set; }
	public Boolean advancedGetFlag { get; set; }
	public Int64 getTime { get; set; }
	public Int64 advancedGetTime { get; set; }
	public Int32 finishValue { get; set; }
	public Int32 finishTarget { get; set; }
	public Int32 advancedFinishValue { get; set; }
	public Int32 advancedFinishTarget { get; set; }

	// RVA: 0x27a2394 VA: 0x7594dba394
	public String get_medalId() { }
	// RVA: 0x27a2290 VA: 0x7594dba290
	public MedalPerData get_currentData() { }
	// RVA: 0x27a232c VA: 0x7594dba32c
	public MedalPerData get_data() { }
	// RVA: 0x27a9760 VA: 0x7594dc1760
	private Void set_data(MedalPerData value) { }
	// RVA: 0x27a97e4 VA: 0x7594dc17e4
	public MedalGetState get_getState() { }
	// RVA: 0x27a984c VA: 0x7594dc184c
	private Void set_getState(MedalGetState value) { }
	// RVA: 0x27a96f8 VA: 0x7594dc16f8
	public Boolean get_hasAdvanced() { }
	// RVA: 0x27a98c8 VA: 0x7594dc18c8
	private Void set_hasAdvanced(Boolean value) { }
	// RVA: 0x27a7834 VA: 0x7594dbf834
	public MedalPerData get_advancedData() { }
	// RVA: 0x27a9948 VA: 0x7594dc1948
	private Void set_advancedData(MedalPerData value) { }
	// RVA: 0x27a2790 VA: 0x7594dba790
	public Boolean get_advancedGetFlag() { }
	// RVA: 0x27a99cc VA: 0x7594dc19cc
	private Void set_advancedGetFlag(Boolean value) { }
	// RVA: 0x27a9a4c VA: 0x7594dc1a4c
	public Int64 get_getTime() { }
	// RVA: 0x27a9ab4 VA: 0x7594dc1ab4
	private Void set_getTime(Int64 value) { }
	// RVA: 0x27a9b30 VA: 0x7594dc1b30
	public Int64 get_advancedGetTime() { }
	// RVA: 0x27a9b98 VA: 0x7594dc1b98
	private Void set_advancedGetTime(Int64 value) { }
	// RVA: 0x27a2d44 VA: 0x7594dbad44
	public Int32 get_finishValue() { }
	// RVA: 0x27a9c14 VA: 0x7594dc1c14
	private Void set_finishValue(Int32 value) { }
	// RVA: 0x27a2dac VA: 0x7594dbadac
	public Int32 get_finishTarget() { }
	// RVA: 0x27a9c90 VA: 0x7594dc1c90
	private Void set_finishTarget(Int32 value) { }
	// RVA: 0x27a789c VA: 0x7594dbf89c
	public Int32 get_advancedFinishValue() { }
	// RVA: 0x27a9d0c VA: 0x7594dc1d0c
	private Void set_advancedFinishValue(Int32 value) { }
	// RVA: 0x27a7904 VA: 0x7594dbf904
	public Int32 get_advancedFinishTarget() { }
	// RVA: 0x27a9d88 VA: 0x7594dc1d88
	private Void set_advancedFinishTarget(Int32 value) { }
	// RVA: 0x27a9e04 VA: 0x7594dc1e04
	public Void SyncPlayerMedalStatus(MedalPerData medalData, Int64 curTs) { }
	// RVA: 0x27aa078 VA: 0x7594dc2078
	public Void SyncPlayerAdvancedStatus(MedalPerData advData) { }
	// RVA: 0x27a3400 VA: 0x7594dbb400
	public DisplayInfoCache GetDisplayInfo() { }
	// RVA: 0x27aa390 VA: 0x7594dc2390
	public Boolean IsAchieved() { }
	// RVA: 0x27aa404 VA: 0x7594dc2404
	public Boolean CheckIfMedalMatchShowType(MedalBarListShowType showType) { }
	// RVA: 0x27a2bd8 VA: 0x7594dbabd8
	public Boolean IsExpired() { }
	// RVA: 0x27a3b90 VA: 0x7594dbbb90
	public Boolean IsPermExpired() { }
	// RVA: 0x27aa4a0 VA: 0x7594dc24a0
	public Boolean IsMedalGotten() { }
	// RVA: 0x27a2c58 VA: 0x7594dbac58
	public String GetProperExpireGetMethodDesc() { }
	// RVA: 0x27a3850 VA: 0x7594dbb850
	public MedalExpireType GetExpireType() { }
	// RVA: 0x27aa514 VA: 0x7594dc2514
	public Boolean IsHidden() { }
	// RVA: 0x27a246c VA: 0x7594dba46c
	public Boolean CheckIfShowPreMedalListDuringNotGet() { }
	// RVA: 0x27a2534 VA: 0x7594dba534
	public Boolean CheckIfShowRewardsDuringNotGet() { }
	// RVA: 0x27a2660 VA: 0x7594dba660
	public Boolean CheckIfShowAdvMedalDuringNotGet() { }
	// RVA: 0x27aa5a0 VA: 0x7594dc25a0
	public static MedalCommonViewModel CreateFromFriendMedal(String medalId, FriendMedalTemplateGroupInfo info) { }
	// RVA: 0x27aa728 VA: 0x7594dc2728
	public Void .ctor() { }
}
```