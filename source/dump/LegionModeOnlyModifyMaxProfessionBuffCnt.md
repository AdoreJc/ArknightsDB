# LegionModeOnlyModifyMaxProfessionBuffCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Int32 _addValue`

- `Boolean _resetToDefault`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyModifyMaxProfessionBuffCnt : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Int32 _addValue; // 0x14
	private Boolean _resetToDefault; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f64660 VA: 0x759457c660
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f646c8 VA: 0x759457c6c8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f648f0 VA: 0x759457c8f0
	public Void .ctor() { }
}
```