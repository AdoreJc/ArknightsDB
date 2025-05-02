# RL03TotemBuffMapViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RoguelikeDungeonZone curZone`

- `Int32 curDepth`

- `Int32 curIndex`

- `String topicId`

- `RL03TotemViewModel m_cachedLocationTotemViewModel`

- `TotemMapNodeSelectType m_mapSelectType`

- `Boolean m_hasNodeSelected`


## Properties

- `Boolean hasNodeSelected`


## Methods

- `Boolean get_hasNodeSelected()`

- `Void LoadData(String, Dictionary`2)`

- `RL03TotemBuffMapNodeViewModel GetNodeViewModel(String)`

- `Void UpdateSelectableNodes(RL03TotemViewModel)`

- `Void SelectNode(Int32, Int32)`

- `Void _CalcAllLocationTotemSelectResult(Dictionary`2)`

- `Boolean _CheckIfLocationTotemChanged(RL03TotemViewModel)`

- `Void _ClearAllSelectInMap()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffMapViewModel : IHotfixable
{
	public RoguelikeDungeonZone curZone; // 0x10
	public Int32 curDepth; // 0x18
	public Int32 curIndex; // 0x1c
	public Dictionary`2 nodeViewModelDict; // 0x20
	public String topicId; // 0x28
	private List`1 m_manualSelectableNodeViewModels; // 0x30
	private RL03TotemViewModel m_cachedLocationTotemViewModel; // 0x38
	private TotemMapNodeSelectType m_mapSelectType; // 0x40
	private Boolean m_hasNodeSelected; // 0x44
	private Dictionary`2 m_locationTotemSelectResultDict; // 0x48
	private static DelegateBridge __Hotfix0_get_hasNodeSelected; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_GetMapNoneSelectableNodeLocationTotemList; // 0x10
	private static DelegateBridge __Hotfix0_GetNodeViewModel; // 0x18
	private static DelegateBridge __Hotfix0_UpdateSelectableNodes; // 0x20
	private static DelegateBridge __Hotfix0_SelectNode; // 0x28
	private static DelegateBridge __Hotfix0_GetSelectNodes; // 0x30
	private static DelegateBridge __Hotfix0__CalcAllLocationTotemSelectResult; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfLocationTotemChanged; // 0x40
	private static DelegateBridge __Hotfix0__ClearAllSelectInMap; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean hasNodeSelected { get; }

	// RVA: 0x2baa700 VA: 0x75951c2700
	public Boolean get_hasNodeSelected() { }
	// RVA: 0x2baaa78 VA: 0x75951c2a78
	public Void LoadData(String topicId, Dictionary`2 locationTotemItemDict) { }
	// RVA: 0x2bab098 VA: 0x75951c3098
	public List`1 GetMapNoneSelectableNodeLocationTotemList() { }
	// RVA: 0x2baa64c VA: 0x75951c264c
	public RL03TotemBuffMapNodeViewModel GetNodeViewModel(String nodeCode) { }
	// RVA: 0x2bab354 VA: 0x75951c3354
	public Void UpdateSelectableNodes(RL03TotemViewModel locationTotemViewModel) { }
	// RVA: 0x2baba30 VA: 0x75951c3a30
	public Void SelectNode(Int32 depth, Int32 index) { }
	// RVA: 0x2babb88 VA: 0x75951c3b88
	public List`1 GetSelectNodes() { }
	// RVA: 0x2baaddc VA: 0x75951c2ddc
	private Void _CalcAllLocationTotemSelectResult(Dictionary`2 locationTotemItemDict) { }
	// RVA: 0x2bab740 VA: 0x75951c3740
	private Boolean _CheckIfLocationTotemChanged(RL03TotemViewModel locationTotemViewModel) { }
	// RVA: 0x2bab85c VA: 0x75951c385c
	private Void _ClearAllSelectInMap() { }
	// RVA: 0x2babd80 VA: 0x75951c3d80
	public Void .ctor() { }
}
```