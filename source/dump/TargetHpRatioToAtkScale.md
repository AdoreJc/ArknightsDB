# TargetHpRatioToAtkScale

**Namespace:** ` `


## Fields

- `Single _startHpRatio`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TargetHpRatioToAtkScale : ActionNode
{
	private Single _startHpRatio; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f34294 VA: 0x759454c294
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f342fc VA: 0x759454c2fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f3459c VA: 0x759454c59c
	public Void .ctor() { }
}
```