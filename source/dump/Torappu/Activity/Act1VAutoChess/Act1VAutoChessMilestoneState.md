# Act1VAutoChessMilestoneState

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessTemplateMilestoneViewAdpater _view`

- `RectTransform _topMenuContainer`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Act1VAutoChessMileStoneStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnSkinRewardPreviewClick()`

- `Void OnMilestoneAllRewardClick()`

- `Void _InitIfNot()`

- `Void _EventOnClickReturnBtn()`

- `Void _OnMilestoneItemClick(String)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessMilestoneState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MSG_MILESTONE_CLICK; // 0x0
	private Act1VAutoChessTemplateMilestoneViewAdpater _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Boolean m_isInited; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private Act1VAutoChessMileStoneStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_OnSkinRewardPreviewClick; // 0x28
	private static DelegateBridge __Hotfix0_OnMilestoneAllRewardClick; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EventOnClickReturnBtn; // 0x40
	private static DelegateBridge __Hotfix0__OnMilestoneItemClick; // 0x48
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x335c484 VA: 0x7595974484
	public override IStateBean GetCacheBean() { }
	// RVA: 0x335c4ec VA: 0x75959744ec
	protected override Void OnEnter() { }
	// RVA: 0x335c7a4 VA: 0x75959747a4
	protected override Void OnResume() { }
	// RVA: 0x335c818 VA: 0x7595974818
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x335c9ac VA: 0x75959749ac
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x335cd48 VA: 0x7595974d48
	public Void OnSkinRewardPreviewClick() { }
	// RVA: 0x335ce64 VA: 0x7595974e64
	public Void OnMilestoneAllRewardClick() { }
	// RVA: 0x335c5c0 VA: 0x75959745c0
	private Void _InitIfNot() { }
	// RVA: 0x335d438 VA: 0x7595975438
	private Void _EventOnClickReturnBtn() { }
	// RVA: 0x335ca58 VA: 0x7595974a58
	private Void _OnMilestoneItemClick(String milestoneId) { }
	// RVA: 0x335d570 VA: 0x7595975570
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x335d658 VA: 0x7595975658
	public Void .ctor() { }
	// RVA: 0x335d7b0 VA: 0x75959757b0
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x335d7d8 VA: 0x75959757d8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x335d7e0 VA: 0x75959757e0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x335d7e8 VA: 0x75959757e8
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```