# HasTileAlongDirection

**Namespace:** ` `


## Fields

- `Boolean _isGravity`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HasTileAlongDirection : ActionNode
{
	private Boolean _isGravity; // 0x10
	private List`1 _tileKeyList; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2edf4 VA: 0x7594546df4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2ee5c VA: 0x7594546e5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2f138 VA: 0x7594547138
	public Void .ctor() { }
}
```