# ActMultiV3ManualState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3ManualView _view`

- `RectTransform _topMenuContainer`

- `String _guideSubSignal`

- `Boolean m_inited`

- `String m_actId`

- `ActMultiV3ManualStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnClickTitle()`

- `Void _OnSwitchTab(Int32)`

- `Void _OnClaimMission(String)`

- `Void _OnClaimAllMission()`

- `Void _OnClaimMissionSuc(List`1, List`1)`

- `Void _OnClickAlbumTab(Int32)`

- `Void _OnClaimAlbum(String)`

- `Void _OnClickPhoto(String, Int32)`

- `Void _CollectPhotoUids(String, ref)`

- `Void _AddPhotoSelectState()`

- `Void _InitIfNot()`

- `String _GetActivityId()`

- `Void _EventOnBtnBack()`

- `Boolean _IsStateStable()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void _RegisterToPhotoSelectState(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_CLICK_TITLE; // 0x0
	public const Int32 ON_SWITCH_TAB; // 0x0
	public const Int32 ON_CLAIM_MISSION; // 0x0
	public const Int32 ON_CLAIM_ALL_MISSION; // 0x0
	public const Int32 ON_CLICK_ALBUM_TAB; // 0x0
	public const Int32 ON_CLAIM_ALBUM; // 0x0
	public const Int32 ON_CLICK_PHOTO; // 0x0
	private ActMultiV3ManualView _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private String _guideSubSignal; // 0x80
	private Boolean m_inited; // 0x88
	private String m_actId; // 0x90
	private ActMultiV3ManualStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnClickTitle; // 0x28
	private static DelegateBridge __Hotfix0__OnSwitchTab; // 0x30
	private static DelegateBridge __Hotfix0__OnClaimMission; // 0x38
	private static DelegateBridge __Hotfix0__OnClaimAllMission; // 0x40
	private static DelegateBridge __Hotfix0__OnClaimMissionSuc; // 0x48
	private static DelegateBridge __Hotfix0__OnClickAlbumTab; // 0x50
	private static DelegateBridge __Hotfix0__OnClaimAlbum; // 0x58
	private static DelegateBridge __Hotfix0__OnClickPhoto; // 0x60
	private static DelegateBridge __Hotfix0__CollectPhotoUids; // 0x68
	private static DelegateBridge __Hotfix0__AddPhotoSelectState; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__GetActivityId; // 0x80
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x88
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x90
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x98
	private static DelegateBridge __Hotfix0__RegisterToPhotoSelectState; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x30f85b4 VA: 0x75957105b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30f861c VA: 0x759571061c
	protected override Void OnEnter() { }
	// RVA: 0x30f89e0 VA: 0x75957109e0
	protected override Void OnResume() { }
	// RVA: 0x30f8b30 VA: 0x7595710b30
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x30f8ca8 VA: 0x7595710ca8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x30f8e10 VA: 0x7595710e10
	private Void _OnClickTitle() { }
	// RVA: 0x30f8f38 VA: 0x7595710f38
	private Void _OnSwitchTab(Int32 tabType) { }
	// RVA: 0x30f9050 VA: 0x7595711050
	private Void _OnClaimMission(String missionId) { }
	// RVA: 0x30f93d4 VA: 0x75957113d4
	private Void _OnClaimAllMission() { }
	// RVA: 0x30fa308 VA: 0x7595712308
	private Void _OnClaimMissionSuc(List`1 missionIds, List`1 items) { }
	// RVA: 0x30f9810 VA: 0x7595711810
	private Void _OnClickAlbumTab(Int32 tabIdx) { }
	// RVA: 0x30f9a5c VA: 0x7595711a5c
	private Void _OnClaimAlbum(String weekRewardId) { }
	// RVA: 0x30f9d14 VA: 0x7595711d14
	private Void _OnClickPhoto(String templateId, Int32 photoTypeIdx) { }
	// RVA: 0x30fa6d8 VA: 0x75957126d8
	private Void _CollectPhotoUids(String templateId, ref HashSet`1 idSet) { }
	// RVA: 0x30fa8a0 VA: 0x75957128a0
	private Void _AddPhotoSelectState() { }
	// RVA: 0x30f8708 VA: 0x7595710708
	private Void _InitIfNot() { }
	// RVA: 0x30f8814 VA: 0x7595710814
	private String _GetActivityId() { }
	// RVA: 0x30fa9b8 VA: 0x75957129b8
	private Void _EventOnBtnBack() { }
	// RVA: 0x30fa1f0 VA: 0x75957121f0
	private Boolean _IsStateStable() { }
	// RVA: 0x30fa608 VA: 0x7595712608
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x30faaac VA: 0x7595712aac
	private Void _RegisterToPhotoSelectState(IStateBean stateBean) { }
	// RVA: 0x30fac48 VA: 0x7595712c48
	public Void .ctor() { }
	// RVA: 0x30fae30 VA: 0x7595712e30
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30fae38 VA: 0x7595712e38
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x30fae40 VA: 0x7595712e40
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```