# HomeMailDetailState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMailDetailView _view`

- `HomeMailDetailStateBean _stateBean`

- `Boolean hasSendSurvey`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnMailClick()`

- `Void _OnEnsureSurveyState()`

- `Void EventOnSurveyClick()`

- `Void _SendReceiveMailService(MailItemViewModel)`

- `Void _SendReceiveSurveyService(MailItemViewModel)`

- `Void _OnReceiveSurveyUrlSucceed(StartSurveyResponse)`

- `Void _SurveyWebCallback(MiniWebRet, Int32)`

- `Void _ReturnAndRefresh()`

- `Void JumpToMonthlySub()`

- `Void _OnReceiveItemSucceed(ReceiveMailResponse)`

- `Void DismissSelfWithRefreshMetaInfo()`

- `Void <RegisterToDataListener>b__6_0(IStateBean)`

- `Void <_OnEnsureSurveyState>b__8_0(ListMailBoxResponse)`

- `Void <DismissSelfWithRefreshMetaInfo>b__18_0(GetMetaInfoListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailDetailState : PopupFloatState
{
	private HomeMailDetailView _view; // 0x70
	private HomeMailDetailStateBean _stateBean; // 0x78
	public Boolean hasSendSurvey; // 0x80
	private Boolean m_isInited; // 0x81
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_EventOnMailClick; // 0x18
	private static DelegateBridge __Hotfix0__OnEnsureSurveyState; // 0x20
	private static DelegateBridge __Hotfix0_EventOnSurveyClick; // 0x28
	private static DelegateBridge __Hotfix0__SendReceiveMailService; // 0x30
	private static DelegateBridge __Hotfix0__SendReceiveSurveyService; // 0x38
	private static DelegateBridge __Hotfix0__OnReceiveSurveyUrlSucceed; // 0x40
	private static DelegateBridge __Hotfix0__SurveyWebCallback; // 0x48
	private static DelegateBridge __Hotfix0__ReturnAndRefresh; // 0x50
	private static DelegateBridge __Hotfix0_JumpToMonthlySub; // 0x58
	private static DelegateBridge __Hotfix0__OnReceiveItemSucceed; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x68
	private static DelegateBridge __Hotfix0_DismissSelfWithRefreshMetaInfo; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x27f46a0 VA: 0x7594e0c6a0
	private Void _InitIfNot() { }
	// RVA: 0x27f47b0 VA: 0x7594e0c7b0
	protected override Void OnEnter() { }
	// RVA: 0x27f4a7c VA: 0x7594e0ca7c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27f4bf4 VA: 0x7594e0cbf4
	public Void EventOnMailClick() { }
	// RVA: 0x27f4cd4 VA: 0x7594e0ccd4
	private Void _OnEnsureSurveyState() { }
	// RVA: 0x27f5014 VA: 0x7594e0d014
	public Void EventOnSurveyClick() { }
	// RVA: 0x27f48bc VA: 0x7594e0c8bc
	private Void _SendReceiveMailService(MailItemViewModel targetMail) { }
	// RVA: 0x27f50bc VA: 0x7594e0d0bc
	private Void _SendReceiveSurveyService(MailItemViewModel targetMail) { }
	// RVA: 0x27f5308 VA: 0x7594e0d308
	private Void _OnReceiveSurveyUrlSucceed(StartSurveyResponse response) { }
	// RVA: 0x27f5454 VA: 0x7594e0d454
	private Void _SurveyWebCallback(MiniWebRet ret, Int32 i) { }
	// RVA: 0x27f54d8 VA: 0x7594e0d4d8
	private Void _ReturnAndRefresh() { }
	// RVA: 0x27f5540 VA: 0x7594e0d540
	public Void JumpToMonthlySub() { }
	// RVA: 0x27f5650 VA: 0x7594e0d650
	private Void _OnReceiveItemSucceed(ReceiveMailResponse response) { }
	// RVA: 0x27f5940 VA: 0x7594e0d940
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27f59a8 VA: 0x7594e0d9a8
	public Void DismissSelfWithRefreshMetaInfo() { }
	// RVA: 0x27f5bc8 VA: 0x7594e0dbc8
	public Void .ctor() { }
	// RVA: 0x27f5c38 VA: 0x7594e0dc38
	private Void <RegisterToDataListener>b__6_0(IStateBean statebean) { }
	// RVA: 0x27f5cdc VA: 0x7594e0dcdc
	private Void <_OnEnsureSurveyState>b__8_0(ListMailBoxResponse response) { }
	// RVA: 0x27f5e00 VA: 0x7594e0de00
	private Void <DismissSelfWithRefreshMetaInfo>b__18_0(GetMetaInfoListResponse response) { }
	// RVA: 0x27f5e34 VA: 0x7594e0de34
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27f5e3c VA: 0x7594e0de3c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```