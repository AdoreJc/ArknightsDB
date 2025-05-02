# AuraWithHostAsSourceAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Boolean <>xLuaBaseProxy_DealTargetTouched(Entity, TargetMeta)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AuraWithHostAsSourceAbility : AuraAbility
{
	private ObjectPtr`1 m_host; // 0x178
	private static DelegateBridge __Hotfix0_DealTargetTouched; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e40260 VA: 0x7594458260
	protected override Boolean DealTargetTouched(Entity target, TargetMeta meta) { }
	// RVA: 0x1e404c8 VA: 0x75944584c8
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e4075c VA: 0x759445875c
	public Void .ctor() { }
	// RVA: 0x1e407c8 VA: 0x75944587c8
	private Boolean <>xLuaBaseProxy_DealTargetTouched(Entity P0, TargetMeta P1) { }
	// RVA: 0x1e407cc VA: 0x75944587cc
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
}
```