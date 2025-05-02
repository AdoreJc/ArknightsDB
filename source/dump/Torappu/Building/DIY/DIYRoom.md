# DIYRoom

**Namespace:** `Torappu.Building.DIY`


## Fields

- `Single _groundGridSize`

- `Single _wallGridSize`

- `Int32 _roomWidth`

- `Int32 _roomHeight`

- `Int32 _roomDepth`

- `Camera _mainCamera`

- `Camera _indicatorCamera`

- `Single _cameraMarginMin`

- `Single _cameraMarginMax`

- `Vector3 _cameraOffset`

- `Vector3 _cameraLookOffset`

- `Boolean _useDIYRoomInfo`

- `DIYRoomPrefabSettings _overrideDIYRoomPrefabSetting`

- `Shader _markShader`

- `Texture2D _okTexture`

- `Texture2D _ngTexture`

- `Texture2D _okSelectTexture`

- `Texture2D _ngSelectTexture`

- `GameObject _indicatorProto`

- `GridLocator m_locatorGround`

- `GridLocator m_locatorWall`

- `GridLocator m_locatorCeiling`

- `GridMachine m_gridMachineGround`

- `GridMachine m_gridMachineCarpet`

- `GridMachine m_gridMachinePoster`

- `GridMachine m_gridMachineCeilingDecal`

- `GridMachine3D m_gridMachine3D`

- `IFurnitureProvider m_furnitureProvider`

- `IDIYRoomModifierProvider m_DIYRoomModifierProvider`

- `IDIYRoomInfoProvider m_DIYRoomInfoProvider`

- `DIYRoomModifier m_wallModifier`

- `DIYRoomModifier m_floorModifier`

- `Material m_wallOriginMaterial`

- `Material m_floorOriginMaterial`

- `Mesh m_wallOriginMesh`

- `Mesh m_floorOriginMesh`

- `Int32 m_currentRoomIndex`

- `GameObject m_dormitoryGameObject`

- `Renderer m_wallRenderer`

- `Renderer m_floorRenderer`

- `ReflectCameraHolder m_floorReflect`

- `IRefectionMaterialFilter m_floorRefectMatFilter`

- `MeshRenderer m_floorReflectBound`

- `Single m_floorReflectFadeHeight`

- `MeshFilter m_wallMeshFilter`

- `MeshFilter m_floorMeshFilter`

- `Mesh m_floorGridMesh`

- `Mesh m_wallGridMesh`

- `Mesh m_ceilingGridMesh`

- `Mesh m_ceilingGridMaskMesh`

- `MeshRenderer m_floorGridMeshRenderer`

- `MeshRenderer m_wallGridMeshRenderer`

- `MeshRenderer m_ceilingGridMeshRenderer`

- `MeshRenderer m_ceilingGridMaskMeshRenderer`

- `GameObject m_frame`

- `Boolean m_preIntersectCarpet`

- `Boolean m_preIntersectPoster`

- `Boolean m_preIntersectCeilingDecal`

- `Boolean m_preIntersect3D`

- `Boolean m_awakeInited`

- `Boolean m_alreadySetup`

- `Camera m_outerCamera`


## Properties

- `Camera mainCamera`

- `Camera indicatorCamera`

- `Int32 roomWidth`

- `Int32 roomHeight`

- `Int32 roomDepth`

- `Int32 roomIndex`


## Methods

- `Camera get_mainCamera()`

- `Camera get_indicatorCamera()`

- `Int32 get_roomWidth()`

- `Int32 get_roomHeight()`

- `Int32 get_roomDepth()`

- `Int32 get_roomIndex()`

- `Void Awake()`

- `Void LateUpdate()`

- `Void OnDestroy()`

- `Void SetCameraMarginRatioBottom(Single)`

- `Void _AwakeInit()`

- `Void ClearupGridMesh()`

- `Void SetOuterCamera(Camera)`

- `Void SetReflectMaterialFilter(IRefectionMaterialFilter)`

- `Mesh _GenerateGridMesh(GridLocator, Int32, Int32, Boolean)`

