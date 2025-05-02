# SiracusaMapNavigationDetailViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `NavigationInfoData <navigationInfoData>k__BackingField`

- `NavigationType <navigationType>k__BackingField`

- `String <zoneId>k__BackingField`

- `Boolean <isTimeLocked>k__BackingField`

- `Boolean <isStageLocked>k__BackingField`

- `String <timeLockedTips>k__BackingField`

- `String <stageLockedTips>k__BackingField`

- `Boolean <isTimeOut>k__BackingField`

- `Boolean <isLocking>k__BackingField`

- `Boolean <isNew>k__BackingField`

- `String <selectingCharCard>k__BackingField`


## Properties

- `NavigationInfoData navigationInfoData`

- `NavigationType navigationType`

- `String zoneId`

- `Boolean isTimeLocked`

- `Boolean isStageLocked`

- `String timeLockedTips`

- `String stageLockedTips`

- `Boolean isTimeOut`

- `Boolean isLocking`

- `Boolean isNew`

- `String selectingCharCard`


## Methods

- `NavigationInfoData get_navigationInfoData()`

- `Void set_navigationInfoData(NavigationInfoData)`

- `NavigationType get_navigationType()`

- `Void set_navigationType(NavigationType)`

- `String get_zoneId()`

- `Void set_zoneId(String)`

- `Boolean get_isTimeLocked()`

- `Void set_isTimeLocked(Boolean)`

- `Boolean get_isStageLocked()`

- `Void set_isStageLocked(Boolean)`

- `String get_timeLockedTips()`

- `Void set_timeLockedTips(String)`

- `String get_stageLockedTips()`

- `Void set_stageLockedTips(String)`

- `Boolean get_isTimeOut()`

- `Void set_isTimeOut(Boolean)`

- `Boolean get_isLocking()`

- `Void set_isLocking(Boolean)`

- `Boolean get_isNew()`

- `Void set_isNew(Boolean)`

- `String get_selectingCharCard()`

- `Void set_selectingCharCard(String)`

- `SiracusaMapStageDetailInfoViewModel UpdateDetailInfoSelectState(String)`

- `Boolean IsStageNavigation()`

- `Color TryGetCurCharColor()`

- `Void UpdateCharCardNavigationState()`

