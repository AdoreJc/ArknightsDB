# CastTile

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _targetOptions`

- `SideType _sourceSide`

- `ActionArray _actions`

- `ActionArray _actionsOnTrigger`

- `ActionArray _actionsToSlot`

- `String _castEffect`

- `String _hitEffect`

- `Int32 _castMaxCnt`

- `Range _extraTargetRange`

- `Boolean _onlyCombatEnemyInExtraRange`

- `Int32 m_maxTriggerCnt`


## Methods

- `Void GatherActionNodes(List`1)`

- `Void _TryCastOnTarget(Entity, Boolean)`

- `Void _TryFindExtraTargets()`

- `Boolean _CheckExtraTarget(Entity)`

- `Int32 <>xLuaBaseProxy_get_maxTriggerCnt()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Void <>xLuaBaseProxy_OnTrigger()`

- `Void <>xLuaBaseProxy_PreloadAssets()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CastTile : Tile, IActionNodeSource
{
	private TargetOptions _targetOptions; // 0x110
	private SideType _sourceSide; // 0x170
	private ActionArray _actions; // 0x178
	private ActionArray _actionsOnTrigger; // 0x180
	private ActionArray _actionsToSlot; // 0x188
	private String _castEffect; // 0x190
	private String _hitEffect; // 0x198
	private Int32 _castMaxCnt; // 0x1a0
	private Range _extraTargetRange; // 0x1a8
	private Boolean _onlyCombatEnemyInExtraRange; // 0x1b0
	private Int32 m_maxTriggerCnt; // 0x1b4
	private static DelegateBridge __Hotfix0_get_maxTriggerCnt; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x10
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x18
	private static DelegateBridge __Hotfix0__TryCastOnTarget; // 0x20
	private static DelegateBridge __Hotfix0__TryFindExtraTargets; // 0x28
	private static DelegateBridge __Hotfix0__CheckExtraTarget; // 0x30
	private static DelegateBridge __Hotfix0_PreloadAssets; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected override Int32 maxTriggerCnt { get; }

	// RVA: 0x4089a1c VA: 0x75966a1a1c
	protected override Int32 get_maxTriggerCnt() { }
	// RVA: 0x4089a84 VA: 0x75966a1a84
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x4089cf4 VA: 0x75966a1cf4
	public Void GatherActionNodes(List`1 results) { }
	// RVA: 0x4089da4 VA: 0x75966a1da4
	protected override Void OnTrigger() { }
	// RVA: 0x408a57c VA: 0x75966a257c
	private Void _TryCastOnTarget(Entity target, Boolean isBuildSlot) { }
	// RVA: 0x408aa20 VA: 0x75966a2a20
	private Void _TryFindExtraTargets() { }
	// RVA: 0x408ad84 VA: 0x75966a2d84
	private Boolean _CheckExtraTarget(Entity candidate) { }
	// RVA: 0x408b21c VA: 0x75966a321c
	protected override Void PreloadAssets() { }
	// RVA: 0x408b380 VA: 0x75966a3380
	public Void .ctor() { }
	// RVA: 0x408b490 VA: 0x75966a3490
	private Int32 <>xLuaBaseProxy_get_maxTriggerCnt() { }
	// RVA: 0x408b4f8 VA: 0x75966a34f8
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x408b4fc VA: 0x75966a34fc
	private Void <>xLuaBaseProxy_OnTrigger() { }
	// RVA: 0x408b500 VA: 0x75966a3500
	private Void <>xLuaBaseProxy_PreloadAssets() { }
}
```