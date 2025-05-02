# TemplateActivityMilestoneGroupViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `ITemplateActivityMilestonePlugin m_plugin`

- `String m_actId`

- `String m_milestoneId`

- `String m_milestoneGroupName`

- `Int32 m_focusIndex`

- `Int32 m_milestoneCount`

- `Boolean m_hasAnyReward`

- `Boolean m_needFocusToIndex`

- `TemplateActivityMileStoneItemModel m_skinMilestoneModel`

- `TemplateActivityMileStoneItemModel m_nameCardSkinMilestoneModel`

- `TemplateActivityMileStoneItemModel m_avatarMilestoneModel`

- `TemplateActivityMileStoneItemModel m_homeThemeMilestoneModel`

- `Boolean m_isUnlock`

- `String m_lockedToastDesc`

- `ActivityStatus m_currActivityStatus`

- `MileStoneProgressData m_mileStoneProgressData`


## Properties

- `String actId`

- `String milestoneId`

- `String milestoneGroupName`

- `Int32 focusIndex`

- `Boolean hasAnyReward`

- `Int32 milestoneCount`

- `TemplateActivityMileStoneItemModel skinMilestoneModel`

- `TemplateActivityMileStoneItemModel nameCardSkinMilestoneModel`

- `TemplateActivityMileStoneItemModel avatarMilestoneModel`

- `TemplateActivityMileStoneItemModel hoomeThemeModel`

- `Boolean needFocusToIdx`

- `Boolean isUnlock`

- `String lockedToastDesc`

- `MileStoneProgressData mileStoneProgressData`

- `ActivityStatus currActivityStatus`


## Methods

- `String get_actId()`

- `String get_milestoneId()`

- `String get_milestoneGroupName()`

- `Int32 get_focusIndex()`

- `Boolean get_hasAnyReward()`

- `Int32 get_milestoneCount()`

- `TemplateActivityMileStoneItemModel get_skinMilestoneModel()`

- `TemplateActivityMileStoneItemModel get_nameCardSkinMilestoneModel()`

- `TemplateActivityMileStoneItemModel get_avatarMilestoneModel()`

- `TemplateActivityMileStoneItemModel get_hoomeThemeModel()`

- `Boolean get_needFocusToIdx()`

- `Boolean get_isUnlock()`

- `String get_lockedToastDesc()`

- `MileStoneProgressData get_mileStoneProgressData()`

- `ActivityStatus get_currActivityStatus()`

- `Void _GenDisplayList()`

- `Boolean _HasAvailReward()`

- `ActivityStatus _GetCurActivityStatus(String)`

- `Void _UpdateProgressData()`

- `Void UpdatePlayerData()`

