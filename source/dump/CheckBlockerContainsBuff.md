# CheckBlockerContainsBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _isAND`

- `Boolean _loadFromBlackboard`

- `Boolean _checkBuffSource`

- `ActionTargetType _buffSourceType`

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
public class CheckBlockerContainsBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _buffKeys; // 0x18
	private Boolean _isAND; // 0x20
	private Boolean _loadFromBlackboard; // 0x21
	private Boolean _checkBuffSource; // 0x22
	private ActionTargetType _buffSourceType; // 0x24
	private Boolean m_result; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_checkBuffSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0__CheckContainsBuffInternal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	public Boolean checkBuffSource { get; }

	// RVA: 0x1f1d234 VA: 0x7594535234
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1d29c VA: 0x759453529c
	public Boolean get_checkBuffSource() { }
	// RVA: 0x1f1d304 VA: 0x7594535304
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1d660 VA: 0x7594535660
	private Boolean _CheckContainsBuffInternal(String buffKey, Entity target, Entity source) { }
	// RVA: 0x1f1d734 VA: 0x7594535734
	public Void .ctor() { }
}
```