# ActMultiV3SquadGroupModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String <actId>k__BackingField`

- `String <selectSquadId>k__BackingField`

- `String <squadLockHintStr>k__BackingField`


## Properties

- `String actId`

- `String selectSquadId`

- `String squadLockHintStr`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `String get_selectSquadId()`

- `Void set_selectSquadId(String)`

- `String get_squadLockHintStr()`

- `Void set_squadLockHintStr(String)`

- `ActMultiV3SquadModel FindCurrSquadModel()`

- `ActMultiV3SquadModel FindSquadModel(String)`

- `ActMultiV3SquadModel FindSquadModel(ActMultiV3MapModeType)`

- `ActMultiV3SquadModel _FindSquadModel(String)`

- `Void LoadData(String)`

- `String _FindInitSquadId()`

- `Boolean TrySelectSquad(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadGroupModel : IHotfixable
{
	private List`1 m_squadList; // 0x10
	private String <actId>k__BackingField; // 0x18
	private String <selectSquadId>k__BackingField; // 0x20
	private String <squadLockHintStr>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectSquadId; // 0x10
	private static DelegateBridge __Hotfix0_set_selectSquadId; // 0x18
	private static DelegateBridge __Hotfix0_get_squadLockHintStr; // 0x20
	private static DelegateBridge __Hotfix0_set_squadLockHintStr; // 0x28
	private static DelegateBridge __Hotfix0_get_squadList; // 0x30
	private static DelegateBridge __Hotfix0_FindCurrSquadModel; // 0x38
	private static DelegateBridge __Hotfix0_FindSquadModel; // 0x40
	private static DelegateBridge __Hotfix1_FindSquadModel; // 0x48
	private static DelegateBridge __Hotfix0__FindSquadModel; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0__FindInitSquadId; // 0x60
	private static DelegateBridge __Hotfix0_TrySelectSquad; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String actId { get; set; }
	public String selectSquadId { get; set; }
	public String squadLockHintStr { get; set; }
	public List`1 squadList { get; }

	// RVA: 0x313ded4 VA: 0x7595755ed4
	public String get_actId() { }
	// RVA: 0x3140524 VA: 0x7595758524
	private Void set_actId(String value) { }
	// RVA: 0x313e664 VA: 0x7595756664
	public String get_selectSquadId() { }
	// RVA: 0x31405a8 VA: 0x75957585a8
	private Void set_selectSquadId(String value) { }
	// RVA: 0x313f874 VA: 0x7595757874
	public String get_squadLockHintStr() { }
	// RVA: 0x314062c VA: 0x759575862c
	private Void set_squadLockHintStr(String value) { }
	// RVA: 0x31406b0 VA: 0x75957586b0
	public List`1 get_squadList() { }
	// RVA: 0x313ef00 VA: 0x7595756f00
	public ActMultiV3SquadModel FindCurrSquadModel() { }
	// RVA: 0x313c4a8 VA: 0x75957544a8
	public ActMultiV3SquadModel FindSquadModel(String squadId) { }
	// RVA: 0x313ce6c VA: 0x7595754e6c
	public ActMultiV3SquadModel FindSquadModel(ActMultiV3MapModeType modeType) { }
	// RVA: 0x3140718 VA: 0x7595758718
	private ActMultiV3SquadModel _FindSquadModel(String squadId) { }
	// RVA: 0x313da04 VA: 0x7595755a04
	public Void LoadData(String actId) { }
	// RVA: 0x3140af0 VA: 0x7595758af0
	private String _FindInitSquadId() { }
	// RVA: 0x313f9c0 VA: 0x75957579c0
	public Boolean TrySelectSquad(String squadId) { }
	// RVA: 0x3140ddc VA: 0x7595758ddc
	public Void .ctor() { }
}
```