# MiniActTrialItemModel

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TrialStatus m_trialStatus`

- `String m_actId`

- `MiniActTrialSingleData m_trialData`

- `Int32 m_trialCollectCount`

- `Int32 m_storyTotalCount`

- `Int32 m_storyUnlockCount`

- `Boolean m_canCollect`


## Properties

- `Int32 totalRewardCount`

- `Int32 collectRewardCount`

- `Int32 storyTotalCount`

- `Int32 storyUnlockCount`

- `Boolean canCollect`

- `Boolean isCompleted`

- `String actId`

- `TrialStatus trialStatus`

- `TimeSpan trialCountDown`


## Methods

- `Int32 get_totalRewardCount()`

- `Int32 get_collectRewardCount()`

- `Int32 get_storyTotalCount()`

- `Int32 get_storyUnlockCount()`

- `Boolean get_canCollect()`

- `Boolean get_isCompleted()`

- `String get_actId()`

- `TrialStatus get_trialStatus()`

- `TimeSpan get_trialCountDown()`

- `Void LoadData(String, MiniActTrialSingleData)`

- `Void _UpdateTrialStatus(MiniActTrialSingleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialItemModel : IHotfixable
{
	private TrialStatus m_trialStatus; // 0x10
	private String m_actId; // 0x18
	private MiniActTrialSingleData m_trialData; // 0x20
	private List`1 m_rewardList; // 0x28
	private Int32 m_trialCollectCount; // 0x30
	private Int32 m_storyTotalCount; // 0x34
	private Int32 m_storyUnlockCount; // 0x38
	private Boolean m_canCollect; // 0x3c
	private static DelegateBridge __Hotfix0_get_rewardList; // 0x0
	private static DelegateBridge __Hotfix0_get_totalRewardCount; // 0x8
	private static DelegateBridge __Hotfix0_get_collectRewardCount; // 0x10
	private static DelegateBridge __Hotfix0_get_storyTotalCount; // 0x18
	private static DelegateBridge __Hotfix0_get_storyUnlockCount; // 0x20
	private static DelegateBridge __Hotfix0_get_canCollect; // 0x28
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x30
	private static DelegateBridge __Hotfix0_get_actId; // 0x38
	private static DelegateBridge __Hotfix0_get_trialStatus; // 0x40
	private static DelegateBridge __Hotfix0_get_trialCountDown; // 0x48
	private static DelegateBridge __Hotfix0_GetAllCollectable; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0__UpdateTrialStatus; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public List`1 rewardList { get; }
	public Int32 totalRewardCount { get; }
	public Int32 collectRewardCount { get; }
	public Int32 storyTotalCount { get; }
	public Int32 storyUnlockCount { get; }
	public Boolean canCollect { get; }
	public Boolean isCompleted { get; }
	public String actId { get; }
	public TrialStatus trialStatus { get; }
	public TimeSpan trialCountDown { get; }

	// RVA: 0x274a454 VA: 0x7594d62454
	public List`1 get_rewardList() { }
	// RVA: 0x2749fd4 VA: 0x7594d61fd4
	public Int32 get_totalRewardCount() { }
	// RVA: 0x2749f6c VA: 0x7594d61f6c
	public Int32 get_collectRewardCount() { }
	// RVA: 0x274a0bc VA: 0x7594d620bc
	public Int32 get_storyTotalCount() { }
	// RVA: 0x274a054 VA: 0x7594d62054
	public Int32 get_storyUnlockCount() { }
	// RVA: 0x274a37c VA: 0x7594d6237c
	public Boolean get_canCollect() { }
	// RVA: 0x274a3e4 VA: 0x7594d623e4
	public Boolean get_isCompleted() { }
	// RVA: 0x2749c08 VA: 0x7594d61c08
	public String get_actId() { }
	// RVA: 0x2749578 VA: 0x7594d61578
	public TrialStatus get_trialStatus() { }
	// RVA: 0x2749de8 VA: 0x7594d61de8
	public TimeSpan get_trialCountDown() { }
	// RVA: 0x274a6d4 VA: 0x7594d626d4
	public List`1 GetAllCollectable() { }
	// RVA: 0x274c8cc VA: 0x7594d648cc
	public Void LoadData(String storyId, MiniActTrialSingleData trialData) { }
	// RVA: 0x274cd90 VA: 0x7594d64d90
	private Void _UpdateTrialStatus(MiniActTrialSingleData trialData) { }
	// RVA: 0x274d03c VA: 0x7594d6503c
	public Void .ctor() { }
}
```