# Act31SideCheckPumpBackTileValid

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideCheckPumpBackTileValid : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edb3a8 VA: 0x75944f33a8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edb410 VA: 0x75944f3410
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edb648 VA: 0x75944f3648
	public Void .ctor() { }
}
```