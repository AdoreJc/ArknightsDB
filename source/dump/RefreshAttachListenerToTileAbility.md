# RefreshAttachListenerToTileAbility

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `String _abilityName`

- `Boolean _checkCanUseAblityFlag`

- `String _syncAbilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RefreshAttachListenerToTileAbility : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private String _abilityName; // 0x18
	private Boolean _checkCanUseAblityFlag; // 0x20
	private String _syncAbilityName; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f91474 VA: 0x75945a9474
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f914dc VA: 0x75945a94dc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9177c VA: 0x75945a977c
	public Void .ctor() { }
}
```