# CreateBuffToCertainProfession

**Namespace:** ` `


## Fields

- `ProfessionCategory _professionMask`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToCertainProfession : ActionNode, IBuffSource
{
	private ProfessionCategory _professionMask; // 0x10
	private BuffData _buffData; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _finishDerivedBuffIfParentFinish; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efa108 VA: 0x7594512108
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efa170 VA: 0x7594512170
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efa444 VA: 0x7594512444
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efa54c VA: 0x759451254c
	public Void .ctor() { }
}
```