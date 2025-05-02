# VaultReflectionCameraHolder

**Namespace:** `Torappu.Building.Vault`


## Fields

- `LODState m_lodState`

- `Boolean m_enabledByLOD`


## Properties

- `Int32 priority`


## Methods

- `Int32 get_priority()`

- `Void OnLODStateChanged(LODState)`

- `Void _RefreshCameraByLOD()`

- `Boolean <>xLuaBaseProxy_get_reflectEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VaultReflectionCameraHolder : ReflectCameraHolder, ILODListener, IHotfixable
{
	private LODState m_lodState; // 0x48
	private Boolean m_enabledByLOD; // 0x50
	private static DelegateBridge __Hotfix0_get_priority; // 0x0
	private static DelegateBridge __Hotfix0_get_reflectEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnLODStateChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge __Hotfix0__RefreshCameraByLOD; // 0x20

	public Int32 priority { get; }
	public override Boolean reflectEnable { get; }

	// RVA: 0x3857dd0 VA: 0x7595e6fdd0
	public Int32 get_priority() { }
	// RVA: 0x385825c VA: 0x7595e7025c
	public override Boolean get_reflectEnable() { }
	// RVA: 0x38582e0 VA: 0x7595e702e0
	public Void OnLODStateChanged(LODState state) { }
	// RVA: 0x3857404 VA: 0x7595e6f404
	public Void .ctor(HGReflectionShaderProfile shaderProfile, VDIYRoom vRoom) { }
	// RVA: 0x385835c VA: 0x7595e7035c
	private Void _RefreshCameraByLOD() { }
	// RVA: 0x3858410 VA: 0x7595e70410
	private Boolean <>xLuaBaseProxy_get_reflectEnable() { }
}
```