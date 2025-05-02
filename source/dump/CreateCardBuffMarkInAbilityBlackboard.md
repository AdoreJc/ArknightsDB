# CreateCardBuffMarkInAbilityBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _abilityName`

- `InfoType _infoType`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffMarkInAbilityBlackboard : BaseCreateCardBuff
{
	private ActionTargetType _sourceType; // 0x20
	private String _abilityName; // 0x28
	private InfoType _infoType; // 0x30
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0788c VA: 0x759451f88c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f078f4 VA: 0x759451f8f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f07c84 VA: 0x759451fc84
	public Void .ctor() { }
	// RVA: 0x1f07d30 VA: 0x759451fd30
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f07d34 VA: 0x759451fd34
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```