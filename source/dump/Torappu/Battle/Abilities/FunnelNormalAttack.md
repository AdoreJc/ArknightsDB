# FunnelNormalAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `CammouTrait m_trait`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class FunnelNormalAttack : RangedAttack
{
	private CammouTrait m_trait; // 0x260
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e0e6b4 VA: 0x75944266b4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e0e8c0 VA: 0x75944268c0
	protected override Void OnCastOnTarget(Entity target, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0ea1c VA: 0x7594426a1c
	public Void .ctor() { }
	// RVA: 0x1e0ea88 VA: 0x7594426a88
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e0eab0 VA: 0x7594426ab0
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```