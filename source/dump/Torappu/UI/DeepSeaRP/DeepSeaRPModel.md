# DeepSeaRPModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPTechModel techModel`

- `String selectedPlaceId`

- `String groupId`

- `Boolean isRetro`

- `Int32 showToastSequence`

- `String m_selectedZoneId`


## Properties

- `String selectedZoneId`


## Methods

- `String get_selectedZoneId()`

- `Void set_selectedZoneId(String)`

- `Void InitData(Boolean, String, String)`

- `Boolean TrySelectPlaceByStageId(String)`

- `Boolean IsBattleSelected()`

- `DeepSeaRPPlaceModel GetSelectedPlaceModel()`

- `DeepSeaRPNodeModel GetSelectedNodeModel()`

- `EventData GetLockEventData()`

- `Void _InitData(Boolean, Act17sideData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPModel : IHotfixable
{
	public List`1 zoneMapModelList; // 0x10
	public Dictionary`2 placeDict; // 0x18
	public Dictionary`2 nodeDict; // 0x20
	public Dictionary`2 mainlineDict; // 0x28
	public DeepSeaRPTechModel techModel; // 0x30
	public String selectedPlaceId; // 0x38
	public String groupId; // 0x40
	public Boolean isRetro; // 0x48
	public Int32 showToastSequence; // 0x4c
	private Dictionary`2 m_stageToPlaceDict; // 0x50
	private String m_selectedZoneId; // 0x58
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedZoneId; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_TrySelectPlaceByStageId; // 0x18
	private static DelegateBridge __Hotfix0_IsBattleSelected; // 0x20
	private static DelegateBridge __Hotfix0_GetSelectedPlaceModel; // 0x28
	private static DelegateBridge __Hotfix0_GetSelectedNodeModel; // 0x30
	private static DelegateBridge __Hotfix0_GetLockEventData; // 0x38
	private static DelegateBridge __Hotfix0__InitData; // 0x40
	private static DelegateBridge __Hotfix0_GetZoneInfoById; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String selectedZoneId { get; set; }

	// RVA: 0x29ccaf8 VA: 0x7594fe4af8
	public String get_selectedZoneId() { }
	// RVA: 0x29d1000 VA: 0x7594fe9000
	public Void set_selectedZoneId(String value) { }
	// RVA: 0x29d1204 VA: 0x7594fe9204
	public Void InitData(Boolean isRetro_, String groupId_, String zoneId_) { }
	// RVA: 0x29d227c VA: 0x7594fea27c
	public Boolean TrySelectPlaceByStageId(String stageId_) { }
	// RVA: 0x29d2434 VA: 0x7594fea434
	public Boolean IsBattleSelected() { }
	// RVA: 0x29d252c VA: 0x7594fea52c
	public DeepSeaRPPlaceModel GetSelectedPlaceModel() { }
	// RVA: 0x29d24b0 VA: 0x7594fea4b0
	public DeepSeaRPNodeModel GetSelectedNodeModel() { }
	// RVA: 0x29d2780 VA: 0x7594fea780
	public EventData GetLockEventData() { }
	// RVA: 0x29d1368 VA: 0x7594fe9368
	private Void _InitData(Boolean isRetro, Act17sideData actData) { }
	// RVA: 0x29d303c VA: 0x7594feb03c
	public static ZoneInfo GetZoneInfoById(String zoneId, Boolean isRetro) { }
	// RVA: 0x29d3274 VA: 0x7594feb274
	public Void .ctor() { }
}
```