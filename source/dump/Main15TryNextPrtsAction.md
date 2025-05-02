# Main15TryNextPrtsAction

**Namespace:** ` `


## Fields

- `Boolean _doNextWhenSuccess`

- `Boolean _forceNext`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Main15TryNextPrtsAction : ActionNode
{
	private Boolean _doNextWhenSuccess; // 0x10
	private Boolean _forceNext; // 0x11
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f70aac VA: 0x7594588aac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f70b14 VA: 0x7594588b14
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f70ccc VA: 0x7594588ccc
	public Void .ctor() { }
}
```