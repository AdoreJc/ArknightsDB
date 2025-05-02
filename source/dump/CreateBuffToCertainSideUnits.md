# CreateBuffToCertainSideUnits

**Namespace:** ` `


## Fields

- `SideType _sideMask`

- `BuffData _buff`

- `Boolean _isDerivedBuff`

- `Boolean _noSource`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToCertainSideUnits : ActionNode, IBuffSource, ICreateBuffNode
{
	private SideType _sideMask; // 0x10
	private BuffData _buff; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _noSource; // 0x21
	private Boolean _finishDerivedBuffIfParentFinish; // 0x22
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efe54c VA: 0x759451654c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efe5b4 VA: 0x75945165b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efe880 VA: 0x7594516880
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efe974 VA: 0x7594516974
	public Void .ctor() { }
}
```