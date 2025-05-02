# EmitProjectileFromManagedProjectiles

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmitProjectileFromManagedProjectiles : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f78108 VA: 0x7594590108
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f78170 VA: 0x7594590170
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f784f0 VA: 0x75945904f0
	public Void .ctor() { }
}
```