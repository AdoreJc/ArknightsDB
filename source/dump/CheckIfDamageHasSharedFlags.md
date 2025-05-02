# CheckIfDamageHasSharedFlags

**Namespace:** ` `


## Fields

- `SharedFlagIndex _sharedFlags`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckIfDamageHasSharedFlags : ActionNode
{
	private SharedFlagIndex _sharedFlags; // 0x10
	private Boolean _isUnset; // 0x12
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f169b4 VA: 0x759452e9b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16a1c VA: 0x759452ea1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f16b00 VA: 0x759452eb00
	public Void .ctor() { }
}
```