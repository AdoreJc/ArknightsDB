# RL03TotemBuffViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03TotemListViewProperty listViewProperty`

- `RL03TotemMapViewProperty mapViewProperty`

- `RL03TotemBottomViewProperty bottomViewProperty`

- `String m_topicId`

- `TotemViewShowType m_showType`

- `Int32 m_sequenceNum`


## Properties

- `String topicId`

- `Boolean isViewOnlyMode`


## Methods

- `String get_topicId()`

- `Boolean get_isViewOnlyMode()`

- `Void LoadData(String, Boolean)`

- `Boolean CheckIfShowMenuBottomBar()`

- `TotemItemDisplayType GetTotemItemDisplayType(String, String)`

- `Void SelectTotemItem(String, String)`

- `Void SelectMapNode(Int32, Int32)`

- `Boolean CheckIfCanUseTotem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffViewModel : IRoguelikeTotemBuffViewModel, IHotfixable
{
	public RL03TotemListViewProperty listViewProperty; // 0x10
	public RL03TotemMapViewProperty mapViewProperty; // 0x18
	public RL03TotemBottomViewProperty bottomViewProperty; // 0x20
	private String m_topicId; // 0x28
	private TotemViewShowType m_showType; // 0x30
	private Int32 m_sequenceNum; // 0x34
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_isViewOnlyMode; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfShowMenuBottomBar; // 0x18
	private static DelegateBridge __Hotfix0_GetTotemItemDisplayType; // 0x20
	private static DelegateBridge __Hotfix0_SelectTotemItem; // 0x28
	private static DelegateBridge __Hotfix0_SelectMapNode; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfCanUseTotem; // 0x38
	private static DelegateBridge __Hotfix0_GetCurTotemIndexList; // 0x40
	private static DelegateBridge __Hotfix0_GetCurSelectNodeList; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String topicId { get; }
	public Boolean isViewOnlyMode { get; }

	// RVA: 0x2bad770 VA: 0x75951c5770
	public String get_topicId() { }
	// RVA: 0x2bac9f4 VA: 0x75951c49f4
	public Boolean get_isViewOnlyMode() { }
	// RVA: 0x2bac504 VA: 0x75951c4504
	public Void LoadData(String topicId, Boolean isOpenDirectFromDungeon) { }
	// RVA: 0x2bae2d0 VA: 0x75951c62d0
	public Boolean CheckIfShowMenuBottomBar() { }
	// RVA: 0x2baca64 VA: 0x75951c4a64
	public TotemItemDisplayType GetTotemItemDisplayType(String totemId, String instId) { }
	// RVA: 0x2bacb1c VA: 0x75951c4b1c
	public Void SelectTotemItem(String totemId, String instId) { }
	// RVA: 0x2bacd74 VA: 0x75951c4d74
	public Void SelectMapNode(Int32 depth, Int32 index) { }
	// RVA: 0x2bacfec VA: 0x75951c4fec
	public Boolean CheckIfCanUseTotem() { }
	// RVA: 0x2bad088 VA: 0x75951c5088
	public List`1 GetCurTotemIndexList() { }
	// RVA: 0x2bad26c VA: 0x75951c526c
	public List`1 GetCurSelectNodeList() { }
	// RVA: 0x2bad998 VA: 0x75951c5998
	public Void .ctor() { }
}
```