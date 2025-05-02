# ActMultiV3MatchPosModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3MatchPosUnlockCond m_unlockCond`

- `Int32 <sortId>k__BackingField`

- `String <name>k__BackingField`

- `String <matchDesc>k__BackingField`

- `String <posToast>k__BackingField`

- `String <desc>k__BackingField`

- `ActMultiV3MatchPosType <posType>k__BackingField`

- `Boolean <isUnlock>k__BackingField`


## Properties

- `Int32 sortId`

- `String name`

- `String matchDesc`

- `String posToast`

- `String desc`

- `ActMultiV3MatchPosType posType`

- `Boolean isUnlock`

- `String unlockHint`


## Methods

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_matchDesc()`

- `Void set_matchDesc(String)`

- `String get_posToast()`

- `Void set_posToast(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `ActMultiV3MatchPosType get_posType()`

- `Void set_posType(ActMultiV3MatchPosType)`

- `Boolean get_isUnlock()`

- `Void set_isUnlock(Boolean)`

- `String get_unlockHint()`

- `Void LoadData(String, ActMultiV3MatchPosData)`

- `Void UpdateUnlockStatus(ActMultiV3QuickMatchModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchPosModel : IHotfixable
{
	private ActMultiV3MatchPosUnlockCond m_unlockCond; // 0x10
	private Int32 <sortId>k__BackingField; // 0x18
	private String <name>k__BackingField; // 0x20
	private String <matchDesc>k__BackingField; // 0x28
	private String <posToast>k__BackingField; // 0x30
	private String <desc>k__BackingField; // 0x38
	private ActMultiV3MatchPosType <posType>k__BackingField; // 0x40
	private Boolean <isUnlock>k__BackingField; // 0x44
	private static DelegateBridge __Hotfix0_get_sortId; // 0x0
	private static DelegateBridge __Hotfix0_set_sortId; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_set_name; // 0x18
	private static DelegateBridge __Hotfix0_get_matchDesc; // 0x20
	private static DelegateBridge __Hotfix0_set_matchDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_posToast; // 0x30
	private static DelegateBridge __Hotfix0_set_posToast; // 0x38
	private static DelegateBridge __Hotfix0_get_desc; // 0x40
	private static DelegateBridge __Hotfix0_set_desc; // 0x48
	private static DelegateBridge __Hotfix0_get_posType; // 0x50
	private static DelegateBridge __Hotfix0_set_posType; // 0x58
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x60
	private static DelegateBridge __Hotfix0_set_isUnlock; // 0x68
	private static DelegateBridge __Hotfix0_get_unlockHint; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x78
	private static DelegateBridge __Hotfix0_UpdateUnlockStatus; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Int32 sortId { get; set; }
	public String name { get; set; }
	public String matchDesc { get; set; }
	public String posToast { get; set; }
	public String desc { get; set; }
	public ActMultiV3MatchPosType posType { get; set; }
	public Boolean isUnlock { get; set; }
	public String unlockHint { get; }

	// RVA: 0x31327a0 VA: 0x759574a7a0
	public Int32 get_sortId() { }
	// RVA: 0x3132924 VA: 0x759574a924
	private Void set_sortId(Int32 value) { }
	// RVA: 0x31329a0 VA: 0x759574a9a0
	public String get_name() { }
	// RVA: 0x3132a08 VA: 0x759574aa08
	private Void set_name(String value) { }
	// RVA: 0x3132a8c VA: 0x759574aa8c
	public String get_matchDesc() { }
	// RVA: 0x3132af4 VA: 0x759574aaf4
	private Void set_matchDesc(String value) { }
	// RVA: 0x3132b78 VA: 0x759574ab78
	public String get_posToast() { }
	// RVA: 0x3132be0 VA: 0x759574abe0
	private Void set_posToast(String value) { }
	// RVA: 0x3132c64 VA: 0x759574ac64
	public String get_desc() { }
	// RVA: 0x3132ccc VA: 0x759574accc
	private Void set_desc(String value) { }
	// RVA: 0x312efa0 VA: 0x7595746fa0
	public ActMultiV3MatchPosType get_posType() { }
	// RVA: 0x3132d50 VA: 0x759574ad50
	private Void set_posType(ActMultiV3MatchPosType value) { }
	// RVA: 0x3132210 VA: 0x759574a210
	public Boolean get_isUnlock() { }
	// RVA: 0x3132dcc VA: 0x759574adcc
	private Void set_isUnlock(Boolean value) { }
	// RVA: 0x3132e4c VA: 0x759574ae4c
	public String get_unlockHint() { }
	// RVA: 0x3130cfc VA: 0x7595748cfc
	public Void LoadData(String actId, ActMultiV3MatchPosData matchPosData) { }
	// RVA: 0x3131bf4 VA: 0x7595749bf4
	public Void UpdateUnlockStatus(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3130c8c VA: 0x7595748c8c
	public Void .ctor() { }
}
```