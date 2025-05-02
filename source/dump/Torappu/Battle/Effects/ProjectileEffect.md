# ProjectileEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _resetMainDir`

- `Direction _mainDir`

- `Boolean _rotate180Y`

- `Single _randomAngle`

- `Single _delayToFinish`

- `Boolean _allowAutoReuse`

- `Boolean _preloadAsMaxCapacity`

- `Int32 _preloadCnt`

- `ParticleSystem m_particleSystem`


## Properties

- `Boolean resetMainDir`


## Methods

- `Boolean get_resetMainDir()`

- `Void ForceApplyPlaybackSpeedMultiplier(Single)`

- `Void _ClearPlaybackSpeedSettings()`

- `Boolean <>xLuaBaseProxy_get_overwriteHeight()`

- `Single <>xLuaBaseProxy_get_heightOffset()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_DoPlay()`

- `Void <>xLuaBaseProxy_OnBeforePlay()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_UpdatePlaybackSpeed(Single)`

- `Void <>xLuaBaseProxy_Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class ProjectileEffect : Effect
{
	private Boolean _resetMainDir; // 0x84
	private Direction _mainDir; // 0x88
	private Boolean _rotate180Y; // 0x8c
	private Single _randomAngle; // 0x90
	private Single _delayToFinish; // 0x94
	private Boolean _allowAutoReuse; // 0x98
	private Boolean _preloadAsMaxCapacity; // 0x99
	private Int32 _preloadCnt; // 0x9c
	private Transform[] _inactiveOnFinish; // 0xa0
	private ParticleSystem m_particleSystem; // 0xa8
	private Animator[] m_animators; // 0xb0
	private ParticleSystem[] m_particleSystems; // 0xb8
	private static DelegateBridge __Hotfix0_get_resetMainDir; // 0x0
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadAsMaxCapacity; // 0x10
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x18
	private static DelegateBridge __Hotfix0_get_useBodyDirection; // 0x20
	private static DelegateBridge __Hotfix0_get_holdByOwner; // 0x28
	private static DelegateBridge __Hotfix0_get_overwriteHeight; // 0x30
	private static DelegateBridge __Hotfix0_get_heightOffset; // 0x38
	private static DelegateBridge __Hotfix0_get_allowAutoReuse; // 0x40
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x48
	private static DelegateBridge __Hotfix0_get_particleSystems; // 0x50
	private static DelegateBridge __Hotfix0_get_animators; // 0x58
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x60
	private static DelegateBridge __Hotfix0_DoPlay; // 0x68
	private static DelegateBridge __Hotfix0_OnBeforePlay; // 0x70
	private static DelegateBridge __Hotfix0_OnFinish; // 0x78
	private static DelegateBridge __Hotfix0_ForceApplyPlaybackSpeedMultiplier; // 0x80
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x88
	private static DelegateBridge __Hotfix0__ClearPlaybackSpeedSettings; // 0x90
	private static DelegateBridge __Hotfix0_Awake; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public Boolean resetMainDir { get; }
	public override Int32 preloadCnt { get; }
	public override Boolean preloadAsMaxCapacity { get; }
	protected override SpawnLocation spawnLocation { get; }
	protected override Boolean useBodyDirection { get; }
	protected override Boolean holdByOwner { get; }
	protected override Boolean overwriteHeight { get; }
	protected override Single heightOffset { get; }
	public override Boolean allowAutoReuse { get; }
	protected internal override Single delayToRecycle { get; }
	protected ParticleSystem[] particleSystems { get; }
	protected Animator[] animators { get; }

	// RVA: 0x2016ec4 VA: 0x759462eec4
	public Boolean get_resetMainDir() { }
	// RVA: 0x2016f2c VA: 0x759462ef2c
	public override Int32 get_preloadCnt() { }
	// RVA: 0x2016f94 VA: 0x759462ef94
	public override Boolean get_preloadAsMaxCapacity() { }
	// RVA: 0x2016ffc VA: 0x759462effc
	protected override SpawnLocation get_spawnLocation() { }
	// RVA: 0x2017060 VA: 0x759462f060
	protected override Boolean get_useBodyDirection() { }
	// RVA: 0x20170c4 VA: 0x759462f0c4
	protected override Boolean get_holdByOwner() { }
	// RVA: 0x2017128 VA: 0x759462f128
	protected override Boolean get_overwriteHeight() { }
	// RVA: 0x201718c VA: 0x759462f18c
	protected override Single get_heightOffset() { }
	// RVA: 0x20171f4 VA: 0x759462f1f4
	public override Boolean get_allowAutoReuse() { }
	// RVA: 0x201725c VA: 0x759462f25c
	protected internal override Single get_delayToRecycle() { }
	// RVA: 0x20172c4 VA: 0x759462f2c4
	protected ParticleSystem[] get_particleSystems() { }
	// RVA: 0x201736c VA: 0x759462f36c
	protected Animator[] get_animators() { }
	// RVA: 0x2017414 VA: 0x759462f414
	public override Void OnRecycle() { }
	// RVA: 0x2017494 VA: 0x759462f494
	protected override Void DoPlay() { }
	// RVA: 0x2017560 VA: 0x759462f560
	protected override Void OnBeforePlay() { }
	// RVA: 0x20177fc VA: 0x759462f7fc
	protected override Void OnFinish() { }
	// RVA: 0x2017b78 VA: 0x759462fb78
	public Void ForceApplyPlaybackSpeedMultiplier(Single speedMultiplier) { }
	// RVA: 0x2017c10 VA: 0x759462fc10
	protected override Void UpdatePlaybackSpeed(Single playbackSpeed) { }
	// RVA: 0x2017918 VA: 0x759462f918
	private Void _ClearPlaybackSpeedSettings() { }
	// RVA: 0x2017ec0 VA: 0x759462fec0
	protected override Void Awake() { }
	// RVA: 0x2017f5c VA: 0x759462ff5c
	public Void .ctor() { }
	// RVA: 0x2018028 VA: 0x7594630028
	private Boolean <>xLuaBaseProxy_get_overwriteHeight() { }
	// RVA: 0x2018030 VA: 0x7594630030
	private Single <>xLuaBaseProxy_get_heightOffset() { }
	// RVA: 0x2018038 VA: 0x7594630038
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
	// RVA: 0x2018040 VA: 0x7594630040
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x2018048 VA: 0x7594630048
	private Void <>xLuaBaseProxy_DoPlay() { }
	// RVA: 0x2018050 VA: 0x7594630050
	private Void <>xLuaBaseProxy_OnBeforePlay() { }
	// RVA: 0x2018058 VA: 0x7594630058
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x2018060 VA: 0x7594630060
	private Void <>xLuaBaseProxy_UpdatePlaybackSpeed(Single P0) { }
	// RVA: 0x2018068 VA: 0x7594630068
	private Void <>xLuaBaseProxy_Awake() { }
}
```