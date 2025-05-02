# AssignBuffCountIntoBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _buffKey`

- `String _stackCountKey`

- `Int32 _stackCountPeeling`

- `Boolean _getStackCountFromFirstBuff`

- `Boolean _showOverrideWarning`

- `Boolean _checkBuffSource`

- `ActionTargetType _sourceType`


## Properties

- `Boolean checkBuffSource`


## Methods

- `Boolean get_checkBuffSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignBuffCountIntoBlackboard : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _buffKey; // 0x18
	private String _stackCountKey; // 0x20
	private Int32 _stackCountPeeling; // 0x28
	private Boolean _getStackCountFromFirstBuff; // 0x2c
	private Boolean _showOverrideWarning; // 0x2d
	private Boolean _checkBuffSource; // 0x2e
	private ActionTargetType _sourceType; // 0x30
	private static DelegateBridge __Hotfix0_get_checkBuffSource; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean checkBuffSource { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1eecb58 VA: 0x7594504b58
	public Boolean get_checkBuffSource() { }
	// RVA: 0x1eecbc0 VA: 0x7594504bc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eecc28 VA: 0x7594504c28
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eece44 VA: 0x7594504e44
	public Void .ctor() { }
}
```