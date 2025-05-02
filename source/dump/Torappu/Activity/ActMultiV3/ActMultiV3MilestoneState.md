# ActMultiV3MilestoneState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3TemplateMilestoneViewAdapter _view`

- `RectTransform _topMenuContainer`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `ActMultiV3MileStoneStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSkinRewardPreviewClick(String)`

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
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MilestoneState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 MSG_MILESTONE_CLICK; // 0x0
	public const Int32 MSG_MILESTONE_SKIN_CHECK; // 0x0
	private ActMultiV3TemplateMilestoneViewAdapter _view; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Boolean m_isInited; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private ActMultiV3MileStoneStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnSkinRewardPreviewClick; // 0x28
	private static DelegateBridge __Hotfix0_OnMilestoneAllRewardClick; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EventOnClickReturnBtn; // 0x40
	private static DelegateBridge __Hotfix0__OnMilestoneItemClick; // 0x48
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x30f3d18 VA: 0x759570bd18
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30f3d80 VA: 0x759570bd80
	protected override Void OnEnter() { }
	// RVA: 0x30f40d0 VA: 0x759570c0d0
	protected override Void OnResume() { }
	// RVA: 0x30f4144 VA: 0x759570c144
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x30f42d8 VA: 0x759570c2d8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x30f4694 VA: 0x759570c694
	private Void _OnSkinRewardPreviewClick(String id) { }
	// RVA: 0x30f4734 VA: 0x759570c734
	public Void OnMilestoneAllRewardClick() { }
	// RVA: 0x30f3eb4 VA: 0x759570beb4
	private Void _InitIfNot() { }
	// RVA: 0x30f4ae0 VA: 0x759570cae0
	private Void _EventOnClickReturnBtn() { }
	// RVA: 0x30f43a4 VA: 0x759570c3a4
	private Void _OnMilestoneItemClick(String milestoneId) { }
	// RVA: 0x30f4c18 VA: 0x759570cc18
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x30f4d00 VA: 0x759570cd00
	public Void .ctor() { }
	// RVA: 0x30f4e58 VA: 0x759570ce58
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x30f4e80 VA: 0x759570ce80
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30f4e88 VA: 0x759570ce88
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x30f4e90 VA: 0x759570ce90
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```