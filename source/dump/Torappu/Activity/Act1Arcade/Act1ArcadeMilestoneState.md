# Act1ArcadeMilestoneState

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeMilestoneViewAdapter _view`

- `Boolean m_isInited`

- `String m_actId`

- `Act1ArcadeMilestoneStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnMilestoneAllRewardClick()`

- `Void OnThemeRewardClick()`

- `Void _InitIfNot()`

- `Void _OnMilestoneItemClick(String)`

- `Void _OnClickBack()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeMilestoneState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MSG_MILESTONE_CLICK; // 0x0
	private Act1ArcadeMilestoneViewAdapter _view; // 0x70
	private Boolean m_isInited; // 0x78
	private String m_actId; // 0x80
	private Act1ArcadeMilestoneStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_OnMilestoneAllRewardClick; // 0x20
	private static DelegateBridge __Hotfix0_OnThemeRewardClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnMilestoneItemClick; // 0x38
	private static DelegateBridge __Hotfix0__OnClickBack; // 0x40
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x34014d8 VA: 0x7595a194d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3401540 VA: 0x7595a19540
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x34019b4 VA: 0x7595a199b4
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x3401b48 VA: 0x7595a19b48
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3401ed0 VA: 0x7595a19ed0
	public Void OnMilestoneAllRewardClick() { }
	// RVA: 0x3402190 VA: 0x7595a1a190
	public Void OnThemeRewardClick() { }
	// RVA: 0x340160c VA: 0x7595a1960c
	private Void _InitIfNot() { }
	// RVA: 0x3401bf4 VA: 0x7595a19bf4
	private Void _OnMilestoneItemClick(String milestoneId) { }
	// RVA: 0x34023f8 VA: 0x7595a1a3f8
	private Void _OnClickBack() { }
	// RVA: 0x340250c VA: 0x7595a1a50c
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x34025f4 VA: 0x7595a1a5f4
	public Void .ctor() { }
	// RVA: 0x340274c VA: 0x7595a1a74c
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x3402774 VA: 0x7595a1a774
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x3402780 VA: 0x7595a1a780
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```