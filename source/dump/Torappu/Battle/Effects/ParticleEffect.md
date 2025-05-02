# ParticleEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Single _delayToPlay`

- `Single _delayToFinish`

- `Single _maxLifetime`

- `Boolean _randomPlayDelay`

- `Boolean _allowAutoReuse`

- `Boolean _preloadAsMaxCapacity`

- `Boolean _usePlaybackSpeed`

- `Single _limitedPlaybackSpeed`

- `Int32 _preloadCnt`

- `RotateType _rotateType`

- `SpawnLocation _spawnLocation`

- `Boolean _leftIsDefault`

- `Boolean _useBodyRotation`

- `Direction _mainDir`

- `Boolean _holdByOwner`

- `Boolean _overwriteHeight`

- `Single _heightOffset`

- `Transform _rotationY`

- `Transform _rotationZ`

- `Transform _flipZ`

- `Animator m_animator`

- `ParticleSystem m_particleSystem`


## Properties

- `Boolean isFourDir`

- `Single maxLifeTime`

- `ParticleSystem particleSystem`


## Methods

- `Boolean get_isFourDir()`

- `Single get_maxLifeTime()`

- `ParticleSystem get_particleSystem()`

- `IEnumerator _CheckIfAlive()`

- `Boolean <>xLuaBaseProxy_get_overwriteHeight()`

- `Single <>xLuaBaseProxy_get_heightOffset()`

- `Single <>xLuaBaseProxy_get_delayToPlay()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`

- `Boolean <>xLuaBaseProxy_get_randomPlayDelay()`

- `Boolean <>xLuaBaseProxy_get_usePlaybackSpeed()`

- `Single <>xLuaBaseProxy_get_limitedPlaybackSpeed()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_DoPlay()`

- `Void <>xLuaBaseProxy_OnBeforePlay()`

- `Void <>xLuaBaseProxy_FaceTo(Vector3)`

- `Void <>xLuaBaseProxy_UpdatePlaybackSpeed(Single)`

