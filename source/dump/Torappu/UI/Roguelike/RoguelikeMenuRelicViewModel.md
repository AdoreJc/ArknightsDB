# RoguelikeMenuRelicViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRelicViewModel initialRelic`

- `RoguelikeTrapViewModel trap`

- `Boolean initProcessing`

- `String <diffName>k__BackingField`

- `Int32 <diffLevel>k__BackingField`

- `String <diffDisplayIconId>k__BackingField`


## Properties

- `String diffName`

- `Int32 diffLevel`

- `String diffDisplayIconId`


## Methods

- `String get_diffName()`

- `Void set_diffName(String)`

- `Int32 get_diffLevel()`

- `Void set_diffLevel(Int32)`

- `String get_diffDisplayIconId()`

- `Void set_diffDisplayIconId(String)`

- `Int32 GetWholeRelicViewModelsCount(CombineParam)`

- `Void _LoadExploreTool(String, Dictionary`2)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicViewModel : RoguelikeMenuCompViewModel
{
	public RoguelikeRelicViewModel initialRelic; // 0x18
	public RoguelikeTrapViewModel trap; // 0x20
	public List`1 relics; // 0x28
	public List`1 exploreTools; // 0x30
	public Boolean initProcessing; // 0x38
	private String <diffName>k__BackingField; // 0x40
	private Int32 <diffLevel>k__BackingField; // 0x48
	private String <diffDisplayIconId>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_diffName; // 0x0
	private static DelegateBridge __Hotfix0_set_diffName; // 0x8
	private static DelegateBridge __Hotfix0_get_diffLevel; // 0x10
	private static DelegateBridge __Hotfix0_set_diffLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_diffDisplayIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_diffDisplayIconId; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_LoadWholeRelicViewModelList; // 0x38
	private static DelegateBridge __Hotfix0_GetWholeRelicViewModelsCount; // 0x40
	private static DelegateBridge __Hotfix0__LoadExploreTool; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String diffName { get; set; }
	public Int32 diffLevel { get; set; }
	public String diffDisplayIconId { get; set; }

	// RVA: 0x2a7328c VA: 0x759508b28c
	public String get_diffName() { }
	// RVA: 0x2a7c4e0 VA: 0x75950944e0
	private Void set_diffName(String value) { }
	// RVA: 0x2a732f4 VA: 0x759508b2f4
	public Int32 get_diffLevel() { }
	// RVA: 0x2a7c564 VA: 0x7595094564
	private Void set_diffLevel(Int32 value) { }
	// RVA: 0x2a7c5e0 VA: 0x75950945e0
	public String get_diffDisplayIconId() { }
	// RVA: 0x2a7c648 VA: 0x7595094648
	private Void set_diffDisplayIconId(String value) { }
	// RVA: 0x2a7c6cc VA: 0x75950946cc
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a688a0 VA: 0x75950808a0
	public List`1 LoadWholeRelicViewModelList(CombineParam combineParam) { }
	// RVA: 0x2a697dc VA: 0x75950817dc
	public Int32 GetWholeRelicViewModelsCount(CombineParam combineParam) { }
	// RVA: 0x2a7cd34 VA: 0x7595094d34
	private Void _LoadExploreTool(String topicId, Dictionary`2 playerExploreToolDict) { }
	// RVA: 0x2a7cfc8 VA: 0x7595094fc8
	public Void .ctor() { }
	// RVA: 0x2a7d0dc VA: 0x75950950dc
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```