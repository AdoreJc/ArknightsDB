# ActMultiV3DifficultyIconViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3MapDiffType <diffType>k__BackingField`

- `String <diffName>k__BackingField`


## Properties

- `ActMultiV3MapDiffType diffType`

- `String diffName`


## Methods

- `ActMultiV3MapDiffType get_diffType()`

- `Void set_diffType(ActMultiV3MapDiffType)`

- `String get_diffName()`

- `Void set_diffName(String)`

- `Void Load(String, ActMultiV3MapDiffType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3DifficultyIconViewModel : IHotfixable
{
	private ActMultiV3MapDiffType <diffType>k__BackingField; // 0x10
	private String <diffName>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_diffType; // 0x0
	private static DelegateBridge __Hotfix0_set_diffType; // 0x8
	private static DelegateBridge __Hotfix0_get_diffName; // 0x10
	private static DelegateBridge __Hotfix0_set_diffName; // 0x18
	private static DelegateBridge __Hotfix0_Load; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public ActMultiV3MapDiffType diffType { get; set; }
	public String diffName { get; set; }

	// RVA: 0x30e3814 VA: 0x75956fb814
	public ActMultiV3MapDiffType get_diffType() { }
	// RVA: 0x30e3a90 VA: 0x75956fba90
	private Void set_diffType(ActMultiV3MapDiffType value) { }
	// RVA: 0x30e387c VA: 0x75956fb87c
	public String get_diffName() { }
	// RVA: 0x30e3b0c VA: 0x75956fbb0c
	private Void set_diffName(String value) { }
	// RVA: 0x30e3b90 VA: 0x75956fbb90
	public Void Load(String actId, ActMultiV3MapDiffType difficultyType) { }
	// RVA: 0x30e3c98 VA: 0x75956fbc98
	public Void .ctor() { }
}
```