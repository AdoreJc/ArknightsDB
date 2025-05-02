# LegionModeOnlyModifyCharLevelDefaultAddCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Int32 _addValue`

- `String _addKey`

- `Boolean _resetToDefault`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyModifyCharLevelDefaultAddCnt : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Int32 _addValue; // 0x14
	private String _addKey; // 0x18
	private Boolean _resetToDefault; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f64e9c VA: 0x759457ce9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f64f04 VA: 0x759457cf04
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f65118 VA: 0x759457d118
	public Void .ctor() { }
}
```