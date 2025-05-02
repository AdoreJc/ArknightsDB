# FurnitureControlNode

**Namespace:** ` `


## Fields

- `Furniture m_furniture`

- `Transform m_parent`

- `ILODHolder m_lodHolder`

- `IDynamicAssetHandler m_assetHandle`

- `IDynamicAssetWrapper m_assetWrapper`

- `GameObject m_gameObject`

- `GridLocator m_locator`

- `GridMachine m_gridMachine`

- `GridMachine3D m_gridMachine3D`

- `GameObject m_gridMark`

- `Mesh m_gridMarkMesh`

- `Material m_gridMarkMat`

- `Int32 m_maxPos0`

- `Int32 m_maxPos1`

- `Int32 m_roomIndex`

- `Boolean m_markState`

- `Boolean m_markWaitingForHide`

- `Boolean m_select`

- `Boolean m_interactable`

- `IListener m_originListener`

- `Single m_xUnit`

- `Single m_yUnit`

- `Single m_zUnit`

- `Shader m_markShader`

- `ReflectCameraHolder m_reflectCameraHolder`

- `IRefectionMaterialFilter m_reflectFilter`

- `Texture2D <okTexture>k__BackingField`

- `Texture2D <ngTexture>k__BackingField`

- `Texture2D <okSelectTexture>k__BackingField`

- `Texture2D <ngSelectTexture>k__BackingField`


## Properties

- `Texture2D okTexture`

- `Texture2D ngTexture`

- `Texture2D okSelectTexture`

- `Texture2D ngSelectTexture`

- `Int32 pos0`

- `Int32 pos1`

- `Int32 dir`

- `Furniture furniture`

- `GameObject gameObject`

- `GridMachine gridMachine`

- `GridMachine3D gridMachine3D`

- `String displayName`

- `Bounds bounds`

- `Vector3 center`

- `Int32 sizeX`

- `Int32 sizeY`

- `Int32 sizeZ`

- `FurnitureLocationType locationType`

- `Boolean isPrefabLoaded`

- `Boolean isReleased`

- `GameObject gridMark`

- `Material gridMarkMat`

- `Boolean isSelected`

- `Boolean isEnableRotate`

- `Boolean isInteractable`


## Methods

- `Texture2D get_okTexture()`

- `Void set_okTexture(Texture2D)`

- `Texture2D get_ngTexture()`

- `Void set_ngTexture(Texture2D)`

- `Texture2D get_okSelectTexture()`

- `Void set_okSelectTexture(Texture2D)`

- `Texture2D get_ngSelectTexture()`

- `Void set_ngSelectTexture(Texture2D)`