- `IMilestoneServiceConfig GenAllMilConfig(Action`1)`

- `IMilestoneServiceConfig GenOneMilConfig(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMilestoneGroupViewModel : TemplateActivityViewModel
{
	private List`1 m_milestoneList; // 0x20
	private ITemplateActivityMilestonePlugin m_plugin; // 0x28
	private List`1 m_displayList; // 0x30
	private String m_actId; // 0x38
	private String m_milestoneId; // 0x40
	private String m_milestoneGroupName; // 0x48
	private Int32 m_focusIndex; // 0x50
	private Int32 m_milestoneCount; // 0x54
	private Boolean m_hasAnyReward; // 0x58
	private Boolean m_needFocusToIndex; // 0x59
	private TemplateActivityMileStoneItemModel m_skinMilestoneModel; // 0x60
	private TemplateActivityMileStoneItemModel m_nameCardSkinMilestoneModel; // 0x68
	private TemplateActivityMileStoneItemModel m_avatarMilestoneModel; // 0x70
	private TemplateActivityMileStoneItemModel m_homeThemeMilestoneModel; // 0x78
	private Boolean m_isUnlock; // 0x80
	private String m_lockedToastDesc; // 0x88
	private ActivityStatus m_currActivityStatus; // 0x90
	private MileStoneProgressData m_mileStoneProgressData; // 0x94
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_milestoneId; // 0x8
	private static DelegateBridge __Hotfix0_get_milestoneGroupName; // 0x10
	private static DelegateBridge __Hotfix0_get_focusIndex; // 0x18
	private static DelegateBridge __Hotfix0_get_hasAnyReward; // 0x20
	private static DelegateBridge __Hotfix0_get_milestoneCount; // 0x28
	private static DelegateBridge __Hotfix0_get_skinMilestoneModel; // 0x30
	private static DelegateBridge __Hotfix0_get_nameCardSkinMilestoneModel; // 0x38
	private static DelegateBridge __Hotfix0_get_avatarMilestoneModel; // 0x40
	private static DelegateBridge __Hotfix0_get_hoomeThemeModel; // 0x48
	private static DelegateBridge __Hotfix0_get_displayList; // 0x50
	private static DelegateBridge __Hotfix0_get_milestoneList; // 0x58
	private static DelegateBridge __Hotfix0_get_needFocusToIdx; // 0x60
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x68
	private static DelegateBridge __Hotfix0_get_lockedToastDesc; // 0x70
	private static DelegateBridge __Hotfix0_get_mileStoneProgressData; // 0x78
	private static DelegateBridge __Hotfix0_get_currActivityStatus; // 0x80
	private static DelegateBridge __Hotfix0__GenDisplayList; // 0x88
	private static DelegateBridge __Hotfix0__HasAvailReward; // 0x90
	private static DelegateBridge __Hotfix0__GetCurActivityStatus; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateProgressData; // 0xa8
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xb0
	private static DelegateBridge __Hotfix0_GenAllMilConfig; // 0xb8
	private static DelegateBridge __Hotfix0_GenOneMilConfig; // 0xc0

	public String actId { get; }
	public String milestoneId { get; }
	public String milestoneGroupName { get; }
	public Int32 focusIndex { get; }
	public Boolean hasAnyReward { get; }
	public Int32 milestoneCount { get; }
	public TemplateActivityMileStoneItemModel skinMilestoneModel { get; }
	public TemplateActivityMileStoneItemModel nameCardSkinMilestoneModel { get; }
	public TemplateActivityMileStoneItemModel avatarMilestoneModel { get; }
	public TemplateActivityMileStoneItemModel hoomeThemeModel { get; }
	public List`1 displayList { get; }
	public List`1 milestoneList { get; }
	public Boolean needFocusToIdx { get; }
	public Boolean isUnlock { get; }
	public String lockedToastDesc { get; }
	public MileStoneProgressData mileStoneProgressData { get; }
	public ActivityStatus currActivityStatus { get; }

	// RVA: 0x30ac77c VA: 0x75956c477c
	public String get_actId() { }
	// RVA: 0x30ac7e4 VA: 0x75956c47e4
	public String get_milestoneId() { }
	// RVA: 0x30ac84c VA: 0x75956c484c
	public String get_milestoneGroupName() { }
	// RVA: 0x30ac8b4 VA: 0x75956c48b4
	public Int32 get_focusIndex() { }
	// RVA: 0x30ac91c VA: 0x75956c491c
	public Boolean get_hasAnyReward() { }
	// RVA: 0x30ac984 VA: 0x75956c4984
	public Int32 get_milestoneCount() { }
	// RVA: 0x30ac9ec VA: 0x75956c49ec
	public TemplateActivityMileStoneItemModel get_skinMilestoneModel() { }
	// RVA: 0x30aca54 VA: 0x75956c4a54
	public TemplateActivityMileStoneItemModel get_nameCardSkinMilestoneModel() { }
	// RVA: 0x30acabc VA: 0x75956c4abc
	public TemplateActivityMileStoneItemModel get_avatarMilestoneModel() { }
	// RVA: 0x30acb24 VA: 0x75956c4b24
	public TemplateActivityMileStoneItemModel get_hoomeThemeModel() { }
	// RVA: 0x30acb8c VA: 0x75956c4b8c
	public List`1 get_displayList() { }
	// RVA: 0x30ad054 VA: 0x75956c5054
	public List`1 get_milestoneList() { }
	// RVA: 0x30ad0bc VA: 0x75956c50bc
	public Boolean get_needFocusToIdx() { }
	// RVA: 0x30ad124 VA: 0x75956c5124
	public Boolean get_isUnlock() { }
	// RVA: 0x30ad18c VA: 0x75956c518c
	public String get_lockedToastDesc() { }
	// RVA: 0x30ad1f4 VA: 0x75956c51f4
	public MileStoneProgressData get_mileStoneProgressData() { }
	// RVA: 0x30ad280 VA: 0x75956c5280
	public ActivityStatus get_currActivityStatus() { }
	// RVA: 0x30acc04 VA: 0x75956c4c04
	private Void _GenDisplayList() { }
	// RVA: 0x30ad2e8 VA: 0x75956c52e8
	private Boolean _HasAvailReward() { }
	// RVA: 0x30ad3e4 VA: 0x75956c53e4
	private ActivityStatus _GetCurActivityStatus(String actId) { }
	// RVA: 0x30ad544 VA: 0x75956c5544
	public Void .ctor(Object param) { }
	// RVA: 0x30adc00 VA: 0x75956c5c00
	private Void _UpdateProgressData() { }
	// RVA: 0x30ade90 VA: 0x75956c5e90
	public Void UpdatePlayerData() { }
	// RVA: 0x30ae120 VA: 0x75956c6120
	public IMilestoneServiceConfig GenAllMilConfig(Action`1 onProceed) { }
	// RVA: 0x30ae234 VA: 0x75956c6234
	public IMilestoneServiceConfig GenOneMilConfig(String milestoneId, Action`1 onProceed) { }
}
```