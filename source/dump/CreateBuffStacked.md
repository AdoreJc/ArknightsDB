# CreateBuffStacked

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`

- `String _stackCntKey`

- `Int32 _stackCnt`

- `Boolean _isDisableOverrideBuff`


## Methods

- `Void _AddBuff(Entity, ref, Blackboard)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffStacked : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private Boolean _finishDerivedBuffIfParentFinish; // 0x1d
	private String _stackCntKey; // 0x20
	private Int32 _stackCnt; // 0x28
	private Boolean _isDisableOverrideBuff; // 0x2c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__AddBuff; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1efea2c VA: 0x7594516a2c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efea94 VA: 0x7594516a94
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efec94 VA: 0x7594516c94
	private Void _AddBuff(Entity buffOwner, ref Snapshot snapshot, Blackboard blackboard) { }
	// RVA: 0x1efede0 VA: 0x7594516de0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efeed4 VA: 0x7594516ed4
	public Void .ctor() { }
}
```