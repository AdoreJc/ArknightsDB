# Main10ZoneRecordController

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main10`


## Fields

- `RectTransform _topMenuContainer`

- `Main10ZoneRecordCommonView _commonView`

- `Main10ZoneRecordDetailView _detailView`

- `Main10ZoneRecordAllRewardView _rewardsView`

- `UIBlurFloatPanel _panelReward`

- `UIBlurFloatPanel _panelDetail`

- `Main10ZoneRecordViewProperty m_recordProperty`

- `ZoneRecordGroupData m_cachedGroupData`

- `String m_cachedRewardKey`


## Methods

- `Void _OnBtnBackClick()`

- `Boolean _TryTrigUnlockAnim()`

- `Void _TryJumpToNewestNote()`

- `Boolean _TryTrigGuid()`

- `Void _JumpToRecordPageByIdx(Int32)`

- `Void _OnRecordDetailClick(StageDiffGroup)`

- `Int32 GetLatestRocordIdx()`

- `Void _OnGetReward(ZoneRecordRewardResponse)`

- `Void _UpdateRecordUnlockInfo(List`1, ZoneRecordUnlockData)`

- `Void OnContentClick(String)`

- `Void OnDetailClose()`

- `Void OnAllRewardClose()`

- `Void OnCoverClick()`

- `Void OnCoverArrowClick()`

- `Void EventOnNormalNoteClick()`

- `Void EventOnToughNoteClick()`

- `Void EventOnAllRewardClick()`

- `Void EventOnHideTips()`

- `Void EventOnNextNote()`

- `Void EventOnPrevNote()`

- `Void SendGetRecordReward()`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main10
public class Main10ZoneRecordController : ZoneRecordController
{
	private RectTransform _topMenuContainer; // 0x28
	private Main10ZoneRecordCommonView _commonView; // 0x30
	private Main10ZoneRecordDetailView _detailView; // 0x38
	private Main10ZoneRecordAllRewardView _rewardsView; // 0x40
	private UIBlurFloatPanel _panelReward; // 0x48
	private UIBlurFloatPanel _panelDetail; // 0x50
	private Main10ZoneRecordViewProperty m_recordProperty; // 0x58
	private ZoneRecordGroupData m_cachedGroupData; // 0x60
	private String m_cachedRewardKey; // 0x68
	private const String FIRST_UNLOCK_CACHE_KEY; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__OnBtnBackClick; // 0x18
	private static DelegateBridge __Hotfix0__TryTrigUnlockAnim; // 0x20
	private static DelegateBridge __Hotfix0__TryJumpToNewestNote; // 0x28
	private static DelegateBridge __Hotfix0__TryTrigGuid; // 0x30
	private static DelegateBridge __Hotfix0__JumpToRecordPageByIdx; // 0x38
	private static DelegateBridge __Hotfix0__OnRecordDetailClick; // 0x40
	private static DelegateBridge __Hotfix0_GetLatestRocordIdx; // 0x48
	private static DelegateBridge __Hotfix0__OnGetReward; // 0x50
	private static DelegateBridge __Hotfix0__UpdateRecordUnlockInfo; // 0x58
	private static DelegateBridge __Hotfix0_OnContentClick; // 0x60
	private static DelegateBridge __Hotfix0_OnDetailClose; // 0x68
	private static DelegateBridge __Hotfix0_OnAllRewardClose; // 0x70
	private static DelegateBridge __Hotfix0_OnCoverClick; // 0x78
	private static DelegateBridge __Hotfix0_OnCoverArrowClick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnNormalNoteClick; // 0x88
	private static DelegateBridge __Hotfix0_EventOnToughNoteClick; // 0x90
	private static DelegateBridge __Hotfix0_EventOnAllRewardClick; // 0x98
	private static DelegateBridge __Hotfix0_EventOnHideTips; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnNextNote; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnPrevNote; // 0xb0
	private static DelegateBridge __Hotfix0_SendGetRecordReward; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x2fddbb0 VA: 0x75955f5bb0
	public override Void Init() { }
	// RVA: 0x2fddeac VA: 0x75955f5eac
	public override Void OnEnter(String zoneId) { }
	// RVA: 0x2fde1d0 VA: 0x75955f61d0
	public override Void OnResume(Boolean isFromStack) { }
	// RVA: 0x2fde8fc VA: 0x75955f68fc
	private Void _OnBtnBackClick() { }
	// RVA: 0x2fde84c VA: 0x75955f684c
	private Boolean _TryTrigUnlockAnim() { }
	// RVA: 0x2fde168 VA: 0x75955f6168
	private Void _TryJumpToNewestNote() { }
	// RVA: 0x2fde0e8 VA: 0x75955f60e8
	private Boolean _TryTrigGuid() { }
	// RVA: 0x2fdea64 VA: 0x75955f6a64
	private Void _JumpToRecordPageByIdx(Int32 idx) { }
	// RVA: 0x2fdebc8 VA: 0x75955f6bc8
	private Void _OnRecordDetailClick(StageDiffGroup diff) { }
	// RVA: 0x2fded6c VA: 0x75955f6d6c
	public Int32 GetLatestRocordIdx() { }
	// RVA: 0x2fdeea8 VA: 0x75955f6ea8
	private Void _OnGetReward(ZoneRecordRewardResponse resp) { }
	// RVA: 0x2fdefa0 VA: 0x75955f6fa0
	private Void _UpdateRecordUnlockInfo(List`1 items, ZoneRecordUnlockData unlockData) { }
	// RVA: 0x2fdf0c4 VA: 0x75955f70c4
	public Void OnContentClick(String recordId) { }
	// RVA: 0x2fdf244 VA: 0x75955f7244
	public Void OnDetailClose() { }
	// RVA: 0x2fdf320 VA: 0x75955f7320
	public Void OnAllRewardClose() { }
	// RVA: 0x2fde9e0 VA: 0x75955f69e0
	public Void OnCoverClick() { }
	// RVA: 0x2fdf3b4 VA: 0x75955f73b4
	public Void OnCoverArrowClick() { }
	// RVA: 0x2fdf420 VA: 0x75955f7420
	public Void EventOnNormalNoteClick() { }
	// RVA: 0x2fdf48c VA: 0x75955f748c
	public Void EventOnToughNoteClick() { }
	// RVA: 0x2fdf4f8 VA: 0x75955f74f8
	public Void EventOnAllRewardClick() { }
	// RVA: 0x2fdf5d8 VA: 0x75955f75d8
	public Void EventOnHideTips() { }
	// RVA: 0x2fdf648 VA: 0x75955f7648
	public Void EventOnNextNote() { }
	// RVA: 0x2fdf728 VA: 0x75955f7728
	public Void EventOnPrevNote() { }
	// RVA: 0x2fdf874 VA: 0x75955f7874
	public Void SendGetRecordReward() { }
	// RVA: 0x2fdf970 VA: 0x75955f7970
	public Void .ctor() { }
	// RVA: 0x2fdfac0 VA: 0x75955f7ac0
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x2fdfac8 VA: 0x75955f7ac8
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x2fdfad0 VA: 0x75955f7ad0
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```