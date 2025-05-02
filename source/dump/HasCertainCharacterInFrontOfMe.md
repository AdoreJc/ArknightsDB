# HasCertainCharacterInFrontOfMe

**Namespace:** ` `


## Fields

- `String _characterKey`

- `ActionTargetType _source`

- `ActionTargetType _target`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HasCertainCharacterInFrontOfMe : ActionNode
{
	private String _characterKey; // 0x10
	private ActionTargetType _source; // 0x18
	private ActionTargetType _target; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9af50 VA: 0x75945b2f50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9afb8 VA: 0x75945b2fb8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9b298 VA: 0x75945b3298
	public Void .ctor() { }
}
```