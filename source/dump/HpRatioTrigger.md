# HpRatioTrigger

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `CompareType _condType`

- `Single _hpRatioEachTime`

- `Boolean _useMinHpRatio`

- `String _minHpKey`


## Properties

- `Boolean useMinHpRatio`


## Methods

- `Boolean get_useMinHpRatio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HpRatioTrigger : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private CompareType _condType; // 0x14
	private Single _hpRatioEachTime; // 0x18
	private Boolean _useMinHpRatio; // 0x1c
	private String _minHpKey; // 0x20
	private static DelegateBridge __Hotfix0_get_useMinHpRatio; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean useMinHpRatio { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f22d4c VA: 0x759453ad4c
	private Boolean get_useMinHpRatio() { }
	// RVA: 0x1f22db4 VA: 0x759453adb4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f22e1c VA: 0x759453ae1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f23250 VA: 0x759453b250
	public Void .ctor() { }
}
```