# TriggerTokensAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`

- `Boolean _checkCanUseAblityFlag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TriggerTokensAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _checkCanUseAblityFlag; // 0x20
	private List`1 m_tokens; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f91f78 VA: 0x75945a9f78
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f91fe0 VA: 0x75945a9fe0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f922e8 VA: 0x75945aa2e8
	public Void .ctor() { }
}
```