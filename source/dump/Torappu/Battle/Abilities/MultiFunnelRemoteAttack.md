# MultiFunnelRemoteAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _alwaysUseFunnelSelector`

- `Boolean _useExtraActiveCntAbility`

- `Int32 m_activeCnt`

- `MultiFunnelTrait m_trait`

- `MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage`


## Methods

- `Void UpdateActiveCntIfAdded()`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiFunnelRemoteAttack : RangedAttack
{
	private Boolean _alwaysUseFunnelSelector; // 0x25c
	private Boolean _useExtraActiveCntAbility; // 0x25d
	private Ability[] _funnelActions; // 0x260
	private Int32 m_activeCnt; // 0x268
	private MultiFunnelTrait m_trait; // 0x270
	private MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage; // 0x278
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0_DoSetData; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_UpdateActiveCntIfAdded; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e133f4 VA: 0x759442b3f4
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e135c0 VA: 0x759442b5c0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e13bb0 VA: 0x759442bbb0
	protected override Void DoDetach() { }
	// RVA: 0x1e13cd4 VA: 0x759442bcd4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e13e28 VA: 0x759442be28
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e139c0 VA: 0x759442b9c0
	public Void UpdateActiveCntIfAdded() { }
	// RVA: 0x1e13fc4 VA: 0x759442bfc4
	public Void .ctor() { }
	// RVA: 0x1e14038 VA: 0x759442c038
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e1403c VA: 0x759442c03c
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e14044 VA: 0x759442c044
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e1404c VA: 0x759442c04c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e14074 VA: 0x759442c074
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```