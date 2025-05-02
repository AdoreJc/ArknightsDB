# EnsureDmgOrHeal

**Namespace:** ` `


## Fields

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnsureDmgOrHeal : ActionNode
{
	private String _key; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f72158 VA: 0x759458a158
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f721c0 VA: 0x759458a1c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f72498 VA: 0x759458a498
	public Void .ctor() { }
}
```