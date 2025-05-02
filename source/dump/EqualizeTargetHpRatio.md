# EqualizeTargetHpRatio

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `ActionTargetType _target`

- `Boolean _useSourceHpRatio`

- `Single _hpRatio`

- `Boolean _skipModifierEvent`


## Properties

- `Boolean useSourceHpRatio`


## Methods

- `Boolean get_useSourceHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EqualizeTargetHpRatio : ActionNode
{
	private ActionTargetType _source; // 0x10
	private ActionTargetType _target; // 0x14
	private Boolean _useSourceHpRatio; // 0x18
	private Single _hpRatio; // 0x1c
	private Boolean _skipModifierEvent; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_useSourceHpRatio; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	private Boolean useSourceHpRatio { get; }

	// RVA: 0x1fccb48 VA: 0x75945e4b48
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fccbb0 VA: 0x75945e4bb0
	private Boolean get_useSourceHpRatio() { }
	// RVA: 0x1fccc18 VA: 0x75945e4c18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fccf10 VA: 0x75945e4f10
	public Void .ctor() { }
}
```