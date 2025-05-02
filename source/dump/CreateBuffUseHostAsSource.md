# CreateBuffUseHostAsSource

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ActionTargetType _targetType`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffUseHostAsSource : ActionNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private BuffData _buffData; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efefc4 VA: 0x7594516fc4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eff02c VA: 0x759451702c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eff2dc VA: 0x75945172dc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1eff3e4 VA: 0x75945173e4
	public Void .ctor() { }
}
```