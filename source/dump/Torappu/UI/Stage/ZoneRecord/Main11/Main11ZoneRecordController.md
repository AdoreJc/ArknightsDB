# Main11ZoneRecordController

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `RectTransform _topMenuContainer`

- `Main11RecordAllRewardsView _rewardsView`

- `UIBlurFloatPanel _panelReward`

- `Main11RecordHomeView _homeView`

- `Main11RecordNoteView _noteView`

- `UIAnimationLocation _enterAnim`

- `Main11ZoneRecordViewProperty m_recordProperty`

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

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11ZoneRecordController : ZoneRecordController
{
	private RectTransform _topMenuContainer; // 0x28
	private Main11RecordAllRewardsView _rewardsView; // 0x30
	private UIBlurFloatPanel _panelReward; // 0x38
	private Main11RecordHomeView _homeView; // 0x40
	private Main11RecordNoteView _noteView; // 0x48
	private UIAnimationLocation _enterAnim; // 0x50
	private Main11ZoneRecordViewProperty m_recordProperty; // 0x60
	private ZoneRecordGroupData m_cachedGroupData; // 0x68
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
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2fdaa6c VA: 0x75955f2a6c
	public override Void Init() { }
	// RVA: 0x2fdad50 VA: 0x75955f2d50
	public override Void OnEnter(String zoneId) { }
	// RVA: 0x2fdaf54 VA: 0x75955f2f54
	public override Void OnResume(Boolean isFromStack) { }
	// RVA: 0x2fdb4e4 VA: 0x75955f34e4
	private Void _JumpToRecordPageByIdx(Int32 idx) { }
	// RVA: 0x2fdb5f8 VA: 0x75955f35f8
	private Boolean _CheckIfRecordUnlockAndShowToast(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fdb6c4 VA: 0x75955f36c4
	private Void _OnPrevBtnClick() { }
	// RVA: 0x2fdb810 VA: 0x75955f3810
	private Void _OnNextBtnClick() { }
	// RVA: 0x2fdb8f0 VA: 0x75955f38f0
	private Void _OnRecordItemBtnClick(String recordId) { }
	// RVA: 0x2fdb9e8 VA: 0x75955f39e8
	private Void _OnClaimAllRewardClick() { }
	// RVA: 0x2fdba98 VA: 0x75955f3a98
	private Void _OnBtnBackClick() { }
	// RVA: 0x2fdbba8 VA: 0x75955f3ba8
	private Void _OnAllRewardBtnClicked() { }
	// RVA: 0x2fdbc1c VA: 0x75955f3c1c
	public Void .ctor() { }
	// RVA: 0x2fdbd34 VA: 0x75955f3d34
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x2fdbd3c VA: 0x75955f3d3c
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x2fdbd44 VA: 0x75955f3d44
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```