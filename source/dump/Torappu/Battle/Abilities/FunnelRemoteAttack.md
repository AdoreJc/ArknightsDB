# FunnelRemoteAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Ability _funnelAction`

- `Boolean m_hasFireFunnel`


## Methods

- `Void _RecycleFunnel(Object)`

- `Void <>xLuaBaseProxy_Reset()`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class FunnelRemoteAttack : RangedAttack
{
	private Ability _funnelAction; // 0x260
	private Boolean m_hasFireFunnel; // 0x268
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0_DoSetData; // 0x20
	private static DelegateBridge __Hotfix0__RecycleFunnel; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1e0eab4 VA: 0x7594426ab4
	protected override Void Reset() { }
	// RVA: 0x1e0ebd4 VA: 0x7594426bd4
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e0ed0c VA: 0x7594426d0c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e0ee34 VA: 0x7594426e34
	protected override Void DoDetach() { }
	// RVA: 0x1e0ef74 VA: 0x7594426f74
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e0f044 VA: 0x7594427044
	private Void _RecycleFunnel(Object param) { }
	// RVA: 0x1e0f0c0 VA: 0x75944270c0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e0f1c4 VA: 0x75944271c4
	public Void .ctor() { }
	// RVA: 0x1e0f230 VA: 0x7594427230
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e0f234 VA: 0x7594427234
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e0f238 VA: 0x7594427238
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e0f240 VA: 0x7594427240
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e0f248 VA: 0x7594427248
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e0f270 VA: 0x7594427270
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```