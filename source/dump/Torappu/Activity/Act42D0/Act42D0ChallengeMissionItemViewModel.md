# Act42D0ChallengeMissionItemViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0ChallengeMissionData missionData`

- `Boolean <isCompleted>k__BackingField`


## Properties

- `Boolean isCompleted`


## Methods

- `Boolean get_isCompleted()`

- `Void set_isCompleted(Boolean)`

- `Void SetIsCompleted(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeMissionItemViewModel : IHotfixable
{
	public Act42D0ChallengeMissionData missionData; // 0x10
	private Boolean <isCompleted>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x0
	private static DelegateBridge __Hotfix0_set_isCompleted; // 0x8
	private static DelegateBridge __Hotfix0_SetIsCompleted; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isCompleted { get; set; }

	// RVA: 0x3209310 VA: 0x7595821310
	public Boolean get_isCompleted() { }
	// RVA: 0x320af54 VA: 0x7595822f54
	private Void set_isCompleted(Boolean value) { }
	// RVA: 0x320ae28 VA: 0x7595822e28
	public Void SetIsCompleted(Boolean isCompleted) { }
	// RVA: 0x320adb8 VA: 0x7595822db8
	public Void .ctor() { }
}
```