- `Void add_positionSetEvent(Action`3)`

- `Void remove_positionSetEvent(Action`3)`

- `Void add_roomIndexChangeEvent(Action`1)`

- `Void remove_roomIndexChangeEvent(Action`1)`

- `Int32 get_pos0()`

- `Int32 get_pos1()`

- `Int32 get_dir()`

- `Furniture get_furniture()`

- `GameObject get_gameObject()`

- `GridMachine get_gridMachine()`

- `GridMachine3D get_gridMachine3D()`

- `String get_displayName()`

- `Bounds get_bounds()`

- `Vector3 get_center()`

- `Int32 get_sizeX()`

- `Int32 get_sizeY()`

- `Int32 get_sizeZ()`

- `FurnitureLocationType get_locationType()`

- `Boolean get_isPrefabLoaded()`

- `Boolean get_isReleased()`

- `Void GatherMaterials(Dictionary`2, Dictionary`2)`

- `Void UpdateMaterials(Dictionary`2, Dictionary`2, Boolean)`

- `Boolean _TryFindModifiedMat(Dictionary`2, Dictionary`2, Material, Boolean, out)`

- `Void UpdatePropertyBlock(Boolean, Single)`

- `Vector3 GetLocation(Int32, Int32)`

- `GameObject get_gridMark()`

- `Material get_gridMarkMat()`

- `Void _UpdateMarkTexture()`

- `Int32 _GetFurnitureWidth()`

- `Int32 _GetFurnitureHeight()`

- `Int32 _GetFurnitureCurrentWidth()`

- `Int32 _GetFurnitureCurrentHeight()`

- `Int32 _GetFurnitureDimY()`

- `Void _OnFurnitureGameObjectReload()`

- `Void _RegisterReflectObject()`

- `Void _ReleaseReflectObject()`

- `Void _OnFurnitureGameObjectRelease()`

- `Void OnLODStateChanged(LODState)`

- `Void UpdateFrame()`

- `Void _InitFurnitureGameObject(GameObject, Transform)`

- `Void ReleaseFurniture(Boolean)`

- `Void OnFurniturePositionChanged(Int32, Int32, Furniture)`

- `Void OnFurnitureRotateChanged(Int32, Furniture)`

- `Void OnFurnitureRoomIndexChanged(Int32, Furniture)`

- `Int32 GetFurnitureCurrentWidth()`

- `Int32 GetFurnitureCurrentHeight()`

- `Int32 GetFurnitureDimY()`

- `Boolean TrySetPosition(Int32, Int32)`

- `Boolean TryRotateToNext()`

- `Boolean FurnitureEquals(Furniture)`

- `Void SetMarkState(Boolean)`

- `Void SetSelect(Boolean)`

- `Boolean get_isSelected()`

- `Boolean get_isEnableRotate()`

- `Void SetInteractable(Boolean)`

- `Boolean get_isInteractable()`

- `Void ShowMark()`

- `Void HideMark()`

- `Boolean RegisterOnGameObjectLoaded(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FurnitureControlNode : IFurnitureController, ISpaceOccupation, IHotfixable, IAttachPointExporter, IListener, ILODListener
{
	private Furniture m_furniture; // 0x10
	private Transform m_parent; // 0x18
	private ILODHolder m_lodHolder; // 0x20
	private IDynamicAssetHandler m_assetHandle; // 0x28
	private IDynamicAssetWrapper m_assetWrapper; // 0x30
	private GameObject m_gameObject; // 0x38
	private GridLocator m_locator; // 0x40
	private GridMachine m_gridMachine; // 0x48
	private GridMachine3D m_gridMachine3D; // 0x50
	private GameObject m_gridMark; // 0x58
	private Mesh m_gridMarkMesh; // 0x60
	private Material m_gridMarkMat; // 0x68
	private Int32 m_maxPos0; // 0x70
	private Int32 m_maxPos1; // 0x74
	private Int32 m_roomIndex; // 0x78
	private Boolean m_markState; // 0x7c
	private Boolean m_markWaitingForHide; // 0x7d
	private Boolean m_select; // 0x7e
	private Boolean m_interactable; // 0x7f
	private IListener m_originListener; // 0x80
	private Single m_xUnit; // 0x88
	private Single m_yUnit; // 0x8c
	private Single m_zUnit; // 0x90
	private Shader m_markShader; // 0x98
	private ReflectCameraHolder m_reflectCameraHolder; // 0xa0
	private IRefectionMaterialFilter m_reflectFilter; // 0xa8
	private List`1 m_registeredRenderer; // 0xb0
	private Action`1 m_onGameObjectLoaded; // 0xb8
	private List`1 m_furnitureLodAllNames; // 0xc0
	private List`1 m_furnitureLodTranforms; // 0xc8
	private Texture2D <okTexture>k__BackingField; // 0xd0
	private Texture2D <ngTexture>k__BackingField; // 0xd8
	private Texture2D <okSelectTexture>k__BackingField; // 0xe0
	private Texture2D <ngSelectTexture>k__BackingField; // 0xe8
	private List`1 _meshRendererList; // 0xf0
	private static MaterialPropertyBlock s_normalMaterialProp; // 0x0
	private static Single OUTLINE_WIDTH_CEILING; // 0x8
	private static Single OUTLINE_WIDTH_NORMAL; // 0xc
	public static String FURNI_OBJ_PREFIX; // 0x10
	private Action`3 positionSetEvent; // 0xf8
	private Action`1 roomIndexChangeEvent; // 0x100
	private static DelegateBridge __Hotfix0_get_okTexture; // 0x18
	private static DelegateBridge __Hotfix0_set_okTexture; // 0x20
	private static DelegateBridge __Hotfix0_get_ngTexture; // 0x28
	private static DelegateBridge __Hotfix0_set_ngTexture; // 0x30
	private static DelegateBridge __Hotfix0_get_okSelectTexture; // 0x38
	private static DelegateBridge __Hotfix0_set_okSelectTexture; // 0x40
	private static DelegateBridge __Hotfix0_get_ngSelectTexture; // 0x48
	private static DelegateBridge __Hotfix0_set_ngSelectTexture; // 0x50
	private static DelegateBridge __Hotfix0_add_positionSetEvent; // 0x58
	private static DelegateBridge __Hotfix0_remove_positionSetEvent; // 0x60
	private static DelegateBridge __Hotfix0_add_roomIndexChangeEvent; // 0x68
	private static DelegateBridge __Hotfix0_remove_roomIndexChangeEvent; // 0x70
	private static DelegateBridge __Hotfix0_get_pos0; // 0x78
	private static DelegateBridge __Hotfix0_get_pos1; // 0x80
	private static DelegateBridge __Hotfix0_get_dir; // 0x88
	private static DelegateBridge __Hotfix0_get_furniture; // 0x90
	private static DelegateBridge __Hotfix0_get_gameObject; // 0x98
	private static DelegateBridge __Hotfix0_get_gridMachine; // 0xa0
	private static DelegateBridge __Hotfix0_get_gridMachine3D; // 0xa8
	private static DelegateBridge __Hotfix0_get_normalMaterialProp; // 0xb0
	private static DelegateBridge __Hotfix0_get_displayName; // 0xb8
	private static DelegateBridge __Hotfix0_get_bounds; // 0xc0
	private static DelegateBridge __Hotfix0_get_center; // 0xc8
	private static DelegateBridge __Hotfix0_get_sizeX; // 0xd0
	private static DelegateBridge __Hotfix0_get_sizeY; // 0xd8
	private static DelegateBridge __Hotfix0_get_sizeZ; // 0xe0
	private static DelegateBridge __Hotfix0_get_locationType; // 0xe8
	private static DelegateBridge __Hotfix0_get_isPrefabLoaded; // 0xf0
	private static DelegateBridge __Hotfix0_get_isReleased; // 0xf8
	private static DelegateBridge __Hotfix0_GatherMaterials; // 0x100
	private static DelegateBridge __Hotfix0_UpdateMaterials; // 0x108
	private static DelegateBridge __Hotfix0__TryFindModifiedMat; // 0x110
	private static DelegateBridge __Hotfix0_UpdatePropertyBlock; // 0x118
	private static DelegateBridge __Hotfix0_GetLocation; // 0x120
	private static DelegateBridge __Hotfix0_get_gridMark; // 0x128
	private static DelegateBridge __Hotfix0_get_gridMarkMat; // 0x130
	private static DelegateBridge __Hotfix0__UpdateMarkTexture; // 0x138
	private static DelegateBridge __Hotfix0__GetFurnitureWidth; // 0x140
	private static DelegateBridge __Hotfix0__GetFurnitureHeight; // 0x148
	private static DelegateBridge __Hotfix0__GetFurnitureCurrentWidth; // 0x150
	private static DelegateBridge __Hotfix0__GetFurnitureCurrentHeight; // 0x158
	private static DelegateBridge __Hotfix0__GetFurnitureDimY; // 0x160
	private static DelegateBridge __Hotfix0__OnFurnitureGameObjectReload; // 0x168
	private static DelegateBridge __Hotfix0__RegisterReflectObject; // 0x170
	private static DelegateBridge __Hotfix0__ReleaseReflectObject; // 0x178
	private static DelegateBridge __Hotfix0__OnFurnitureGameObjectRelease; // 0x180
	private static DelegateBridge _c__Hotfix0_ctor; // 0x188
	private static DelegateBridge __Hotfix0_OnLODStateChanged; // 0x190
	private static DelegateBridge __Hotfix0_UpdateFrame; // 0x198
	private static DelegateBridge __Hotfix0__InitFurnitureGameObject; // 0x1a0
	private static DelegateBridge __Hotfix0_ReleaseFurniture; // 0x1a8
	private static DelegateBridge __Hotfix0_OnFurniturePositionChanged; // 0x1b0
	private static DelegateBridge __Hotfix0_OnFurnitureRotateChanged; // 0x1b8
	private static DelegateBridge __Hotfix0_OnFurnitureRoomIndexChanged; // 0x1c0
	private static DelegateBridge __Hotfix0_GetFurnitureCurrentWidth; // 0x1c8
	private static DelegateBridge __Hotfix0_GetFurnitureCurrentHeight; // 0x1d0
	private static DelegateBridge __Hotfix0_GetFurnitureDimY; // 0x1d8
	private static DelegateBridge __Hotfix0_TrySetPosition; // 0x1e0
	private static DelegateBridge __Hotfix0_TryRotateToNext; // 0x1e8
	private static DelegateBridge __Hotfix0_FurnitureEquals; // 0x1f0
	private static DelegateBridge __Hotfix0_get_attachPoints; // 0x1f8
	private static DelegateBridge __Hotfix0_SetMarkState; // 0x200
	private static DelegateBridge __Hotfix0_SetSelect; // 0x208
	private static DelegateBridge __Hotfix0_get_isSelected; // 0x210
	private static DelegateBridge __Hotfix0_get_isEnableRotate; // 0x218
	private static DelegateBridge __Hotfix0_SetInteractable; // 0x220
	private static DelegateBridge __Hotfix0_get_isInteractable; // 0x228
	private static DelegateBridge __Hotfix0_ShowMark; // 0x230
	private static DelegateBridge __Hotfix0_HideMark; // 0x238
	private static DelegateBridge __Hotfix0_RegisterOnGameObjectLoaded; // 0x240

	public Texture2D okTexture { get; set; }
	public Texture2D ngTexture { get; set; }
	public Texture2D okSelectTexture { get; set; }
	public Texture2D ngSelectTexture { get; set; }
	public Int32 pos0 { get; }
	public Int32 pos1 { get; }
	public Int32 dir { get; }
	public Furniture furniture { get; }
	public GameObject gameObject { get; }
	public GridMachine gridMachine { get; }
	public GridMachine3D gridMachine3D { get; }
	public static MaterialPropertyBlock normalMaterialProp { get; }
	public String displayName { get; }
	public Bounds bounds { get; }
	public Vector3 center { get; }
	public Int32 sizeX { get; }
	public Int32 sizeY { get; }
	public Int32 sizeZ { get; }
	public FurnitureLocationType locationType { get; }
	private Boolean isPrefabLoaded { get; }
	private Boolean isReleased { get; }
	private GameObject gridMark { get; }
	private Material gridMarkMat { get; }
	public IEnumerable`1 attachPoints { get; }
	public Boolean isSelected { get; }
	public Boolean isEnableRotate { get; }
	public Boolean isInteractable { get; }

	// RVA: 0x37bd180 VA: 0x7595dd5180
	public Texture2D get_okTexture() { }
	// RVA: 0x37b7198 VA: 0x7595dcf198
	public Void set_okTexture(Texture2D value) { }
	// RVA: 0x37bd1f8 VA: 0x7595dd51f8
	public Texture2D get_ngTexture() { }
	// RVA: 0x37b722c VA: 0x7595dcf22c
	public Void set_ngTexture(Texture2D value) { }
	// RVA: 0x37bd270 VA: 0x7595dd5270
	public Texture2D get_okSelectTexture() { }
	// RVA: 0x37b72c0 VA: 0x7595dcf2c0
	public Void set_okSelectTexture(Texture2D value) { }
	// RVA: 0x37bd2e8 VA: 0x7595dd52e8
	public Texture2D get_ngSelectTexture() { }
	// RVA: 0x37b7354 VA: 0x7595dcf354
	public Void set_ngSelectTexture(Texture2D value) { }
	// RVA: 0x37b6f8c VA: 0x7595dcef8c
	public Void add_positionSetEvent(Action`3 value) { }
	// RVA: 0x37b798c VA: 0x7595dcf98c
	public Void remove_positionSetEvent(Action`3 value) { }
	// RVA: 0x37b7090 VA: 0x7595dcf090
	public Void add_roomIndexChangeEvent(Action`1 value) { }
	// RVA: 0x37b7a90 VA: 0x7595dcfa90
	public Void remove_roomIndexChangeEvent(Action`1 value) { }
	// RVA: 0x37bd360 VA: 0x7595dd5360
	public Int32 get_pos0() { }
	// RVA: 0x37bd3e4 VA: 0x7595dd53e4
	public Int32 get_pos1() { }
	// RVA: 0x37bd468 VA: 0x7595dd5468
	public Int32 get_dir() { }
	// RVA: 0x37b5ba0 VA: 0x7595dcdba0
	public Furniture get_furniture() { }
	// RVA: 0x37bd4ec VA: 0x7595dd54ec
	public GameObject get_gameObject() { }
	// RVA: 0x37bd564 VA: 0x7595dd5564
	public GridMachine get_gridMachine() { }
	// RVA: 0x37bd5dc VA: 0x7595dd55dc
	public GridMachine3D get_gridMachine3D() { }
	// RVA: 0x37bd654 VA: 0x7595dd5654
	public static MaterialPropertyBlock get_normalMaterialProp() { }
	// RVA: 0x37bd758 VA: 0x7595dd5758
	public String get_displayName() { }
	// RVA: 0x37bd874 VA: 0x7595dd5874
	public Bounds get_bounds() { }
	// RVA: 0x37be038 VA: 0x7595dd6038
	public Vector3 get_center() { }
	// RVA: 0x37bdb80 VA: 0x7595dd5b80
	public Int32 get_sizeX() { }
	// RVA: 0x37bdcdc VA: 0x7595dd5cdc
	public Int32 get_sizeY() { }
	// RVA: 0x37bdddc VA: 0x7595dd5ddc
	public Int32 get_sizeZ() { }
	// RVA: 0x37bdf38 VA: 0x7595dd5f38
	public FurnitureLocationType get_locationType() { }
	// RVA: 0x37be0e0 VA: 0x7595dd60e0
	private Boolean get_isPrefabLoaded() { }
	// RVA: 0x37be188 VA: 0x7595dd6188
	private Boolean get_isReleased() { }
	// RVA: 0x37b73e8 VA: 0x7595dcf3e8
	public Void GatherMaterials(Dictionary`2 matDict, Dictionary`2 modifiedMatDict) { }
	// RVA: 0x37be208 VA: 0x7595dd6208
	public Void UpdateMaterials(Dictionary`2 matPairs, Dictionary`2 modifierMatPairs, Boolean isReset) { }
	// RVA: 0x37be390 VA: 0x7595dd6390
	private Boolean _TryFindModifiedMat(Dictionary`2 matPairs, Dictionary`2 modifierMatPairs, Material mat, Boolean revert, out Material foundMat) { }
	// RVA: 0x37be5c0 VA: 0x7595dd65c0
	public Void UpdatePropertyBlock(Boolean isReset, Single progress) { }
	// RVA: 0x37bda28 VA: 0x7595dd5a28
	public Vector3 GetLocation(Int32 pos0, Int32 pos1) { }
	// RVA: 0x37be8b4 VA: 0x7595dd68b4
	private GameObject get_gridMark() { }
	// RVA: 0x37bf7c8 VA: 0x7595dd77c8
	private Material get_gridMarkMat() { }
	// RVA: 0x37be6f0 VA: 0x7595dd66f0
	private Void _UpdateMarkTexture() { }
	// RVA: 0x37bf6d8 VA: 0x7595dd76d8
	private Int32 _GetFurnitureWidth() { }
	// RVA: 0x37bf4a8 VA: 0x7595dd74a8
	private Int32 _GetFurnitureHeight() { }
	// RVA: 0x37bf938 VA: 0x7595dd7938
	private Int32 _GetFurnitureCurrentWidth() { }
	// RVA: 0x37bfa7c VA: 0x7595dd7a7c
	private Int32 _GetFurnitureCurrentHeight() { }
	// RVA: 0x37bfcfc VA: 0x7595dd7cfc
	private Int32 _GetFurnitureDimY() { }
	// RVA: 0x37bfdf0 VA: 0x7595dd7df0
	private Void _OnFurnitureGameObjectReload() { }
	// RVA: 0x37bfe78 VA: 0x7595dd7e78
	private Void _RegisterReflectObject() { }
	// RVA: 0x37c00a0 VA: 0x7595dd80a0
	private Void _ReleaseReflectObject() { }
	// RVA: 0x37c01e4 VA: 0x7595dd81e4
	public Void _OnFurnitureGameObjectRelease() { }
	// RVA: 0x37b67fc VA: 0x7595dce7fc
	public Void .ctor(Furniture furniture, Transform parent, GridLocator locator, GridMachine machine, GridMachine3D machine3D, Int32 width, Int32 height, Int32 deep, Int32 roomIndex, Single xUnit, Single yUnit, Single zUnit, Shader markShader, ReflectCameraHolder reflectCameraHolder, IRefectionMaterialFilter reflectFilter, Boolean isAsync) { }
	// RVA: 0x37c0c2c VA: 0x7595dd8c2c
	public Void OnLODStateChanged(LODState state) { }
	// RVA: 0x37b904c VA: 0x7595dd104c
	public Void UpdateFrame() { }
	// RVA: 0x37c026c VA: 0x7595dd826c
	private Void _InitFurnitureGameObject(GameObject prefab, Transform parent) { }
	// RVA: 0x37b7b98 VA: 0x7595dcfb98
	public Void ReleaseFurniture(Boolean recoverListener) { }
	// RVA: 0x37c100c VA: 0x7595dd900c
	public Void OnFurniturePositionChanged(Int32 oldPos0, Int32 oldPos1, Furniture furniture) { }
	// RVA: 0x37c1110 VA: 0x7595dd9110
	public Void OnFurnitureRotateChanged(Int32 dir, Furniture furniture) { }
	// RVA: 0x37c1244 VA: 0x7595dd9244
	public Void OnFurnitureRoomIndexChanged(Int32 oldIndex, Furniture furniture) { }
	// RVA: 0x37c12fc VA: 0x7595dd92fc
	public Int32 GetFurnitureCurrentWidth() { }
	// RVA: 0x37c1374 VA: 0x7595dd9374
	public Int32 GetFurnitureCurrentHeight() { }
	// RVA: 0x37c13ec VA: 0x7595dd93ec
	public Int32 GetFurnitureDimY() { }
	// RVA: 0x37c1464 VA: 0x7595dd9464
	public Boolean TrySetPosition(Int32 pos0, Int32 pos1) { }
	// RVA: 0x37c157c VA: 0x7595dd957c
	public Boolean TryRotateToNext() { }
	// RVA: 0x37c17a4 VA: 0x7595dd97a4
	public Boolean FurnitureEquals(Furniture furniture) { }
	// RVA: 0x37c1838 VA: 0x7595dd9838
	public IEnumerable`1 get_attachPoints() { }
	// RVA: 0x37c1930 VA: 0x7595dd9930
	public Void SetMarkState(Boolean ok) { }
	// RVA: 0x37c1a74 VA: 0x7595dd9a74
	public Void SetSelect(Boolean select) { }
	// RVA: 0x37c1b54 VA: 0x7595dd9b54
	public Boolean get_isSelected() { }
	// RVA: 0x37c1bcc VA: 0x7595dd9bcc
	public Boolean get_isEnableRotate() { }
	// RVA: 0x37c1d00 VA: 0x7595dd9d00
	public Void SetInteractable(Boolean interactable) { }
	// RVA: 0x37c1d90 VA: 0x7595dd9d90
	public Boolean get_isInteractable() { }
	// RVA: 0x37c1e08 VA: 0x7595dd9e08
	public Void ShowMark() { }
	// RVA: 0x37c1eb8 VA: 0x7595dd9eb8
	public Void HideMark() { }
	// RVA: 0x37bad2c VA: 0x7595dd2d2c
	public Boolean RegisterOnGameObjectLoaded(Action`1 onLoaded) { }
	// RVA: 0x37c1fb0 VA: 0x7595dd9fb0
	private static Void .cctor() { }
}
```