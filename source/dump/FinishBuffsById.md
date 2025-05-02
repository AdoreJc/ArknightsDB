# FinishBuffsById

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`

- `ActionTargetType _targetType`

- `Boolean _checkBuffSource`

- `ActionTargetType _sourceType`

- `Boolean _alsoClearNullSource`

- `Boolean _finishHostBuff`


## Properties

- `Boolean checkBuffSource`


## Methods

- `Boolean get_checkBuffSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishBuffsById : ActionNode
{
	private String _buffKey; // 0x10
	private Boolean _loadFromBlackboard; // 0x18
	private Boolean _decCntIfStack; // 0x19
	private Boolean _updateOverrideMap; // 0x1a
	private ActionTargetType _targetType; // 0x1c
	private Boolean _checkBuffSource; // 0x20
	private ActionTargetType _sourceType; // 0x24
	private Boolean _alsoClearNullSource; // 0x28
	private Boolean _finishHostBuff; // 0x29
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_checkBuffSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	private Boolean checkBuffSource { get; }

	// RVA: 0x1ef6c5c VA: 0x759450ec5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef6cc4 VA: 0x759450ecc4
	private Boolean get_checkBuffSource() { }
	// RVA: 0x1ef6d2c VA: 0x759450ed2c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef6fd8 VA: 0x759450efd8
	public Void .ctor() { }
}
```