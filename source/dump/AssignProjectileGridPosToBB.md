# AssignProjectileGridPosToBB

**Namespace:** ` `


## Fields

- `String _rowKey`

- `String _colKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignProjectileGridPosToBB : ActionNode
{
	private String _rowKey; // 0x10
	private String _colKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef477c VA: 0x759450c77c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef47e4 VA: 0x759450c7e4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef4908 VA: 0x759450c908
	public Void .ctor() { }
}
```