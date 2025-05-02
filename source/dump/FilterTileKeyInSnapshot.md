# FilterTileKeyInSnapshot

**Namespace:** ` `


## Fields

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterTileKeyInSnapshot : ActionNode
{
	private String _key; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f617d4 VA: 0x75945797d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6183c VA: 0x759457983c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f61944 VA: 0x7594579944
	public Void .ctor() { }
}
```