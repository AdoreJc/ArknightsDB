# CheckHasStands

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHasStands : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _abilityName; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6e4dc VA: 0x75945864dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6e544 VA: 0x7594586544
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6e714 VA: 0x7594586714
	public Void .ctor() { }
}
```