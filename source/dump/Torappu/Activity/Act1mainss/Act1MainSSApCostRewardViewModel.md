# Act1MainSSApCostRewardViewModel

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `Int64 m_endTime`

- `Int32 <rewardPoint>k__BackingField`


## Properties

- `Int32 rewardPoint`


## Methods

- `Int32 get_rewardPoint()`

- `Void set_rewardPoint(Int32)`

- `Output GetOutput()`

- `Int32 GetRewardCount()`

- `Void _LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1mainss
public class Act1MainSSApCostRewardViewModel : TemplateActivityViewModel
{
	private readonly List`1 m_rewardItems; // 0x20
	private readonly Dictionary`2 m_presentingItemDict; // 0x28
	private readonly List`1 m_presentingItemList; // 0x30
	private Int64 m_endTime; // 0x38
	private Int32 <rewardPoint>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_rewardPoint; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardPoint; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_GetOutput; // 0x18
	private static DelegateBridge __Hotfix0_GetRewardCount; // 0x20
	private static DelegateBridge __Hotfix0__LoadData; // 0x28
	private static DelegateBridge __Hotfix0__RewardItemComparison; // 0x30

	public Int32 rewardPoint { get; set; }

	// RVA: 0x3392fec VA: 0x75959aafec
	public Int32 get_rewardPoint() { }
	// RVA: 0x3393174 VA: 0x75959ab174
	private Void set_rewardPoint(Int32 value) { }
	// RVA: 0x3391134 VA: 0x75959a9134
	public Void .ctor(Object param) { }
	// RVA: 0x3392788 VA: 0x75959aa788
	public Output GetOutput() { }
	// RVA: 0x33906a4 VA: 0x75959a86a4
	public Int32 GetRewardCount() { }
	// RVA: 0x33931f0 VA: 0x75959ab1f0
	private Void _LoadData() { }
	// RVA: 0x339362c VA: 0x75959ab62c
	private static Int32 _RewardItemComparison(Act1MainSSApCostRewardItem x, Act1MainSSApCostRewardItem y) { }
}
```