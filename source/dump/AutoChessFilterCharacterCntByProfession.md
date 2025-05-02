# AutoChessFilterCharacterCntByProfession

**Namespace:** ` `


## Fields

- `Int32 _compareCnt`

- `CompareType _condType`

- `String _blackboardKey`

- `Boolean _byblackboardProfession`


## Properties

- `ProfessionCategory professionGroup`


## Methods

- `ProfessionCategory get_professionGroup()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterCharacterCntByProfession : ActionNode
{
	private ProfessionCategory[] _profession; // 0x10
	private Int32 _compareCnt; // 0x18
	private CompareType _condType; // 0x1c
	private String _blackboardKey; // 0x20
	private Boolean _byblackboardProfession; // 0x28
	private static DelegateBridge __Hotfix0_get_professionGroup; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ProfessionCategory professionGroup { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1ee28d4 VA: 0x75944fa8d4
	private ProfessionCategory get_professionGroup() { }
	// RVA: 0x1ee298c VA: 0x75944fa98c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee29f4 VA: 0x75944fa9f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee2d3c VA: 0x75944fad3c
	public Void .ctor() { }
}
```