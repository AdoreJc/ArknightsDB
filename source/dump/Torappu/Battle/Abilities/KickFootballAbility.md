# KickFootballAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `FootballPlayerEnemy m_abilityOwner`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class KickFootballAbility : AnimatedActionToOwnerAbility
{
	private FootballPlayerEnemy m_abilityOwner; // 0x1c8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e76b6c VA: 0x759448eb6c
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e76ca4 VA: 0x759448eca4
	protected override Void OnCastStart() { }
	// RVA: 0x1e76e90 VA: 0x759448ee90
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e76f98 VA: 0x759448ef98
	public Void .ctor() { }
	// RVA: 0x1e77008 VA: 0x759448f008
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e77030 VA: 0x759448f030
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e77038 VA: 0x759448f038
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
}
```