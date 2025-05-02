# ActMultiV3MatchModeGroupModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int64 m_unlockTs`

- `ActMultiV3MapModeType <modeType>k__BackingField`

- `String <color>k__BackingField`

- `String <name>k__BackingField`

- `Int32 <sortId>k__BackingField`


## Properties

- `ActMultiV3MapModeType modeType`

- `String color`

- `String name`

- `Int32 sortId`


## Methods

- `ActMultiV3MapModeType get_modeType()`

- `Void set_modeType(ActMultiV3MapModeType)`

- `String get_color()`

- `Void set_color(String)`

- `String get_name()`

- `Void set_name(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `Boolean TryGetDiffModel(String, out)`

- `Boolean FindNearestLockStage(Int64, out)`

- `Boolean CheckModeGroupUnlock(Int64, out)`

- `Boolean TryGetDiffModel(ActMultiV3MapDiffType, out)`

- `Boolean CheckDiffSelect(List`1)`

- `Void AddDefaultSelectToList(Int64, List`1)`

- `Void LoadData(String, ActMultiV3Data, ActMultiV3MapModeData)`

- `Void UpdatePlayerData()`

- `Void UpdateUnlockStatus(ActMultiV3QuickMatchModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchModeGroupModel : IHotfixable
{
	private Dictionary`2 m_diffDict; // 0x10
	private Int64 m_unlockTs; // 0x18
	private ActMultiV3MapModeType <modeType>k__BackingField; // 0x20
	private String <color>k__BackingField; // 0x28
	private String <name>k__BackingField; // 0x30
	private Int32 <sortId>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_modeType; // 0x0
	private static DelegateBridge __Hotfix0_set_modeType; // 0x8
	private static DelegateBridge __Hotfix0_get_color; // 0x10
	private static DelegateBridge __Hotfix0_set_color; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_set_name; // 0x28
	private static DelegateBridge __Hotfix0_get_sortId; // 0x30
	private static DelegateBridge __Hotfix0_set_sortId; // 0x38
	private static DelegateBridge __Hotfix0_TryGetDiffModel; // 0x40
	private static DelegateBridge __Hotfix0_FindNearestLockStage; // 0x48
	private static DelegateBridge __Hotfix0_CheckModeGroupUnlock; // 0x50
	private static DelegateBridge __Hotfix1_TryGetDiffModel; // 0x58
	private static DelegateBridge __Hotfix0_CheckDiffSelect; // 0x60
	private static DelegateBridge __Hotfix0_AddDefaultSelectToList; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x78
	private static DelegateBridge __Hotfix0_UpdateUnlockStatus; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public ActMultiV3MapModeType modeType { get; set; }
	public String color { get; set; }
	public String name { get; set; }
	public Int32 sortId { get; set; }

	// RVA: 0x312f130 VA: 0x7595747130
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x3132ff8 VA: 0x759574aff8
	private Void set_modeType(ActMultiV3MapModeType value) { }
	// RVA: 0x3133074 VA: 0x759574b074
	public String get_color() { }
	// RVA: 0x31330dc VA: 0x759574b0dc
	private Void set_color(String value) { }
	// RVA: 0x3133160 VA: 0x759574b160
	public String get_name() { }
	// RVA: 0x31331c8 VA: 0x759574b1c8
	private Void set_name(String value) { }
	// RVA: 0x3132854 VA: 0x759574a854
	public Int32 get_sortId() { }
	// RVA: 0x313324c VA: 0x759574b24c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x31313c0 VA: 0x75957493c0
	public Boolean TryGetDiffModel(String modeId, out ActMultiV3MatchModeDiffModel diffModel) { }
	// RVA: 0x31332c8 VA: 0x759574b2c8
	public Boolean FindNearestLockStage(Int64 currTs, out String unlockTimeStr) { }
	// RVA: 0x3133608 VA: 0x759574b608
	public Boolean CheckModeGroupUnlock(Int64 currTs, out String unlockHint) { }
	// RVA: 0x31316b0 VA: 0x75957496b0
	public Boolean TryGetDiffModel(ActMultiV3MapDiffType diffType, out ActMultiV3MatchModeDiffModel targetModel) { }
	// RVA: 0x312f198 VA: 0x7595747198
	public Boolean CheckDiffSelect(List`1 selectList) { }
	// RVA: 0x3132348 VA: 0x759574a348
	public Void AddDefaultSelectToList(Int64 currTs, List`1 selectList) { }
	// RVA: 0x3130ea8 VA: 0x7595748ea8
	public Void LoadData(String actId, ActMultiV3Data actData, ActMultiV3MapModeData mapModeData) { }
	// RVA: 0x3131d6c VA: 0x7595749d6c
	public Void UpdatePlayerData() { }
	// RVA: 0x31319f4 VA: 0x75957499f4
	public Void UpdateUnlockStatus(ActMultiV3QuickMatchModel matchModel) { }
	// RVA: 0x3130de4 VA: 0x7595748de4
	public Void .ctor() { }
}
```