- `Void UpdateLevelNavigationState(List`1)`

- `Void TryUpdateExploreMoreModel(Boolean)`

- `Boolean _ContainsExploreMoreItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapNavigationDetailViewModel : IHotfixable
{
	private NavigationInfoData <navigationInfoData>k__BackingField; // 0x10
	private NavigationType <navigationType>k__BackingField; // 0x18
	private String <zoneId>k__BackingField; // 0x20
	private Boolean <isTimeLocked>k__BackingField; // 0x28
	private Boolean <isStageLocked>k__BackingField; // 0x29
	private String <timeLockedTips>k__BackingField; // 0x30
	private String <stageLockedTips>k__BackingField; // 0x38
	private Boolean <isTimeOut>k__BackingField; // 0x40
	private Boolean <isLocking>k__BackingField; // 0x41
	private Boolean <isNew>k__BackingField; // 0x42
	public List`1 infoViewModels; // 0x48
	private String <selectingCharCard>k__BackingField; // 0x50
	private Dictionary`2 m_charCardColorDic; // 0x58
	private static DelegateBridge __Hotfix0_get_navigationInfoData; // 0x0
	private static DelegateBridge __Hotfix0_set_navigationInfoData; // 0x8
	private static DelegateBridge __Hotfix0_get_navigationType; // 0x10
	private static DelegateBridge __Hotfix0_set_navigationType; // 0x18
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x20
	private static DelegateBridge __Hotfix0_set_zoneId; // 0x28
	private static DelegateBridge __Hotfix0_get_isTimeLocked; // 0x30
	private static DelegateBridge __Hotfix0_set_isTimeLocked; // 0x38
	private static DelegateBridge __Hotfix0_get_isStageLocked; // 0x40
	private static DelegateBridge __Hotfix0_set_isStageLocked; // 0x48
	private static DelegateBridge __Hotfix0_get_timeLockedTips; // 0x50
	private static DelegateBridge __Hotfix0_set_timeLockedTips; // 0x58
	private static DelegateBridge __Hotfix0_get_stageLockedTips; // 0x60
	private static DelegateBridge __Hotfix0_set_stageLockedTips; // 0x68
	private static DelegateBridge __Hotfix0_get_isTimeOut; // 0x70
	private static DelegateBridge __Hotfix0_set_isTimeOut; // 0x78
	private static DelegateBridge __Hotfix0_get_isLocking; // 0x80
	private static DelegateBridge __Hotfix0_set_isLocking; // 0x88
	private static DelegateBridge __Hotfix0_get_isNew; // 0x90
	private static DelegateBridge __Hotfix0_set_isNew; // 0x98
	private static DelegateBridge __Hotfix0_get_selectingCharCard; // 0xa0
	private static DelegateBridge __Hotfix0_set_selectingCharCard; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateDetailInfoSelectState; // 0xb0
	private static DelegateBridge __Hotfix0_IsStageNavigation; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0
	private static DelegateBridge __Hotfix0_CreateLevelNavigation; // 0xc8
	private static DelegateBridge __Hotfix0_CreateAvgNavigation; // 0xd0
	private static DelegateBridge __Hotfix0_CreateCharCardNavigation; // 0xd8
	private static DelegateBridge __Hotfix0_TryGetCurCharColor; // 0xe0
	private static DelegateBridge __Hotfix0_UpdateCharCardNavigationState; // 0xe8
	private static DelegateBridge __Hotfix0_UpdateLevelNavigationState; // 0xf0
	private static DelegateBridge __Hotfix0_TryUpdateExploreMoreModel; // 0xf8
	private static DelegateBridge __Hotfix0__ContainsExploreMoreItem; // 0x100

	public NavigationInfoData navigationInfoData { get; set; }
	public NavigationType navigationType { get; set; }
	public String zoneId { get; set; }
	public Boolean isTimeLocked { get; set; }
	public Boolean isStageLocked { get; set; }
	public String timeLockedTips { get; set; }
	public String stageLockedTips { get; set; }
	public Boolean isTimeOut { get; set; }
	public Boolean isLocking { get; set; }
	public Boolean isNew { get; set; }
	public String selectingCharCard { get; set; }

	// RVA: 0x23e08cc VA: 0x75949f88cc
	public NavigationInfoData get_navigationInfoData() { }
	// RVA: 0x23e0934 VA: 0x75949f8934
	private Void set_navigationInfoData(NavigationInfoData value) { }
	// RVA: 0x23db854 VA: 0x75949f3854
	public NavigationType get_navigationType() { }
	// RVA: 0x23e09b8 VA: 0x75949f89b8
	private Void set_navigationType(NavigationType value) { }
	// RVA: 0x23df698 VA: 0x75949f7698
	public String get_zoneId() { }
	// RVA: 0x23e0a34 VA: 0x75949f8a34
	private Void set_zoneId(String value) { }
	// RVA: 0x23dc49c VA: 0x75949f449c
	public Boolean get_isTimeLocked() { }
	// RVA: 0x23e0ab8 VA: 0x75949f8ab8
	private Void set_isTimeLocked(Boolean value) { }
	// RVA: 0x23dc56c VA: 0x75949f456c
	public Boolean get_isStageLocked() { }
	// RVA: 0x23e0b38 VA: 0x75949f8b38
	private Void set_isStageLocked(Boolean value) { }
	// RVA: 0x23dc504 VA: 0x75949f4504
	public String get_timeLockedTips() { }
	// RVA: 0x23e0bb8 VA: 0x75949f8bb8
	private Void set_timeLockedTips(String value) { }
	// RVA: 0x23dc5d4 VA: 0x75949f45d4
	public String get_stageLockedTips() { }
	// RVA: 0x23e0c3c VA: 0x75949f8c3c
	private Void set_stageLockedTips(String value) { }
	// RVA: 0x23dc33c VA: 0x75949f433c
	public Boolean get_isTimeOut() { }
	// RVA: 0x23e0cc0 VA: 0x75949f8cc0
	private Void set_isTimeOut(Boolean value) { }
	// RVA: 0x23dba5c VA: 0x75949f3a5c
	public Boolean get_isLocking() { }
	// RVA: 0x23e0d40 VA: 0x75949f8d40
	private Void set_isLocking(Boolean value) { }
	// RVA: 0x23dc1d4 VA: 0x75949f41d4
	public Boolean get_isNew() { }
	// RVA: 0x23e0dc0 VA: 0x75949f8dc0
	private Void set_isNew(Boolean value) { }
	// RVA: 0x23dbac4 VA: 0x75949f3ac4
	public String get_selectingCharCard() { }
	// RVA: 0x23e0e40 VA: 0x75949f8e40
	private Void set_selectingCharCard(String value) { }
	// RVA: 0x23e0ec4 VA: 0x75949f8ec4
	public SiracusaMapStageDetailInfoViewModel UpdateDetailInfoSelectState(String selectingKey) { }
	// RVA: 0x23e1034 VA: 0x75949f9034
	public Boolean IsStageNavigation() { }
	// RVA: 0x23e10c0 VA: 0x75949f90c0
	private Void .ctor() { }
	// RVA: 0x23de5d0 VA: 0x75949f65d0
	public static SiracusaMapNavigationDetailViewModel CreateLevelNavigation(NavigationInfoData navigationInfoData, String zoneId, Boolean isTimeLocked, Boolean isTimeOut, String timeLockTips, String stageLockTips) { }
	// RVA: 0x23de3e8 VA: 0x75949f63e8
	public static SiracusaMapNavigationDetailViewModel CreateAvgNavigation(NavigationInfoData navigationInfoData) { }
	// RVA: 0x23de15c VA: 0x75949f615c
	public static SiracusaMapNavigationDetailViewModel CreateCharCardNavigation(NavigationInfoData navigationInfoData, Dictionary`2 charCardMap) { }
	// RVA: 0x23dbb2c VA: 0x75949f3b2c
	public Color TryGetCurCharColor() { }
	// RVA: 0x23df5d0 VA: 0x75949f75d0
	public Void UpdateCharCardNavigationState() { }
	// RVA: 0x23df700 VA: 0x75949f7700
	public Void UpdateLevelNavigationState(List`1 stageInfoViewModels) { }
	// RVA: 0x23dfd14 VA: 0x75949f7d14
	public Void TryUpdateExploreMoreModel(Boolean needShowExploreMore) { }
	// RVA: 0x23e1184 VA: 0x75949f9184
	private Boolean _ContainsExploreMoreItem() { }
}
```