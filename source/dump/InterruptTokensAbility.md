# InterruptTokensAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptTokensAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private List`1 m_tokens; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f923ec VA: 0x75945aa3ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f92454 VA: 0x75945aa454
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f926e8 VA: 0x75945aa6e8
	public Void .ctor() { }
}
```