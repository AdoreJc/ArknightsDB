# AutoChessCreateBuffMulti

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`

- `String _buffCntKey`

- `Int32 _buffCnt`


## Methods

- `Void _AddBuff(Entity, Buff, Blackboard)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessCreateBuffMulti : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private String _buffCntKey; // 0x20
	private Int32 _buffCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__AddBuff; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee1f78 VA: 0x75944f9f78
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee1fe0 VA: 0x75944f9fe0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee2174 VA: 0x75944fa174
	private Void _AddBuff(Entity buffOwner, Buff buffInSnapshot, Blackboard blackboard) { }
	// RVA: 0x1ee22ac VA: 0x75944fa2ac
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ee23a0 VA: 0x75944fa3a0
	public Void .ctor() { }
}
```