- `Void <>xLuaBaseProxy_OnPausedUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class ParticleEffect : Effect
{
	private const String CHILD_NAME_ROTATION_Y; // 0x0
	private const String CHILD_NAME_ROTATION_Z; // 0x0
	private const String CHILD_NAME_FLIP_X; // 0x0
	private const Single CHECK_IF_ALIVE_DELTA; // 0x0
	private Single _delayToPlay; // 0x84
	private Single _delayToFinish; // 0x88
	private Single _maxLifetime; // 0x8c
	private Boolean _randomPlayDelay; // 0x90
	private Boolean _allowAutoReuse; // 0x91
	private Boolean _preloadAsMaxCapacity; // 0x92
	private Boolean _usePlaybackSpeed; // 0x93
	private Single _limitedPlaybackSpeed; // 0x94
	private Int32 _preloadCnt; // 0x98
	private RotateType _rotateType; // 0x9c
	private SpawnLocation _spawnLocation; // 0xa0
	private Boolean _leftIsDefault; // 0xa4
	private Boolean _useBodyRotation; // 0xa5
	private Direction _mainDir; // 0xa8
	private Boolean _holdByOwner; // 0xac
	private Boolean _overwriteHeight; // 0xad
	private Single _heightOffset; // 0xb0
	private Transform _rotationY; // 0xb8
	private Transform _rotationZ; // 0xc0
	private Transform _flipZ; // 0xc8
	private Transform[] _inactiveOnFinish; // 0xd0
	private Animator m_animator; // 0xd8
	private ParticleSystem m_particleSystem; // 0xe0
	private ParticleSystem[] m_particleSystems; // 0xe8
	private static DelegateBridge __Hotfix0_get_isFourDir; // 0x0
	private static DelegateBridge __Hotfix0_get_maxLifeTime; // 0x8
	private static DelegateBridge __Hotfix0_get_allowAutoReuse; // 0x10
	private static DelegateBridge __Hotfix0_get_preloadAsMaxCapacity; // 0x18
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x28
	private static DelegateBridge __Hotfix0_get_useBodyDirection; // 0x30
	private static DelegateBridge __Hotfix0_get_holdByOwner; // 0x38
	private static DelegateBridge __Hotfix0_get_overwriteHeight; // 0x40
	private static DelegateBridge __Hotfix0_get_heightOffset; // 0x48
	private static DelegateBridge __Hotfix0_get_delayToPlay; // 0x50
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x58
	private static DelegateBridge __Hotfix0_get_randomPlayDelay; // 0x60
	private static DelegateBridge __Hotfix0_get_usePlaybackSpeed; // 0x68
	private static DelegateBridge __Hotfix0_get_limitedPlaybackSpeed; // 0x70
	private static DelegateBridge __Hotfix0_get_particleSystem; // 0x78
	private static DelegateBridge __Hotfix0_get_particleSystems; // 0x80
	private static DelegateBridge __Hotfix0_OnFinish; // 0x88
	private static DelegateBridge __Hotfix0_DoPlay; // 0x90
	private static DelegateBridge __Hotfix0_OnBeforePlay; // 0x98
	private static DelegateBridge __Hotfix0_FaceTo; // 0xa0
	private static DelegateBridge __Hotfix0__CheckIfAlive; // 0xa8
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0xb0
	private static DelegateBridge __Hotfix0_OnPausedUpdated; // 0xb8
	private static DelegateBridge __Hotfix0_OnEnable; // 0xc0
	private static DelegateBridge __Hotfix0_Awake; // 0xc8
	private static DelegateBridge __Hotfix0_OnRecycle; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Boolean isFourDir { get; }
	public Single maxLifeTime { get; }
	public override Boolean allowAutoReuse { get; }
	public override Boolean preloadAsMaxCapacity { get; }
	public override Int32 preloadCnt { get; }
	protected override SpawnLocation spawnLocation { get; }
	protected override Boolean useBodyDirection { get; }
	protected override Boolean holdByOwner { get; }
	protected override Boolean overwriteHeight { get; }
	protected override Single heightOffset { get; }
	protected override Single delayToPlay { get; }
	protected internal override Single delayToRecycle { get; }
	protected override Boolean randomPlayDelay { get; }
	protected override Boolean usePlaybackSpeed { get; }
	protected override Single limitedPlaybackSpeed { get; }
	protected ParticleSystem particleSystem { get; }
	protected ParticleSystem[] particleSystems { get; }

	// RVA: 0x2015834 VA: 0x759462d834
	public Boolean get_isFourDir() { }
	// RVA: 0x20158a8 VA: 0x759462d8a8
	public Single get_maxLifeTime() { }
	// RVA: 0x2015910 VA: 0x759462d910
	public override Boolean get_allowAutoReuse() { }
	// RVA: 0x2015978 VA: 0x759462d978
	public override Boolean get_preloadAsMaxCapacity() { }
	// RVA: 0x20159e0 VA: 0x759462d9e0
	public override Int32 get_preloadCnt() { }
	// RVA: 0x2015a48 VA: 0x759462da48
	protected override SpawnLocation get_spawnLocation() { }
	// RVA: 0x2015ab0 VA: 0x759462dab0
	protected override Boolean get_useBodyDirection() { }
	// RVA: 0x2015b18 VA: 0x759462db18
	protected override Boolean get_holdByOwner() { }
	// RVA: 0x2015b80 VA: 0x759462db80
	protected override Boolean get_overwriteHeight() { }
	// RVA: 0x2015be8 VA: 0x759462dbe8
	protected override Single get_heightOffset() { }
	// RVA: 0x2015c50 VA: 0x759462dc50
	protected override Single get_delayToPlay() { }
	// RVA: 0x2015cb8 VA: 0x759462dcb8
	protected internal override Single get_delayToRecycle() { }
	// RVA: 0x2015d20 VA: 0x759462dd20
	protected override Boolean get_randomPlayDelay() { }
	// RVA: 0x2015d88 VA: 0x759462dd88
	protected override Boolean get_usePlaybackSpeed() { }
	// RVA: 0x2015df0 VA: 0x759462ddf0
	protected override Single get_limitedPlaybackSpeed() { }
	// RVA: 0x2015e58 VA: 0x759462de58
	protected ParticleSystem get_particleSystem() { }
	// RVA: 0x2015ec0 VA: 0x759462dec0
	protected ParticleSystem[] get_particleSystems() { }
	// RVA: 0x2015f68 VA: 0x759462df68
	protected override Void OnFinish() { }
	// RVA: 0x2016070 VA: 0x759462e070
	protected override Void DoPlay() { }
	// RVA: 0x20160f8 VA: 0x759462e0f8
	protected override Void OnBeforePlay() { }
	// RVA: 0x2016248 VA: 0x759462e248
	public override Void FaceTo(Vector3 direction) { }
	// RVA: 0x201662c VA: 0x759462e62c
	private IEnumerator _CheckIfAlive() { }
	// RVA: 0x2016700 VA: 0x759462e700
	protected override Void UpdatePlaybackSpeed(Single playbackSpeed) { }
	// RVA: 0x201683c VA: 0x759462e83c
	protected override Void OnPausedUpdated(Boolean originIsPaused) { }
	// RVA: 0x20169a0 VA: 0x759462e9a0
	protected override Void OnEnable() { }
	// RVA: 0x2016a24 VA: 0x759462ea24
	protected override Void Awake() { }
	// RVA: 0x2016af0 VA: 0x759462eaf0
	public override Void OnRecycle() { }
	// RVA: 0x2016b70 VA: 0x759462eb70
	public Void .ctor() { }
	// RVA: 0x2016c40 VA: 0x759462ec40
	private Boolean <>xLuaBaseProxy_get_overwriteHeight() { }
	// RVA: 0x2016c48 VA: 0x759462ec48
	private Single <>xLuaBaseProxy_get_heightOffset() { }
	// RVA: 0x2016c50 VA: 0x759462ec50
	private Single <>xLuaBaseProxy_get_delayToPlay() { }
	// RVA: 0x2016c58 VA: 0x759462ec58
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
	// RVA: 0x2016c60 VA: 0x759462ec60
	private Boolean <>xLuaBaseProxy_get_randomPlayDelay() { }
	// RVA: 0x2016c68 VA: 0x759462ec68
	private Boolean <>xLuaBaseProxy_get_usePlaybackSpeed() { }
	// RVA: 0x2016c70 VA: 0x759462ec70
	private Single <>xLuaBaseProxy_get_limitedPlaybackSpeed() { }
	// RVA: 0x2016c78 VA: 0x759462ec78
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x2016c80 VA: 0x759462ec80
	private Void <>xLuaBaseProxy_DoPlay() { }
	// RVA: 0x2016c88 VA: 0x759462ec88
	private Void <>xLuaBaseProxy_OnBeforePlay() { }
	// RVA: 0x2016c90 VA: 0x759462ec90
	private Void <>xLuaBaseProxy_FaceTo(Vector3 P0) { }
	// RVA: 0x2016c98 VA: 0x759462ec98
	private Void <>xLuaBaseProxy_UpdatePlaybackSpeed(Single P0) { }
	// RVA: 0x2016ca0 VA: 0x759462eca0
	private Void <>xLuaBaseProxy_OnPausedUpdated(Boolean P0) { }
	// RVA: 0x2016cac VA: 0x759462ecac
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x2016cb4 VA: 0x759462ecb4
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x2016cbc VA: 0x759462ecbc
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```