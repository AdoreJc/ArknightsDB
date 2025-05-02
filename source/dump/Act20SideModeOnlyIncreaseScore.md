# Act20SideModeOnlyIncreaseScore

**Namespace:** ` `


## Fields

- `Int32 _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act20SideModeOnlyIncreaseScore : ActionNode
{
	private Int32 _value; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f58d5c VA: 0x7594570d5c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f58dc4 VA: 0x7594570dc4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f58f80 VA: 0x7594570f80
	public Void .ctor() { }
}
```