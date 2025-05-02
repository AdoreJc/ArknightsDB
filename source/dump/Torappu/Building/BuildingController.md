# BuildingController

**Namespace:** `Torappu.Building`


## Fields

- `BlueprintMode _blueprintMode`

- `BuildingArchitecture _architecture`

- `VaultMode _vaultMode`

- `BuildingFactory _factory`

- `BuildingModuleHolder _moduleHolder`

- `Transform _buildingHolder`

- `Options _options`

- `Boolean _useMock`

- `Boolean _localTest`

- `IDIYFeatureComponents m_diy`

- `FurnitureManager m_visitFurnitureManager`

- `DIYRoomModifierManager m_visitModifierManager`

- `OperationMode m_operationMode`

- `BuildingModel m_model`

- `BuildingStateMachine m_stateMachine`

- `BuildingModeRaycastManager m_raycastBlockMngr`

- `BuildingServiceController m_serviceController`

- `HGReflectionShaderProfile m_reflectShaderProfile`

- `Boolean m_isRefectProfileUnavailable`

- `Boolean m_isToDoNotifyOn`


## Properties

- `Boolean isToDoNotifyOn`

- `Boolean localTest`

- `BuildingFactory factory`

- `VaultMode vaultMode`

- `BuildingModel model`

- `BuildingServiceController service`

- `Boolean isEmpty`

- `Options options`

- `IDIYFeatureComponents diy`

- `IFurnitureDataProvider furnitureDataProvider`

- `IDIYRoomModifierDataProvider modifierDataProvider`

- `OperationMode operationMode`

- `IFurnitureManager furnitureManager`

- `IDIYRoomModifierManager DIYRoomModifierManager`

- `IFurnitureTypeDB furnitureTypeDB`

- `IDIYRoomInfoProvider DIYRoomInfoManager`

- `IDIYPresetManager DIYPresetManager`

- `IDIYShop DIYItemShop`

- `IFurnitureStorage furnitureStorage`

- `IFurnitureSaver furnitureSaver`

- `IFurnitureGroupDataProvider furnitureGroupDataDB`

- `Boolean isModeTransiting`

- `Boolean showBuildings`

- `IBuildingMode curBuildingMode`

- `Camera buildingCamera`

- `HGReflectionShaderProfile reflectShaderProfile`


## Methods

- `Boolean get_isToDoNotifyOn()`

- `Void set_isToDoNotifyOn(Boolean)`

- `Boolean get_localTest()`

- `BuildingFactory get_factory()`

- `VaultMode get_vaultMode()`

- `BuildingModel get_model()`

- `BuildingServiceController get_service()`

- `Boolean get_isEmpty()`

- `Options get_options()`

- `IDIYFeatureComponents get_diy()`

- `IFurnitureDataProvider get_furnitureDataProvider()`

- `IDIYRoomModifierDataProvider get_modifierDataProvider()`

- `OperationMode get_operationMode()`

- `Void set_operationMode(OperationMode)`

- `IFurnitureManager get_furnitureManager()`

- `IDIYRoomModifierManager get_DIYRoomModifierManager()`

- `IFurnitureTypeDB get_furnitureTypeDB()`

- `IDIYRoomInfoProvider get_DIYRoomInfoManager()`

- `IDIYPresetManager get_DIYPresetManager()`

- `IDIYShop get_DIYItemShop()`

- `IFurnitureStorage get_furnitureStorage()`

- `IFurnitureSaver get_furnitureSaver()`

- `IFurnitureGroupDataProvider get_furnitureGroupDataDB()`

- `Boolean get_isModeTransiting()`

- `Void ReleaseDIYCachedResources()`

- `Boolean get_showBuildings()`

- `Void set_showBuildings(Boolean)`

- `Void RMOnly_BlockVaultRaycast(BuildingModeRaycastManager, Boolean)`

- `Void RMOnly_BlockBlueprintRaycast(BuildingModeRaycastManager, Boolean)`

- `Void BMOnly_BlockBuildingModeRaycast(IBuildingMode, Boolean)`

- `Void AVGOnly_BlockBuildingModeRaycastForAllModes(RaycastBlockKey, Boolean)`

- `Void BlockBuildingRaycast(RaycastBlockKey, Boolean)`

