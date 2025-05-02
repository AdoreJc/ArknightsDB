# CheckContainsBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean isAND`

- `Boolean _loadFromBlackboard`

- `Boolean _checkBuffSource`

- `ActionTargetType _buffSourceType`

- `Boolean _checkSourceHost`

- `Boolean m_result`


## Properties

- `Boolean checkBuffSource`


## Methods

- `Boolean get_checkBuffSource()`

- `Boolean _CheckContainsBuffInternal(String, Entity, Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckContainsBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _buffKeys; // 0x18
	private Boolean isAND; // 0x20
	private Boolean _loadFromBlackboard; // 0x21
	private Boolean _checkBuffSource; // 0x22
	private ActionTargetType _buffSourceType; // 0x24
	private Boolean _checkSourceHost; // 0x28
	private Boolean m_result; // 0x29
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_checkBuffSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__CheckContainsBuffInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public Boolean checkBuffSource { get; }

	// RVA: 0x1f1c844 VA: 0x7594534844
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1c8ac VA: 0x75945348ac
	public Boolean get_checkBuffSource() { }
	// RVA: 0x1f1c914 VA: 0x7594534914
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1cbf0 VA: 0x7594534bf0
	private Boolean _CheckContainsBuffInternal(String buffKey, Entity target, Entity source) { }
	// RVA: 0x1f1cdb0 VA: 0x7594534db0
	public Void .ctor() { }
}
```