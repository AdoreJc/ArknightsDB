# ClearTrap

**Namespace:** ` `


## Fields

- `String _charKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearTrap : ActionNode
{
	private String _charKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f377f4 VA: 0x759454f7f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f3785c VA: 0x759454f85c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f37bfc VA: 0x759454fbfc
	public Void .ctor() { }
}
```