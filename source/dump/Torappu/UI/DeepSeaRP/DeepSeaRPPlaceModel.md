# DeepSeaRPPlaceModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `String m_placeId`

- `PlaceData m_placeData`

- `PlaceStatus m_status`

- `EventData m_lockEventData`


## Properties

- `EventData lockEventData`

- `PlaceStatus status`

- `PlaceData placeData`


## Methods

- `EventData get_lockEventData()`

- `PlaceStatus get_status()`

- `PlaceData get_placeData()`

- `DeepSeaRPNodeModel FetchActiveNodeModel()`

- `Void InitData(String, PlaceData, Act17sideData)`

- `Void UpdatePlaceStatus(PlayerDeepSea)`

- `Void AddNode(DeepSeaRPNodeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPPlaceModel : IHotfixable
{
	private String m_placeId; // 0x10
	private PlaceData m_placeData; // 0x18
	private List`1 m_nodeList; // 0x20
	private PlaceStatus m_status; // 0x28
	private EventData m_lockEventData; // 0x30
	private static DelegateBridge __Hotfix0_get_lockEventData; // 0x0
	private static DelegateBridge __Hotfix0_get_status; // 0x8
	private static DelegateBridge __Hotfix0_get_placeData; // 0x10
	private static DelegateBridge __Hotfix0_get_nodeList; // 0x18
	private static DelegateBridge __Hotfix0_FetchActiveNodeModel; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0_UpdatePlaceStatus; // 0x30
	private static DelegateBridge __Hotfix0_AddNode; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public EventData lockEventData { get; }
	public PlaceStatus status { get; }
	public PlaceData placeData { get; }
	public List`1 nodeList { get; }

	// RVA: 0x29d284c VA: 0x7594fea84c
	public EventData get_lockEventData() { }
	// RVA: 0x29d23cc VA: 0x7594fea3cc
	public PlaceStatus get_status() { }
	// RVA: 0x29ce6e8 VA: 0x7594fe66e8
	public PlaceData get_placeData() { }
	// RVA: 0x29ce750 VA: 0x7594fe6750
	public List`1 get_nodeList() { }
	// RVA: 0x29d25ec VA: 0x7594fea5ec
	public DeepSeaRPNodeModel FetchActiveNodeModel() { }
	// RVA: 0x29d2aec VA: 0x7594feaaec
	public Void InitData(String placeId, PlaceData placeData, Act17sideData actData) { }
	// RVA: 0x29d3834 VA: 0x7594feb834
	public Void UpdatePlaceStatus(PlayerDeepSea playerDeepSea) { }
	// RVA: 0x29d2f40 VA: 0x7594feaf40
	public Void AddNode(DeepSeaRPNodeModel nodeModel) { }
	// RVA: 0x29d2a7c VA: 0x7594feaa7c
	public Void .ctor() { }
}
```