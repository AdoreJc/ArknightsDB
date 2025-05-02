# RegisterAsStand

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _hostAbilityName`

- `String _standAbilityName`

- `Boolean useIdToFindHost`

- `String hostId`


## Methods

- `Boolean _RegistStand(Enemy, Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RegisterAsStand : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String _hostAbilityName; // 0x18
	private String _standAbilityName; // 0x20
	private Boolean useIdToFindHost; // 0x28
	private String hostId; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__RegistStand; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6ef68 VA: 0x7594586f68
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6efd0 VA: 0x7594586fd0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6f2bc VA: 0x75945872bc
	private Boolean _RegistStand(Enemy host, Enemy stand) { }
	// RVA: 0x1f6f644 VA: 0x7594587644
	public Void .ctor() { }
}
```