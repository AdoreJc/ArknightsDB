# CheckCharacterInBornState

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterInBornState : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2a1d8 VA: 0x75945421d8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2a240 VA: 0x7594542240
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2a3b8 VA: 0x75945423b8
	public Void .ctor() { }
}
```