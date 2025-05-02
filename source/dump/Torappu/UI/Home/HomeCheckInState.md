# HomeCheckInState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeCheckInGridView _gridView`

- `HomeCheckInCountDownView _countDownView`

- `HomeCheckInProgressGPInfoView _progressGpInfoView`

- `HomeCheckInCommonRewardView _commonRewardView`

- `HomeCheckInProgressGPDetailView _detailView`

- `HomeCheckInStateBean m_stateBean`

- `Boolean m_hasInited`

- `Boolean m_isItemGained`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnBackPressed()`

- `Void _InitIfNot()`

- `Void _SendCheckInRequest()`

- `IEnumerator _ReceiveItemsCoroutine(CheckInResponse, UIPage)`

- `Void _OnSignInItemClicked(Int32)`

- `Void _SetProgressDetailShownStatus(Boolean)`

- `Void <_SendCheckInRequest>b__18_0(CheckInResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInState : PopupFloatState, IValueMsgReceiver, IHotfixable
{
	private const Single DELAY_CHECKIN_TODAY_EFFECT; // 0x0
	public const Int32 MSG_ON_SIGN_IN_ITEM_CLICKED; // 0x0
	public const Int32 MSG_ON_PROGRESS_DETAIL_CLICKED; // 0x0
	public const Int32 MSG_ON_PROGRESS_DETAIL_HIDE_CLICKED; // 0x0
	private HomeCheckInGridView _gridView; // 0x70
	private HomeCheckInCountDownView _countDownView; // 0x78
	private HomeCheckInProgressGPInfoView _progressGpInfoView; // 0x80
	private HomeCheckInCommonRewardView _commonRewardView; // 0x88
	private HomeCheckInProgressGPDetailView _detailView; // 0x90
	private HomeCheckInStateBean m_stateBean; // 0x98
	private Boolean m_hasInited; // 0xa0
	private Boolean m_isItemGained; // 0xa1
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBackPressed; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SendCheckInRequest; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__OnSignInItemClicked; // 0x40
	private static DelegateBridge __Hotfix0__SetProgressDetailShownStatus; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x27eec4c VA: 0x7594e06c4c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27eecb4 VA: 0x7594e06cb4
	protected override Void OnEnter() { }
	// RVA: 0x27eefa0 VA: 0x7594e06fa0
	protected override Void OnResume() { }
	// RVA: 0x27ef194 VA: 0x7594e07194
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27ef44c VA: 0x7594e0744c
	public Void EventOnBackPressed() { }
	// RVA: 0x27eeda0 VA: 0x7594e06da0
	private Void _InitIfNot() { }
	// RVA: 0x27ef050 VA: 0x7594e07050
	private Void _SendCheckInRequest() { }
	// RVA: 0x27ef568 VA: 0x7594e07568
	private IEnumerator _ReceiveItemsCoroutine(CheckInResponse response, UIPage page) { }
	// RVA: 0x27ef298 VA: 0x7594e07298
	private Void _OnSignInItemClicked(Int32 index) { }
	// RVA: 0x27ef368 VA: 0x7594e07368
	private Void _SetProgressDetailShownStatus(Boolean isShown) { }
	// RVA: 0x27ef678 VA: 0x7594e07678
	public Void .ctor() { }
	// RVA: 0x27ef728 VA: 0x7594e07728
	private Void <_SendCheckInRequest>b__18_0(CheckInResponse response) { }
	// RVA: 0x27ef838 VA: 0x7594e07838
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27ef840 VA: 0x7594e07840
	private Void <>xLuaBaseProxy_OnResume() { }
}
```