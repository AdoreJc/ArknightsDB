# EnableShadowController

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _enabled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnableShadowController : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	public Boolean _enabled; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1257c VA: 0x759452a57c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f125e4 VA: 0x759452a5e4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f127a4 VA: 0x759452a7a4
	public Void .ctor() { }
}
```