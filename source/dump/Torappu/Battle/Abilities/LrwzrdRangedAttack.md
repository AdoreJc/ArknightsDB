# LrwzrdRangedAttack

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _rightProjectile`

- `String _leftProjectile`

- `String _upProjectile`

- `String _downProjectile`

- `Boolean _useOwnerDirection`

- `Boolean _hasExtraAction`

- `ActionArray _extraActions`


## Properties

- `Boolean hasExtraAction`


## Methods

- `Boolean get_hasExtraAction()`

- `Void _CreateProjectile(String, FixedPosition, FixedPosition)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_OnCastEnd(FinishReason)`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LrwzrdRangedAttack : RangedAttack
{
	private String _rightProjectile; // 0x260
	private String _leftProjectile; // 0x268
	private String _upProjectile; // 0x270
	private String _downProjectile; // 0x278
	private Boolean _useOwnerDirection; // 0x280
	private Boolean _hasExtraAction; // 0x281
	private ActionArray _extraActions; // 0x288
	private static DelegateBridge __Hotfix0_get_hasExtraAction; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_DoCastOnTargets; // 0x10
	private static DelegateBridge __Hotfix0_OnCastEnd; // 0x18
	private static DelegateBridge __Hotfix0__CreateProjectile; // 0x20
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean hasExtraAction { get; }

	// RVA: 0x1e10964 VA: 0x7594428964
	public Boolean get_hasExtraAction() { }
	// RVA: 0x1e109cc VA: 0x75944289cc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e10ad8 VA: 0x7594428ad8
	protected override Boolean DoCastOnTargets(IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e11504 VA: 0x7594429504
	protected override Void OnCastEnd(FinishReason reason) { }
	// RVA: 0x1e112f8 VA: 0x75944292f8
	private Void _CreateProjectile(String projectileKey, FixedPosition start, FixedPosition target) { }
	// RVA: 0x1e11738 VA: 0x7594429738
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e117dc VA: 0x75944297dc
	public Void .ctor() { }
	// RVA: 0x1e11888 VA: 0x7594429888
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e118b0 VA: 0x75944298b0
	private Boolean <>xLuaBaseProxy_DoCastOnTargets(IList`1 P0, IList`1 P1, IList`1 P2) { }
	// RVA: 0x1e118b4 VA: 0x75944298b4
	private Void <>xLuaBaseProxy_OnCastEnd(FinishReason P0) { }
	// RVA: 0x1e118b8 VA: 0x75944298b8
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```