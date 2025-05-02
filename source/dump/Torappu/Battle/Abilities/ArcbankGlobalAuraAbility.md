# ArcbankGlobalAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _blackboardKey`

- `Blackboard m_extraBlackboard`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_DealTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ArcbankGlobalAuraAbility : GlobalAuraAbility
{
	private String _blackboardKey; // 0x178
	private Blackboard m_extraBlackboard; // 0x180
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DealTarget; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e45d40 VA: 0x759445dd40
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e45e60 VA: 0x759445de60
	protected override Boolean DealTarget(Entity target) { }
	// RVA: 0x1e46174 VA: 0x759445e174
	public Void .ctor() { }
	// RVA: 0x1e46250 VA: 0x759445e250
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e46274 VA: 0x759445e274
	private Boolean <>xLuaBaseProxy_DealTarget(Entity P0) { }
}
```