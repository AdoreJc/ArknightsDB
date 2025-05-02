# ActMultiV3PrepareMainPlayerInfoViewModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `PlayerViewModel <partnerInfo>k__BackingField`

- `PlayerViewModel <selfInfo>k__BackingField`

- `BusinessType <businessType>k__BackingField`

- `Boolean <selfIsRoomOwner>k__BackingField`

- `Boolean <enableChat>k__BackingField`

- `Boolean <hasChatNew>k__BackingField`

- `String m_actId`


## Properties

- `PlayerViewModel partnerInfo`

- `PlayerViewModel selfInfo`

- `BusinessType businessType`

- `Boolean selfIsRoomOwner`

- `Boolean enableChat`

- `Boolean hasChatNew`


## Methods

- `PlayerViewModel get_partnerInfo()`

- `Void set_partnerInfo(PlayerViewModel)`

- `PlayerViewModel get_selfInfo()`

- `Void set_selfInfo(PlayerViewModel)`

- `BusinessType get_businessType()`

- `Void set_businessType(BusinessType)`

- `Boolean get_selfIsRoomOwner()`

- `Void set_selfIsRoomOwner(Boolean)`

- `Boolean get_enableChat()`

- `Void set_enableChat(Boolean)`

- `Boolean get_hasChatNew()`

- `Void set_hasChatNew(Boolean)`

- `Void LoadStableData(String)`

- `Void UpdateData(ActMultiV3PrepareStepType)`

- `Void RefreshChatTrackPoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainPlayerInfoViewModel : IHotfixable
{
	private PlayerViewModel <partnerInfo>k__BackingField; // 0x10
	private PlayerViewModel <selfInfo>k__BackingField; // 0x18
	private BusinessType <businessType>k__BackingField; // 0x20
	private Boolean <selfIsRoomOwner>k__BackingField; // 0x24
	private Boolean <enableChat>k__BackingField; // 0x25
	private Boolean <hasChatNew>k__BackingField; // 0x26
	private String m_actId; // 0x28
	private static DelegateBridge __Hotfix0_get_partnerInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_partnerInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_selfInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_selfInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_businessType; // 0x20
	private static DelegateBridge __Hotfix0_set_businessType; // 0x28
	private static DelegateBridge __Hotfix0_get_selfIsRoomOwner; // 0x30
	private static DelegateBridge __Hotfix0_set_selfIsRoomOwner; // 0x38
	private static DelegateBridge __Hotfix0_get_enableChat; // 0x40
	private static DelegateBridge __Hotfix0_set_enableChat; // 0x48
	private static DelegateBridge __Hotfix0_get_hasChatNew; // 0x50
	private static DelegateBridge __Hotfix0_set_hasChatNew; // 0x58
	private static DelegateBridge __Hotfix0_LoadStableData; // 0x60
	private static DelegateBridge __Hotfix0_UpdateData; // 0x68
	private static DelegateBridge __Hotfix0_RefreshChatTrackPoint; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public PlayerViewModel partnerInfo { get; set; }
	public PlayerViewModel selfInfo { get; set; }
	public BusinessType businessType { get; set; }
	public Boolean selfIsRoomOwner { get; set; }
	public Boolean enableChat { get; set; }
	public Boolean hasChatNew { get; set; }

	// RVA: 0x3155908 VA: 0x759576d908
	public PlayerViewModel get_partnerInfo() { }
	// RVA: 0x3155970 VA: 0x759576d970
	private Void set_partnerInfo(PlayerViewModel value) { }
	// RVA: 0x31559f4 VA: 0x759576d9f4
	public PlayerViewModel get_selfInfo() { }
	// RVA: 0x3155a5c VA: 0x759576da5c
	private Void set_selfInfo(PlayerViewModel value) { }
	// RVA: 0x3155ae0 VA: 0x759576dae0
	public BusinessType get_businessType() { }
	// RVA: 0x3155b48 VA: 0x759576db48
	private Void set_businessType(BusinessType value) { }
	// RVA: 0x3155bc4 VA: 0x759576dbc4
	public Boolean get_selfIsRoomOwner() { }
	// RVA: 0x3155c2c VA: 0x759576dc2c
	private Void set_selfIsRoomOwner(Boolean value) { }
	// RVA: 0x3155cac VA: 0x759576dcac
	public Boolean get_enableChat() { }
	// RVA: 0x3155d14 VA: 0x759576dd14
	private Void set_enableChat(Boolean value) { }
	// RVA: 0x3155d94 VA: 0x759576dd94
	public Boolean get_hasChatNew() { }
	// RVA: 0x3155dfc VA: 0x759576ddfc
	private Void set_hasChatNew(Boolean value) { }
	// RVA: 0x3155e7c VA: 0x759576de7c
	public Void LoadStableData(String actId) { }
	// RVA: 0x3155f78 VA: 0x759576df78
	public Void UpdateData(ActMultiV3PrepareStepType curStep) { }
	// RVA: 0x31561b4 VA: 0x759576e1b4
	public Void RefreshChatTrackPoint() { }
	// RVA: 0x3156224 VA: 0x759576e224
	public Void .ctor() { }
}
```