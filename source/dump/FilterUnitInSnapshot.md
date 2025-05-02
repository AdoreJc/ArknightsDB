# FilterUnitInSnapshot

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterUnitInSnapshot : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f619b4 VA: 0x75945799b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f61a1c VA: 0x7594579a1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f61bac VA: 0x7594579bac
	public Void .ctor() { }
}
```