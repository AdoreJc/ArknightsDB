# TargetHpRatioCompareToValValidator

**Namespace:** `Torappu.Battle`


## Fields

- `Single _defaultValue`

- `String _hpRatioKey`

- `CompareType _type`

- `FP m_hpRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TargetHpRatioCompareToValValidator : TargetValidator
{
	private Single _defaultValue; // 0x8c
	private String _hpRatioKey; // 0x90
	private CompareType _type; // 0x98
	private FP m_hpRatio; // 0xa0


	// RVA: 0x1bdbd60 VA: 0x75941f3d60
	public override Void SetData(Entity owner, Blackboard blackboard, Boolean ignoreTargetSide) { }
	// RVA: 0x1bdbe10 VA: 0x75941f3e10
	public override Boolean Validate(Entity target) { }
	// RVA: 0x1bdbef0 VA: 0x75941f3ef0
	public Void .ctor() { }
}
```