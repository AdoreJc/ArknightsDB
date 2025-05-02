# ActMultiV3PrepareMainStageChooseViewModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3Data m_actData`

- `Boolean m_cachedBothPrepared`

- `MapType m_cachedMapType`

- `String m_cachedStageId`

- `String <actId>k__BackingField`

- `Boolean <isPartnerIn>k__BackingField`

- `Boolean <isSelfOwner>k__BackingField`

- `Boolean <isSelfPrepared>k__BackingField`

- `Boolean <isPartnerPrepared>k__BackingField`

- `Boolean <isPartnerOffline>k__BackingField`

- `Boolean <isFlipMode>k__BackingField`

- `Boolean <flipModeUnlock>k__BackingField`

- `FriendDataWithNameCard <partnerNameCardData>k__BackingField`

- `ActMultiV3PrepareMapInfoViewModel <mapViewModel>k__BackingField`

- `ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField`

- `String <roomId>k__BackingField`

- `String <roomNumCopyToast>k__BackingField`

- `String <ownerModeChangedToast>k__BackingField`

- `String <guestModeChangedToast>k__BackingField`

- `String <ownerMapChangedToast>k__BackingField`

- `String <guestMapChangedToast>k__BackingField`

- `String <flipLockHintToast>k__BackingField`

- `String <ownerWaitingStatusDesc>k__BackingField`

- `String <guestWaitingStatusDesc>k__BackingField`

- `String <partnerEnterToast>k__BackingField`

- `String <partnerExitToast>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Int32 <modeChangeSeqNum>k__BackingField`

- `Int32 <partnerInSeqNum>k__BackingField`

- `Int32 <mapChangedNum>k__BackingField`


## Properties

- `String actId`

- `Boolean isPartnerIn`

- `Boolean isSelfOwner`

- `Boolean isSelfPrepared`

- `Boolean isPartnerPrepared`

- `Boolean isPartnerOffline`

- `Boolean isFlipMode`

- `Boolean flipModeUnlock`

- `FriendDataWithNameCard partnerNameCardData`

- `ActMultiV3PrepareMapInfoViewModel mapViewModel`

- `ActMultiV3DifficultyIconViewModel diffIconModel`

- `String roomId`

- `String roomNumCopyToast`

- `String ownerModeChangedToast`

- `String guestModeChangedToast`

- `String ownerMapChangedToast`

- `String guestMapChangedToast`

- `String flipLockHintToast`

- `String ownerWaitingStatusDesc`

- `String guestWaitingStatusDesc`

- `String partnerEnterToast`

- `String partnerExitToast`

- `Int32 enterSeqNum`

- `Int32 modeChangeSeqNum`

- `Int32 partnerInSeqNum`

- `Int32 mapChangedNum`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `Boolean get_isPartnerIn()`

- `Void set_isPartnerIn(Boolean)`

- `Boolean get_isSelfOwner()`

- `Void set_isSelfOwner(Boolean)`

- `Boolean get_isSelfPrepared()`

- `Void set_isSelfPrepared(Boolean)`

- `Boolean get_isPartnerPrepared()`

- `Void set_isPartnerPrepared(Boolean)`

- `Boolean get_isPartnerOffline()`

- `Void set_isPartnerOffline(Boolean)`

- `Boolean get_isFlipMode()`

- `Void set_isFlipMode(Boolean)`

- `Boolean get_flipModeUnlock()`

- `Void set_flipModeUnlock(Boolean)`

- `FriendDataWithNameCard get_partnerNameCardData()`

- `Void set_partnerNameCardData(FriendDataWithNameCard)`

- `ActMultiV3PrepareMapInfoViewModel get_mapViewModel()`

- `Void set_mapViewModel(ActMultiV3PrepareMapInfoViewModel)`

- `ActMultiV3DifficultyIconViewModel get_diffIconModel()`

- `Void set_diffIconModel(ActMultiV3DifficultyIconViewModel)`

- `String get_roomId()`

- `Void set_roomId(String)`

