# CharmRecycleState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `RectTransform _topMenuContainer`

- `GameObject _recycle`

- `RectTransform _listRoot`

- `CharmCard _charmCardPrefab`

- `GameObject _bottom`

- `Text _totalExchangeCoin`

- `GameObject _empty`

- `Text _curCoinNum`

- `CharmExchangeBar _exchangeBar`

- `AnimationWrapper _animWrapper`

- `Act12sideJunkdealerView _junkDealerView`

- `String m_activity`

- `Act12SideData m_actData`

- `Int32 m_nextStack`

- `Int32 m_rewardThreshold`

- `Boolean m_recycling`

- `Boolean m_refreshedOnEnter`


## Methods

- `Void _Refresh()`

- `Void _InitIfNot()`

- `Void _TriggerRecycleDialog(Int32, Boolean)`

- `Int32 _GetCoinNum(PlayerAct12sideActivity)`

- `Boolean _CheckCanRecycle()`

- `Void EventUpdateCurCoin()`

- `Void EventOnRecycle()`

- `IEnumerator _PlayRecycleAnim(List`1, List`1)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void EventOnShop()`

- `Void EventOnShowRewardList()`

- `String _GetTheActivityOpenedMe()`

- `Act12sideStageController _FindController()`

- `Void <_InitIfNot>b__25_0()`

- `Void <EventOnRecycle>b__31_0(RecycleCharmsResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmRecycleState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private GameObject _recycle; // 0x78
	private RectTransform _listRoot; // 0x80
	private CharmCard _charmCardPrefab; // 0x88
	private GameObject _bottom; // 0x90
	private Text _totalExchangeCoin; // 0x98
	private GameObject[] _recycleTips; // 0xa0
	private GameObject _empty; // 0xa8
	private Text _curCoinNum; // 0xb0
	private CharmExchangeBar _exchangeBar; // 0xb8
	private AnimationWrapper _animWrapper; // 0xc0
	private Act12sideJunkdealerView _junkDealerView; // 0xc8
	private const String ANIM_TIP_FADEOUT; // 0x0
	private const String ANIM_SWITCH_EMPTY; // 0x0
	private List`1 m_charmModels; // 0xd0
	private List`1 m_items; // 0xd8
	private String m_activity; // 0xe0
	private Act12SideData m_actData; // 0xe8
	private Int32 m_nextStack; // 0xf0
	private Int32 m_rewardThreshold; // 0xf4
	private Boolean m_recycling; // 0xf8
	private Boolean m_refreshedOnEnter; // 0xf9
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__Refresh; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__TriggerRecycleDialog; // 0x20
	private static DelegateBridge __Hotfix0__GetCoinNum; // 0x28
	private static DelegateBridge __Hotfix0__CheckCanRecycle; // 0x30
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x38
	private static DelegateBridge __Hotfix0_EventUpdateCurCoin; // 0x40
	private static DelegateBridge __Hotfix0_EventOnRecycle; // 0x48
	private static DelegateBridge __Hotfix0__PlayRecycleAnim; // 0x50
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_EventOnShop; // 0x60
	private static DelegateBridge __Hotfix0_EventOnShowRewardList; // 0x68
	private static DelegateBridge __Hotfix0__GetTheActivityOpenedMe; // 0x70
	private static DelegateBridge __Hotfix0__FindController; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x34529b0 VA: 0x7595a6a9b0
	protected override Void OnEnter() { }
	// RVA: 0x3453650 VA: 0x7595a6b650
	protected override Void OnResume() { }
	// RVA: 0x3452dd4 VA: 0x7595a6add4
	private Void _Refresh() { }
	// RVA: 0x3452a2c VA: 0x7595a6aa2c
	private Void _InitIfNot() { }
	// RVA: 0x3453760 VA: 0x7595a6b760
	private Void _TriggerRecycleDialog(Int32 recyclePoints, Boolean isGacha) { }
	// RVA: 0x34536d0 VA: 0x7595a6b6d0
	private Int32 _GetCoinNum(PlayerAct12sideActivity status) { }
	// RVA: 0x345392c VA: 0x7595a6b92c
	private Boolean _CheckCanRecycle() { }
	// RVA: 0x3453a14 VA: 0x7595a6ba14
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3453a78 VA: 0x7595a6ba78
	public Void EventUpdateCurCoin() { }
	// RVA: 0x3453b24 VA: 0x7595a6bb24
	public Void EventOnRecycle() { }
	// RVA: 0x3453d34 VA: 0x7595a6bd34
	private IEnumerator _PlayRecycleAnim(List`1 coinReward, List`1 charmReward) { }
	// RVA: 0x3453e44 VA: 0x7595a6be44
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x3453f34 VA: 0x7595a6bf34
	public Void EventOnShop() { }
	// RVA: 0x34540a8 VA: 0x7595a6c0a8
	public Void EventOnShowRewardList() { }
	// RVA: 0x3453844 VA: 0x7595a6b844
	private String _GetTheActivityOpenedMe() { }
	// RVA: 0x34541b4 VA: 0x7595a6c1b4
	private Act12sideStageController _FindController() { }
	// RVA: 0x3454358 VA: 0x7595a6c358
	public Void .ctor() { }
	// RVA: 0x34543c8 VA: 0x7595a6c3c8
	private Void <_InitIfNot>b__25_0() { }
	// RVA: 0x34543d8 VA: 0x7595a6c3d8
	private Void <EventOnRecycle>b__31_0(RecycleCharmsResponse response) { }
	// RVA: 0x34544a8 VA: 0x7595a6c4a8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x34544b0 VA: 0x7595a6c4b0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```