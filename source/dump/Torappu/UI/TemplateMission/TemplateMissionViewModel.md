# TemplateMissionViewModel

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TemplateMissionListClaimAllItemViewModel m_claimAllViewModel`

- `TemplateMissionCoinViewModel m_missionCoinViewModel`

- `TemplateMissionStyleData m_missionViewStyleData`

- `ITemplateMissionViewModelPlugin m_plugin`


## Properties

- `TemplateMissionStyleData missionViewStyleData`

- `TemplateMissionCoinViewModel missionCoinViewModel`

- `ITemplateMissionViewModelPlugin plugin`


## Methods

- `TemplateMissionStyleData get_missionViewStyleData()`

- `TemplateMissionCoinViewModel get_missionCoinViewModel()`

- `ITemplateMissionViewModelPlugin get_plugin()`

- `Void InitViewModel(TemplateMissionInputParam)`

- `Void RefreshMissionState()`

- `Boolean CheckHaveMissionToGet(Int64)`

- `Int32 GetCompletedMissionCount()`

- `Boolean CheckMissionListPlayerDataChanged(PlayerDataModel, PlayerDataModel)`

- `Void _InitMissionList(TemplateMissionInputParam)`

- `Void _InitListNormalItemViewModels(TemplateMissionInputParam)`

- `Void _InitClaimAllViewModel()`

- `Void _RefreshMissionList()`

- `Void _RefreshListNormalItemViewModels()`

- `Void _RefreshClaimAllItemViewModel()`

- `Void _RefreshClaimAllItemInMissionList()`

- `Boolean _IsClaimAllItemShowInList()`

- `TemplateMissionListClaimAllItemViewModel _TryGetClaimAllItemInMissionList()`

- `Void _SortMissionList()`

- `Int32 <_SortMissionList>b__29_0(ITemplateMissionListItemViewModel, ITemplateMissionListItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionViewModel : IHotfixable
{
	private List`1 m_missionList; // 0x10
	private TemplateMissionListClaimAllItemViewModel m_claimAllViewModel; // 0x18
	private TemplateMissionCoinViewModel m_missionCoinViewModel; // 0x20
	private TemplateMissionStyleData m_missionViewStyleData; // 0x28
	private ITemplateMissionViewModelPlugin m_plugin; // 0x30
	private static DelegateBridge __Hotfix0_get_missionViewStyleData; // 0x0
	private static DelegateBridge __Hotfix0_get_missionCoinViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_missionItemList; // 0x10
	private static DelegateBridge __Hotfix0_get_plugin; // 0x18
	private static DelegateBridge __Hotfix0_InitViewModel; // 0x20
	private static DelegateBridge __Hotfix0_RefreshMissionState; // 0x28
	private static DelegateBridge __Hotfix0_CheckHaveMissionToGet; // 0x30
	private static DelegateBridge __Hotfix0_GetCompletedMissionCount; // 0x38
	private static DelegateBridge __Hotfix0_CheckMissionListPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0_GetCanClaimMissionList; // 0x48
	private static DelegateBridge __Hotfix0__InitMissionList; // 0x50
	private static DelegateBridge __Hotfix0__InitListNormalItemViewModels; // 0x58
	private static DelegateBridge __Hotfix0__InitClaimAllViewModel; // 0x60
	private static DelegateBridge __Hotfix0__RefreshMissionList; // 0x68
	private static DelegateBridge __Hotfix0__RefreshListNormalItemViewModels; // 0x70
	private static DelegateBridge __Hotfix0__RefreshClaimAllItemViewModel; // 0x78
	private static DelegateBridge __Hotfix0__RefreshClaimAllItemInMissionList; // 0x80
	private static DelegateBridge __Hotfix0__IsClaimAllItemShowInList; // 0x88
	private static DelegateBridge __Hotfix0__TryGetClaimAllItemInMissionList; // 0x90
	private static DelegateBridge __Hotfix0__SortMissionList; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public TemplateMissionStyleData missionViewStyleData { get; }
	public TemplateMissionCoinViewModel missionCoinViewModel { get; }
	public List`1 missionItemList { get; }
	public ITemplateMissionViewModelPlugin plugin { get; }

	// RVA: 0x2368894 VA: 0x7594980894
	public TemplateMissionStyleData get_missionViewStyleData() { }
	// RVA: 0x236a048 VA: 0x7594982048
	public TemplateMissionCoinViewModel get_missionCoinViewModel() { }
	// RVA: 0x236b130 VA: 0x7594983130
	public List`1 get_missionItemList() { }
	// RVA: 0x236f5cc VA: 0x75949875cc
	public ITemplateMissionViewModelPlugin get_plugin() { }
	// RVA: 0x236f634 VA: 0x7594987634
	public Void InitViewModel(TemplateMissionInputParam param) { }
	// RVA: 0x236f9b8 VA: 0x75949879b8
	public Void RefreshMissionState() { }
	// RVA: 0x236fa98 VA: 0x7594987a98
	public Boolean CheckHaveMissionToGet(Int64 currTs) { }
	// RVA: 0x236fc84 VA: 0x7594987c84
	public Int32 GetCompletedMissionCount() { }
	// RVA: 0x236fdc8 VA: 0x7594987dc8
	public Boolean CheckMissionListPlayerDataChanged(PlayerDataModel prevData, PlayerDataModel curData) { }
	// RVA: 0x2370408 VA: 0x7594988408
	public List`1 GetCanClaimMissionList() { }
	// RVA: 0x236f920 VA: 0x7594987920
	private Void _InitMissionList(TemplateMissionInputParam param) { }
	// RVA: 0x2370620 VA: 0x7594988620
	private Void _InitListNormalItemViewModels(TemplateMissionInputParam param) { }
	// RVA: 0x2370be0 VA: 0x7594988be0
	private Void _InitClaimAllViewModel() { }
	// RVA: 0x236fa20 VA: 0x7594987a20
	private Void _RefreshMissionList() { }
	// RVA: 0x237128c VA: 0x759498928c
	private Void _RefreshListNormalItemViewModels() { }
	// RVA: 0x2370d4c VA: 0x7594988d4c
	private Void _RefreshClaimAllItemViewModel() { }
	// RVA: 0x2371510 VA: 0x7594989510
	private Void _RefreshClaimAllItemInMissionList() { }
	// RVA: 0x237164c VA: 0x759498964c
	private Boolean _IsClaimAllItemShowInList() { }
	// RVA: 0x23716e4 VA: 0x75949896e4
	private TemplateMissionListClaimAllItemViewModel _TryGetClaimAllItemInMissionList() { }
	// RVA: 0x2370f28 VA: 0x7594988f28
	private Void _SortMissionList() { }
	// RVA: 0x2371804 VA: 0x7594989804
	public Void .ctor() { }
	// RVA: 0x23718c8 VA: 0x75949898c8
	private Int32 <_SortMissionList>b__29_0(ITemplateMissionListItemViewModel a, ITemplateMissionListItemViewModel b) { }
}
```