# VDIYRoom

**Namespace:** `Torappu.Building.Vault`


## Fields

- `DIYRoom _diyRoom`

- `Single _reflectFadeHeight`

- `Int32 m_roomIndex`

- `ReflectCameraHolder m_reflectCameraHolder`

- `Boolean m_needBuildInteractSlot`

- `Byte m_buildInteractSlotLatestNonce`


## Properties

- `Int32 roomIndex`


## Methods

- `Int32 get_roomIndex()`

- `Void EnableVFurnitureOutline(Boolean)`

- `Void EnableFurnitureOutlineBySubType(Boolean, FurnitureSubType)`

- `Boolean CheckHasInteractFurniture()`

- `Void StopAllMusicInteractFurniture()`

- `Void _RefreshFurnitureBridge()`

- `Void _SetupInternalDIYRoom()`

- `Void OnSetup()`

- `Void OnFurnitureRegistered(IFurnitureController)`

- `Void OnFurnitureUnregistered(IFurnitureController)`

- `Void OnFloorModifierChanged(DIYRoomModifier, DIYRoomModifier)`

- `Void OnWallModifierChanged(DIYRoomModifier, DIYRoomModifier)`

- `Void OnIntersectionStateChanged(Boolean)`

- `Void <>xLuaBaseProxy_OnPreInit()`

- `Void <>xLuaBaseProxy_OnPostInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_UpdateVFurniture(Object)`

- `Void <>xLuaBaseProxy_OnDestroyRoom()`

- `Void <>xLuaBaseProxy_OnVCharacterUpdated(VCharacter)`

- `Void <>xLuaBaseProxy_OnVCharacterToDestroy(VCharacter)`

