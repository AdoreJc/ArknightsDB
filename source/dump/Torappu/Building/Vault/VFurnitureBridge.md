# VFurnitureBridge

**Namespace:** `Torappu.Building.Vault`


## Fields

- `GridPosition m_gridPos`

- `IAttachPointExporter m_attachPointExporter`

- `Bounds m_bounds`

- `GameObject m_obj`

- `VFurnitureOutline m_vFurnitureOutline`

- `Vector3 <worldCenter>k__BackingField`

- `VGridPlane <plane>k__BackingField`


## Properties

- `String displayName`

- `Vector2 gridPos`

- `GridPosition gridPosAsInt`

- `GridMap gridMap`

- `Vector3 worldCenter`

- `VGridPlane plane`

- `Bounds bounds`

- `Boolean interactable`


## Methods

- `String get_displayName()`

- `Vector2 get_gridPos()`

- `GridPosition get_gridPosAsInt()`

- `GridMap get_gridMap()`

- `Vector3 get_worldCenter()`

- `Void set_worldCenter(Vector3)`

- `VGridPlane get_plane()`

- `Void set_plane(VGridPlane)`

- `Bounds get_bounds()`

- `Boolean get_interactable()`

- `Void OnEnter()`

- `Void OnExit()`

- `Void EnableFurnitureOutline(Boolean)`

- `Boolean IsVCharInteractable(VCharacter)`

- `Void OnVCharInteract(VCharacter)`

- `Void OnInteractableChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VFurnitureBridge : IObject, IVCharInteractable, IHotfixable
{
	private GridPosition m_gridPos; // 0x10
	private InteractSlot[] m_slots; // 0x18
	private IAttachPointExporter m_attachPointExporter; // 0x20
	private Bounds m_bounds; // 0x28
	private GameObject m_obj; // 0x40
	private VFurnitureOutline m_vFurnitureOutline; // 0x48
	private Vector3 <worldCenter>k__BackingField; // 0x50
	private VGridPlane <plane>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_displayName; // 0x0
	private static DelegateBridge __Hotfix0_get_gridPos; // 0x8
	private static DelegateBridge __Hotfix0_get_gridPosAsInt; // 0x10
	private static DelegateBridge __Hotfix0_get_gridMap; // 0x18
	private static DelegateBridge __Hotfix0_get_worldCenter; // 0x20
	private static DelegateBridge __Hotfix0_set_worldCenter; // 0x28
	private static DelegateBridge __Hotfix0_get_plane; // 0x30
	private static DelegateBridge __Hotfix0_set_plane; // 0x38
	private static DelegateBridge __Hotfix0_get_bounds; // 0x40
	private static DelegateBridge __Hotfix0_get_slots; // 0x48
	private static DelegateBridge __Hotfix0_get_interactable; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58
	private static DelegateBridge __Hotfix0_OnEnter; // 0x60
	private static DelegateBridge __Hotfix0_OnExit; // 0x68
	private static DelegateBridge __Hotfix0_EnableFurnitureOutline; // 0x70
	private static DelegateBridge __Hotfix0__GenerateInteractSlots; // 0x78
	private static DelegateBridge __Hotfix0_IsVCharInteractable; // 0x80
	private static DelegateBridge __Hotfix0_OnVCharInteract; // 0x88
	private static DelegateBridge __Hotfix0_OnInteractableChanged; // 0x90

	public String displayName { get; }
	public Vector2 gridPos { get; }
	public GridPosition gridPosAsInt { get; }
	public GridMap gridMap { get; }
	public Vector3 worldCenter { get; set; }
	protected VGridPlane plane { get; set; }
	public Bounds bounds { get; }
	public InteractSlot[] slots { get; }
	public Boolean interactable { get; }

	// RVA: 0x3852d88 VA: 0x7595e6ad88
	public String get_displayName() { }
	// RVA: 0x3852e64 VA: 0x7595e6ae64
	public Vector2 get_gridPos() { }
	// RVA: 0x3852ef8 VA: 0x7595e6aef8
	public GridPosition get_gridPosAsInt() { }
	// RVA: 0x3852f60 VA: 0x7595e6af60
	public GridMap get_gridMap() { }
	// RVA: 0x3853040 VA: 0x7595e6b040
	public Vector3 get_worldCenter() { }
	// RVA: 0x38530a8 VA: 0x7595e6b0a8
	private Void set_worldCenter(Vector3 value) { }
	// RVA: 0x3852fd8 VA: 0x7595e6afd8
	protected VGridPlane get_plane() { }
	// RVA: 0x3853144 VA: 0x7595e6b144
	private Void set_plane(VGridPlane value) { }
	// RVA: 0x38531c8 VA: 0x7595e6b1c8
	public Bounds get_bounds() { }
	// RVA: 0x3853258 VA: 0x7595e6b258
	public InteractSlot[] get_slots() { }
	// RVA: 0x38532c0 VA: 0x7595e6b2c0
	public Boolean get_interactable() { }
	// RVA: 0x385333c VA: 0x7595e6b33c
	public Void .ctor(IAttachPointExporter controller, VGridPlane plane) { }
	// RVA: 0x3853f20 VA: 0x7595e6bf20
	public Void OnEnter() { }
	// RVA: 0x3854038 VA: 0x7595e6c038
	public Void OnExit() { }
	// RVA: 0x384e6b8 VA: 0x7595e666b8
	public Void EnableFurnitureOutline(Boolean value) { }
	// RVA: 0x385376c VA: 0x7595e6b76c
	private InteractSlot[] _GenerateInteractSlots() { }
	// RVA: 0x3854174 VA: 0x7595e6c174
	public Boolean IsVCharInteractable(VCharacter character) { }
	// RVA: 0x3854314 VA: 0x7595e6c314
	public Void OnVCharInteract(VCharacter character) { }
	// RVA: 0x3854718 VA: 0x7595e6c718
	public Void OnInteractableChanged(Boolean interactable) { }
}
```