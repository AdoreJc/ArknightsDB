# AmmoSkillCountModifier

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _modifyMaxCount`

- `Boolean _restoreMaxCount`

- `String _addCountBBKey`

- `Int32 _addCount`

- `Boolean _recoverEventCount`

- `String _recoverCountBBKey`

- `Int32 _recoverCount`


## Properties

- `Boolean addMaxCount`


## Methods

- `Boolean get_addMaxCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AmmoSkillCountModifier : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _modifyMaxCount; // 0x14
	private Boolean _restoreMaxCount; // 0x15
	private String _addCountBBKey; // 0x18
	private Int32 _addCount; // 0x20
	private Boolean _recoverEventCount; // 0x24
	private String _recoverCountBBKey; // 0x28
	private Int32 _recoverCount; // 0x30
	private static DelegateBridge __Hotfix0_get_addMaxCount; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean addMaxCount { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f8e544 VA: 0x75945a6544
	private Boolean get_addMaxCount() { }
	// RVA: 0x1f8e5c4 VA: 0x75945a65c4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8e62c VA: 0x75945a662c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8e8f0 VA: 0x75945a68f0
	public Void .ctor() { }
}
```