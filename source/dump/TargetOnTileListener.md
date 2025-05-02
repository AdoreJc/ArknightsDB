# TargetOnTileListener

**Namespace:** ` `


## Fields

- `Tile m_tile`

- `EnvEnableBuffToTargetsOnTile m_executer`

- `UInt32 m_instanceUid`

- `UInt32 <instanceUid>k__BackingField`


## Properties

- `UInt32 instanceUid`


## Methods

- `Void Reset(Tile, EnvEnableBuffToTargetsOnTile)`

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`

- `Void OnTick()`

- `Void SetEnabled(Boolean)`

- `Void _AddBuffToTarget(Entity)`

- `Void _RemoveBuffFromTarget(Entity)`

- `Void _EnsureMap(Entity)`

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TargetOnTileListener : ITileListener, IHotfixable, IReusableObject, IReusable, IPtrObject
{
	protected Dictionary`2 m_targetMap; // 0x10
	protected HashSet`1 m_attachedTargets; // 0x18
	private Tile m_tile; // 0x20
	private EnvEnableBuffToTargetsOnTile m_executer; // 0x28
	private UInt32 m_instanceUid; // 0x30
	public static UInt32 s_globalCounter; // 0x0
	private UInt32 <instanceUid>k__BackingField; // 0x34
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x10
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_SetEnabled; // 0x30
	private static DelegateBridge __Hotfix0__AddBuffToTarget; // 0x38
	private static DelegateBridge __Hotfix0__RemoveBuffFromTarget; // 0x40
	private static DelegateBridge __Hotfix0__EnsureMap; // 0x48
	private static DelegateBridge __Hotfix0_CreateListener; // 0x50
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x58
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0x60
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x68
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public UInt32 instanceUid { get; set; }

	// RVA: 0x4021ba8 VA: 0x7596639ba8
	public Void Reset(Tile tile, EnvEnableBuffToTargetsOnTile executer) { }
	// RVA: 0x4021c94 VA: 0x7596639c94
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x40224e0 VA: 0x759663a4e0
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x40225e4 VA: 0x759663a5e4
	public Void OnEntityLeave(Entity entity) { }
	// RVA: 0x40226c0 VA: 0x759663a6c0
	public Void OnTick() { }
	// RVA: 0x40229ec VA: 0x759663a9ec
	public Void SetEnabled(Boolean enabled) { }
	// RVA: 0x4022234 VA: 0x759663a234
	private Void _AddBuffToTarget(Entity entity) { }
	// RVA: 0x4021f04 VA: 0x7596639f04
	private Void _RemoveBuffFromTarget(Entity entity) { }
	// RVA: 0x4021d98 VA: 0x7596639d98
	private Void _EnsureMap(Entity entity) { }
	// RVA: 0x4022e20 VA: 0x759663ae20
	public static TargetOnTileListener CreateListener() { }
	// RVA: 0x4022fdc VA: 0x759663afdc
	public UInt32 get_instanceUid() { }
	// RVA: 0x4023044 VA: 0x759663b044
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x40230c0 VA: 0x759663b0c0
	public Void OnAllocate() { }
	// RVA: 0x4023134 VA: 0x759663b134
	public Void OnRecycle() { }
	// RVA: 0x4022ec8 VA: 0x759663aec8
	public Void .ctor() { }
}
```