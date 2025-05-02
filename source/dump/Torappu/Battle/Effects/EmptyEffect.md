# EmptyEffect

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Single _delayToFinish`

- `Boolean _allowAutoReuse`

- `Boolean _preloadAsMaxCapacity`

- `Int32 _preloadCnt`


## Methods

- `Boolean <>xLuaBaseProxy_get_overwriteHeight()`

- `Single <>xLuaBaseProxy_get_heightOffset()`

- `Single <>xLuaBaseProxy_get_delayToRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class EmptyEffect : Effect
{
	private Single _delayToFinish; // 0x84
	private Boolean _allowAutoReuse; // 0x88
	private Boolean _preloadAsMaxCapacity; // 0x89
	private Int32 _preloadCnt; // 0x8c
	private static DelegateBridge __Hotfix0_get_allowAutoReuse; // 0x0
	private static DelegateBridge __Hotfix0_get_preloadCnt; // 0x8
	private static DelegateBridge __Hotfix0_get_preloadAsMaxCapacity; // 0x10
	private static DelegateBridge __Hotfix0_get_spawnLocation; // 0x18
	private static DelegateBridge __Hotfix0_get_useBodyDirection; // 0x20
	private static DelegateBridge __Hotfix0_get_holdByOwner; // 0x28
	private static DelegateBridge __Hotfix0_get_overwriteHeight; // 0x30
	private static DelegateBridge __Hotfix0_get_heightOffset; // 0x38
	private static DelegateBridge __Hotfix0_get_delayToRecycle; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Boolean allowAutoReuse { get; }
	public override Int32 preloadCnt { get; }
	public override Boolean preloadAsMaxCapacity { get; }
	protected override SpawnLocation spawnLocation { get; }
	protected override Boolean useBodyDirection { get; }
	protected override Boolean holdByOwner { get; }
	protected override Boolean overwriteHeight { get; }
	protected override Single heightOffset { get; }
	protected internal override Single delayToRecycle { get; }

	// RVA: 0x2014960 VA: 0x759462c960
	public override Boolean get_allowAutoReuse() { }
	// RVA: 0x20149c8 VA: 0x759462c9c8
	public override Int32 get_preloadCnt() { }
	// RVA: 0x2014a30 VA: 0x759462ca30
	public override Boolean get_preloadAsMaxCapacity() { }
	// RVA: 0x2014a98 VA: 0x759462ca98
	protected override SpawnLocation get_spawnLocation() { }
	// RVA: 0x2014afc VA: 0x759462cafc
	protected override Boolean get_useBodyDirection() { }
	// RVA: 0x2014b60 VA: 0x759462cb60
	protected override Boolean get_holdByOwner() { }
	// RVA: 0x2014bc4 VA: 0x759462cbc4
	protected override Boolean get_overwriteHeight() { }
	// RVA: 0x2014c28 VA: 0x759462cc28
	protected override Single get_heightOffset() { }
	// RVA: 0x2014c90 VA: 0x759462cc90
	protected internal override Single get_delayToRecycle() { }
	// RVA: 0x2014cf8 VA: 0x759462ccf8
	public Void .ctor() { }
	// RVA: 0x2014d80 VA: 0x759462cd80
	private Boolean <>xLuaBaseProxy_get_overwriteHeight() { }
	// RVA: 0x2014d88 VA: 0x759462cd88
	private Single <>xLuaBaseProxy_get_heightOffset() { }
	// RVA: 0x2014d90 VA: 0x759462cd90
	private Single <>xLuaBaseProxy_get_delayToRecycle() { }
}
```