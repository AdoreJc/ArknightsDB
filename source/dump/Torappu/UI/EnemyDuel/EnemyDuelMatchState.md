# EnemyDuelMatchState

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelMatchView _view`

- `RectTransform _backBtnRect`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _loopAnim`

- `AnimationSwitchTween m_enterAnimSwitchTween`

- `Boolean m_isInited`

- `EnemyDuelMatchStateBean m_stateBean`

- `LoopRequestSender m_loopSender`

- `EnemyDuelTeamInfo m_cacheTeamInst`


## Methods

- `Void _InitIfNot()`

- `Void _PassDataToWaitConnectState(IStateBean)`

- `Boolean CustomSetActive(Boolean)`

- `Boolean _CreateInitRequest(out, out)`

- `Boolean _OnInitMatchResponse(EnemyDuelStartMatchResponse)`

- `Boolean _CreateMatchQueryRequest(Boolean, out, out)`

- `Boolean _CreateCancelRequest(out, out)`

- `Boolean _CreateQueryRequest(out, out)`

- `Boolean _OnQueryMatchResponse(EnemyDuelQueryMatchResponse)`

- `Void _OnLoopSenderTick(Single)`

- `Void EventOnCancelMatchClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMatchState : UIPopupState, IPopupCustomActive
{
	private const Int32 QUERY_REQUEST_INTERVAL; // 0x0
	private EnemyDuelMatchView _view; // 0x60
	private RectTransform _backBtnRect; // 0x68
	private UIAnimationLocation _enterAnim; // 0x70
	private UIAnimationLocation _loopAnim; // 0x80
	private AnimationSwitchTween m_enterAnimSwitchTween; // 0x90
	private Boolean m_isInited; // 0x98
	private EnemyDuelMatchStateBean m_stateBean; // 0xa0
	private LoopRequestSender m_loopSender; // 0xa8
	private EnemyDuelTeamInfo m_cacheTeamInst; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x30
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x38
	private static DelegateBridge __Hotfix0__PassDataToWaitConnectState; // 0x40
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x48
	private static DelegateBridge __Hotfix0__CreateInitRequest; // 0x50
	private static DelegateBridge __Hotfix0__OnInitMatchResponse; // 0x58
	private static DelegateBridge __Hotfix0__CreateMatchQueryRequest; // 0x60
	private static DelegateBridge __Hotfix0__CreateCancelRequest; // 0x68
	private static DelegateBridge __Hotfix0__CreateQueryRequest; // 0x70
	private static DelegateBridge __Hotfix0__OnQueryMatchResponse; // 0x78
	private static DelegateBridge __Hotfix0__OnLoopSenderTick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnCancelMatchClick; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x2996270 VA: 0x7594fae270
	private Void _InitIfNot() { }
	// RVA: 0x29963f4 VA: 0x7594fae3f4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x299645c VA: 0x7594fae45c
	protected override Void OnEnter() { }
	// RVA: 0x2996998 VA: 0x7594fae998
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2996b10 VA: 0x7594faeb10
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2996c1c VA: 0x7594faec1c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2996d94 VA: 0x7594faed94
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2996ea0 VA: 0x7594faeea0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2997018 VA: 0x7594faf018
	private Void _PassDataToWaitConnectState(IStateBean stateBean) { }
	// RVA: 0x2997140 VA: 0x7594faf140
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x29971bc VA: 0x7594faf1bc
	private Boolean _CreateInitRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x29973dc VA: 0x7594faf3dc
	private Boolean _OnInitMatchResponse(EnemyDuelStartMatchResponse response) { }
	// RVA: 0x2997558 VA: 0x7594faf558
	private Boolean _CreateMatchQueryRequest(Boolean isCancel, out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x2997784 VA: 0x7594faf784
	private Boolean _CreateCancelRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x2997814 VA: 0x7594faf814
	private Boolean _CreateQueryRequest(out Request request, out UISenderRequestParam requestParam) { }
	// RVA: 0x29978a4 VA: 0x7594faf8a4
	private Boolean _OnQueryMatchResponse(EnemyDuelQueryMatchResponse response) { }
	// RVA: 0x2997c1c VA: 0x7594fafc1c
	private Void _OnLoopSenderTick(Single waitSec) { }
	// RVA: 0x2997d78 VA: 0x7594fafd78
	public Void EventOnCancelMatchClick() { }
	// RVA: 0x2997ed8 VA: 0x7594fafed8
	public Void .ctor() { }
	// RVA: 0x2998030 VA: 0x7594fb0030
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2998038 VA: 0x7594fb0038
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```