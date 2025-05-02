# SetSharedFlag

**Namespace:** ` `


## Fields

- `SharedFlagIndex _sharedFlagIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetSharedFlag : ActionNode
{
	private SharedFlagIndex _sharedFlagIndex; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f73ad4 VA: 0x759458bad4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f73b3c VA: 0x759458bb3c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f73c10 VA: 0x759458bc10
	public Void .ctor() { }
}
```