- `String get_roomNumCopyToast()`

- `Void set_roomNumCopyToast(String)`

- `String get_ownerModeChangedToast()`

- `Void set_ownerModeChangedToast(String)`

- `String get_guestModeChangedToast()`

- `Void set_guestModeChangedToast(String)`

- `String get_ownerMapChangedToast()`

- `Void set_ownerMapChangedToast(String)`

- `String get_guestMapChangedToast()`

- `Void set_guestMapChangedToast(String)`

- `String get_flipLockHintToast()`

- `Void set_flipLockHintToast(String)`

- `String get_ownerWaitingStatusDesc()`

- `Void set_ownerWaitingStatusDesc(String)`

- `String get_guestWaitingStatusDesc()`

- `Void set_guestWaitingStatusDesc(String)`

- `String get_partnerEnterToast()`

- `Void set_partnerEnterToast(String)`

- `String get_partnerExitToast()`

- `Void set_partnerExitToast(String)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Int32 get_modeChangeSeqNum()`

- `Void set_modeChangeSeqNum(Int32)`

- `Int32 get_partnerInSeqNum()`

- `Void set_partnerInSeqNum(Int32)`

- `Int32 get_mapChangedNum()`

- `Void set_mapChangedNum(Int32)`

- `Void LoadStableData(String)`

- `Void UpdateData()`

