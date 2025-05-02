# SimpleEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _allowAutoReuse`

- `Boolean _preloadAsMaxCapacity`

- `Int32 _preloadCnt`

- `Single _lifeTime`

- `SpawnLocation _spawnLocation`

- `Boolean _useBodyRotation`

- `Boolean _holdByOwner`

- `Boolean _overwriteHeight`

- `Single _heightOffset`

- `Single _delayToFinish`


## Methods

- `IEnumerator _CheckIfAlive()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`

- `Boolean <>xLuaBaseProxy_get_overwriteHeight()`

- `Single <>xLuaBaseProxy_get_heightOffset()`

- `Void <>xLuaBaseProxy_OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SimpleEffect : Effect
{
	private const Single CHECK_IF_ALIVE_DELTA; // 0x0
	private Boolean _allowAutoReuse; // 0x84
	private Boolean _preloadAsMaxCapacity; // 0x85
	private Int32 _preloadCnt; // 0x88
	private Single _lifeTime; // 0x8c
	private SpawnLocation _spawnLocation; // 0x90
	private Boolean _useBodyRotation; // 0x94
	private Boolean _holdByOwner; // 0x95
	private Boolean _overwriteHeight; // 0x96
	private Single _heightOffset; // 0x98
	private Single _delayToFinish; // 0x9c
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x0
	private static DelegateBridge __Hotfix0_get_allowAutoReuse; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadAsMaxCapacity; // 0x10
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x18
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x20
	private static DelegateBridge __Hotfix0_get_useBodyDirection; // 0x28
	private static DelegateBridge __Hotfix0_get_holdByOwner; // 0x30
	private static DelegateBridge __Hotfix0_get_overwriteHeight; // 0x38
	private static DelegateBridge __Hotfix0_get_heightOffset; // 0x40
	private static DelegateBridge __Hotfix0__CheckIfAlive; // 0x48
	private static DelegateBridge __Hotfix0_OnEnable; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected internal override Single delayToRecycle { get; }
	public override Boolean allowAutoReuse { get; }
	public override Boolean preloadAsMaxCapacity { get; }
	public override Int32 preloadCnt { get; }
	protected override SpawnLocation spawnLocation { get; }
	protected override Boolean useBodyDirection { get; }
	protected override Boolean holdByOwner { get; }
	protected override Boolean overwriteHeight { get; }
	protected override Single heightOffset { get; }

	// RVA: 0x2018070 VA: 0x7594630070
	protected internal override Single get_delayToRecycle() { }
	// RVA: 0x20180d8 VA: 0x75946300d8
	public override Boolean get_allowAutoReuse() { }
	// RVA: 0x2018140 VA: 0x7594630140
	public override Boolean get_preloadAsMaxCapacity() { }
	// RVA: 0x20181a8 VA: 0x75946301a8
	public override Int32 get_preloadCnt() { }
	// RVA: 0x2018210 VA: 0x7594630210
	protected override SpawnLocation get_spawnLocation() { }
	// RVA: 0x2018278 VA: 0x7594630278
	protected override Boolean get_useBodyDirection() { }
	// RVA: 0x20182e0 VA: 0x75946302e0
	protected override Boolean get_holdByOwner() { }
	// RVA: 0x2018348 VA: 0x7594630348
	protected override Boolean get_overwriteHeight() { }
	// RVA: 0x20183b0 VA: 0x75946303b0
	protected override Single get_heightOffset() { }
	// RVA: 0x2018418 VA: 0x7594630418
	private IEnumerator _CheckIfAlive() { }
	// RVA: 0x20184ec VA: 0x75946304ec
	protected override Void OnEnable() { }
	// RVA: 0x2018570 VA: 0x7594630570
	public Void .ctor() { }
	// RVA: 0x20185f4 VA: 0x75946305f4
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
	// RVA: 0x20185fc VA: 0x75946305fc
	private Boolean <>xLuaBaseProxy_get_overwriteHeight() { }
	// RVA: 0x2018604 VA: 0x7594630604
	private Single <>xLuaBaseProxy_get_heightOffset() { }
	// RVA: 0x201860c VA: 0x759463060c
	private Void <>xLuaBaseProxy_OnEnable() { }
}
```