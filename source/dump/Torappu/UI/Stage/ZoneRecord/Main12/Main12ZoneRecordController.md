# Main12ZoneRecordController

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `RectTransform _topMenuContainer`

- `UIBlurFloatPanel _panelReward`

- `Main12RecordHomeView _homeView`

- `Transform _homeViewContainer`

- `Main12RecordNoteView _noteView`

- `Transform _noteViewContainer`

- `Main12RecordAllRewardsView _rewardsView`

- `Transform _rewardsViewContainer`

- `Main12RecordHomeView m_homeView`

- `Main12RecordNoteView m_noteView`

- `Main12RecordAllRewardsView m_rewardsView`

- `Main12ZoneRecordViewProperty m_recordProperty`

- `ZoneRecordGroupData m_cachedGroupData`


## Methods

- `Void _JumpToRecordPageByIdx(Int32)`

- `Boolean _CheckIfRecordUnlockAndShowToast(ZoneRecordViewModel)`

- `Void _OnPrevBtnClick()`

- `Void _OnNextBtnClick()`

- `Void _OnRecordItemBtnClick(String)`

- `Void _OnClaimAllRewardClick()`

- `Void _OnBtnBackClick()`

- `Void _OnAllRewardBtnClicked()`

- `Void _AllClaimCallBack(ZoneRecordRewardResponse)`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12ZoneRecordController : ZoneRecordController
{
	private RectTransform _topMenuContainer; // 0x28
	private UIBlurFloatPanel _panelReward; // 0x30
	private Main12RecordHomeView _homeView; // 0x38
	private Transform _homeViewContainer; // 0x40
	private Main12RecordNoteView _noteView; // 0x48
	private Transform _noteViewContainer; // 0x50
	private Main12RecordAllRewardsView _rewardsView; // 0x58
	private Transform _rewardsViewContainer; // 0x60
	private Main12RecordHomeView m_homeView; // 0x68
	private Main12RecordNoteView m_noteView; // 0x70
	private Main12RecordAllRewardsView m_rewardsView; // 0x78
	private Main12ZoneRecordViewProperty m_recordProperty; // 0x80
	private ZoneRecordGroupData m_cachedGroupData; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__JumpToRecordPageByIdx; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfRecordUnlockAndShowToast; // 0x20
	private static DelegateBridge __Hotfix0__OnPrevBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__OnNextBtnClick; // 0x30
	private static DelegateBridge __Hotfix0__OnRecordItemBtnClick; // 0x38
	private static DelegateBridge __Hotfix0__OnClaimAllRewardClick; // 0x40
	private static DelegateBridge __Hotfix0__OnBtnBackClick; // 0x48
	private static DelegateBridge __Hotfix0__OnAllRewardBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0__AllClaimCallBack; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2fd300c VA: 0x75955eb00c
	public override Void Init() { }
	// RVA: 0x2fd346c VA: 0x75955eb46c
	public override Void OnEnter(String zoneId) { }
	// RVA: 0x2fd3658 VA: 0x75955eb658
	public override Void OnResume(Boolean isFromStack) { }
	// RVA: 0x2fd3c60 VA: 0x75955ebc60
	private Void _JumpToRecordPageByIdx(Int32 idx) { }
	// RVA: 0x2fd3d70 VA: 0x75955ebd70
	private Boolean _CheckIfRecordUnlockAndShowToast(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd3e3c VA: 0x75955ebe3c
	private Void _OnPrevBtnClick() { }
	// RVA: 0x2fd3f84 VA: 0x75955ebf84
	private Void _OnNextBtnClick() { }
	// RVA: 0x2fd4060 VA: 0x75955ec060
	private Void _OnRecordItemBtnClick(String recordId) { }
	// RVA: 0x2fd4150 VA: 0x75955ec150
	private Void _OnClaimAllRewardClick() { }
	// RVA: 0x2fd4244 VA: 0x75955ec244
	private Void _OnBtnBackClick() { }
	// RVA: 0x2fd4384 VA: 0x75955ec384
	private Void _OnAllRewardBtnClicked() { }
	// RVA: 0x2fd43f8 VA: 0x75955ec3f8
	private Void _AllClaimCallBack(ZoneRecordRewardResponse res) { }
	// RVA: 0x2fd467c VA: 0x75955ec67c
	public Void .ctor() { }
	// RVA: 0x2fd4790 VA: 0x75955ec790
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x2fd4794 VA: 0x75955ec794
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x2fd4798 VA: 0x75955ec798
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```