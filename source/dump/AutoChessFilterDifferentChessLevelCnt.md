# AutoChessFilterDifferentChessLevelCnt

**Namespace:** ` `


## Fields

- `Int32 _compareCnt`

- `CompareType _condType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterDifferentChessLevelCnt : ActionNode
{
	private Int32 _compareCnt; // 0x10
	private CompareType _condType; // 0x14
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee2ddc VA: 0x75944faddc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee2e44 VA: 0x75944fae44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee31b8 VA: 0x75944fb1b8
	public Void .ctor() { }
}
```