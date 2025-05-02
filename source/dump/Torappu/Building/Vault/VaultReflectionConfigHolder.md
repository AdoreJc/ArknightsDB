# VaultReflectionConfigHolder

**Namespace:** `Torappu.Building.Vault`


## Fields

- `PeriodicTicker m_idleTicker`

- `Int32 m_cameraCount`

- `Boolean m_isInited`

- `ReflectMatFilter m_matFilter`


## Properties

- `IRefectionMaterialFilter reflectFilter`


## Methods

- `IRefectionMaterialFilter get_reflectFilter()`

- `Void InitIfNot()`

- `ReflectCameraHolder GetReflectCameraHolder(VDIYRoom)`

- `Void _RefreshActiveCameras()`

- `Int32 _CalculatePriority()`

- `Void _ReleaseLowPriorityCameras(Int32)`

- `Void _HoldFreeCameras(Int32)`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VaultReflectionConfigHolder : MonoBehaviour, IHotfixable
{
	private String[] _reflectExcludeMaterialNames; // 0x18
	private ReflectCamera[] _reflectCameras; // 0x20
	private PeriodicTicker m_idleTicker; // 0x28
	private Int32 m_cameraCount; // 0x30
	private Boolean m_isInited; // 0x34
	private ReflectMatFilter m_matFilter; // 0x38
	private Dictionary`2 m_cameraHolders; // 0x40
	private List`1 m_activeHolders; // 0x48
	private List`1 m_freeCameras; // 0x50
	private Heap`1 m_enabledHolderPriority; // 0x58
	private static DelegateBridge __Hotfix0_get_reflectFilter; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_GetReflectCameraHolder; // 0x10
	private static DelegateBridge __Hotfix0__RefreshActiveCameras; // 0x18
	private static DelegateBridge __Hotfix0__CalculatePriority; // 0x20
	private static DelegateBridge __Hotfix0__ReleaseLowPriorityCameras; // 0x28
	private static DelegateBridge __Hotfix0__HoldFreeCameras; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public IRefectionMaterialFilter reflectFilter { get; }

	// RVA: 0x3856d98 VA: 0x7595e6ed98
	public IRefectionMaterialFilter get_reflectFilter() { }
	// RVA: 0x3857008 VA: 0x7595e6f008
	public Void InitIfNot() { }
	// RVA: 0x3857208 VA: 0x7595e6f208
	public ReflectCameraHolder GetReflectCameraHolder(VDIYRoom vRoom) { }
	// RVA: 0x38574e0 VA: 0x7595e6f4e0
	private Void _RefreshActiveCameras() { }
	// RVA: 0x38575a8 VA: 0x7595e6f5a8
	private Int32 _CalculatePriority() { }
	// RVA: 0x38578d8 VA: 0x7595e6f8d8
	private Void _ReleaseLowPriorityCameras(Int32 validPriority) { }
	// RVA: 0x3857ad0 VA: 0x7595e6fad0
	private Void _HoldFreeCameras(Int32 validPriority) { }
	// RVA: 0x3857e5c VA: 0x7595e6fe5c
	private Void Update() { }
	// RVA: 0x3857ef8 VA: 0x7595e6fef8
	private Void OnDestroy() { }
	// RVA: 0x3857fb0 VA: 0x7595e6ffb0
	public Void .ctor() { }
}
```