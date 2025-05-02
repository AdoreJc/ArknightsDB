# MapEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Vector3 _spawnMapOffset`

- `Boolean _pauseIfTileIsLocated`

- `Boolean _forceZeroHeight`

- `Tile m_tile`


## Methods

- `Void Play(MapEffectData)`

- `Void SetTile(Tile)`

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`

- `Boolean <>xLuaBaseProxy_get_overwriteHeight()`

- `Single <>xLuaBaseProxy_get_heightOffset()`

- `Void <>xLuaBaseProxy_OnBeforePlay()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_OnPausedUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class MapEffect : Effect, ITileListener
{
	private Vector3 _spawnMapOffset; // 0x84
	private Boolean _pauseIfTileIsLocated; // 0x90
	private Boolean _forceZeroHeight; // 0x91
	private Tile m_tile; // 0x98
	private static DelegateBridge __Hotfix0_get_allowAutoReuse; // 0x0
	private static DelegateBridge __Hotfix0_get_preloadAsMaxCapacity; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x18
	private static DelegateBridge __Hotfix0_get_useBodyDirection; // 0x20
	private static DelegateBridge __Hotfix0_get_holdByOwner; // 0x28
	private static DelegateBridge __Hotfix0_get_overwriteHeight; // 0x30
	private static DelegateBridge __Hotfix0_get_heightOffset; // 0x38
	private static DelegateBridge __Hotfix0_Play; // 0x40
	private static DelegateBridge __Hotfix0_OnBeforePlay; // 0x48
	private static DelegateBridge __Hotfix0_OnFinish; // 0x50
	private static DelegateBridge __Hotfix0_OnPausedUpdated; // 0x58
	private static DelegateBridge __Hotfix0_SetTile; // 0x60
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x68
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x70
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public override Boolean allowAutoReuse { get; }
	public override Boolean preloadAsMaxCapacity { get; }
	public override Int32 preloadCnt { get; }
	protected override SpawnLocation spawnLocation { get; }
	protected override Boolean useBodyDirection { get; }
	protected override Boolean holdByOwner { get; }
	protected override Boolean overwriteHeight { get; }
	protected override Single heightOffset { get; }

	// RVA: 0x2014d98 VA: 0x759462cd98
	public override Boolean get_allowAutoReuse() { }
	// RVA: 0x2014dfc VA: 0x759462cdfc
	public override Boolean get_preloadAsMaxCapacity() { }
	// RVA: 0x2014e60 VA: 0x759462ce60
	public override Int32 get_preloadCnt() { }
	// RVA: 0x2014ec8 VA: 0x759462cec8
	protected override SpawnLocation get_spawnLocation() { }
	// RVA: 0x2014f2c VA: 0x759462cf2c
	protected override Boolean get_useBodyDirection() { }
	// RVA: 0x2014f90 VA: 0x759462cf90
	protected override Boolean get_holdByOwner() { }
	// RVA: 0x2014ff4 VA: 0x759462cff4
	protected override Boolean get_overwriteHeight() { }
	// RVA: 0x2015058 VA: 0x759462d058
	protected override Single get_heightOffset() { }
	// RVA: 0x20150c0 VA: 0x759462d0c0
	public Void Play(MapEffectData data) { }
	// RVA: 0x20151dc VA: 0x759462d1dc
	protected override Void OnBeforePlay() { }
	// RVA: 0x20152e4 VA: 0x759462d2e4
	protected override Void OnFinish() { }
	// RVA: 0x20153cc VA: 0x759462d3cc
	protected override Void OnPausedUpdated(Boolean originIsPaused) { }
	// RVA: 0x20154a4 VA: 0x759462d4a4
	public Void SetTile(Tile tile) { }
	// RVA: 0x2015598 VA: 0x759462d598
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x2015668 VA: 0x759462d668
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x20156e0 VA: 0x759462d6e0
	public Void OnEntityLeave(Entity entity) { }
	// RVA: 0x2015758 VA: 0x759462d758
	public Void .ctor() { }
	// RVA: 0x2015808 VA: 0x759462d808
	private Boolean <>xLuaBaseProxy_get_overwriteHeight() { }
	// RVA: 0x2015810 VA: 0x759462d810
	private Single <>xLuaBaseProxy_get_heightOffset() { }
	// RVA: 0x2015818 VA: 0x759462d818
	private Void <>xLuaBaseProxy_OnBeforePlay() { }
	// RVA: 0x2015820 VA: 0x759462d820
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x2015828 VA: 0x759462d828
	private Void <>xLuaBaseProxy_OnPausedUpdated(Boolean P0) { }
}
```