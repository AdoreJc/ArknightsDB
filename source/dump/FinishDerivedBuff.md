# FinishDerivedBuff

**Namespace:** ` `


## Fields

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishDerivedBuff : ActionNode
{
	private Boolean _updateOverrideMap; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef7de4 VA: 0x759450fde4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef7e4c VA: 0x759450fe4c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef7ef8 VA: 0x759450fef8
	public Void .ctor() { }
}
```