- `Void <>xLuaBaseProxy_OnSelectChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VDIYRoom : VRoom, IListener
{
	private DIYRoom _diyRoom; // 0x80
	private Single _reflectFadeHeight; // 0x88
	private Int32 m_roomIndex; // 0x8c
	private ReflectCameraHolder m_reflectCameraHolder; // 0x90
	private List`1 m_reflectRegistedRenderers; // 0x98
	private List`1 m_vFurnitureList; // 0xa0
	private Boolean m_needBuildInteractSlot; // 0xa8
	private Byte m_buildInteractSlotLatestNonce; // 0xa9
	private static DelegateBridge __Hotfix0_get_roomIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_vFurnitureList; // 0x8
	private static DelegateBridge __Hotfix0_OnPreInit; // 0x10
	private static DelegateBridge __Hotfix0_OnPostInit; // 0x18
	private static DelegateBridge __Hotfix0_EnableVFurnitureOutline; // 0x20
	private static DelegateBridge __Hotfix0_EnableFurnitureOutlineBySubType; // 0x28
	private static DelegateBridge __Hotfix0_CheckHasInteractFurniture; // 0x30
	private static DelegateBridge __Hotfix0_StopAllMusicInteractFurniture; // 0x38
	private static DelegateBridge __Hotfix0__RefreshFurnitureBridge; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_UpdateVFurniture; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroyRoom; // 0x58
	private static DelegateBridge __Hotfix0_GenerateDynamicObstacles; // 0x60
	private static DelegateBridge __Hotfix0_OnVCharacterUpdated; // 0x68
	private static DelegateBridge __Hotfix0_OnVCharacterToDestroy; // 0x70
	private static DelegateBridge __Hotfix0__SetupInternalDIYRoom; // 0x78
	private static DelegateBridge __Hotfix0_OnSelectChanged; // 0x80
	private static DelegateBridge __Hotfix0_OnSetup; // 0x88
	private static DelegateBridge __Hotfix0_OnFurnitureRegistered; // 0x90
	private static DelegateBridge __Hotfix0_OnFurnitureUnregistered; // 0x98
	private static DelegateBridge __Hotfix0_OnFloorModifierChanged; // 0xa0
	private static DelegateBridge __Hotfix0_OnWallModifierChanged; // 0xa8
	private static DelegateBridge __Hotfix0_OnIntersectionStateChanged; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Int32 roomIndex { get; }
	public List`1 vFurnitureList { get; }

	// RVA: 0x385739c VA: 0x7595e6f39c
	public Int32 get_roomIndex() { }
	// RVA: 0x38598f4 VA: 0x7595e718f4
	public List`1 get_vFurnitureList() { }
	// RVA: 0x385995c VA: 0x7595e7195c
	protected override Void OnPreInit() { }
	// RVA: 0x3859c04 VA: 0x7595e71c04
	protected override Void OnPostInit() { }
	// RVA: 0x3859c7c VA: 0x7595e71c7c
	public Void EnableVFurnitureOutline(Boolean value) { }
	// RVA: 0x3859d6c VA: 0x7595e71d6c
	public Void EnableFurnitureOutlineBySubType(Boolean value, FurnitureSubType subType) { }
	// RVA: 0x3859e88 VA: 0x7595e71e88
	public Boolean CheckHasInteractFurniture() { }
	// RVA: 0x3859f14 VA: 0x7595e71f14
	public Void StopAllMusicInteractFurniture() { }
	// RVA: 0x385a040 VA: 0x7595e72040
	private Void _RefreshFurnitureBridge() { }
	// RVA: 0x385a2dc VA: 0x7595e722dc
	public override Void OnEnter() { }
	// RVA: 0x385a368 VA: 0x7595e72368
	protected override Void UpdateVFurniture(Object obj) { }
	// RVA: 0x385a4dc VA: 0x7595e724dc
	protected override Void OnDestroyRoom() { }
	// RVA: 0x385a61c VA: 0x7595e7261c
	protected override ObstacleRect[] GenerateDynamicObstacles(GridPosition gridSize) { }
	// RVA: 0x385a7f4 VA: 0x7595e727f4
	protected override Void OnVCharacterUpdated(VCharacter vc) { }
	// RVA: 0x385a990 VA: 0x7595e72990
	protected override Void OnVCharacterToDestroy(VCharacter vc) { }
	// RVA: 0x38599d0 VA: 0x7595e719d0
	private Void _SetupInternalDIYRoom() { }
	// RVA: 0x385ab2c VA: 0x7595e72b2c
	public override Void OnSelectChanged(Boolean isOn) { }
	// RVA: 0x385abc0 VA: 0x7595e72bc0
	public Void OnSetup() { }
	// RVA: 0x385ac24 VA: 0x7595e72c24
	public Void OnFurnitureRegistered(IFurnitureController controller) { }
	// RVA: 0x385affc VA: 0x7595e72ffc
	public Void OnFurnitureUnregistered(IFurnitureController controller) { }
	// RVA: 0x385b34c VA: 0x7595e7334c
	public Void OnFloorModifierChanged(DIYRoomModifier pre, DIYRoomModifier post) { }
	// RVA: 0x385b3cc VA: 0x7595e733cc
	public Void OnWallModifierChanged(DIYRoomModifier pre, DIYRoomModifier post) { }
	// RVA: 0x385b44c VA: 0x7595e7344c
	public Void OnIntersectionStateChanged(Boolean intersect) { }
	// RVA: 0x385b4c4 VA: 0x7595e734c4
	public Void .ctor() { }
	// RVA: 0x385b610 VA: 0x7595e73610
	private Void <>xLuaBaseProxy_OnPreInit() { }
	// RVA: 0x385b618 VA: 0x7595e73618
	private Void <>xLuaBaseProxy_OnPostInit() { }
	// RVA: 0x385b620 VA: 0x7595e73620
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x385b628 VA: 0x7595e73628
	private Void <>xLuaBaseProxy_UpdateVFurniture(Object P0) { }
	// RVA: 0x385b630 VA: 0x7595e73630
	private Void <>xLuaBaseProxy_OnDestroyRoom() { }
	// RVA: 0x385b638 VA: 0x7595e73638
	private ObstacleRect[] <>xLuaBaseProxy_GenerateDynamicObstacles(GridPosition P0) { }
	// RVA: 0x385b640 VA: 0x7595e73640
	private Void <>xLuaBaseProxy_OnVCharacterUpdated(VCharacter P0) { }
	// RVA: 0x385b648 VA: 0x7595e73648
	private Void <>xLuaBaseProxy_OnVCharacterToDestroy(VCharacter P0) { }
	// RVA: 0x385b650 VA: 0x7595e73650
	private Void <>xLuaBaseProxy_OnSelectChanged(Boolean P0) { }
}
```