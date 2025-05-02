# TileTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _minTileNum`

- `TileSelector m_selector`

- `CompoundPeriodicTicker m_findTargetTicker`


## Properties

- `Entity owner`


## Methods

- `Entity get_owner()`

- `Void Awake()`

- `Void FixedUpdate()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TileTrigger : TargetTrigger
{
	private const Int32 SEARCH_TARGET_TICK; // 0x0
	private Int32 _minTileNum; // 0x20
	private TileSelector m_selector; // 0x28
	private CompoundPeriodicTicker m_findTargetTicker; // 0x30
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_owner; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_Search; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Entity target { get; }
	protected Entity owner { get; }

	// RVA: 0x1bd9c54 VA: 0x75941f1c54
	public override Entity get_target() { }
	// RVA: 0x1bd9cbc VA: 0x75941f1cbc
	protected Entity get_owner() { }
	// RVA: 0x1bd9d30 VA: 0x75941f1d30
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd9e28 VA: 0x75941f1e28
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd9f24 VA: 0x75941f1f24
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd9fb4 VA: 0x75941f1fb4
	private Void Awake() { }
	// RVA: 0x1bda044 VA: 0x75941f2044
	private Void FixedUpdate() { }
	// RVA: 0x1bda0b8 VA: 0x75941f20b8
	public Void .ctor() { }
	// RVA: 0x1bda174 VA: 0x75941f2174
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
}
```