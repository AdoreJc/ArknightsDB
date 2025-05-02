# CreateBuffToFootball

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToFootball : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private BuffData _buffData; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f4f114 VA: 0x7594567114
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4f17c VA: 0x759456717c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4f3e8 VA: 0x75945673e8
	public Void .ctor() { }
}
```