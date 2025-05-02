# AutoChessFilterProfessionById

**Namespace:** ` `


## Fields

- `Boolean _byblackboardProfession`


## Properties

- `ProfessionCategory professionGroup`


## Methods

- `ProfessionCategory get_professionGroup()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterProfessionById : ActionNode
{
	private ProfessionCategory[] _profession; // 0x10
	private Boolean _byblackboardProfession; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_professionGroup; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	private ProfessionCategory professionGroup { get; }

	// RVA: 0x1ee2490 VA: 0x75944fa490
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee24f8 VA: 0x75944fa4f8
	private ProfessionCategory get_professionGroup() { }
	// RVA: 0x1ee25b0 VA: 0x75944fa5b0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee2864 VA: 0x75944fa864
	public Void .ctor() { }
}
```