# ContinuouslyRangedHeal

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _continuousHealScale`

- `Boolean _applyScaleForEPHeal`

- `String _secondProjectileKey`

- `Boolean m_isLastTarget`

- `Single m_continuousHealScale`


## Methods

- `Void _UpdateLastTarget(Entity)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `String <>xLuaBaseProxy_GetProjectileKey()`

- `Void <>xLuaBaseProxy_GatherProjectiles(List`1)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ContinuouslyRangedHeal : RangedHeal
{
	private Single _continuousHealScale; // 0x200
	private Boolean _applyScaleForEPHeal; // 0x204
	private String _secondProjectileKey; // 0x208
	private Boolean m_isLastTarget; // 0x210
	private Single m_continuousHealScale; // 0x214
	private ObjectPtr`1 m_lastTarget; // 0x218
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0__UpdateLastTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x10
	private static DelegateBridge __Hotfix0_GetProjectileKey; // 0x18
	private static DelegateBridge __Hotfix0_GatherProjectiles; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e1dfe0 VA: 0x7594435fe0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e1e490 VA: 0x7594436490
	private Void _UpdateLastTarget(Entity target) { }
	// RVA: 0x1e1e5b4 VA: 0x75944365b4
	protected override Void OnCastStart() { }
	// RVA: 0x1e1e94c VA: 0x759443694c
	protected override String GetProjectileKey() { }
	// RVA: 0x1e1ea34 VA: 0x7594436a34
	public override Void GatherProjectiles(List`1 projectiles) { }
	// RVA: 0x1e1ec78 VA: 0x7594436c78
	protected override Void Reset() { }
	// RVA: 0x1e1ed24 VA: 0x7594436d24
	public Void .ctor() { }
	// RVA: 0x1e1ee50 VA: 0x7594436e50
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1ee74 VA: 0x7594436e74
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e1ee7c VA: 0x7594436e7c
	private String <>xLuaBaseProxy_GetProjectileKey() { }
	// RVA: 0x1e1ee80 VA: 0x7594436e80
	private Void <>xLuaBaseProxy_GatherProjectiles(List`1 P0) { }
	// RVA: 0x1e1ee84 VA: 0x7594436e84
	private Void <>xLuaBaseProxy_Reset() { }
}
```