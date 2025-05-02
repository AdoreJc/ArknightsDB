# CheckContainsDerviedBuff

**Namespace:** ` `


## Fields

- `String _derviedBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckContainsDerviedBuff : ActionNode
{
	private String _derviedBuffKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1db6c VA: 0x7594535b6c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1dbd4 VA: 0x7594535bd4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1dcc0 VA: 0x7594535cc0
	public Void .ctor() { }
}
```