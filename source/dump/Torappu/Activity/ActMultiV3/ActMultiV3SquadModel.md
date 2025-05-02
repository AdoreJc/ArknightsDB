# ActMultiV3SquadModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int64 m_unlockTs`

- `Int32 m_leastNeedCharCnt`

- `String m_actId`

- `ActMultiV3PriClassModel m_highPriModel`

- `ActMultiV3PriClassModel m_lowPriModel`

- `String <squadId>k__BackingField`

- `String <name>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `ActMultiV3MapModeType <modeType>k__BackingField`

- `String <effectIconId>k__BackingField`


## Properties

- `String squadId`

- `String name`

- `Int32 sortId`

- `ActMultiV3MapModeType modeType`

- `String effectIconId`

- `ActMultiV3PriClassModel highPriModel`

- `ActMultiV3PriClassModel lowPriModel`


## Methods

- `String get_squadId()`

- `Void set_squadId(String)`

- `String get_name()`

- `Void set_name(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `ActMultiV3MapModeType get_modeType()`

- `Void set_modeType(ActMultiV3MapModeType)`

- `String get_effectIconId()`

- `Void set_effectIconId(String)`

- `ActMultiV3PriClassModel get_highPriModel()`

- `ActMultiV3PriClassModel get_lowPriModel()`

- `Int32 GetPriClassMaxCnt(ActMultiV3IdentityType)`

- `Int32 GetTargetInstId(ActMultiV3IdentityType, String)`

- `Boolean CheckIfNewOpen()`

- `Void ConsumeNewOpenTrack()`

- `Boolean IsCharNumAdequate()`

- `Void LoadData(String, ActMultiV3Data, ActMultiV3SquadInfoData)`

- `Void UpdateEffectData()`

- `Void _UpdateEffectData()`

- `Boolean IsSquadUnlock()`

- `ActMultiV3PriClassModel _GetPriModel(ActMultiV3IdentityType)`

- `Void GenCharIdTypeDict(Dictionary`2)`

- `Void GenSelectCharList(ActMultiV3IdentityType, List`1)`

- `Void ApplySelectCharList(ActMultiV3IdentityType, List`1)`

- `Void UpdatePlayerData()`

- `Boolean CheckIfSquadChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadModel : IHotfixable
{
	private Int64 m_unlockTs; // 0x10
	private Int32 m_leastNeedCharCnt; // 0x18
	private String m_actId; // 0x20
	private ActMultiV3PriClassModel m_highPriModel; // 0x28
	private ActMultiV3PriClassModel m_lowPriModel; // 0x30
	private HashSet`1 m_tempCharInstSet; // 0x38
	private String <squadId>k__BackingField; // 0x40
	private String <name>k__BackingField; // 0x48
	private Int32 <sortId>k__BackingField; // 0x50
	private ActMultiV3MapModeType <modeType>k__BackingField; // 0x54
	private String <effectIconId>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_squadId; // 0x0
	private static DelegateBridge __Hotfix0_set_squadId; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_set_name; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_modeType; // 0x30
	private static DelegateBridge __Hotfix0_set_modeType; // 0x38
	private static DelegateBridge __Hotfix0_get_effectIconId; // 0x40
	private static DelegateBridge __Hotfix0_set_effectIconId; // 0x48
	private static DelegateBridge __Hotfix0_get_highPriModel; // 0x50
	private static DelegateBridge __Hotfix0_get_lowPriModel; // 0x58
	private static DelegateBridge __Hotfix0_GetPriClassMaxCnt; // 0x60
	private static DelegateBridge __Hotfix0_GetTargetInstId; // 0x68
	private static DelegateBridge __Hotfix0_CheckIfNewOpen; // 0x70
	private static DelegateBridge __Hotfix0_ConsumeNewOpenTrack; // 0x78
	private static DelegateBridge __Hotfix0_IsCharNumAdequate; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x88
	private static DelegateBridge __Hotfix0_UpdateEffectData; // 0x90
	private static DelegateBridge __Hotfix0__UpdateEffectData; // 0x98
	private static DelegateBridge __Hotfix0_IsSquadUnlock; // 0xa0
	private static DelegateBridge __Hotfix0__GetPriModel; // 0xa8
	private static DelegateBridge __Hotfix0_GenCharIdTypeDict; // 0xb0
	private static DelegateBridge __Hotfix0_GenSelectCharList; // 0xb8
	private static DelegateBridge __Hotfix0_ApplySelectCharList; // 0xc0
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xc8
	private static DelegateBridge __Hotfix0_CheckIfSquadChanged; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public String squadId { get; set; }
	public String name { get; set; }
	public Int32 sortId { get; set; }
	public ActMultiV3MapModeType modeType { get; set; }
	public String effectIconId { get; set; }
	public ActMultiV3PriClassModel highPriModel { get; }
	public ActMultiV3PriClassModel lowPriModel { get; }

	// RVA: 0x313f048 VA: 0x7595757048
	public String get_squadId() { }
	// RVA: 0x3140fcc VA: 0x7595758fcc
	private Void set_squadId(String value) { }
	// RVA: 0x3141050 VA: 0x7595759050
	public String get_name() { }
	// RVA: 0x31410b8 VA: 0x75957590b8
	private Void set_name(String value) { }
	// RVA: 0x3140f64 VA: 0x7595758f64
	public Int32 get_sortId() { }
	// RVA: 0x314113c VA: 0x759575913c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x313f670 VA: 0x7595757670
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x31411b8 VA: 0x75957591b8
	private Void set_modeType(ActMultiV3MapModeType value) { }
	// RVA: 0x3141234 VA: 0x7595759234
	public String get_effectIconId() { }
	// RVA: 0x314129c VA: 0x759575929c
	private Void set_effectIconId(String value) { }
	// RVA: 0x313fc3c VA: 0x7595757c3c
	public ActMultiV3PriClassModel get_highPriModel() { }
	// RVA: 0x313fca4 VA: 0x7595757ca4
	public ActMultiV3PriClassModel get_lowPriModel() { }
	// RVA: 0x313f308 VA: 0x7595757308
	public Int32 GetPriClassMaxCnt(ActMultiV3IdentityType idType) { }
	// RVA: 0x313f3c0 VA: 0x75957573c0
	public Int32 GetTargetInstId(ActMultiV3IdentityType idType, String charId) { }
	// RVA: 0x31413bc VA: 0x75957593bc
	public Boolean CheckIfNewOpen() { }
	// RVA: 0x3140d60 VA: 0x7595758d60
	public Void ConsumeNewOpenTrack() { }
	// RVA: 0x3140cc0 VA: 0x7595758cc0
	public Boolean IsCharNumAdequate() { }
	// RVA: 0x314096c VA: 0x759575896c
	public Void LoadData(String actId, ActMultiV3Data actData, ActMultiV3SquadInfoData squadInfo) { }
	// RVA: 0x313cf80 VA: 0x7595754f80
	public Void UpdateEffectData() { }
	// RVA: 0x3141450 VA: 0x7595759450
	private Void _UpdateEffectData() { }
	// RVA: 0x313f7d8 VA: 0x75957577d8
	public Boolean IsSquadUnlock() { }
	// RVA: 0x3141320 VA: 0x7595759320
	private ActMultiV3PriClassModel _GetPriModel(ActMultiV3IdentityType idType) { }
	// RVA: 0x313ef74 VA: 0x7595756f74
	public Void GenCharIdTypeDict(Dictionary`2 outputDict) { }
	// RVA: 0x313f0b0 VA: 0x75957570b0
	public Void GenSelectCharList(ActMultiV3IdentityType idType, List`1 outputList) { }
	// RVA: 0x313c528 VA: 0x7595754528
	public Void ApplySelectCharList(ActMultiV3IdentityType idType, List`1 selectedList) { }
	// RVA: 0x313cc8c VA: 0x7595754c8c
	public Void UpdatePlayerData() { }
	// RVA: 0x313fb28 VA: 0x7595757b28
	public Boolean CheckIfSquadChanged() { }
	// RVA: 0x3140844 VA: 0x7595758844
	public Void .ctor() { }
}
```