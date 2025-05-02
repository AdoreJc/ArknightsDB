# StageRewardStateBean

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean isGet`

- `Boolean isComplete`

- `Boolean hasOverrideBuff`

- `OverrideDropInfo overrideDropInfo`

- `StageData m_stageData`


## Properties

- `StageData stageData`


## Methods

- `StageData get_stageData()`

- `Void ApplyStageData(String, CampaignStageType)`

- `Void _InsertViewModel(DisplayDetailRewards)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRewardStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public Dictionary`2 groupRewardList; // 0x18
	public List`1 timelyRewardList; // 0x20
	public Boolean isGet; // 0x28
	public Boolean isComplete; // 0x29
	public Boolean hasOverrideBuff; // 0x2a
	public OverrideDropInfo overrideDropInfo; // 0x30
	private StageData m_stageData; // 0x38
	private static DelegateBridge __Hotfix0_get_stageData; // 0x0
	private static DelegateBridge __Hotfix0_ApplyStageData; // 0x8
	private static DelegateBridge __Hotfix0__InsertViewModel; // 0x10
	private static DelegateBridge __Hotfix0__GetActivityRewards; // 0x18
	private static DelegateBridge __Hotfix0__GetDisplayDetailRewards; // 0x20
	private static DelegateBridge __Hotfix0__GetReplaceDropDisplay; // 0x28
	private static DelegateBridge __Hotfix0__GetTimelyDropDisplay; // 0x30
	private static DelegateBridge __Hotfix0__GetIfHasOverrideDropDisplay; // 0x38
	private static DelegateBridge __Hotfix0__GetTimelyDisplayDetailRewards; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public StageData stageData { get; }

	// RVA: 0x2f79428 VA: 0x7595591428
	public StageData get_stageData() { }
	// RVA: 0x2f79490 VA: 0x7595591490
	public Void ApplyStageData(String stageId, CampaignStageType stageType) { }
	// RVA: 0x2f7a124 VA: 0x7595592124
	private Void _InsertViewModel(DisplayDetailRewards detailRewards) { }
	// RVA: 0x2f7a330 VA: 0x7595592330
	private IList`1 _GetActivityRewards(StageData stageData) { }
	// RVA: 0x2f79e20 VA: 0x7595591e20
	private IList`1 _GetDisplayDetailRewards(StageData stageData, CampaignStageType campaignStageType) { }
	// RVA: 0x2f7a530 VA: 0x7595592530
	private Dictionary`2 _GetReplaceDropDisplay(StageData data) { }
	// RVA: 0x2f7a788 VA: 0x7595592788
	private Dictionary`2 _GetTimelyDropDisplay(StageData data) { }
	// RVA: 0x2f7a5b8 VA: 0x75955925b8
	private Dictionary`2 _GetIfHasOverrideDropDisplay(StageData data, Boolean checkRepalce, Boolean isReplace) { }
	// RVA: 0x2f79a78 VA: 0x7595591a78
	private List`1 _GetTimelyDisplayDetailRewards(StageData stageData) { }
	// RVA: 0x2f7a984 VA: 0x7595592984
	public Void .ctor() { }
}
```