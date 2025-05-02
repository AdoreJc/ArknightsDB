# StagePreviewCampaignBreakDetailPanel

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `SimpleLayoutContent _breakLayout`

- `ScrollRect _scrollRect`

- `BreakRewardConfirmedEvent _onBreakRewardConfirmedEvent`

- `CampaignStateViewModel m_campModel`

- `BreakAdapter m_breakAdapter`

- `FadeSwitchTween m_fadeSwitchTween`

- `Boolean m_topMenuInited`


## Properties

- `Boolean isShow`

- `String currentStageId`


## Methods

- `Boolean get_isShow()`

- `String get_currentStageId()`

- `Void Show(CampaignStateViewModel)`

- `Void Hide()`

- `Void _SetVisibility(Boolean)`

- `Void _OnBreakRewardConfirmed(Int32)`

- `Void _UpdateAndSortBreakRewardList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class StagePreviewCampaignBreakDetailPanel : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _breakLayout; // 0x18
	private ScrollRect _scrollRect; // 0x20
	private BreakRewardConfirmedEvent _onBreakRewardConfirmedEvent; // 0x28
	private CampaignStateViewModel m_campModel; // 0x30
	private BreakAdapter m_breakAdapter; // 0x38
	private FadeSwitchTween m_fadeSwitchTween; // 0x40
	private List`1 m_breakModels; // 0x48
	private Boolean m_topMenuInited; // 0x50
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_get_currentStageId; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge __Hotfix0__SetVisibility; // 0x20
	private static DelegateBridge __Hotfix0__OnBreakRewardConfirmed; // 0x28
	private static DelegateBridge __Hotfix0__UpdateAndSortBreakRewardList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isShow { get; }
	public String currentStageId { get; }

	// RVA: 0x2de07e8 VA: 0x75953f87e8
	public Boolean get_isShow() { }
	// RVA: 0x2de0864 VA: 0x75953f8864
	public String get_currentStageId() { }
	// RVA: 0x2de08f8 VA: 0x75953f88f8
	public Void Show(CampaignStateViewModel campModel) { }
	// RVA: 0x2de0d88 VA: 0x75953f8d88
	public Void Hide() { }
	// RVA: 0x2de0c64 VA: 0x75953f8c64
	private Void _SetVisibility(Boolean isVisible) { }
	// RVA: 0x2de0df4 VA: 0x75953f8df4
	private Void _OnBreakRewardConfirmed(Int32 index) { }
	// RVA: 0x2de0a24 VA: 0x75953f8a24
	private Void _UpdateAndSortBreakRewardList() { }
	// RVA: 0x2de0eac VA: 0x75953f8eac
	public Void .ctor() { }
}
```