# CalculateTraitAbilityBlackboard

**Namespace:** ` `


## Fields

- `String _addBlackboardKey`

- `Boolean _useTraitBBToAdd`

- `Boolean _isSub`

- `String _fromBlackboardKey`

- `String _targetBlackboardKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CalculateTraitAbilityBlackboard : ActionNode
{
	private String _addBlackboardKey; // 0x10
	private Boolean _useTraitBBToAdd; // 0x18
	private Boolean _isSub; // 0x19
	private String _fromBlackboardKey; // 0x20
	private String _targetBlackboardKey; // 0x28
	private ActionTargetType _targetType; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef15ac VA: 0x75945095ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef1614 VA: 0x7594509614
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef18d4 VA: 0x75945098d4
	public Void .ctor() { }
}
```