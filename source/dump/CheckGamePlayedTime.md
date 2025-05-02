# CheckGamePlayedTime

**Namespace:** ` `


## Fields

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckGamePlayedTime : ActionNode
{
	private CompareType _condType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f28458 VA: 0x7594540458
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f284c0 VA: 0x75945404c0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f28640 VA: 0x7594540640
	public Void .ctor() { }
}
```