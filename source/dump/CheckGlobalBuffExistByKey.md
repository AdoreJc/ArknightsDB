# CheckGlobalBuffExistByKey

**Namespace:** ` `


## Fields

- `String _globalBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckGlobalBuffExistByKey : ActionNode
{
	private String _globalBuffKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f805c0 VA: 0x75945985c0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f80628 VA: 0x7594598628
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8076c VA: 0x759459876c
	public Void .ctor() { }
}
```