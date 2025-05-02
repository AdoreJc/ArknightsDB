# ActMultiV3SquadEffectSelectStateBean

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadEffectSelectProp m_prop`

- `String <actId>k__BackingField`

- `ActMultiV3MapModeType <modeType>k__BackingField`


## Properties

- `String actId`

- `ActMultiV3MapModeType modeType`

- `ActMultiV3SquadEffectSelectProp prop`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `ActMultiV3MapModeType get_modeType()`

- `Void set_modeType(ActMultiV3MapModeType)`

- `ActMultiV3SquadEffectSelectProp get_prop()`

- `Void SetActIdAndSquadMode(String, ActMultiV3MapModeType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectSelectStateBean : IStateBean, IHotfixable
{
	private ActMultiV3SquadEffectSelectProp m_prop; // 0x10
	private String <actId>k__BackingField; // 0x18
	private ActMultiV3MapModeType <modeType>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_modeType; // 0x10
	private static DelegateBridge __Hotfix0_set_modeType; // 0x18
	private static DelegateBridge __Hotfix0_get_prop; // 0x20
	private static DelegateBridge __Hotfix0_SetActIdAndSquadMode; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String actId { get; set; }
	public ActMultiV3MapModeType modeType { get; set; }
	public ActMultiV3SquadEffectSelectProp prop { get; }

	// RVA: 0x313a140 VA: 0x7595752140
	public String get_actId() { }
	// RVA: 0x313a1a8 VA: 0x75957521a8
	private Void set_actId(String value) { }
	// RVA: 0x313a22c VA: 0x759575222c
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x313a294 VA: 0x7595752294
	private Void set_modeType(ActMultiV3MapModeType value) { }
	// RVA: 0x313a310 VA: 0x7595752310
	public ActMultiV3SquadEffectSelectProp get_prop() { }
	// RVA: 0x313a378 VA: 0x7595752378
	public Void SetActIdAndSquadMode(String actId, ActMultiV3MapModeType modeType) { }
	// RVA: 0x313a40c VA: 0x759575240c
	public Void .ctor() { }
}
```