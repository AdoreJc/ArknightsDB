# CheckManhattanDistance

**Namespace:** ` `


## Fields

- `Int32 _minDist`

- `Int32 _maxDist`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckManhattanDistance : ActionNode
{
	private Int32 _minDist; // 0x10
	private Int32 _maxDist; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f184dc VA: 0x75945304dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f18544 VA: 0x7594530544
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f186e4 VA: 0x75945306e4
	public Void .ctor() { }
}
```