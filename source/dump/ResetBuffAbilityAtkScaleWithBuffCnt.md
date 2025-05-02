# ResetBuffAbilityAtkScaleWithBuffCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _defaultValue`

- `String _factorValue`

- `String _buffKey`

- `Boolean _overwriteAtkScale`

- `Boolean _checkBuffSource`

- `ActionTargetType _buffSourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ResetBuffAbilityAtkScaleWithBuffCnt : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _defaultValue; // 0x18
	private String _factorValue; // 0x20
	private String _buffKey; // 0x28
	private Boolean _overwriteAtkScale; // 0x30
	private Boolean _checkBuffSource; // 0x31
	private ActionTargetType _buffSourceType; // 0x34
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f419f8 VA: 0x75945599f8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f41a60 VA: 0x7594559a60
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f41da8 VA: 0x7594559da8
	public Void .ctor() { }
}
```