# FinishCardBuffByCard

**Namespace:** ` `


## Fields

- `Boolean _exceptOwner`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishCardBuffByCard : ActionNode
{
	private Boolean _exceptOwner; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f081ec VA: 0x75945201ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f08254 VA: 0x7594520254
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f084e0 VA: 0x75945204e0
	public Void .ctor() { }
}
```