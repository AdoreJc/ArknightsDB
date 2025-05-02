# MiniActTrialRewardItemModel

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `String m_actId`

- `MiniActTrialRewardData m_rewardData`

- `Boolean m_isGot`

- `Boolean m_meetCondition`

- `String m_themeColor`


## Properties

- `String actId`

- `ItemBundle itemBundle`

- `String rewardId`

- `Boolean meetCond`

- `Int32 targetCount`

- `Color themeColor`


## Methods

- `String get_actId()`

- `ItemBundle get_itemBundle()`

- `String get_rewardId()`

- `Boolean get_meetCond()`

- `Int32 get_targetCount()`

- `Color get_themeColor()`

- `Boolean IsGot()`

- `Boolean CanCollect()`

- `Boolean IsItemAvail()`

- `Void LoadData(String, MiniActTrialRewardData, Boolean, Boolean, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialRewardItemModel : IHotfixable
{
	private String m_actId; // 0x10
	private MiniActTrialRewardData m_rewardData; // 0x18
	private Boolean m_isGot; // 0x20
	private Boolean m_meetCondition; // 0x21
	private String m_themeColor; // 0x28
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_itemBundle; // 0x8
	private static DelegateBridge __Hotfix0_get_rewardId; // 0x10
	private static DelegateBridge __Hotfix0_get_meetCond; // 0x18
	private static DelegateBridge __Hotfix0_get_targetCount; // 0x20
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x28
	private static DelegateBridge __Hotfix0_IsGot; // 0x30
	private static DelegateBridge __Hotfix0_CanCollect; // 0x38
	private static DelegateBridge __Hotfix0_IsItemAvail; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String actId { get; }
	public ItemBundle itemBundle { get; }
	public String rewardId { get; }
	public Boolean meetCond { get; }
	public Int32 targetCount { get; }
	public Color themeColor { get; }

	// RVA: 0x274baac VA: 0x7594d63aac
	public String get_actId() { }
	// RVA: 0x274b828 VA: 0x7594d63828
	public ItemBundle get_itemBundle() { }
	// RVA: 0x274bb14 VA: 0x7594d63b14
	public String get_rewardId() { }
	// RVA: 0x274b62c VA: 0x7594d6362c
	public Boolean get_meetCond() { }
	// RVA: 0x274b89c VA: 0x7594d6389c
	public Int32 get_targetCount() { }
	// RVA: 0x274b794 VA: 0x7594d63794
	public Color get_themeColor() { }
	// RVA: 0x274b694 VA: 0x7594d63694
	public Boolean IsGot() { }
	// RVA: 0x274b718 VA: 0x7594d63718
	public Boolean CanCollect() { }
	// RVA: 0x274d100 VA: 0x7594d65100
	public Boolean IsItemAvail() { }
	// RVA: 0x274cf50 VA: 0x7594d64f50
	public Void LoadData(String actId, MiniActTrialRewardData rewardData, Boolean isGot, Boolean meetCondition, String themeColor) { }
	// RVA: 0x274cee0 VA: 0x7594d64ee0
	public Void .ctor() { }
}
```