- `Void GatherFloorObstacleRect(Action`1)`

- `Void RemoveHighlightMark(GameObject)`

- `Void ClearHighlightMark()`

- `Boolean HasFurnitureIntersection()`

- `Boolean _CheckIntersectedFurnitures(GridMachine, Int32, Int32)`

- `Boolean _CheckIntersectedFurnitures3D(GridMachine3D, Int32, Int32, Int32)`

- `Void _CheckIntersectedFurnitures(Furniture)`

- `Void _OnFurnitureControlNodePositionSetEvent(FurnitureControlNode, Int32, Int32)`

- `Void _OnFurnitureControlNodeRoomIndexChangeEvent(FurnitureControlNode)`

- `Void _RegisterFurniture(Furniture, Boolean)`

- `Void UpdateMaterialOutlineIfNeeded(Boolean, Single)`

- `Void UpdateMaterialRenderQueue(Boolean)`

- `Void _UnregisterFurniture(Furniture)`

- `Void _ApplyDIYRoomModifier(Renderer[], MeshFilter, DIYRoomModifier, Material, Mesh)`

- `Void _ApplyFloorDIYRoomModifier(DIYRoomModifier)`

- `Void _ApplyWallDIYRoomModifier(DIYRoomModifier)`

- `Void _UpdateCamera()`

- `Void RegisterListener(IListener)`

- `Void UnregisterListener(IListener)`

- `Void ShowGridMesh(Boolean, Boolean, Boolean, Boolean)`

- `Void ShowFrame(Boolean)`

- `Void HideAllGridMesh()`

- `Void UpdateTime(Single)`

- `Void Setup(IFurnitureProvider, IDIYRoomModifierProvider, IDIYRoomInfoProvider, Int32, GameObject, GameObject, Boolean, Boolean, ReflectCameraHolder, Single)`

- `Void _SetupByPrefabSetting(ReflectCameraHolder, Single)`

- `Void _SetupByDIYRoomInfo(GameObject, GameObject, ReflectCameraHolder, Single)`

- `Void SwitchOffFurnitureDisplay(List`1)`

- `Void ClearUp()`

- `Void RefreshIntersection()`

- `Void ForEachFurnitureController(Action`1)`

- `Void ForEachAttachPointExporterAsync(Action`1)`

- `Void OnFurnitureAdded(Furniture)`

- `Void OnFurnitureRemoved(Furniture)`

- `Void OnDIYRoomModifierAdded(DIYRoomModifier)`

- `Void OnDIYRoomModifierRemoved(DIYRoomModifier)`

- `Void OnDIYRoomModifierRoomIndexChanged(Int32, DIYRoomModifier)`

- `Void OnFurniturePositionChanged(Int32, Int32, Furniture)`

- `Void OnFurnitureRotateChanged(Int32, Furniture)`

- `Void OnFurnitureRoomIndexChanged(Int32, Furniture)`

- `Void <_CheckIntersectedFurnitures>b__99_0(IGridRect)`

- `Void <_CheckIntersectedFurnitures>b__99_1(IGridRect, IGridRect)`

- `Void <_CheckIntersectedFurnitures>b__99_2(IGridRect)`

- `Void <_CheckIntersectedFurnitures3D>b__100_0(IGridCube)`

- `Void <_CheckIntersectedFurnitures3D>b__100_1(IGridCube, IGridCube)`

- `Void <_CheckIntersectedFurnitures3D>b__100_2(IGridCube)`

- `Boolean <_SetupByPrefabSetting>b__119_0(DIYRoomInfo)`

- `Void <_SetupByPrefabSetting>b__119_1(DIYRoomInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoom : MonoBehaviour, IHotfixable, IFurnitureProviderListener, IDIYRoomModifierProviderListener, IListener, IListener, ITimeWatcher
{
	private Single _groundGridSize; // 0x18
	private Single _wallGridSize; // 0x1c
	private Int32 _roomWidth; // 0x20
	private Int32 _roomHeight; // 0x24
	private Int32 _roomDepth; // 0x28
	private Camera _mainCamera; // 0x30
	private Camera _indicatorCamera; // 0x38
	private Single _cameraMarginMin; // 0x40
	private Single _cameraMarginMax; // 0x44
	public Vector3 _cameraOffset; // 0x48
	public Vector3 _cameraLookOffset; // 0x54
	private Boolean _useDIYRoomInfo; // 0x60
	private DIYRoomPrefabSettings _overrideDIYRoomPrefabSetting; // 0x68
	private Shader _markShader; // 0x70
	private Texture2D _okTexture; // 0x78
	private Texture2D _ngTexture; // 0x80
	private Texture2D _okSelectTexture; // 0x88
	private Texture2D _ngSelectTexture; // 0x90
	private GameObject _indicatorProto; // 0x98
	private const Int32 VCHARACTER_HEIGHT_BOUNDING_GRID_SIZE; // 0x0
	public const String SHADER_PROPERTY_OUTLINE; // 0x0
	public const Int32 ABOVE_CEILING_RENDER_QUEUE; // 0x0
	private const String UNSUPPORT_ORTHO_LEGACY_NORMAL_SHADER; // 0x0
	private const String UNSUPPORT_ORTHO_LEGACY_ALPHA_SHADER; // 0x0
	private GridLocator m_locatorGround; // 0xa0
	private GridLocator m_locatorWall; // 0xa8
	private GridLocator m_locatorCeiling; // 0xb0
	private GridMachine m_gridMachineGround; // 0xb8
	private GridMachine m_gridMachineCarpet; // 0xc0
	private GridMachine m_gridMachinePoster; // 0xc8
	private GridMachine m_gridMachineCeilingDecal; // 0xd0
	private GridMachine3D m_gridMachine3D; // 0xd8
	private IFurnitureProvider m_furnitureProvider; // 0xe0
	private IDIYRoomModifierProvider m_DIYRoomModifierProvider; // 0xe8
	private IDIYRoomInfoProvider m_DIYRoomInfoProvider; // 0xf0
	private DIYRoomModifier m_wallModifier; // 0xf8
	private DIYRoomModifier m_floorModifier; // 0x100
	private Material m_wallOriginMaterial; // 0x108
	private Material m_floorOriginMaterial; // 0x110
	private Mesh m_wallOriginMesh; // 0x118
	private Mesh m_floorOriginMesh; // 0x120
	private Int32 m_currentRoomIndex; // 0x128
	private GameObject m_dormitoryGameObject; // 0x130
	private Renderer m_wallRenderer; // 0x138
	private Renderer m_floorRenderer; // 0x140
	private ReflectCameraHolder m_floorReflect; // 0x148
	private IRefectionMaterialFilter m_floorRefectMatFilter; // 0x150
	private MeshRenderer m_floorReflectBound; // 0x158
	private Single m_floorReflectFadeHeight; // 0x160
	private Renderer[] m_doorRenderers; // 0x168
	private MeshFilter m_wallMeshFilter; // 0x170
	private MeshFilter m_floorMeshFilter; // 0x178
	private List`1 m_listeners; // 0x180
	private List`1 m_highlightMarks; // 0x188
	private Mesh m_floorGridMesh; // 0x190
	private Mesh m_wallGridMesh; // 0x198
	private Mesh m_ceilingGridMesh; // 0x1a0
	private Mesh m_ceilingGridMaskMesh; // 0x1a8
	private MeshRenderer m_floorGridMeshRenderer; // 0x1b0
	private MeshRenderer m_wallGridMeshRenderer; // 0x1b8
	private MeshRenderer m_ceilingGridMeshRenderer; // 0x1c0
	private MeshRenderer m_ceilingGridMaskMeshRenderer; // 0x1c8
	private List`1 m_obstacleIndicatorList; // 0x1d0
	private GameObject m_frame; // 0x1d8
	private Boolean m_preIntersectCarpet; // 0x1e0
	private Boolean m_preIntersectPoster; // 0x1e1
	private Boolean m_preIntersectCeilingDecal; // 0x1e2
	private Boolean m_preIntersect3D; // 0x1e3
	private List`1 m_furnitureList; // 0x1e8
	private Dictionary`2 m_furnitureMaterial; // 0x1f0
	private Dictionary`2 m_modifiedFurnitureMaterial; // 0x1f8
	private Boolean m_awakeInited; // 0x200
	private Boolean m_alreadySetup; // 0x201
	private Camera m_outerCamera; // 0x208
	private static DelegateBridge __Hotfix0_get_mainCamera; // 0x0
	private static DelegateBridge __Hotfix0_get_indicatorCamera; // 0x8
	private static DelegateBridge __Hotfix0_get_roomWidth; // 0x10
	private static DelegateBridge __Hotfix0_get_roomHeight; // 0x18
	private static DelegateBridge __Hotfix0_get_roomDepth; // 0x20
	private static DelegateBridge __Hotfix0_get_roomIndex; // 0x28
	private static DelegateBridge __Hotfix0_Awake; // 0x30
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_SetCameraMarginRatioBottom; // 0x48
	private static DelegateBridge __Hotfix0__AwakeInit; // 0x50
	private static DelegateBridge __Hotfix0_ClearupGridMesh; // 0x58
	private static DelegateBridge __Hotfix0_SetOuterCamera; // 0x60
	private static DelegateBridge __Hotfix0_SetReflectMaterialFilter; // 0x68
	private static DelegateBridge __Hotfix0__GenerateGridMesh; // 0x70
	private static DelegateBridge __Hotfix0_GatherFloorObstacleRect; // 0x78
	private static DelegateBridge __Hotfix0_RemoveHighlightMark; // 0x80
	private static DelegateBridge __Hotfix0_ClearHighlightMark; // 0x88
	private static DelegateBridge __Hotfix0_HasFurnitureIntersection; // 0x90
	private static DelegateBridge __Hotfix0__CheckIntersectedFurnitures; // 0x98
	private static DelegateBridge __Hotfix0__CheckIntersectedFurnitures3D; // 0xa0
	private static DelegateBridge __Hotfix1__CheckIntersectedFurnitures; // 0xa8
	private static DelegateBridge __Hotfix0__OnFurnitureControlNodePositionSetEvent; // 0xb0
	private static DelegateBridge __Hotfix0__OnFurnitureControlNodeRoomIndexChangeEvent; // 0xb8
	private static DelegateBridge __Hotfix0__RegisterFurniture; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateMaterialOutlineIfNeeded; // 0xc8
	private static DelegateBridge __Hotfix0_UpdateMaterialRenderQueue; // 0xd0
	private static DelegateBridge __Hotfix0__UnregisterFurniture; // 0xd8
	private static DelegateBridge __Hotfix0__ApplyDIYRoomModifier; // 0xe0
	private static DelegateBridge __Hotfix0__ApplyFloorDIYRoomModifier; // 0xe8
	private static DelegateBridge __Hotfix0__ApplyWallDIYRoomModifier; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateCamera; // 0xf8
	private static DelegateBridge __Hotfix0_RegisterListener; // 0x100
	private static DelegateBridge __Hotfix0_UnregisterListener; // 0x108
	private static DelegateBridge __Hotfix0_ShowGridMesh; // 0x110
	private static DelegateBridge __Hotfix0_ShowFrame; // 0x118
	private static DelegateBridge __Hotfix0_HideAllGridMesh; // 0x120
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x128
	private static DelegateBridge __Hotfix0_Setup; // 0x130
	private static DelegateBridge __Hotfix0__SetupByPrefabSetting; // 0x138
	private static DelegateBridge __Hotfix0__SetupByDIYRoomInfo; // 0x140
	private static DelegateBridge __Hotfix0_SwitchOffFurnitureDisplay; // 0x148
	private static DelegateBridge __Hotfix0_ClearUp; // 0x150
	private static DelegateBridge __Hotfix0_RefreshIntersection; // 0x158
	private static DelegateBridge __Hotfix0_ForEachFurnitureController; // 0x160
	private static DelegateBridge __Hotfix0_ForEachAttachPointExporterAsync; // 0x168
	private static DelegateBridge __Hotfix0_OnFurnitureAdded; // 0x170
	private static DelegateBridge __Hotfix0_OnFurnitureRemoved; // 0x178
	private static DelegateBridge __Hotfix0_OnDIYRoomModifierAdded; // 0x180
	private static DelegateBridge __Hotfix0_OnDIYRoomModifierRemoved; // 0x188
	private static DelegateBridge __Hotfix0_OnDIYRoomModifierRoomIndexChanged; // 0x190
	private static DelegateBridge __Hotfix0_OnFurniturePositionChanged; // 0x198
	private static DelegateBridge __Hotfix0_OnFurnitureRotateChanged; // 0x1a0
	private static DelegateBridge __Hotfix0_OnFurnitureRoomIndexChanged; // 0x1a8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b0

	public Camera mainCamera { get; }
	public Camera indicatorCamera { get; }
	public Int32 roomWidth { get; }
	public Int32 roomHeight { get; }
	public Int32 roomDepth { get; }
	public Int32 roomIndex { get; }

	// RVA: 0x37b3680 VA: 0x7595dcb680
	public Camera get_mainCamera() { }
	// RVA: 0x37b36e8 VA: 0x7595dcb6e8
	public Camera get_indicatorCamera() { }
	// RVA: 0x37b3750 VA: 0x7595dcb750
	public Int32 get_roomWidth() { }
	// RVA: 0x37b37b8 VA: 0x7595dcb7b8
	public Int32 get_roomHeight() { }
	// RVA: 0x37b3820 VA: 0x7595dcb820
	public Int32 get_roomDepth() { }
	// RVA: 0x37b3888 VA: 0x7595dcb888
	public Int32 get_roomIndex() { }
	// RVA: 0x37b38f0 VA: 0x7595dcb8f0
	private Void Awake() { }
	// RVA: 0x37b3cd4 VA: 0x7595dcbcd4
	private Void LateUpdate() { }
	// RVA: 0x37b3ef0 VA: 0x7595dcbef0
	private Void OnDestroy() { }
	// RVA: 0x37b4514 VA: 0x7595dcc514
	public Void SetCameraMarginRatioBottom(Single ratio) { }
	// RVA: 0x37b3958 VA: 0x7595dcb958
	private Void _AwakeInit() { }
	// RVA: 0x37b4654 VA: 0x7595dcc654
	private Void ClearupGridMesh() { }
	// RVA: 0x37b479c VA: 0x7595dcc79c
	public Void SetOuterCamera(Camera camera) { }
	// RVA: 0x37b4820 VA: 0x7595dcc820
	public Void SetReflectMaterialFilter(IRefectionMaterialFilter filter) { }
	// RVA: 0x37b48e8 VA: 0x7595dcc8e8
	private Mesh _GenerateGridMesh(GridLocator locator, Int32 size0, Int32 size1, Boolean clockwise) { }
	// RVA: 0x37b4d68 VA: 0x7595dccd68
	public Void GatherFloorObstacleRect(Action`1 action) { }
	// RVA: 0x37b4ea0 VA: 0x7595dccea0
	public Void RemoveHighlightMark(GameObject mark) { }
	// RVA: 0x37b5034 VA: 0x7595dcd034
	public Void ClearHighlightMark() { }
	// RVA: 0x37b5230 VA: 0x7595dcd230
	public Boolean HasFurnitureIntersection() { }
	// RVA: 0x37b53e8 VA: 0x7595dcd3e8
	private Boolean _CheckIntersectedFurnitures(GridMachine gridMachine, Int32 w, Int32 h) { }
	// RVA: 0x37b5598 VA: 0x7595dcd598
	private Boolean _CheckIntersectedFurnitures3D(GridMachine3D gridMachine3D, Int32 w, Int32 h, Int32 d) { }
	// RVA: 0x37b5770 VA: 0x7595dcd770
	private Void _CheckIntersectedFurnitures(Furniture furniture) { }
	// RVA: 0x37b5af4 VA: 0x7595dcdaf4
	private Void _OnFurnitureControlNodePositionSetEvent(FurnitureControlNode node, Int32 oldPos0, Int32 oldPos1) { }
	// RVA: 0x37b5c18 VA: 0x7595dcdc18
	private Void _OnFurnitureControlNodeRoomIndexChangeEvent(FurnitureControlNode node) { }
	// RVA: 0x37b5fc0 VA: 0x7595dcdfc0
	private Void _RegisterFurniture(Furniture furniture, Boolean isAsync) { }
	// RVA: 0x37b7708 VA: 0x7595dcf708
	public Void UpdateMaterialOutlineIfNeeded(Boolean isReset, Single progress) { }
	// RVA: 0x37b7848 VA: 0x7595dcf848
	public Void UpdateMaterialRenderQueue(Boolean isReset) { }
	// RVA: 0x37b5cc0 VA: 0x7595dcdcc0
	private Void _UnregisterFurniture(Furniture furniture) { }
	// RVA: 0x37b804c VA: 0x7595dd004c
	private Void _ApplyDIYRoomModifier(Renderer[] renderers, MeshFilter meshFilter, DIYRoomModifier modifier, Material originMat, Mesh originMesh) { }
	// RVA: 0x37b842c VA: 0x7595dd042c
	private Void _ApplyFloorDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37b855c VA: 0x7595dd055c
	private Void _ApplyWallDIYRoomModifier(DIYRoomModifier modifier) { }
	// RVA: 0x37b3d3c VA: 0x7595dcbd3c
	private Void _UpdateCamera() { }
	// RVA: 0x37b8900 VA: 0x7595dd0900
	public Void RegisterListener(IListener listener) { }
	// RVA: 0x37b8a38 VA: 0x7595dd0a38
	public Void UnregisterListener(IListener listener) { }
	// RVA: 0x37b8b14 VA: 0x7595dd0b14
	public Void ShowGridMesh(Boolean showFloor, Boolean showWall, Boolean showCeiling, Boolean showCeilingMask) { }
	// RVA: 0x37b8cc8 VA: 0x7595dd0cc8
	public Void ShowFrame(Boolean isShow) { }
	// RVA: 0x37b8d4c VA: 0x7595dd0d4c
	public Void HideAllGridMesh() { }
	// RVA: 0x37b8ec0 VA: 0x7595dd0ec0
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x37b9298 VA: 0x7595dd1298
	public Void Setup(IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider DIYRoomModifierProvider, IDIYRoomInfoProvider DIYRoomInfoProvider, Int32 roomIndex, GameObject leftDoorProto, GameObject rightDoorProto, Boolean force, Boolean isAsync, ReflectCameraHolder reflectCameraHolder, Single reflectFadeHeight) { }
	// RVA: 0x37ba0cc VA: 0x7595dd20cc
	private Void _SetupByPrefabSetting(ReflectCameraHolder reflectCameraHolder, Single reflectFadeHeight) { }
	// RVA: 0x37b9ea8 VA: 0x7595dd1ea8
	private Void _SetupByDIYRoomInfo(GameObject leftDoorProto, GameObject rightDoorProto, ReflectCameraHolder reflectCameraHolder, Single reflectFadeHeight) { }
	// RVA: 0x37ba7e8 VA: 0x7595dd27e8
	public Void SwitchOffFurnitureDisplay(List`1 typeList) { }
	// RVA: 0x37b3f58 VA: 0x7595dcbf58
	public Void ClearUp() { }
	// RVA: 0x37ba5d0 VA: 0x7595dd25d0
	public Void RefreshIntersection() { }
	// RVA: 0x37ba918 VA: 0x7595dd2918
	public Void ForEachFurnitureController(Action`1 action) { }
	// RVA: 0x37baa04 VA: 0x7595dd2a04
	public Void ForEachAttachPointExporterAsync(Action`1 action) { }
	// RVA: 0x37baec8 VA: 0x7595dd2ec8
	public Void OnFurnitureAdded(Furniture furniture) { }
	// RVA: 0x37bafa4 VA: 0x7595dd2fa4
	public Void OnFurnitureRemoved(Furniture furniture) { }
	// RVA: 0x37bb070 VA: 0x7595dd3070
	public Void OnDIYRoomModifierAdded(DIYRoomModifier modifier) { }
	// RVA: 0x37bb3ac VA: 0x7595dd33ac
	public Void OnDIYRoomModifierRemoved(DIYRoomModifier modifier) { }
	// RVA: 0x37bb6f8 VA: 0x7595dd36f8
	public Void OnDIYRoomModifierRoomIndexChanged(Int32 oldIndex, DIYRoomModifier modifier) { }
	// RVA: 0x37bbebc VA: 0x7595dd3ebc
	public Void OnFurniturePositionChanged(Int32 oldPos0, Int32 oldPos1, Furniture furniture) { }
	// RVA: 0x37bbf50 VA: 0x7595dd3f50
	public Void OnFurnitureRotateChanged(Int32 dir, Furniture furniture) { }
	// RVA: 0x37bbfd0 VA: 0x7595dd3fd0
	public Void OnFurnitureRoomIndexChanged(Int32 oldIndex, Furniture furniture) { }
	// RVA: 0x37bc090 VA: 0x7595dd4090
	public Void .ctor() { }
	// RVA: 0x37bc344 VA: 0x7595dd4344
	private Void <_CheckIntersectedFurnitures>b__99_0(IGridRect x) { }
	// RVA: 0x37bc4d4 VA: 0x7595dd44d4
	private Void <_CheckIntersectedFurnitures>b__99_1(IGridRect x, IGridRect y) { }
	// RVA: 0x37bc6cc VA: 0x7595dd46cc
	private Void <_CheckIntersectedFurnitures>b__99_2(IGridRect x) { }
	// RVA: 0x37bc840 VA: 0x7595dd4840
	private Void <_CheckIntersectedFurnitures3D>b__100_0(IGridCube x) { }
	// RVA: 0x37bcac8 VA: 0x7595dd4ac8
	private Void <_CheckIntersectedFurnitures3D>b__100_1(IGridCube x, IGridCube y) { }
	// RVA: 0x37bcd74 VA: 0x7595dd4d74
	private Void <_CheckIntersectedFurnitures3D>b__100_2(IGridCube x) { }
	// RVA: 0x37bcee8 VA: 0x7595dd4ee8
	private Boolean <_SetupByPrefabSetting>b__119_0(DIYRoomInfo x) { }
	// RVA: 0x37bcf0c VA: 0x7595dd4f0c
	private Void <_SetupByPrefabSetting>b__119_1(DIYRoomInfo x) { }
}
```