- `Void InitBuildingForCurrentPlayer(String, PlayerBuilding)`

- `Void InitBuildingForVisit(VisitBuildingResponse)`

- `Void Display()`

- `Void ToggleMode()`

- `Void SwitchMode(TransitionParam)`

- `Sprite GetBlurBlueprintImage(Shader)`

- `T GetState()`

- `IBuildingMode get_curBuildingMode()`

- `Int32 QueryRoomIndex(String)`

- `String QueryRoomSlotId(Int32)`

- `Camera get_buildingCamera()`

- `HGReflectionShaderProfile get_reflectShaderProfile()`

- `Void OnBuildingRouted()`

- `Void FocusRoomInVault(String)`

- `Void OnBackFromFuncFurniturePage(FurnitureSubType)`

- `Boolean CallbackPrivateDormOwner(String)`

- `Void _InitStateMachineForCurPlayer()`

- `Void _InitBindTools()`

- `Void _InitStateMachineForVisiting()`

- `Void _LoadDataForCurPlayer(String, PlayerBuilding)`

- `Void _LoadDataForVisiting(VisitBuildingResponse)`

- `Void _ChangeOperationModeInternal(OperationMode)`

- `Void FixedUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IBuildingContext, IHotfixable
{
	private BlueprintMode _blueprintMode; // 0x18
	private BuildingArchitecture _architecture; // 0x20
	private VaultMode _vaultMode; // 0x28
	private BuildingFactory _factory; // 0x30
	private BuildingModuleHolder _moduleHolder; // 0x38
	private Transform _buildingHolder; // 0x40
	private Options _options; // 0x48
	private Boolean _useMock; // 0x50
	private Boolean _localTest; // 0x51
	private IDIYFeatureComponents m_diy; // 0x58
	private FurnitureManager m_visitFurnitureManager; // 0x60
	private DIYRoomModifierManager m_visitModifierManager; // 0x68
	private OperationMode m_operationMode; // 0x70
	private BuildingModel m_model; // 0x78
	private BuildingStateMachine m_stateMachine; // 0x80
	private EventPool`1 m_eventPool; // 0x88
	private BuildingModeRaycastManager m_raycastBlockMngr; // 0x90
	private BuildingServiceController m_serviceController; // 0x98
	private HGReflectionShaderProfile m_reflectShaderProfile; // 0xa0
	private Boolean m_isRefectProfileUnavailable; // 0xa8
	private List`1 m_bindTools; // 0xb0
	private Boolean m_isToDoNotifyOn; // 0xb8
	private static DelegateBridge __Hotfix0_get_isToDoNotifyOn; // 0x0
	private static DelegateBridge __Hotfix0_set_isToDoNotifyOn; // 0x8
	private static DelegateBridge __Hotfix0_get_localTest; // 0x10
	private static DelegateBridge __Hotfix0_get_factory; // 0x18
	private static DelegateBridge __Hotfix0_get_vaultMode; // 0x20
	private static DelegateBridge __Hotfix0_get_model; // 0x28
	private static DelegateBridge __Hotfix0_get_service; // 0x30
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x38
	private static DelegateBridge __Hotfix0_get_options; // 0x40
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x48
	private static DelegateBridge __Hotfix0_get_diy; // 0x50
	private static DelegateBridge __Hotfix0_get_furnitureDataProvider; // 0x58
	private static DelegateBridge __Hotfix0_get_modifierDataProvider; // 0x60
	private static DelegateBridge __Hotfix0_get_operationMode; // 0x68
	private static DelegateBridge __Hotfix0_set_operationMode; // 0x70
	private static DelegateBridge __Hotfix0_get_furnitureManager; // 0x78
	private static DelegateBridge __Hotfix0_get_DIYRoomModifierManager; // 0x80
	private static DelegateBridge __Hotfix0_get_furnitureTypeDB; // 0x88
	private static DelegateBridge __Hotfix0_get_DIYRoomInfoManager; // 0x90
	private static DelegateBridge __Hotfix0_get_DIYPresetManager; // 0x98
	private static DelegateBridge __Hotfix0_get_DIYItemShop; // 0xa0
	private static DelegateBridge __Hotfix0_get_furnitureStorage; // 0xa8
	private static DelegateBridge __Hotfix0_get_furnitureSaver; // 0xb0
	private static DelegateBridge __Hotfix0_get_furnitureGroupDataDB; // 0xb8
	private static DelegateBridge __Hotfix0_get_isModeTransiting; // 0xc0
	private static DelegateBridge __Hotfix0_ReleaseDIYCachedResources; // 0xc8
	private static DelegateBridge __Hotfix0_OnInit; // 0xd0
	private static DelegateBridge __Hotfix0_get_showBuildings; // 0xd8
	private static DelegateBridge __Hotfix0_set_showBuildings; // 0xe0
	private static DelegateBridge __Hotfix0_RMOnly_BlockVaultRaycast; // 0xe8
	private static DelegateBridge __Hotfix0_RMOnly_BlockBlueprintRaycast; // 0xf0
	private static DelegateBridge __Hotfix0_BMOnly_BlockBuildingModeRaycast; // 0xf8
	private static DelegateBridge __Hotfix0_AVGOnly_BlockBuildingModeRaycastForAllModes; // 0x100
	private static DelegateBridge __Hotfix0_BlockBuildingRaycast; // 0x108
	private static DelegateBridge __Hotfix0_InitBuildingForCurrentPlayer; // 0x110
	private static DelegateBridge __Hotfix0_InitBuildingForVisit; // 0x118
	private static DelegateBridge __Hotfix0_Display; // 0x120
	private static DelegateBridge __Hotfix0_ToggleMode; // 0x128
	private static DelegateBridge __Hotfix0_SwitchMode; // 0x130
	private static DelegateBridge __Hotfix0_GetBlurBlueprintImage; // 0x138
	private static DelegateBridge __Hotfix0_GetState; // 0x140
	private static DelegateBridge __Hotfix0_get_curBuildingMode; // 0x148
	private static DelegateBridge __Hotfix0_QueryRoomIndex; // 0x150
	private static DelegateBridge __Hotfix0_QueryRoomSlotId; // 0x158
	private static DelegateBridge __Hotfix0_get_buildingCamera; // 0x160
	private static DelegateBridge __Hotfix0_get_reflectShaderProfile; // 0x168
	private static DelegateBridge __Hotfix0_IsReflectionEnabled; // 0x170
	private static DelegateBridge __Hotfix0_OnBuildingRouted; // 0x178
	private static DelegateBridge __Hotfix0_ConfigTopMenuRouteEvents; // 0x180
	private static DelegateBridge __Hotfix0_FocusRoomInVault; // 0x188
	private static DelegateBridge __Hotfix0_OnBackFromFuncFurniturePage; // 0x190
	private static DelegateBridge __Hotfix0_CallbackPrivateDormOwner; // 0x198
	private static DelegateBridge __Hotfix0__InitStateMachineForCurPlayer; // 0x1a0
	private static DelegateBridge __Hotfix0__InitBindTools; // 0x1a8
	private static DelegateBridge __Hotfix0__InitStateMachineForVisiting; // 0x1b0
	private static DelegateBridge __Hotfix0__LoadDataForCurPlayer; // 0x1b8
	private static DelegateBridge __Hotfix0__LoadDataForVisiting; // 0x1c0
	private static DelegateBridge __Hotfix0__ChangeOperationModeInternal; // 0x1c8
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x1d0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x1d8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1e0

	public Boolean isToDoNotifyOn { get; set; }
	public Boolean localTest { get; }
	public BuildingFactory factory { get; }
	public VaultMode vaultMode { get; }
	public BuildingModel model { get; }
	public BuildingServiceController service { get; }
	public Boolean isEmpty { get; }
	public Options options { get; }
	public EventPool`1 eventPool { get; }
	private IDIYFeatureComponents diy { get; }
	public IFurnitureDataProvider furnitureDataProvider { get; }
	public IDIYRoomModifierDataProvider modifierDataProvider { get; }
	public OperationMode operationMode { get; set; }
	public IFurnitureManager furnitureManager { get; }
	public IDIYRoomModifierManager DIYRoomModifierManager { get; }
	public IFurnitureTypeDB furnitureTypeDB { get; }
	public IDIYRoomInfoProvider DIYRoomInfoManager { get; }
	public IDIYPresetManager DIYPresetManager { get; }
	public IDIYShop DIYItemShop { get; }
	public IFurnitureStorage furnitureStorage { get; }
	public IFurnitureSaver furnitureSaver { get; }
	public IFurnitureGroupDataProvider furnitureGroupDataDB { get; }
	public Boolean isModeTransiting { get; }
	public Boolean showBuildings { get; set; }
	public IBuildingMode curBuildingMode { get; }
	public Camera buildingCamera { get; }
	public HGReflectionShaderProfile reflectShaderProfile { get; }

	// RVA: 0x3777f10 VA: 0x7595d8ff10
	public Boolean get_isToDoNotifyOn() { }
	// RVA: 0x3777f78 VA: 0x7595d8ff78
	public Void set_isToDoNotifyOn(Boolean value) { }
	// RVA: 0x3778044 VA: 0x7595d90044
	public Boolean get_localTest() { }
	// RVA: 0x37780ac VA: 0x7595d900ac
	public BuildingFactory get_factory() { }
	// RVA: 0x3776c44 VA: 0x7595d8ec44
	public VaultMode get_vaultMode() { }
	// RVA: 0x3778114 VA: 0x7595d90114
	public BuildingModel get_model() { }
	// RVA: 0x377817c VA: 0x7595d9017c
	public BuildingServiceController get_service() { }
	// RVA: 0x37781e4 VA: 0x7595d901e4
	public Boolean get_isEmpty() { }
	// RVA: 0x3778248 VA: 0x7595d90248
	public Options get_options() { }
	// RVA: 0x37782b0 VA: 0x7595d902b0
	public EventPool`1 get_eventPool() { }
	// RVA: 0x3778318 VA: 0x7595d90318
	private IDIYFeatureComponents get_diy() { }
	// RVA: 0x3778478 VA: 0x7595d90478
	public IFurnitureDataProvider get_furnitureDataProvider() { }
	// RVA: 0x377855c VA: 0x7595d9055c
	public IDIYRoomModifierDataProvider get_modifierDataProvider() { }
	// RVA: 0x3778640 VA: 0x7595d90640
	public OperationMode get_operationMode() { }
	// RVA: 0x37786a8 VA: 0x7595d906a8
	public Void set_operationMode(OperationMode value) { }
	// RVA: 0x377890c VA: 0x7595d9090c
	public IFurnitureManager get_furnitureManager() { }
	// RVA: 0x3778a04 VA: 0x7595d90a04
	public IDIYRoomModifierManager get_DIYRoomModifierManager() { }
	// RVA: 0x3778afc VA: 0x7595d90afc
	public IFurnitureTypeDB get_furnitureTypeDB() { }
	// RVA: 0x3778be0 VA: 0x7595d90be0
	public IDIYRoomInfoProvider get_DIYRoomInfoManager() { }
	// RVA: 0x3778cc4 VA: 0x7595d90cc4
	public IDIYPresetManager get_DIYPresetManager() { }
	// RVA: 0x3778da8 VA: 0x7595d90da8
	public IDIYShop get_DIYItemShop() { }
	// RVA: 0x3778e8c VA: 0x7595d90e8c
	public IFurnitureStorage get_furnitureStorage() { }
	// RVA: 0x3778f70 VA: 0x7595d90f70
	public IFurnitureSaver get_furnitureSaver() { }
	// RVA: 0x3779054 VA: 0x7595d91054
	public IFurnitureGroupDataProvider get_furnitureGroupDataDB() { }
	// RVA: 0x377690c VA: 0x7595d8e90c
	public Boolean get_isModeTransiting() { }
	// RVA: 0x3779138 VA: 0x7595d91138
	public Void ReleaseDIYCachedResources() { }
	// RVA: 0x377921c VA: 0x7595d9121c
	protected override Void OnInit() { }
	// RVA: 0x37792b4 VA: 0x7595d912b4
	public Boolean get_showBuildings() { }
	// RVA: 0x3779334 VA: 0x7595d91334
	public Void set_showBuildings(Boolean value) { }
	// RVA: 0x3779420 VA: 0x7595d91420
	public Void RMOnly_BlockVaultRaycast(BuildingModeRaycastManager manager, Boolean isBlock) { }
	// RVA: 0x37794ec VA: 0x7595d914ec
	public Void RMOnly_BlockBlueprintRaycast(BuildingModeRaycastManager manager, Boolean isBlock) { }
	// RVA: 0x37795b8 VA: 0x7595d915b8
	public Void BMOnly_BlockBuildingModeRaycast(IBuildingMode buildingMode, Boolean isBlock) { }
	// RVA: 0x3779650 VA: 0x7595d91650
	public Void AVGOnly_BlockBuildingModeRaycastForAllModes(RaycastBlockKey key, Boolean isBlock) { }
	// RVA: 0x3776cac VA: 0x7595d8ecac
	public Void BlockBuildingRaycast(RaycastBlockKey key, Boolean isBlock) { }
	// RVA: 0x37796f8 VA: 0x7595d916f8
	public Void InitBuildingForCurrentPlayer(String layoutId, PlayerBuilding playerBuilding) { }
	// RVA: 0x3779ccc VA: 0x7595d91ccc
	public Void InitBuildingForVisit(VisitBuildingResponse response) { }
	// RVA: 0x377a0d8 VA: 0x7595d920d8
	public Void Display() { }
	// RVA: 0x377a268 VA: 0x7595d92268
	public Void ToggleMode() { }
	// RVA: 0x VA: 0x0
	public Void SwitchMode(TransitionParam param) { }
	// RVA: 0x377a450 VA: 0x7595d92450
	public Sprite GetBlurBlueprintImage(Shader blurShader) { }
	// RVA: 0x VA: 0x0
	public T GetState() { }
	// RVA: 0x377a514 VA: 0x7595d92514
	public IBuildingMode get_curBuildingMode() { }
	// RVA: 0x377a58c VA: 0x7595d9258c
	public Int32 QueryRoomIndex(String roomId) { }
	// RVA: 0x377a61c VA: 0x7595d9261c
	public String QueryRoomSlotId(Int32 index) { }
	// RVA: 0x377a6ac VA: 0x7595d926ac
	public Camera get_buildingCamera() { }
	// RVA: 0x377a784 VA: 0x7595d92784
	public HGReflectionShaderProfile get_reflectShaderProfile() { }
	// RVA: 0x377a930 VA: 0x7595d92930
	public static Boolean IsReflectionEnabled() { }
	// RVA: 0x377a9f4 VA: 0x7595d929f4
	public Void OnBuildingRouted() { }
	// RVA: 0x377ab00 VA: 0x7595d92b00
	public static Void ConfigTopMenuRouteEvents(CommonTopMenu topMenu) { }
	// RVA: 0x377ad00 VA: 0x7595d92d00
	public Void FocusRoomInVault(String slotId) { }
	// RVA: 0x377ae58 VA: 0x7595d92e58
	public Void OnBackFromFuncFurniturePage(FurnitureSubType subType) { }
	// RVA: 0x377afcc VA: 0x7595d92fcc
	public Boolean CallbackPrivateDormOwner(String slotId) { }
	// RVA: 0x37799a8 VA: 0x7595d919a8
	private Void _InitStateMachineForCurPlayer() { }
	// RVA: 0x3779a98 VA: 0x7595d91a98
	private Void _InitBindTools() { }
	// RVA: 0x3779fe0 VA: 0x7595d91fe0
	private Void _InitStateMachineForVisiting() { }
	// RVA: 0x3779800 VA: 0x7595d91800
	private Void _LoadDataForCurPlayer(String layoutId, PlayerBuilding playerData) { }
	// RVA: 0x3779ea8 VA: 0x7595d91ea8
	private Void _LoadDataForVisiting(VisitBuildingResponse response) { }
	// RVA: 0x3778728 VA: 0x7595d90728
	private Void _ChangeOperationModeInternal(OperationMode newMode) { }
	// RVA: 0x377b2d0 VA: 0x7595d932d0
	private Void FixedUpdate() { }
	// RVA: 0x377b504 VA: 0x7595d93504
	protected override Void OnDestroy() { }
	// RVA: 0x377b58c VA: 0x7595d9358c
	public Void .ctor() { }
}
```