# Act20sideCarVoteState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCarVoteView _carVoteView`

- `Act20sideCarVotePlayerDetailView _detailView`

- `Act20sideCarVoteStateBean m_stateBean`

- `Boolean m_isInited`

- `Boolean m_playEnterAnim`

- `String m_cachedActId`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateCarVoteProperty(Boolean)`

- `Void _Vote(Int32)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void EventOnVoteClick(Int32)`

- `Void EventOnPlayerClick(Int32)`

- `Void EventOnCarDetailClick(Int32)`

- `Void EventOnDetailDismiss()`

- `Void EventOnFriendRequestSuc(String)`

- `Void EventOnBackClick()`

- `Void <_Vote>b__10_0(CarExhibitionPickResponse)`

- `Void <_Vote>b__10_2()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteState : PopupFadeState
{
	private Act20sideCarVoteView _carVoteView; // 0x70
	private Act20sideCarVotePlayerDetailView _detailView; // 0x78
	private Act20sideCarVoteStateBean m_stateBean; // 0x80
	private Boolean m_isInited; // 0x88
	private Boolean m_playEnterAnim; // 0x89
	private String m_cachedActId; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateCarVoteProperty; // 0x18
	private static DelegateBridge __Hotfix0__Vote; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_EventOnVoteClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnPlayerClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCarDetailClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnDetailDismiss; // 0x48
	private static DelegateBridge __Hotfix0_EventOnFriendRequestSuc; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x32f49bc VA: 0x759590c9bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f4a24 VA: 0x759590ca24
	protected override Void OnEnter() { }
	// RVA: 0x32f4ad8 VA: 0x759590cad8
	private Void _InitIfNot() { }
	// RVA: 0x32f4c34 VA: 0x759590cc34
	private Void _UpdateCarVoteProperty(Boolean updateNext) { }
	// RVA: 0x32f5238 VA: 0x759590d238
	private Void _Vote(Int32 index) { }
	// RVA: 0x32f5514 VA: 0x759590d514
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x32f5614 VA: 0x759590d614
	public Void EventOnVoteClick(Int32 index) { }
	// RVA: 0x32f57f8 VA: 0x759590d7f8
	public Void EventOnPlayerClick(Int32 index) { }
	// RVA: 0x32f5de8 VA: 0x759590dde8
	public Void EventOnCarDetailClick(Int32 index) { }
	// RVA: 0x32f5f40 VA: 0x759590df40
	public Void EventOnDetailDismiss() { }
	// RVA: 0x32f5fb0 VA: 0x759590dfb0
	public Void EventOnFriendRequestSuc(String uid) { }
	// RVA: 0x32f619c VA: 0x759590e19c
	public Void EventOnBackClick() { }
	// RVA: 0x32f6238 VA: 0x759590e238
	public Void .ctor() { }
	// RVA: 0x32f62ec VA: 0x759590e2ec
	private Void <_Vote>b__10_0(CarExhibitionPickResponse response) { }
	// RVA: 0x32f6438 VA: 0x759590e438
	private Void <_Vote>b__10_2() { }
	// RVA: 0x32f6448 VA: 0x759590e448
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```