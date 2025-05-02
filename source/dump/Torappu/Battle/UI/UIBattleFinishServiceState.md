# UIBattleFinishServiceState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _raycastBlocker`

- `BattleFinishServiceStateParam m_stateParam`

- `Int32 m_retryCount`

- `Int32 m_maxRetryCount`


## Methods

- `Boolean _OnFinishBattleServiceFailed(ResponseError)`

- `Void _OnFinishBattleServiceSuc(T)`

- `Void _OnContinueBattleServiceSuc(T)`

- `IEnumerator _SendBattleService(Boolean)`

- `Void SendFinishBattleService(String, TRequest, Boolean)`

- `Void SendContinueBattleService(String, TRequest, Boolean)`

- `TRequest ParseCommonFinishBattleRequest()`

- `Void _DoSendFinishBattleService(String, TRequest, Boolean)`

- `Void _DoSendContinueBattleService(String, TRequest, Boolean)`

- `Void _DoSendBattleServiceImpl(String, TRequest, Boolean, Action`1)`

- `Void _ShowRetryDialog(ResponseError)`

- `Void _ConfirmServiceFail()`

- `T _ParseCommonFinishBattleRequest()`

- `DefaultFinishBattleRequest _ParseDefaultFinishBattleRequest()`

- `CampaignFinishBattleRequest _ParseCampaignFinishBattleRequest()`

- `String _AchieveBattleLog()`

- `Void <_ShowRetryDialog>b__28_0()`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`

- `Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleFinishServiceState : UIStateNode, IFinishBattleServiceSender
{
	private const Int32 MAX_RETRY_COUNT; // 0x0
	private GameObject _raycastBlocker; // 0x20
	private BattleFinishServiceStateParam m_stateParam; // 0x28
	private Int32 m_retryCount; // 0x2c
	private Int32 m_maxRetryCount; // 0x30
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x8
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0_CheckSwitchOut; // 0x38
	private static DelegateBridge __Hotfix0__OnFinishBattleServiceFailed; // 0x40
	private static DelegateBridge __Hotfix0__OnFinishBattleServiceSuc; // 0x48
	private static DelegateBridge __Hotfix0__OnContinueBattleServiceSuc; // 0x50
	private static DelegateBridge __Hotfix0__LogBattleInfoToGameAnalytics; // 0x58
	private static DelegateBridge __Hotfix0__SendBattleService; // 0x60
	private static DelegateBridge __Hotfix0_SendFinishBattleService; // 0x68
	private static DelegateBridge __Hotfix0_SendContinueBattleService; // 0x70
	private static DelegateBridge __Hotfix0_ParseCommonFinishBattleRequest; // 0x78
	private static DelegateBridge __Hotfix0__DoSendFinishBattleService; // 0x80
	private static DelegateBridge __Hotfix0__DoSendContinueBattleService; // 0x88
	private static DelegateBridge __Hotfix0__DoSendBattleServiceImpl; // 0x90
	private static DelegateBridge __Hotfix0__ShowRetryDialog; // 0x98
	private static DelegateBridge __Hotfix0__ConfirmServiceFail; // 0xa0
	private static DelegateBridge __Hotfix0__ParseCommonFinishBattleRequest; // 0xa8
	private static DelegateBridge __Hotfix0__ParseDefaultFinishBattleRequest; // 0xb0
	private static DelegateBridge __Hotfix0__ParseCampaignFinishBattleRequest; // 0xb8
	private static DelegateBridge __Hotfix0__AchieveBattleLog; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public override UIStateEnum uiState { get; }
	public override Boolean enablePause { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x2055ce8 VA: 0x759466dce8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x2055d50 VA: 0x759466dd50
	public override Boolean get_enablePause() { }
	// RVA: 0x2055db4 VA: 0x759466ddb4
	public override Boolean get_enableShowRange() { }
	// RVA: 0x2055e18 VA: 0x759466de18
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2055e7c VA: 0x759466de7c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2056108 VA: 0x759466e108
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x205623c VA: 0x759466e23c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20562b4 VA: 0x759466e2b4
	public override Boolean CheckSwitchOut(Int32 nextState) { }
	// RVA: 0x2056334 VA: 0x759466e334
	private Boolean _OnFinishBattleServiceFailed(ResponseError respError) { }
	// RVA: 0x VA: 0x0
	private Void _OnFinishBattleServiceSuc(T response) { }
	// RVA: 0x VA: 0x0
	private Void _OnContinueBattleServiceSuc(T response) { }
	// RVA: 0x205678c VA: 0x759466e78c
	private static Void _LogBattleInfoToGameAnalytics(BattleInOut battleInOut) { }
	// RVA: 0x2056040 VA: 0x759466e040
	private IEnumerator _SendBattleService(Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	public Void SendFinishBattleService(String serviceCode, TRequest request, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	public Void SendContinueBattleService(String serviceCode, TRequest request, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	public TRequest ParseCommonFinishBattleRequest() { }
	// RVA: 0x VA: 0x0
	private Void _DoSendFinishBattleService(String serviceCode, TRequest request, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	private Void _DoSendContinueBattleService(String serviceCode, TRequest request, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	private Void _DoSendBattleServiceImpl(String serviceCode, TRequest request, Boolean isRetry, Action`1 callback) { }
	// RVA: 0x20564f8 VA: 0x759466e4f8
	private Void _ShowRetryDialog(ResponseError errorInfo) { }
	// RVA: 0x2056a24 VA: 0x759466ea24
	private Void _ConfirmServiceFail() { }
	// RVA: 0x VA: 0x0
	private T _ParseCommonFinishBattleRequest() { }
	// RVA: 0x2056bb4 VA: 0x759466ebb4
	private DefaultFinishBattleRequest _ParseDefaultFinishBattleRequest() { }
	// RVA: 0x2056c34 VA: 0x759466ec34
	private CampaignFinishBattleRequest _ParseCampaignFinishBattleRequest() { }
	// RVA: 0x2056cb4 VA: 0x759466ecb4
	private String _AchieveBattleLog() { }
	// RVA: 0x2056eac VA: 0x759466eeac
	public Void .ctor() { }
	// RVA: 0x2056f24 VA: 0x759466ef24
	private Void <_ShowRetryDialog>b__28_0() { }
	// RVA: 0x2056f90 VA: 0x759466ef90
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x2056f98 VA: 0x759466ef98
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x2056fa0 VA: 0x759466efa0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x2056fa8 VA: 0x759466efa8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2056fb0 VA: 0x759466efb0
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
	// RVA: 0x2056fb8 VA: 0x759466efb8
	private Boolean <>xLuaBaseProxy_CheckSwitchOut(Int32 P0) { }
}
```