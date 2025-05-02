# NetCatcherProjectile

**Namespace:** `Torappu.Battle`


## Fields

- `String _blackboardPrefix`

- `Int32 _pullForceLevel`

- `Single _firstPartTime`

- `Boolean _stopAfterFirstPulledBack`

- `Boolean _allowInputTargetDead`

- `Single _secondPullSourceOffset`

- `Single _secondPartTime`

- `Boolean _stopAfterSecondPulledBack`

- `Single _maxRandomOffset`

- `Int32 m_pullForceLevel`

- `Vector2 m_firstPullBackDestination`

- `Vector2 m_secondPullBackDestination`

- `Vector2 m_lastInputTargetMapPosition`

- `Boolean m_isFirstPart`

- `Boolean m_isPullStopped`


## Properties

- `Vector2 firstPullBackDestination`

- `Boolean isFirstPart`

- `Int32 pullForceLevel`


## Methods

- `Vector2 get_firstPullBackDestination()`

- `Boolean get_isFirstPart()`

- `Int32 get_pullForceLevel()`

- `Void SetPullForceLevel(Int32)`

- `Void _StopForceOnEnemy(Entity)`

- `Void StartSecondPartProjectile()`

- `IEnumerator DoLink_SecondPart(Entity)`

- `Void SetPullTime(Enemy, Single)`

- `IEnumerator _DoPull(Enemy, Vector2, Single, Func`1, Boolean)`

- `Enemy GetEffectFollowTarget()`

- `Boolean <DoLink>b__29_0()`

- `IEnumerator <>n__0(Entity)`

- `Boolean <DoLink_SecondPart>b__30_0()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnInit(Single)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`

- `Boolean <>xLuaBaseProxy_ExtraCheckToFinish()`

- `IEnumerator <>xLuaBaseProxy_DoLink(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class NetCatcherProjectile : LinkProjectile
{
	private String _blackboardPrefix; // 0x1c8
	private Int32 _pullForceLevel; // 0x1d0
	private Single _firstPartTime; // 0x1d4
	private Boolean _stopAfterFirstPulledBack; // 0x1d8
	private Boolean _allowInputTargetDead; // 0x1d9
	private Single _secondPullSourceOffset; // 0x1dc
	private Single _secondPartTime; // 0x1e0
	private Boolean _stopAfterSecondPulledBack; // 0x1e4
	private Single _maxRandomOffset; // 0x1e8
	private Int32 m_pullForceLevel; // 0x1ec
	private Vector2 m_firstPullBackDestination; // 0x1f0
	private Vector2 m_secondPullBackDestination; // 0x1f8
	private Vector2 m_lastInputTargetMapPosition; // 0x200
	protected Boolean m_isFirstPart; // 0x208
	protected Boolean m_isPullStopped; // 0x209
	private const Int32 FILTER_TOO_HEAVY_MASS_LEVEL; // 0x0
	private static DelegateBridge __Hotfix0_get_firstPullBackDestination; // 0x0
	private static DelegateBridge __Hotfix0_get_isFirstPart; // 0x8
	private static DelegateBridge __Hotfix0_get_pullForceLevel; // 0x10
	private static DelegateBridge __Hotfix0_OnReset; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x28
	private static DelegateBridge __Hotfix0_SetPullForceLevel; // 0x30
	private static DelegateBridge __Hotfix0_ExtraCheckToFinish; // 0x38
	private static DelegateBridge __Hotfix0__StopForceOnEnemy; // 0x40
	private static DelegateBridge __Hotfix0_StartSecondPartProjectile; // 0x48
	private static DelegateBridge __Hotfix0_DoLink; // 0x50
	private static DelegateBridge __Hotfix0_DoLink_SecondPart; // 0x58
	private static DelegateBridge __Hotfix0_SetPullTime; // 0x60
	private static DelegateBridge __Hotfix0_OnTick; // 0x68
	private static DelegateBridge __Hotfix0__DoPull; // 0x70
	private static DelegateBridge __Hotfix0_GetEffectFollowTarget; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Vector2 firstPullBackDestination { get; }
	public Boolean isFirstPart { get; }
	public Int32 pullForceLevel { get; }

	// RVA: 0x40aad50 VA: 0x75966c2d50
	public Vector2 get_firstPullBackDestination() { }
	// RVA: 0x40aadb8 VA: 0x75966c2db8
	public Boolean get_isFirstPart() { }
	// RVA: 0x40aae20 VA: 0x75966c2e20
	public Int32 get_pullForceLevel() { }
	// RVA: 0x40aae88 VA: 0x75966c2e88
	protected override Void OnReset() { }
	// RVA: 0x40aaef8 VA: 0x75966c2ef8
	protected override Void OnInit(Single initHeight) { }
	// RVA: 0x40ab398 VA: 0x75966c3398
	protected override Void OnProjectileStop() { }
	// RVA: 0x40ab5b8 VA: 0x75966c35b8
	public Void SetPullForceLevel(Int32 level) { }
	// RVA: 0x40ab634 VA: 0x75966c3634
	protected override Boolean ExtraCheckToFinish() { }
	// RVA: 0x40ab6e0 VA: 0x75966c36e0
	private Void _StopForceOnEnemy(Entity rawTarget) { }
	// RVA: 0x40ab800 VA: 0x75966c3800
	protected Void StartSecondPartProjectile() { }
	// RVA: 0x40ab99c VA: 0x75966c399c
	protected override IEnumerator DoLink(Entity rawTarget) { }
	// RVA: 0x40ab8cc VA: 0x75966c38cc
	protected IEnumerator DoLink_SecondPart(Entity rawTarget) { }
	// RVA: 0x40ababc VA: 0x75966c3abc
	protected Void SetPullTime(Enemy target, Single pullTime) { }
	// RVA: 0x40abbbc VA: 0x75966c3bbc
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40abec0 VA: 0x75966c3ec0
	private IEnumerator _DoPull(Enemy target, Vector2 destination, Single duration, Func`1 pullCond, Boolean stopAfterPulledBack) { }
	// RVA: 0x40ac024 VA: 0x75966c4024
	public Enemy GetEffectFollowTarget() { }
	// RVA: 0x40ac3f0 VA: 0x75966c43f0
	public Void .ctor() { }
	// RVA: 0x40ac464 VA: 0x75966c4464
	private Boolean <DoLink>b__29_0() { }
	// RVA: 0x40ac46c VA: 0x75966c446c
	private IEnumerator <>n__0(Entity target) { }
	// RVA: 0x40ac470 VA: 0x75966c4470
	private Boolean <DoLink_SecondPart>b__30_0() { }
	// RVA: 0x40ac480 VA: 0x75966c4480
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x40ac484 VA: 0x75966c4484
	private Void <>xLuaBaseProxy_OnInit(Single P0) { }
	// RVA: 0x40ac488 VA: 0x75966c4488
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
	// RVA: 0x40ac48c VA: 0x75966c448c
	private Boolean <>xLuaBaseProxy_ExtraCheckToFinish() { }
	// RVA: 0x40ac4f8 VA: 0x75966c44f8
	private IEnumerator <>xLuaBaseProxy_DoLink(Entity P0) { }
	// RVA: 0x40ac4fc VA: 0x75966c44fc
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```