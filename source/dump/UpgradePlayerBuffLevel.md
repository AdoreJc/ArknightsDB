# UpgradePlayerBuffLevel

**Namespace:** ` `


## Fields

- `Int32 _count`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UpgradePlayerBuffLevel : ActionNode
{
	private Int32 _count; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f38958 VA: 0x7594550958
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f389c0 VA: 0x75945509c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f38ae4 VA: 0x7594550ae4
	public Void .ctor() { }
}
```