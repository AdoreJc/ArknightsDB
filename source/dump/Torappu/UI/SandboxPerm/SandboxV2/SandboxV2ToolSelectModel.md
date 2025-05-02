# SandboxV2ToolSelectModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `Boolean m_isMultipleMode`

- `Int32 m_selectMaxCnt`

- `String m_focusToolId`

- `Int32 m_scrollSeqNum`

- `Int32 m_scrollTargetIdx`


## Properties

- `String topicId`

- `Boolean isMultipleMode`

- `Int32 scrollSeqNum`

- `Int32 scrollTargetIdx`


## Methods

- `String get_topicId()`

- `Boolean get_isMultipleMode()`

- `Int32 get_scrollSeqNum()`

- `Int32 get_scrollTargetIdx()`

- `Void _ScrollToIdx(Int32)`

- `SandboxV2SquadToolModel FindFocusToolModel()`

- `Void LoadData(Input)`

- `Void _InitTotalToolList()`

- `Void UpdatePlayerData()`

- `Boolean TryGetSelectIdx(String, out)`

- `Void ClearSelect()`

- `Void SelectTool(Int32)`

- `Void _SelectToolInSingleMode(String)`

- `Void _SelectToolInMultipleMode(String)`

- `Void _UpdatePlayerData()`

- `Int32 _SortByCustomRule(SandboxV2SquadToolModel, SandboxV2SquadToolModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectModel : IHotfixable
{
	private String m_topicId; // 0x10
	private Boolean m_isMultipleMode; // 0x18
	private Int32 m_selectMaxCnt; // 0x1c
	private String m_focusToolId; // 0x20
	private List`1 m_initSelectList; // 0x28
	private List`1 m_selectToolList; // 0x30
	private List`1 m_blackToolList; // 0x38
	private List`1 m_totalToolIdList; // 0x40
	private List`1 m_displayList; // 0x48
	private Int32 m_scrollSeqNum; // 0x50
	private Int32 m_scrollTargetIdx; // 0x54
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_isMultipleMode; // 0x8
	private static DelegateBridge __Hotfix0_get_displayList; // 0x10
	private static DelegateBridge __Hotfix0_get_scrollSeqNum; // 0x18
	private static DelegateBridge __Hotfix0_get_scrollTargetIdx; // 0x20
	private static DelegateBridge __Hotfix0__ScrollToIdx; // 0x28
	private static DelegateBridge __Hotfix0_FindFocusToolModel; // 0x30
	private static DelegateBridge __Hotfix0_GenSelectToolList; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__InitTotalToolList; // 0x48
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x50
	private static DelegateBridge __Hotfix0_TryGetSelectIdx; // 0x58
	private static DelegateBridge __Hotfix0_ClearSelect; // 0x60
	private static DelegateBridge __Hotfix0_SelectTool; // 0x68
	private static DelegateBridge __Hotfix0__SelectToolInSingleMode; // 0x70
	private static DelegateBridge __Hotfix0__SelectToolInMultipleMode; // 0x78
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x80
	private static DelegateBridge __Hotfix0__SortByCustomRule; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public String topicId { get; }
	public Boolean isMultipleMode { get; }
	public List`1 displayList { get; }
	public Int32 scrollSeqNum { get; }
	public Int32 scrollTargetIdx { get; }

	// RVA: 0x2623f64 VA: 0x7594c3bf64
	public String get_topicId() { }
	// RVA: 0x2622b88 VA: 0x7594c3ab88
	public Boolean get_isMultipleMode() { }
	// RVA: 0x26244b4 VA: 0x7594c3c4b4
	public List`1 get_displayList() { }
	// RVA: 0x262451c VA: 0x7594c3c51c
	public Int32 get_scrollSeqNum() { }
	// RVA: 0x2624584 VA: 0x7594c3c584
	public Int32 get_scrollTargetIdx() { }
	// RVA: 0x26245ec VA: 0x7594c3c5ec
	private Void _ScrollToIdx(Int32 targetIdx) { }
	// RVA: 0x2624670 VA: 0x7594c3c670
	public SandboxV2SquadToolModel FindFocusToolModel() { }
	// RVA: 0x26242a8 VA: 0x7594c3c2a8
	public List`1 GenSelectToolList() { }
	// RVA: 0x2623084 VA: 0x7594c3b084
	public Void LoadData(Input input) { }
	// RVA: 0x2624788 VA: 0x7594c3c788
	private Void _InitTotalToolList() { }
	// RVA: 0x2623564 VA: 0x7594c3b564
	public Void UpdatePlayerData() { }
	// RVA: 0x2622a54 VA: 0x7594c3aa54
	public Boolean TryGetSelectIdx(String toolId, out Int32 selectIdx) { }
	// RVA: 0x2623ab4 VA: 0x7594c3bab4
	public Void ClearSelect() { }
	// RVA: 0x26237b8 VA: 0x7594c3b7b8
	public Void SelectTool(Int32 selectIdx) { }
	// RVA: 0x2624de4 VA: 0x7594c3cde4
	private Void _SelectToolInSingleMode(String toolId) { }
	// RVA: 0x2624c40 VA: 0x7594c3cc40
	private Void _SelectToolInMultipleMode(String toolId) { }
	// RVA: 0x2624984 VA: 0x7594c3c984
	private Void _UpdatePlayerData() { }
	// RVA: 0x2624f60 VA: 0x7594c3cf60
	private Int32 _SortByCustomRule(SandboxV2SquadToolModel x, SandboxV2SquadToolModel y) { }
	// RVA: 0x2625078 VA: 0x7594c3d078
	public Void .ctor() { }
}
```