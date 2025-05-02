# FuzeSkill2Trigger

**Namespace:** `Torappu.Battle`


## Fields

- `Entity m_owner`

- `Boolean m_isLastSearchSucceed`


## Methods

- `Boolean _IsValidTrap(Tile)`

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FuzeSkill2Trigger : TargetTrigger
{
	private const Int32 MIN_SKILL_TRIGGER_TILE_CNT; // 0x0
	private const String SHELTR_KEY; // 0x0
	private Entity m_owner; // 0x20
	private Boolean m_isLastSearchSucceed; // 0x28
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_Search; // 0x18
	private static DelegateBridge __Hotfix0__IsValidTrap; // 0x20
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd6668 VA: 0x75941ee668
	public override Entity get_target() { }
	// RVA: 0x1bd66e0 VA: 0x75941ee6e0
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd6748 VA: 0x75941ee748
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd686c VA: 0x75941ee86c
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd6ac4 VA: 0x75941eeac4
	private Boolean _IsValidTrap(Tile tile) { }
	// RVA: 0x1bd6cc0 VA: 0x75941eecc0
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd6d3c VA: 0x75941eed3c
	public Void .ctor() { }
	// RVA: 0x1bd6da8 VA: 0x75941eeda8
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
	// RVA: 0x1bd6dac VA: 0x75941eedac
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
}
```