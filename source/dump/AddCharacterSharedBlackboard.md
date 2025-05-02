# AddCharacterSharedBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _blackboardKey`

- `Single _value`

- `Boolean _isOverwrite`

- `Boolean _useValueKey`

- `String _valueKey`


## Properties

- `Boolean useValueKey`


## Methods

- `Boolean get_useValueKey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddCharacterSharedBlackboard : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _blackboardKey; // 0x18
	private Single _value; // 0x20
	private Boolean _isOverwrite; // 0x24
	private Boolean _useValueKey; // 0x25
	private String _valueKey; // 0x28
	private static DelegateBridge __Hotfix0_get_useValueKey; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean useValueKey { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f133d0 VA: 0x759452b3d0
	public Boolean get_useValueKey() { }
	// RVA: 0x1f13438 VA: 0x759452b438
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f134a0 VA: 0x759452b4a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f136c4 VA: 0x759452b6c4
	public Void .ctor() { }
}
```