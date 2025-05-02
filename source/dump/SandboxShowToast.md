# SandboxShowToast

**Namespace:** ` `


## Fields

- `Single _lastTime`

- `Boolean _useStringTableKey`

- `Boolean _useNameAsParmInMap`

- `ActionTargetType _target`

- `String _toastKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxShowToast : ActionNode
{
	private Single _lastTime; // 0x10
	private Boolean _useStringTableKey; // 0x14
	private Boolean _useNameAsParmInMap; // 0x15
	private ActionTargetType _target; // 0x18
	private String _toastKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8be30 VA: 0x75945a3e30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8be98 VA: 0x75945a3e98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8c1d0 VA: 0x75945a41d0
	public Void .ctor() { }
}
```