# OriginCostTargetValidator

**Namespace:** `Torappu.Battle`


## Fields

- `String _blackboardPrefix`

- `CompareType _compareType`

- `Int32 m_conditonCost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class OriginCostTargetValidator : TargetValidator
{
	private String _blackboardPrefix; // 0x90
	private CompareType _compareType; // 0x98
	private Int32 m_conditonCost; // 0x9c


	// RVA: 0x1bdb698 VA: 0x75941f3698
	public override Void SetData(Entity owner, Blackboard blackboard, Boolean ignoreTargetSide) { }
	// RVA: 0x1bdb7d0 VA: 0x75941f37d0
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bdb9c0 VA: 0x75941f39c0
	public Void .ctor() { }
}
```