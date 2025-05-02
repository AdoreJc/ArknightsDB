# MultiFunnelsNormalAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useExtraActiveCntAbility`

- `Int32 m_activeCnt`

- `MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage`


## Methods

- `Void RuntimeAddActiveCnt(Int32)`

- `Void UpdateActiveCntIfAdded()`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiFunnelsNormalAttack : RangedAttack
{
	private Boolean _useExtraActiveCntAbility; // 0x25c
	private Ability[] _funnelActions; // 0x260
	private Int32 m_activeCnt; // 0x268
	private MultiFunnelExtraActiveCntAbility m_extraActiveCntStorage; // 0x270
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DoDetach; // 0x10
	private static DelegateBridge __Hotfix0_DoSetData; // 0x18
	private static DelegateBridge __Hotfix0_RuntimeAddActiveCnt; // 0x20
	private static DelegateBridge __Hotfix0_UpdateActiveCntIfAdded; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e1407c VA: 0x759442c07c
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e141f0 VA: 0x759442c1f0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e1470c VA: 0x759442c70c
	protected override Void DoDetach() { }
	// RVA: 0x1e14830 VA: 0x759442c830
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e149c8 VA: 0x759442c9c8
	public Void RuntimeAddActiveCnt(Int32 cnt) { }
	// RVA: 0x1e1451c VA: 0x759442c51c
	public Void UpdateActiveCntIfAdded() { }
	// RVA: 0x1e14ab0 VA: 0x759442cab0
	public Void .ctor() { }
	// RVA: 0x1e14b24 VA: 0x759442cb24
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e14b28 VA: 0x759442cb28
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e14b30 VA: 0x759442cb30
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e14b38 VA: 0x759442cb38
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
}
```