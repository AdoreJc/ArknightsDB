# BouncedAdvancedMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `Single _speedAfterFirstReach`

- `Boolean m_firstReachFlag`

- `Boolean m_checkReachInNextTick`

- `Single m_originSpeed`


## Properties

- `Boolean checkReachInNextTick`


## Methods

- `Boolean get_checkReachInNextTick()`

- `Void set_checkReachInNextTick(Boolean)`

- `Void ChangeTraceTarget(Entity)`

- `Void EndBounce()`

- `Void DoComeBack()`

- `Void <>xLuaBaseProxy_DealReached()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_DoCheckReached()`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnProjectileStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class BouncedAdvancedMovement : AdvancedMovement
{
	private Single _speedAfterFirstReach; // 0x114
	private Boolean m_firstReachFlag; // 0x118
	private Boolean m_checkReachInNextTick; // 0x119
	private Single m_originSpeed; // 0x11c
	private static DelegateBridge __Hotfix0_get_checkReachInNextTick; // 0x0
	private static DelegateBridge __Hotfix0_set_checkReachInNextTick; // 0x8
	private static DelegateBridge __Hotfix0_DealReached; // 0x10
	private static DelegateBridge __Hotfix0_ChangeTraceTarget; // 0x18
	private static DelegateBridge __Hotfix0_EndBounce; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_DoCheckReached; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_OnProjectileStop; // 0x40
	private static DelegateBridge __Hotfix0_DoComeBack; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected Boolean checkReachInNextTick { get; set; }

	// RVA: 0x1d9e5d0 VA: 0x75943b65d0
	protected Boolean get_checkReachInNextTick() { }
	// RVA: 0x1d9e638 VA: 0x75943b6638
	protected Void set_checkReachInNextTick(Boolean value) { }
	// RVA: 0x1d9e6b8 VA: 0x75943b66b8
	protected override Void DealReached() { }
	// RVA: 0x1d9e7b8 VA: 0x75943b67b8
	public Void ChangeTraceTarget(Entity target) { }
	// RVA: 0x1d9e8c4 VA: 0x75943b68c4
	public Void EndBounce() { }
	// RVA: 0x1d9e954 VA: 0x75943b6954
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x1d9e9dc VA: 0x75943b69dc
	protected override Void DoCheckReached() { }
	// RVA: 0x1d9ea78 VA: 0x75943b6a78
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1d9eb34 VA: 0x75943b6b34
	public override Void OnProjectileStop() { }
	// RVA: 0x1d9eba4 VA: 0x75943b6ba4
	public Void DoComeBack() { }
	// RVA: 0x1d9ed40 VA: 0x75943b6d40
	public Void .ctor() { }
	// RVA: 0x1d9edac VA: 0x75943b6dac
	private Void <>xLuaBaseProxy_DealReached() { }
	// RVA: 0x1d9edb4 VA: 0x75943b6db4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d9edb8 VA: 0x75943b6db8
	private Void <>xLuaBaseProxy_DoCheckReached() { }
	// RVA: 0x1d9edbc VA: 0x75943b6dbc
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
	// RVA: 0x1d9edc0 VA: 0x75943b6dc0
	private Void <>xLuaBaseProxy_OnProjectileStop() { }
}
```