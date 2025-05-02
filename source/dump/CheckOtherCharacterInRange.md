# CheckOtherCharacterInRange

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _rangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckOtherCharacterInRange : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String _rangeId; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2e690 VA: 0x7594546690
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2e6f8 VA: 0x75945466f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2e9d4 VA: 0x75945469d4
	public Void .ctor() { }
}
```