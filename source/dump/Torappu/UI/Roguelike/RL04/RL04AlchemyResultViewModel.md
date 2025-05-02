# RL04AlchemyResultViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RoguelikeRewardListViewModel <otherRewardListViewModel>k__BackingField`

- `ResultState <resultState>k__BackingField`

- `Boolean <isMultiChoiceReward>k__BackingField`


## Properties

- `RoguelikeRewardListViewModel otherRewardListViewModel`

- `ResultState resultState`

- `Boolean isMultiChoiceReward`


## Methods

- `RoguelikeRewardListViewModel get_otherRewardListViewModel()`

- `Void set_otherRewardListViewModel(RoguelikeRewardListViewModel)`

- `Void set_ssrRewardListViewModel(List`1)`

- `ResultState get_resultState()`

- `Void set_resultState(ResultState)`

- `Boolean get_isMultiChoiceReward()`

- `Void set_isMultiChoiceReward(Boolean)`

- `Void _RefreshSsrRewardListModel(String, List`1, Int32)`

- `Void _RefreshOtherRewardsList(String, List`1, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyResultViewModel : IHotfixable
{
	private RoguelikeRewardListViewModel <otherRewardListViewModel>k__BackingField; // 0x10
	private List`1 <ssrRewardListViewModel>k__BackingField; // 0x18
	private ResultState <resultState>k__BackingField; // 0x20
	private Boolean <isMultiChoiceReward>k__BackingField; // 0x24
	private const Int32 MAX_REWARDS_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_get_otherRewardListViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_otherRewardListViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_ssrRewardListViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_ssrRewardListViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_resultState; // 0x20
	private static DelegateBridge __Hotfix0_set_resultState; // 0x28
	private static DelegateBridge __Hotfix0_get_isMultiChoiceReward; // 0x30
	private static DelegateBridge __Hotfix0_set_isMultiChoiceReward; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40
	private static DelegateBridge __Hotfix0__RefreshSsrRewardListModel; // 0x48
	private static DelegateBridge __Hotfix0__RefreshOtherRewardsList; // 0x50

	public RoguelikeRewardListViewModel otherRewardListViewModel { get; set; }
	public List`1 ssrRewardListViewModel { get; set; }
	public ResultState resultState { get; set; }
	public Boolean isMultiChoiceReward { get; set; }

	// RVA: 0x2b02870 VA: 0x759511a870
	public RoguelikeRewardListViewModel get_otherRewardListViewModel() { }
	// RVA: 0x2b028d8 VA: 0x759511a8d8
	private Void set_otherRewardListViewModel(RoguelikeRewardListViewModel value) { }
	// RVA: 0x2b0295c VA: 0x759511a95c
	public List`1 get_ssrRewardListViewModel() { }
	// RVA: 0x2b029c4 VA: 0x759511a9c4
	private Void set_ssrRewardListViewModel(List`1 value) { }
	// RVA: 0x2b02a48 VA: 0x759511aa48
	public ResultState get_resultState() { }
	// RVA: 0x2b02ab0 VA: 0x759511aab0
	private Void set_resultState(ResultState value) { }
	// RVA: 0x2b02b2c VA: 0x759511ab2c
	public Boolean get_isMultiChoiceReward() { }
	// RVA: 0x2b02b94 VA: 0x759511ab94
	private Void set_isMultiChoiceReward(Boolean value) { }
	// RVA: 0x2b02c14 VA: 0x759511ac14
	public Void .ctor(String topicId, List`1 items, Boolean isSsr, Boolean isFail) { }
	// RVA: 0x2b02df0 VA: 0x759511adf0
	private Void _RefreshSsrRewardListModel(String topicId, List`1 items, Int32 maxCount) { }
	// RVA: 0x2b03070 VA: 0x759511b070
	private Void _RefreshOtherRewardsList(String topicId, List`1 items, Int32 maxCount) { }
}
```