# RoguelikeLogExp

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `ExpType _expType`

- `String _expKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeLogExp : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ExpType _expType; // 0x14
	private String _expKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7f2a0 VA: 0x75945972a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7f308 VA: 0x7594597308
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7f574 VA: 0x7594597574
	public Void .ctor() { }
}
```