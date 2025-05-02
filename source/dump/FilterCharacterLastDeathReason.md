# FilterCharacterLastDeathReason

**Namespace:** ` `


## Fields

- `ActionTargetType _characterType`

- `FinishReason _finishReason`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterCharacterLastDeathReason : ActionNode
{
	private ActionTargetType _characterType; // 0x10
	private FinishReason _finishReason; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f33450 VA: 0x759454b450
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f334b8 VA: 0x759454b4b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f33638 VA: 0x759454b638
	public Void .ctor() { }
}
```