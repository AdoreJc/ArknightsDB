# DeepSeaRPCommonNodeDetailStateBean

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `String m_actId`

- `DeepSeaRPNodeModel m_nodeModel`

- `EventData m_lockedEventData`


## Properties

- `String actId`

- `DeepSeaRPNodeModel nodeModel`

- `EventData lockedEventData`


## Methods

- `String get_actId()`

- `DeepSeaRPNodeModel get_nodeModel()`

- `EventData get_lockedEventData()`

- `Void LoadData(String, DeepSeaRPNodeModel, EventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPCommonNodeDetailStateBean : IStateBean, IHotfixable
{
	private String m_actId; // 0x10
	private DeepSeaRPNodeModel m_nodeModel; // 0x18
	private EventData m_lockedEventData; // 0x20
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_nodeModel; // 0x8
	private static DelegateBridge __Hotfix0_get_lockedEventData; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String actId { get; }
	public DeepSeaRPNodeModel nodeModel { get; }
	public EventData lockedEventData { get; }

	// RVA: 0x29e6c0c VA: 0x7594ffec0c
	public String get_actId() { }
	// RVA: 0x29e6c74 VA: 0x7594ffec74
	public DeepSeaRPNodeModel get_nodeModel() { }
	// RVA: 0x29e6cdc VA: 0x7594ffecdc
	public EventData get_lockedEventData() { }
	// RVA: 0x29e6d44 VA: 0x7594ffed44
	public Void LoadData(String actId, DeepSeaRPNodeModel nodeModel, EventData eventData) { }
	// RVA: 0x29e6e04 VA: 0x7594ffee04
	public Void .ctor() { }
}
```