- `Void UpdateOnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainStageChooseViewModel : IHotfixable
{
	private ActMultiV3Data m_actData; // 0x10
	private Boolean m_cachedBothPrepared; // 0x18
	private MapType m_cachedMapType; // 0x1c
	private String m_cachedStageId; // 0x20
	private String <actId>k__BackingField; // 0x28
	private Boolean <isPartnerIn>k__BackingField; // 0x30
	private Boolean <isSelfOwner>k__BackingField; // 0x31
	private Boolean <isSelfPrepared>k__BackingField; // 0x32
	private Boolean <isPartnerPrepared>k__BackingField; // 0x33
	private Boolean <isPartnerOffline>k__BackingField; // 0x34
	private Boolean <isFlipMode>k__BackingField; // 0x35
	private Boolean <flipModeUnlock>k__BackingField; // 0x36
	private FriendDataWithNameCard <partnerNameCardData>k__BackingField; // 0x38
	private ActMultiV3PrepareMapInfoViewModel <mapViewModel>k__BackingField; // 0x40
	private ActMultiV3DifficultyIconViewModel <diffIconModel>k__BackingField; // 0x48
	private String <roomId>k__BackingField; // 0x50
	private String <roomNumCopyToast>k__BackingField; // 0x58
	private String <ownerModeChangedToast>k__BackingField; // 0x60
	private String <guestModeChangedToast>k__BackingField; // 0x68
	private String <ownerMapChangedToast>k__BackingField; // 0x70
	private String <guestMapChangedToast>k__BackingField; // 0x78
	private String <flipLockHintToast>k__BackingField; // 0x80
	private String <ownerWaitingStatusDesc>k__BackingField; // 0x88
	private String <guestWaitingStatusDesc>k__BackingField; // 0x90
	private String <partnerEnterToast>k__BackingField; // 0x98
	private String <partnerExitToast>k__BackingField; // 0xa0
	private Int32 <enterSeqNum>k__BackingField; // 0xa8
	private Int32 <modeChangeSeqNum>k__BackingField; // 0xac
	private Int32 <partnerInSeqNum>k__BackingField; // 0xb0
	private Int32 <mapChangedNum>k__BackingField; // 0xb4
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_isPartnerIn; // 0x10
	private static DelegateBridge __Hotfix0_set_isPartnerIn; // 0x18
	private static DelegateBridge __Hotfix0_get_isSelfOwner; // 0x20
	private static DelegateBridge __Hotfix0_set_isSelfOwner; // 0x28
	private static DelegateBridge __Hotfix0_get_isSelfPrepared; // 0x30
	private static DelegateBridge __Hotfix0_set_isSelfPrepared; // 0x38
	private static DelegateBridge __Hotfix0_get_isPartnerPrepared; // 0x40
	private static DelegateBridge __Hotfix0_set_isPartnerPrepared; // 0x48
	private static DelegateBridge __Hotfix0_get_isPartnerOffline; // 0x50
	private static DelegateBridge __Hotfix0_set_isPartnerOffline; // 0x58
	private static DelegateBridge __Hotfix0_get_isFlipMode; // 0x60
	private static DelegateBridge __Hotfix0_set_isFlipMode; // 0x68
	private static DelegateBridge __Hotfix0_get_flipModeUnlock; // 0x70
	private static DelegateBridge __Hotfix0_set_flipModeUnlock; // 0x78
	private static DelegateBridge __Hotfix0_get_partnerNameCardData; // 0x80
	private static DelegateBridge __Hotfix0_set_partnerNameCardData; // 0x88
	private static DelegateBridge __Hotfix0_get_mapViewModel; // 0x90
	private static DelegateBridge __Hotfix0_set_mapViewModel; // 0x98
	private static DelegateBridge __Hotfix0_get_diffIconModel; // 0xa0
	private static DelegateBridge __Hotfix0_set_diffIconModel; // 0xa8
	private static DelegateBridge __Hotfix0_get_roomId; // 0xb0
	private static DelegateBridge __Hotfix0_set_roomId; // 0xb8
	private static DelegateBridge __Hotfix0_get_roomNumCopyToast; // 0xc0
	private static DelegateBridge __Hotfix0_set_roomNumCopyToast; // 0xc8
	private static DelegateBridge __Hotfix0_get_ownerModeChangedToast; // 0xd0
	private static DelegateBridge __Hotfix0_set_ownerModeChangedToast; // 0xd8
	private static DelegateBridge __Hotfix0_get_guestModeChangedToast; // 0xe0
	private static DelegateBridge __Hotfix0_set_guestModeChangedToast; // 0xe8
	private static DelegateBridge __Hotfix0_get_ownerMapChangedToast; // 0xf0
	private static DelegateBridge __Hotfix0_set_ownerMapChangedToast; // 0xf8
	private static DelegateBridge __Hotfix0_get_guestMapChangedToast; // 0x100
	private static DelegateBridge __Hotfix0_set_guestMapChangedToast; // 0x108
	private static DelegateBridge __Hotfix0_get_flipLockHintToast; // 0x110
	private static DelegateBridge __Hotfix0_set_flipLockHintToast; // 0x118
	private static DelegateBridge __Hotfix0_get_ownerWaitingStatusDesc; // 0x120
	private static DelegateBridge __Hotfix0_set_ownerWaitingStatusDesc; // 0x128
	private static DelegateBridge __Hotfix0_get_guestWaitingStatusDesc; // 0x130
	private static DelegateBridge __Hotfix0_set_guestWaitingStatusDesc; // 0x138
	private static DelegateBridge __Hotfix0_get_partnerEnterToast; // 0x140
	private static DelegateBridge __Hotfix0_set_partnerEnterToast; // 0x148
	private static DelegateBridge __Hotfix0_get_partnerExitToast; // 0x150
	private static DelegateBridge __Hotfix0_set_partnerExitToast; // 0x158
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x160
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x168
	private static DelegateBridge __Hotfix0_get_modeChangeSeqNum; // 0x170
	private static DelegateBridge __Hotfix0_set_modeChangeSeqNum; // 0x178
	private static DelegateBridge __Hotfix0_get_partnerInSeqNum; // 0x180
	private static DelegateBridge __Hotfix0_set_partnerInSeqNum; // 0x188
	private static DelegateBridge __Hotfix0_get_mapChangedNum; // 0x190
	private static DelegateBridge __Hotfix0_set_mapChangedNum; // 0x198
	private static DelegateBridge __Hotfix0_LoadStableData; // 0x1a0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x1a8
	private static DelegateBridge __Hotfix0_UpdateOnEnter; // 0x1b0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b8

	public String actId { get; set; }
	public Boolean isPartnerIn { get; set; }
	public Boolean isSelfOwner { get; set; }
	public Boolean isSelfPrepared { get; set; }
	public Boolean isPartnerPrepared { get; set; }
	public Boolean isPartnerOffline { get; set; }
	public Boolean isFlipMode { get; set; }
	public Boolean flipModeUnlock { get; set; }
	public FriendDataWithNameCard partnerNameCardData { get; set; }
	public ActMultiV3PrepareMapInfoViewModel mapViewModel { get; set; }
	public ActMultiV3DifficultyIconViewModel diffIconModel { get; set; }
	public String roomId { get; set; }
	public String roomNumCopyToast { get; set; }
	public String ownerModeChangedToast { get; set; }
	public String guestModeChangedToast { get; set; }
	public String ownerMapChangedToast { get; set; }
	public String guestMapChangedToast { get; set; }
	public String flipLockHintToast { get; set; }
	public String ownerWaitingStatusDesc { get; set; }
	public String guestWaitingStatusDesc { get; set; }
	public String partnerEnterToast { get; set; }
	public String partnerExitToast { get; set; }
	public Int32 enterSeqNum { get; set; }
	public Int32 modeChangeSeqNum { get; set; }
	public Int32 partnerInSeqNum { get; set; }
	public Int32 mapChangedNum { get; set; }

	// RVA: 0x3179048 VA: 0x7595791048
	public String get_actId() { }
	// RVA: 0x3179a2c VA: 0x7595791a2c
	private Void set_actId(String value) { }
	// RVA: 0x31780a8 VA: 0x75957900a8
	public Boolean get_isPartnerIn() { }
	// RVA: 0x3179ab0 VA: 0x7595791ab0
	private Void set_isPartnerIn(Boolean value) { }
	// RVA: 0x3178040 VA: 0x7595790040
	public Boolean get_isSelfOwner() { }
	// RVA: 0x3179b30 VA: 0x7595791b30
	private Void set_isSelfOwner(Boolean value) { }
	// RVA: 0x31791e8 VA: 0x75957911e8
	public Boolean get_isSelfPrepared() { }
	// RVA: 0x3179bb0 VA: 0x7595791bb0
	private Void set_isSelfPrepared(Boolean value) { }
	// RVA: 0x3179250 VA: 0x7595791250
	public Boolean get_isPartnerPrepared() { }
	// RVA: 0x3179c30 VA: 0x7595791c30
	private Void set_isPartnerPrepared(Boolean value) { }
	// RVA: 0x3178110 VA: 0x7595790110
	public Boolean get_isPartnerOffline() { }
	// RVA: 0x3179cb0 VA: 0x7595791cb0
	private Void set_isPartnerOffline(Boolean value) { }
	// RVA: 0x3178384 VA: 0x7595790384
	public Boolean get_isFlipMode() { }
	// RVA: 0x3179d30 VA: 0x7595791d30
	private Void set_isFlipMode(Boolean value) { }
	// RVA: 0x31782b4 VA: 0x75957902b4
	public Boolean get_flipModeUnlock() { }
	// RVA: 0x3179db0 VA: 0x7595791db0
	private Void set_flipModeUnlock(Boolean value) { }
	// RVA: 0x3179e30 VA: 0x7595791e30
	public FriendDataWithNameCard get_partnerNameCardData() { }
	// RVA: 0x3179e98 VA: 0x7595791e98
	private Void set_partnerNameCardData(FriendDataWithNameCard value) { }
	// RVA: 0x3177c50 VA: 0x759578fc50
	public ActMultiV3PrepareMapInfoViewModel get_mapViewModel() { }
	// RVA: 0x3179f1c VA: 0x7595791f1c
	private Void set_mapViewModel(ActMultiV3PrepareMapInfoViewModel value) { }
	// RVA: 0x3179180 VA: 0x7595791180
	public ActMultiV3DifficultyIconViewModel get_diffIconModel() { }
	// RVA: 0x3179fa0 VA: 0x7595791fa0
	private Void set_diffIconModel(ActMultiV3DifficultyIconViewModel value) { }
	// RVA: 0x3177cb8 VA: 0x759578fcb8
	public String get_roomId() { }
	// RVA: 0x317a024 VA: 0x7595792024
	private Void set_roomId(String value) { }
	// RVA: 0x3177d20 VA: 0x759578fd20
	public String get_roomNumCopyToast() { }
	// RVA: 0x317a0a8 VA: 0x75957920a8
	private Void set_roomNumCopyToast(String value) { }
	// RVA: 0x317964c VA: 0x759579164c
	public String get_ownerModeChangedToast() { }
	// RVA: 0x317a12c VA: 0x759579212c
	private Void set_ownerModeChangedToast(String value) { }
	// RVA: 0x31795e4 VA: 0x75957915e4
	public String get_guestModeChangedToast() { }
	// RVA: 0x317a1b0 VA: 0x75957921b0
	private Void set_guestModeChangedToast(String value) { }
	// RVA: 0x3179784 VA: 0x7595791784
	public String get_ownerMapChangedToast() { }
	// RVA: 0x317a234 VA: 0x7595792234
	private Void set_ownerMapChangedToast(String value) { }
	// RVA: 0x317971c VA: 0x759579171c
	public String get_guestMapChangedToast() { }
	// RVA: 0x317a2b8 VA: 0x75957922b8
	private Void set_guestMapChangedToast(String value) { }
	// RVA: 0x317831c VA: 0x759579031c
	public String get_flipLockHintToast() { }
	// RVA: 0x317a33c VA: 0x759579233c
	private Void set_flipLockHintToast(String value) { }
	// RVA: 0x31790b0 VA: 0x75957910b0
	public String get_ownerWaitingStatusDesc() { }
	// RVA: 0x317a3c0 VA: 0x75957923c0
	private Void set_ownerWaitingStatusDesc(String value) { }
	// RVA: 0x3179118 VA: 0x7595791118
	public String get_guestWaitingStatusDesc() { }
	// RVA: 0x317a444 VA: 0x7595792444
	private Void set_guestWaitingStatusDesc(String value) { }
	// RVA: 0x31798bc VA: 0x75957918bc
	public String get_partnerEnterToast() { }
	// RVA: 0x317a4c8 VA: 0x75957924c8
	private Void set_partnerEnterToast(String value) { }
	// RVA: 0x3179854 VA: 0x7595791854
	public String get_partnerExitToast() { }
	// RVA: 0x317a54c VA: 0x759579254c
	private Void set_partnerExitToast(String value) { }
	// RVA: 0x31793a0 VA: 0x75957913a0
	public Int32 get_enterSeqNum() { }
	// RVA: 0x317a5d0 VA: 0x75957925d0
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x317957c VA: 0x759579157c
	public Int32 get_modeChangeSeqNum() { }
	// RVA: 0x317a64c VA: 0x759579264c
	private Void set_modeChangeSeqNum(Int32 value) { }
	// RVA: 0x31797ec VA: 0x75957917ec
	public Int32 get_partnerInSeqNum() { }
	// RVA: 0x317a6c8 VA: 0x75957926c8
	private Void set_partnerInSeqNum(Int32 value) { }
	// RVA: 0x31796b4 VA: 0x75957916b4
	public Int32 get_mapChangedNum() { }
	// RVA: 0x317a744 VA: 0x7595792744
	private Void set_mapChangedNum(Int32 value) { }
	// RVA: 0x3177244 VA: 0x759578f244
	public Void LoadStableData(String actId) { }
	// RVA: 0x31775f4 VA: 0x759578f5f4
	public Void UpdateData() { }
	// RVA: 0x31774e8 VA: 0x759578f4e8
	public Void UpdateOnEnter() { }
	// RVA: 0x317a7c0 VA: 0x75957927c0
	public Void .ctor() { }
}
```