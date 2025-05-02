# LegionModeOnlyAddProfessionLevel

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _levelCnt`

- `Boolean _specifyProfessionCategory`

- `ProfessionCategory _professionCategory`

- `Boolean _addSourceProfessionLevel`

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyAddProfessionLevel : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _levelCnt; // 0x14
	private Boolean _specifyProfessionCategory; // 0x18
	private ProfessionCategory _professionCategory; // 0x1c
	private Boolean _addSourceProfessionLevel; // 0x20
	private ActionTargetType _sourceType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6623c VA: 0x759457e23c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f662a4 VA: 0x759457e2a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f665b4 VA: 0x759457e5b4
	public Void .ctor() { }
}
```