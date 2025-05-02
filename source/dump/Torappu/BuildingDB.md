# BuildingDB

**Namespace:** `Torappu`


## Methods

- `Void LoadBuildingTable()`

- `Boolean TryGetRoom(String, out, out)`

- `Boolean TryGetRoomData(String, out)`

- `Boolean TryGetRoomData(RoomType, out)`

- `Boolean TryGetItemFormula(String, out)`

- `Boolean TryGetRoomPrefab(String, out)`

- `Boolean TryGetFurnitureData(String, out)`

- `String GetSubTypeDisplayName(FurnitureSubType)`

- `String GetFurnitureTypeDisplayName(FurnitureType)`

- `String GetFilterDisplayName(DIYFilterType)`

- `Void QueryRoomDataByCategoryAndSize(RoomCategory, GridPosition, Action`1)`

- `IRoomBean GetRoomBean(RoomType)`

- `Boolean TryGetLayout(String, out)`

- `Boolean TryGetStorey(String, out)`

- `Boolean CheckIfSkinInteractable(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingDB : ConstTable`2
{
	private Dictionary`2 m_beans; // 0x60
	private String[] m_furnitureNames; // 0x68
	private Dictionary`2 m_interactSkinInfo; // 0x70
	private Dictionary`2 m_formaulaInfo; // 0x78
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_LoadBuildingTable; // 0x8
	private static DelegateBridge __Hotfix0_TryGetRoom; // 0x10
	private static DelegateBridge __Hotfix0_TryGetRoomData; // 0x18
	private static DelegateBridge __Hotfix1_TryGetRoomData; // 0x20
	private static DelegateBridge __Hotfix0_TryGetItemFormula; // 0x28
	private static DelegateBridge __Hotfix0_TryGetRoomPrefab; // 0x30
	private static DelegateBridge __Hotfix0_TryGetFurnitureData; // 0x38
	private static DelegateBridge __Hotfix0_GetAllFurnitureNames; // 0x40
	private static DelegateBridge __Hotfix0_LoadTypes; // 0x48
	private static DelegateBridge __Hotfix0_LoadSubTypesByType; // 0x50
	private static DelegateBridge __Hotfix0_GetSubTypeDisplayName; // 0x58
	private static DelegateBridge __Hotfix0_GetFurnitureTypeDisplayName; // 0x60
	private static DelegateBridge __Hotfix0_GetFilterDisplayName; // 0x68
	private static DelegateBridge __Hotfix0_QueryRoomDataByCategoryAndSize; // 0x70
	private static DelegateBridge __Hotfix0_GetRoomBean; // 0x78
	private static DelegateBridge __Hotfix0_TryGetLayout; // 0x80
	private static DelegateBridge __Hotfix0_TryGetStorey; // 0x88
	private static DelegateBridge __Hotfix0_CheckIfSkinInteractable; // 0x90
	private static DelegateBridge __Hotfix0__LoadRoomBeans; // 0x98
	private static DelegateBridge __Hotfix0__LoadAllFurnitureNames; // 0xa0
	private static DelegateBridge __Hotfix0__LoadInteractSkinInfo; // 0xa8
	private static DelegateBridge __Hotfix0__LoadItemFormulatInfo; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8


	// RVA: 0x31e67b0 VA: 0x75957fe7b0
	protected override Void OnInit() { }
	// RVA: 0x31e6838 VA: 0x75957fe838
	public Void LoadBuildingTable() { }
	// RVA: 0x31e7274 VA: 0x75957ff274
	public Boolean TryGetRoom(String id, out RoomData room, out IRoomBean bean) { }
	// RVA: 0x31e73cc VA: 0x75957ff3cc
	public Boolean TryGetRoomData(String id, out RoomData room) { }
	// RVA: 0x31e74b8 VA: 0x75957ff4b8
	public Boolean TryGetRoomData(RoomType type, out RoomData room) { }
	// RVA: 0x31e764c VA: 0x75957ff64c
	public Boolean TryGetItemFormula(String itemId, out String formulaId) { }
	// RVA: 0x31e7734 VA: 0x75957ff734
	public Boolean TryGetRoomPrefab(String prefabId, out PrefabInfo prefabInfo) { }
	// RVA: 0x31e7820 VA: 0x75957ff820
	public Boolean TryGetFurnitureData(String id, out FurnitureData furnitureData) { }
	// RVA: 0x31e7928 VA: 0x75957ff928
	public String[] GetAllFurnitureNames() { }
	// RVA: 0x31e7a04 VA: 0x75957ffa04
	public List`1 LoadTypes(RoomType selectedRoomId, Boolean filterRoomType) { }
	// RVA: 0x31e7c08 VA: 0x75957ffc08
	public List`1 LoadSubTypesByType(FurnitureType type, RoomType selectedRoomId, Boolean filterRoomType) { }
	// RVA: 0x31e7eec VA: 0x75957ffeec
	public String GetSubTypeDisplayName(FurnitureSubType subType) { }
	// RVA: 0x31e7fec VA: 0x75957fffec
	public String GetFurnitureTypeDisplayName(FurnitureType type) { }
	// RVA: 0x31e80f0 VA: 0x75958000f0
	public String GetFilterDisplayName(DIYFilterType filterType) { }
	// RVA: 0x31e81f4 VA: 0x75958001f4
	public Void QueryRoomDataByCategoryAndSize(RoomCategory category, GridPosition size, Action`1 action) { }
	// RVA: 0x31e8434 VA: 0x7595800434
	public IRoomBean GetRoomBean(RoomType type) { }
	// RVA: 0x31e84dc VA: 0x75958004dc
	public Boolean TryGetLayout(String id, out LayoutData layout) { }
	// RVA: 0x31e85a8 VA: 0x75958005a8
	public Boolean TryGetStorey(String storeyId, out StoreyData storeyData) { }
	// RVA: 0x31e86e8 VA: 0x75958006e8
	public Boolean CheckIfSkinInteractable(String interactId, String skinId) { }
	// RVA: 0x31e68f8 VA: 0x75957fe8f8
	private Dictionary`2 _LoadRoomBeans() { }
	// RVA: 0x31e6acc VA: 0x75957feacc
	private String[] _LoadAllFurnitureNames() { }
	// RVA: 0x31e6d88 VA: 0x75957fed88
	private Dictionary`2 _LoadInteractSkinInfo() { }
	// RVA: 0x31e7020 VA: 0x75957ff020
	private Dictionary`2 _LoadItemFormulatInfo() { }
	// RVA: 0x31e87fc VA: 0x75958007fc
	public Void .ctor() { }
}
```