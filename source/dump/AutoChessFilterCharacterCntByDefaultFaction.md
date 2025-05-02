# AutoChessFilterCharacterCntByDefaultFaction

**Namespace:** ` `


## Fields

- `Int32 _compareCnt`

- `CompareType _condType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterCharacterCntByDefaultFaction : ActionNode
{
	private Int32 _compareCnt; // 0x10
	private CompareType _condType; // 0x14
	private String _blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee3258 VA: 0x75944fb258
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee32c0 VA: 0x75944fb2c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee353c VA: 0x75944fb53c
	public Void .ctor() { }
}
```