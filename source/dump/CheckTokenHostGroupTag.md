# CheckTokenHostGroupTag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _filterTag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTokenHostGroupTag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _filterTag; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1b1c0 VA: 0x75945331c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1b228 VA: 0x7594533228
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1b478 VA: 0x7594533478
	public Void .ctor() { }
}
```