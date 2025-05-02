# AtkScaleUp

**Namespace:** ` `


## Fields

- `Boolean _filterApplyWay`

- `SourceApplyWay _applyWay`

- `Single _defaultValue`

- `Boolean _filterNoneApplyWay`

- `Boolean _cancelIfAtkScaleZero`

- `String _atkScaleKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AtkScaleUp : ActionNode
{
	private Boolean _filterApplyWay; // 0x10
	private SourceApplyWay _applyWay; // 0x14
	private Single _defaultValue; // 0x18
	private Boolean _filterNoneApplyWay; // 0x1c
	private Boolean _cancelIfAtkScaleZero; // 0x1d
	private String _atkScaleKey; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f40b20 VA: 0x7594558b20
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f40b88 VA: 0x7594558b88
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f40d88 VA: 0x7594558d88
	public Void .ctor() { }
}
```