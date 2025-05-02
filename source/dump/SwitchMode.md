# SwitchMode

**Namespace:** ` `


## Fields

- `Int32 _modeIndex`

- `Boolean _loadModeFromBlackboard`

- `Boolean _restoreDefault`

- `Boolean _restartFSM`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchMode : ActionNode
{
	private Int32 _modeIndex; // 0x10
	private Boolean _loadModeFromBlackboard; // 0x14
	private Boolean _restoreDefault; // 0x15
	private Boolean _restartFSM; // 0x16
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0dac4 VA: 0x7594525ac4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0db2c VA: 0x7594525b2c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0dd00 VA: 0x7594525d00
	public Void .ctor() { }
}
```