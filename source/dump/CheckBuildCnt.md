# CheckBuildCnt

**Namespace:** ` `


## Fields

- `Int32 _checkBuildCnt`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckBuildCnt : ActionNode
{
	private Int32 _checkBuildCnt; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f234d8 VA: 0x759453b4d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f23540 VA: 0x759453b540
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f23794 VA: 0x759453b794
	public Void .ctor() { }
}
```