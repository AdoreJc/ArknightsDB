# RoguelikeTopicBattlePassPurchaseViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBP curBpData`

- `Int32 curBpPoint`

- `String topicId`

- `Int64 widgetId`

- `Int64 dragId`

- `Boolean wheelScrolling`

- `Int32 selectedIndex`

- `IndexUpdateStrategy indexUpdateStrategy`


## Methods

- `Void SelectGrandPrizeOnInit(String)`

- `Int32 GetIndexByBpLevel(Int32)`

- `Boolean GetBpLevelByIndex(Int32, out)`

- `Boolean GetSelectedLevel(out)`

- `Int32 GetMaxLevel()`

- `Boolean GetGrandPrizeFocusRange(out, out)`

- `Void GenerateOverviewPrizeList(out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseViewModel : IHotfixable
{
	public List`1 purchasableBpObjList; // 0x10
	public ListDict`2 grandPrizeList; // 0x18
	public RoguelikeTopicBP curBpData; // 0x20
	public Int32 curBpPoint; // 0x28
	public String topicId; // 0x30
	public Int64 widgetId; // 0x38
	public Int64 dragId; // 0x40
	public Boolean wheelScrolling; // 0x48
	public Int32 selectedIndex; // 0x4c
	public IndexUpdateStrategy indexUpdateStrategy; // 0x50
	private static DelegateBridge __Hotfix0_SelectGrandPrizeOnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetIndexByBpLevel; // 0x8
	private static DelegateBridge __Hotfix0_GetBpLevelByIndex; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedLevel; // 0x18
	private static DelegateBridge __Hotfix0_GetMaxLevel; // 0x20
	private static DelegateBridge __Hotfix0_GetGrandPrizeFocusRange; // 0x28
	private static DelegateBridge __Hotfix0_GenerateOverviewPrizeList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2674b38 VA: 0x7594c8cb38
	public Void SelectGrandPrizeOnInit(String selectedGrandPrizeId) { }
	// RVA: 0x2674c1c VA: 0x7594c8cc1c
	public Int32 GetIndexByBpLevel(Int32 level) { }
	// RVA: 0x2674dcc VA: 0x7594c8cdcc
	public Boolean GetBpLevelByIndex(Int32 index, out Int32 level) { }
	// RVA: 0x2674e98 VA: 0x7594c8ce98
	public Boolean GetSelectedLevel(out Int32 level) { }
	// RVA: 0x2674f1c VA: 0x7594c8cf1c
	public Int32 GetMaxLevel() { }
	// RVA: 0x2674fe0 VA: 0x7594c8cfe0
	public Boolean GetGrandPrizeFocusRange(out Int32 minIndex, out Int32 maxIndex) { }
	// RVA: 0x26751dc VA: 0x7594c8d1dc
	public Void GenerateOverviewPrizeList(out ListDict`2 grandPrizeList, out ListDict`2 normalPrizeList) { }
	// RVA: 0x2675634 VA: 0x7594c8d634
	public Void .ctor() { }
}
```