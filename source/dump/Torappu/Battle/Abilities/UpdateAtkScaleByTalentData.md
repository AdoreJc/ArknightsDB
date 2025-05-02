# UpdateAtkScaleByTalentData

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _defaultValue`

- `String _talentKey`

- `Boolean _overwrite`

- `TargetValidator _ownerValidator`

- `FP m_atkScale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UpdateAtkScaleByTalentData : Behaviour
{
	private Single _defaultValue; // 0x20
	private String _talentKey; // 0x28
	private Boolean _overwrite; // 0x30
	private TargetValidator _ownerValidator; // 0x38
	private FP m_atkScale; // 0x40


	// RVA: 0x1ed3890 VA: 0x75944eb890
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed3b90 VA: 0x75944ebb90
	public override Void OnCastStart() { }
	// RVA: 0x1ed3ce4 VA: 0x75944ebce4
	public Void .ctor() { }
}
```