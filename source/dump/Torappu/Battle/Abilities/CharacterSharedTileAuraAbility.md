# CharacterSharedTileAuraAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _showEffectWhenAttach`

- `String _tileEffectKey`

- `Single _effectInterval`

- `Int32 m_curTile`

- `Int32 m_cntTileRow`

- `Vector2 m_offset`

- `PeriodicTimer m_effectTimer`


## Methods

- `Void _SetColliderOffset()`

- `Int32 _SetTilesCollider()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class CharacterSharedTileAuraAbility : AuraAbility
{
	private Boolean _showEffectWhenAttach; // 0x178
	private String _tileEffectKey; // 0x180
	private Single _effectInterval; // 0x188
	private List`1 m_showEffectTile; // 0x190
	private List`1 m_cachedcolliders; // 0x198
	private Int32 m_curTile; // 0x1a0
	private Int32 m_cntTileRow; // 0x1a4
	private Vector2 m_offset; // 0x1a8
	private ObjectPtr`1 m_character; // 0x1b0
	private PeriodicTimer m_effectTimer; // 0x1c0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__SetColliderOffset; // 0x20
	private static DelegateBridge __Hotfix0__SetTilesCollider; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e407d0 VA: 0x75944587d0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e4124c VA: 0x759445924c
	protected override Void OnDetached() { }
	// RVA: 0x1e41334 VA: 0x7594459334
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1e41454 VA: 0x7594459454
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e410c4 VA: 0x75944590c4
	private Void _SetColliderOffset() { }
	// RVA: 0x1e40adc VA: 0x7594458adc
	private Int32 _SetTilesCollider() { }
	// RVA: 0x1e41690 VA: 0x7594459690
	public Void .ctor() { }
	// RVA: 0x1e417e8 VA: 0x75944597e8
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e4180c VA: 0x759445980c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e41814 VA: 0x7594459814
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1e41818 VA: 0x7594459818
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```