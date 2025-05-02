# CheckContainsCardBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckContainsCardBuff : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f08e60 VA: 0x7594520e60
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f08ec8 VA: 0x7594520ec8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f09094 VA: 0x7594521094
	public Void .ctor() { }
}
```