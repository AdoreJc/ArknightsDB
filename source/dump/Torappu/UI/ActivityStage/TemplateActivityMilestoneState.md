# TemplateActivityMilestoneState

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `TemplateActivityMilestoneHolder _holder`

- `RectTransform _topMenuContainer`

- `IBaseActHanlder m_handler`

- `Boolean m_hasInited`


## Methods

- `Void BindHandler(IBaseActHanlder)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnBtnAllReward()`

- `Void EventOnBtnCharSkinClick()`

- `Void _InitIfNot()`

- `Void _OnMilestoneItemClick(String)`

- `Void _OnMilestoneCharSkinClick()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnExit()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMilestoneState : PopupFloatState, IBaseActStateBinder, IHotfixable, IValueMsgReceiver
{
	private TemplateActivityMilestoneHolder _holder; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	public const Int32 MSG_MILESTONE_CLICK; // 0x0
	public const Int32 MSG_CHAR_SKIN_CLICK; // 0x0
	private IBaseActHanlder m_handler; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_BindHandler; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnAllReward; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnCharSkinClick; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnMilestoneItemClick; // 0x50
	private static DelegateBridge __Hotfix0__OnMilestoneCharSkinClick; // 0x58
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x309b6f8 VA: 0x75956b36f8
	public Void BindHandler(IBaseActHanlder handler) { }
	// RVA: 0x309b77c VA: 0x75956b377c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x309b7e0 VA: 0x75956b37e0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x309bf64 VA: 0x75956b3f64
	protected override Void OnEnter() { }
	// RVA: 0x309c148 VA: 0x75956b4148
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x309c330 VA: 0x75956b4330
	protected override Void OnExit() { }
	// RVA: 0x309c444 VA: 0x75956b4444
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x309c5d8 VA: 0x75956b45d8
	public Void EventOnBtnAllReward() { }
	// RVA: 0x309c9bc VA: 0x75956b49bc
	public Void EventOnBtnCharSkinClick() { }
	// RVA: 0x309c080 VA: 0x75956b4080
	private Void _InitIfNot() { }
	// RVA: 0x309b8a8 VA: 0x75956b38a8
	private Void _OnMilestoneItemClick(String milestoneId) { }
	// RVA: 0x309bca8 VA: 0x75956b3ca8
	private Void _OnMilestoneCharSkinClick() { }
	// RVA: 0x309ca2c VA: 0x75956b4a2c
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x309cb14 VA: 0x75956b4b14
	public Void .ctor() { }
	// RVA: 0x309cb84 VA: 0x75956b4b84
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x309cbac VA: 0x75956b4bac
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x309cbb4 VA: 0x75956b4bb4
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x309cbc0 VA: 0x75956b4bc0
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x309cbc8 VA: 0x75956b4bc8
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```