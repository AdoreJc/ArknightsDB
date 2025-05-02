# CreateNoSourceBuff

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `ActionTargetType _buffOwner`

- `Boolean _isDerivedBuff`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateNoSourceBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private ActionTargetType _buffOwner; // 0x18
	private Boolean _isDerivedBuff; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f04600 VA: 0x759451c600
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f04668 VA: 0x759451c668
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f04830 VA: 0x759451c830
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f04924 VA: 0x759451c924
	public Void .ctor() { }
}
```