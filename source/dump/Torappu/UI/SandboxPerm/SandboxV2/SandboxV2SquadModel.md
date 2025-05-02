# SandboxV2SquadModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 m_index`

- `String m_topicId`

- `Int32 m_squadCharCapacity`

- `Int32 m_miniSquadCharCapacity`

- `Int32 m_emptySquadDrinkCost`

- `Int32 m_miniSquadDrinkCost`

- `Int32 m_normalSquadDrinkCost`

- `Int32 m_toolboxCapacity`

- `SandboxV2SquadPanelShowMode m_showMode`

- `Boolean m_isTutorial`


## Properties

- `Int32 squadIndex`

- `Int32 squadToolCapacity`

- `Int32 squadCharCapacity`

- `Boolean isWithoutDrinkCost`


## Methods

- `Int32 get_squadIndex()`

- `Int32 get_squadToolCapacity()`

- `Int32 get_squadCharCapacity()`

- `Boolean get_isWithoutDrinkCost()`

- `Boolean CheckIfSquadChanged(String)`

- `Boolean _CheckIfCharListChanged(List`1)`

- `Boolean _CheckIfToolListChanged(List`1)`

- `Void ClearSquad(String)`

- `Void UpdateCharPlayerData()`

- `Void UpdateCharList(String, List`1)`

- `Void UpdateChar(String, Int32, List`1)`

- `Void UpdateToolPlayerData()`

- `Void RebuildToolList()`

- `Void UpdateToolList(String, List`1)`

- `Void UpdateTool(String, Int32, List`1)`

- `SandboxV2SquadCharModel GetCharModelBy(Int32)`

- `SquadScale CalcSquadScale()`

- `Int32 CalcDrinkCost()`

- `Int32 _CalcDrinkCost()`

- `Int32 CalcDisplayToolCount()`

- `Int32 _CalcTotalToolCount()`

- `Int32 _CalcTotalCharCount(Boolean)`

- `Void Init(String, Int32, Troop, SandboxV2SquadPanelShowMode)`

- `Void _InitCharList(List`1, Boolean)`

- `Void _InitToolList(List`1)`

- `Void _UpdateCharList(String, List`1)`

- `Void _UpdateToolList(String, List`1)`

- `Boolean IsDrinkEnough(String)`

- `Boolean IsCharEmpty()`

- `Boolean IsLargeSquad()`

- `Boolean HasCharAbnormal()`

- `CharUISkinStruct GetRandomCharSkin()`

- `Boolean HasToolLack()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadModel : IHotfixable
{
	private List`1 m_toolList; // 0x10
	private List`1 m_charList; // 0x18
	private List`1 m_slotStatusList; // 0x20
	private Int32 m_index; // 0x28
	private String m_topicId; // 0x30
	private Int32 m_squadCharCapacity; // 0x38
	private Int32 m_miniSquadCharCapacity; // 0x3c
	private Int32 m_emptySquadDrinkCost; // 0x40
	private Int32 m_miniSquadDrinkCost; // 0x44
	private Int32 m_normalSquadDrinkCost; // 0x48
	private Int32 m_toolboxCapacity; // 0x4c
	private SandboxV2SquadPanelShowMode m_showMode; // 0x50
	private Boolean m_isTutorial; // 0x54
	private static DelegateBridge __Hotfix0_get_squadIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_charList; // 0x8
	private static DelegateBridge __Hotfix0_get_toolList; // 0x10
	private static DelegateBridge __Hotfix0_get_squadToolCapacity; // 0x18
	private static DelegateBridge __Hotfix0_get_squadCharCapacity; // 0x20
	private static DelegateBridge __Hotfix0_get_isWithoutDrinkCost; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfSquadChanged; // 0x30
	private static DelegateBridge __Hotfix0__CheckIfCharListChanged; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfToolListChanged; // 0x40
	private static DelegateBridge __Hotfix0_ClearSquad; // 0x48
	private static DelegateBridge __Hotfix0_UpdateCharPlayerData; // 0x50
	private static DelegateBridge __Hotfix0_UpdateCharList; // 0x58
	private static DelegateBridge __Hotfix0_UpdateChar; // 0x60
	private static DelegateBridge __Hotfix0_UpdateToolPlayerData; // 0x68
	private static DelegateBridge __Hotfix0_RebuildToolList; // 0x70
	private static DelegateBridge __Hotfix0_UpdateToolList; // 0x78
	private static DelegateBridge __Hotfix0_UpdateTool; // 0x80
	private static DelegateBridge __Hotfix0_GenCharInstIdList; // 0x88
	private static DelegateBridge __Hotfix0_GenToolIdList; // 0x90
	private static DelegateBridge __Hotfix0_GenCharSquadList; // 0x98
	private static DelegateBridge __Hotfix0_GetCharModelBy; // 0xa0
	private static DelegateBridge __Hotfix0_CalcSlotStatusList; // 0xa8
	private static DelegateBridge __Hotfix0_CalcSquadScale; // 0xb0
	private static DelegateBridge __Hotfix0_CalcDrinkCost; // 0xb8
	private static DelegateBridge __Hotfix0__CalcDrinkCost; // 0xc0
	private static DelegateBridge __Hotfix0_CalcDisplayToolCount; // 0xc8
	private static DelegateBridge __Hotfix0__CalcTotalToolCount; // 0xd0
	private static DelegateBridge __Hotfix0__CalcTotalCharCount; // 0xd8
	private static DelegateBridge __Hotfix0_Init; // 0xe0
	private static DelegateBridge __Hotfix0__InitCharList; // 0xe8
	private static DelegateBridge __Hotfix0__InitToolList; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateCharList; // 0xf8
	private static DelegateBridge __Hotfix0__UpdateToolList; // 0x100
	private static DelegateBridge __Hotfix0_GenRequestSlotList; // 0x108
	private static DelegateBridge __Hotfix0_IsDrinkEnough; // 0x110
	private static DelegateBridge __Hotfix0_IsCharEmpty; // 0x118
	private static DelegateBridge __Hotfix0_IsLargeSquad; // 0x120
	private static DelegateBridge __Hotfix0_HasCharAbnormal; // 0x128
	private static DelegateBridge __Hotfix0_GenBattleSlots; // 0x130
	private static DelegateBridge __Hotfix0_GetRandomCharSkin; // 0x138
	private static DelegateBridge __Hotfix0_GenToolDict; // 0x140
	private static DelegateBridge __Hotfix0_HasToolLack; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public Int32 squadIndex { get; }
	public List`1 charList { get; }
	public List`1 toolList { get; }
	public Int32 squadToolCapacity { get; }
	public Int32 squadCharCapacity { get; }
	public Boolean isWithoutDrinkCost { get; }

	// RVA: 0x2613790 VA: 0x7594c2b790
	public Int32 get_squadIndex() { }
	// RVA: 0x2615404 VA: 0x7594c2d404
	public List`1 get_charList() { }
	// RVA: 0x2614a64 VA: 0x7594c2ca64
	public List`1 get_toolList() { }
	// RVA: 0x2614dc0 VA: 0x7594c2cdc0
	public Int32 get_squadToolCapacity() { }
	// RVA: 0x2615668 VA: 0x7594c2d668
	public Int32 get_squadCharCapacity() { }
	// RVA: 0x2618f38 VA: 0x7594c30f38
	public Boolean get_isWithoutDrinkCost() { }
	// RVA: 0x2613800 VA: 0x7594c2b800
	public Boolean CheckIfSquadChanged(String topicId) { }
	// RVA: 0x2618fa8 VA: 0x7594c30fa8
	private Boolean _CheckIfCharListChanged(List`1 slots) { }
	// RVA: 0x26190f0 VA: 0x7594c310f0
	private Boolean _CheckIfToolListChanged(List`1 tools) { }
	// RVA: 0x2618ea4 VA: 0x7594c30ea4
	public Void ClearSquad(String topicId) { }
	// RVA: 0x261117c VA: 0x7594c2917c
	public Void UpdateCharPlayerData() { }
	// RVA: 0x2616cac VA: 0x7594c2ecac
	public Void UpdateCharList(String topicId, List`1 selectCharList) { }
	// RVA: 0x2616d38 VA: 0x7594c2ed38
	public Void UpdateChar(String topicId, Int32 editIndex, List`1 selectCharList) { }
	// RVA: 0x2617004 VA: 0x7594c2f004
	public Void UpdateToolPlayerData() { }
	// RVA: 0x2611264 VA: 0x7594c29264
	public Void RebuildToolList() { }
	// RVA: 0x2617270 VA: 0x7594c2f270
	public Void UpdateToolList(String topicId, List`1 selectToolList) { }
	// RVA: 0x26172fc VA: 0x7594c2f2fc
	public Void UpdateTool(String topicId, Int32 editIndex, List`1 selectToolList) { }
	// RVA: 0x2615738 VA: 0x7594c2d738
	public List`1 GenCharInstIdList(Int32 ignoreInstId) { }
	// RVA: 0x2613b6c VA: 0x7594c2bb6c
	public List`1 GenToolIdList() { }
	// RVA: 0x261546c VA: 0x7594c2d46c
	public ListDict`2 GenCharSquadList(Int32 ignoreInstId) { }
	// RVA: 0x2613fb8 VA: 0x7594c2bfb8
	public SandboxV2SquadCharModel GetCharModelBy(Int32 instId) { }
	// RVA: 0x261a01c VA: 0x7594c3201c
	public List`1 CalcSlotStatusList() { }
	// RVA: 0x261a288 VA: 0x7594c32288
	public SquadScale CalcSquadScale() { }
	// RVA: 0x261a334 VA: 0x7594c32334
	public Int32 CalcDrinkCost() { }
	// RVA: 0x261a39c VA: 0x7594c3239c
	private Int32 _CalcDrinkCost() { }
	// RVA: 0x261a448 VA: 0x7594c32448
	public Int32 CalcDisplayToolCount() { }
	// RVA: 0x261947c VA: 0x7594c3147c
	private Int32 _CalcTotalToolCount() { }
	// RVA: 0x261923c VA: 0x7594c3123c
	private Int32 _CalcTotalCharCount(Boolean skipUsedChar) { }
	// RVA: 0x2611d0c VA: 0x7594c29d0c
	public Void Init(String topicId, Int32 squadIdx, Troop troop, SandboxV2SquadPanelShowMode showMode) { }
	// RVA: 0x261a4c0 VA: 0x7594c324c0
	private Void _InitCharList(List`1 playerSlotList, Boolean isTutorial) { }
	// RVA: 0x2619c40 VA: 0x7594c31c40
	private Void _InitToolList(List`1 playerToolList) { }
	// RVA: 0x2619578 VA: 0x7594c31578
	private Void _UpdateCharList(String topicId, List`1 selectCharList) { }
	// RVA: 0x26197ac VA: 0x7594c317ac
	private Void _UpdateToolList(String topicId, List`1 selectToolList) { }
	// RVA: 0x2613958 VA: 0x7594c2b958
	public List`1 GenRequestSlotList() { }
	// RVA: 0x2617d18 VA: 0x7594c2fd18
	public Boolean IsDrinkEnough(String topicId) { }
	// RVA: 0x2617ca0 VA: 0x7594c2fca0
	public Boolean IsCharEmpty() { }
	// RVA: 0x261a984 VA: 0x7594c32984
	public Boolean IsLargeSquad() { }
	// RVA: 0x2617aa0 VA: 0x7594c2faa0
	public Boolean HasCharAbnormal() { }
	// RVA: 0x2618a10 VA: 0x7594c30a10
	public List`1 GenBattleSlots() { }
	// RVA: 0x2618670 VA: 0x7594c30670
	public CharUISkinStruct GetRandomCharSkin() { }
	// RVA: 0x2618898 VA: 0x7594c30898
	public Dictionary`2 GenToolDict() { }
	// RVA: 0x2617b98 VA: 0x7594c2fb98
	public Boolean HasToolLack() { }
	// RVA: 0x2611ba8 VA: 0x7594c29ba8
	public Void .ctor() { }
}
```