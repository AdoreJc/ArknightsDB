# FilterCharacterSkill

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterCharacterSkill : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f60870 VA: 0x7594578870
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f608d8 VA: 0x75945788d8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f60a88 VA: 0x7594578a88
	public Void .ctor() { }
}
```