# Act20sideMilestoneState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Button _claimMilestoneBtn`

- `Button _recycleBtn`

- `Button _collectionBtn`

- `Text _collectionProgressText`

- `Text _claimCountText`

- `Text _pointProgressNumText`

- `Text _itemRandomRangeTipText`

- `FillProgressBar _bar`

- `UICommonTrackPoint _recycleTrackPoint`

- `UICommonTrackPoint _newTrackPoint`

- `AnimationWrapper _claimAnimWrap`

- `UIRecycleHorizonLayoutGroup _recycleList`

- `RectTransform _viewPort`

- `Act20sideMilestoneLoopItemView _loopItemPrefab`

- `Act20sideMilestoneLoopItemAdapter m_adapter`

- `Act20sideRecycleView m_recycleView`

- `Sequence m_seq`

- `Act20sideMilestoneStateBean m_statebean`

- `TrackPointViewProperty m_trackProperty`

- `TrackPointViewProperty m_recycleProperty`

- `Boolean m_hasInited`

- `Boolean m_isClaiming`


## Methods

- `Void OnDestroy()`

- `Void _OnJumpToCollectionState(IStateBean)`

- `Void Refresh(Boolean)`

- `Void _BlockDuringClaim(Boolean)`

- `Void OnClaimClicked()`

- `Void OnCollectionClicked()`

- `Void OnRecycleClicked()`

- `Void _InitIfNot()`

- `Void _ReceiveItems(List`1)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void _TweenMoveAdapter(Int32, Single)`

- `Void <OnClaimClicked>b__33_0(ClaimMilestoneAwardResponse)`

- `Void <_ReceiveItems>b__37_0()`

- `Void <_TweenMoveAdapter>b__39_1(Single)`

- `Void <_TweenMoveAdapter>b__39_2()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideMilestoneState : PopupFadeState
{
	private const String PROGRESS_FORMAT; // 0x0
	private const String ANIM_STATE_NAME; // 0x0
	private const Single MILESTONE_LIST_ANIM_DUATION; // 0x0
	private Button _claimMilestoneBtn; // 0x70
	private Button _recycleBtn; // 0x78
	private Button _collectionBtn; // 0x80
	private Text _collectionProgressText; // 0x88
	private Text _claimCountText; // 0x90
	private Text _pointProgressNumText; // 0x98
	private Text _itemRandomRangeTipText; // 0xa0
	private FillProgressBar _bar; // 0xa8
	private UICommonTrackPoint _recycleTrackPoint; // 0xb0
	private UICommonTrackPoint _newTrackPoint; // 0xb8
	private AnimationWrapper _claimAnimWrap; // 0xc0
	private UIRecycleHorizonLayoutGroup _recycleList; // 0xc8
	private RectTransform _viewPort; // 0xd0
	private Act20sideMilestoneLoopItemView _loopItemPrefab; // 0xd8
	private Act20sideMilestoneLoopItemAdapter m_adapter; // 0xe0
	private Act20sideRecycleView m_recycleView; // 0xe8
	private Sequence m_seq; // 0xf0
	private Act20sideMilestoneStateBean m_statebean; // 0xf8
	private TrackPointViewProperty m_trackProperty; // 0x100
	private TrackPointViewProperty m_recycleProperty; // 0x108
	private Boolean m_hasInited; // 0x110
	private Boolean m_isClaiming; // 0x111
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToCollectionState; // 0x28
	private static DelegateBridge __Hotfix0_Refresh; // 0x30
	private static DelegateBridge __Hotfix0__BlockDuringClaim; // 0x38
	private static DelegateBridge __Hotfix0_OnClaimClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnCollectionClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnRecycleClicked; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__ReceiveItems; // 0x60
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__TweenMoveAdapter; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x32f82a0 VA: 0x75959102a0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f8308 VA: 0x7595910308
	protected override Void OnEnter() { }
	// RVA: 0x32f94b8 VA: 0x75959114b8
	protected override Void OnResume() { }
	// RVA: 0x32f954c VA: 0x759591154c
	private Void OnDestroy() { }
	// RVA: 0x32f95bc VA: 0x75959115bc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32f9734 VA: 0x7595911734
	private Void _OnJumpToCollectionState(IStateBean stateBean) { }
	// RVA: 0x32f8da8 VA: 0x7595910da8
	private Void Refresh(Boolean packClaimed) { }
	// RVA: 0x32f9824 VA: 0x7595911824
	private Void _BlockDuringClaim(Boolean isToBlock) { }
	// RVA: 0x32f98e8 VA: 0x75959118e8
	private Void OnClaimClicked() { }
	// RVA: 0x32f9bac VA: 0x7595911bac
	private Void OnCollectionClicked() { }
	// RVA: 0x32f9d28 VA: 0x7595911d28
	private Void OnRecycleClicked() { }
	// RVA: 0x32f84dc VA: 0x75959104dc
	private Void _InitIfNot() { }
	// RVA: 0x32fa29c VA: 0x759591229c
	private Void _ReceiveItems(List`1 rewardL) { }
	// RVA: 0x32fa3dc VA: 0x75959123dc
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x32f917c VA: 0x759591117c
	private Void _TweenMoveAdapter(Int32 col, Single duration) { }
	// RVA: 0x32fa4dc VA: 0x75959124dc
	public Void .ctor() { }
	// RVA: 0x32fa634 VA: 0x7595912634
	private Void <OnClaimClicked>b__33_0(ClaimMilestoneAwardResponse response) { }
	// RVA: 0x32fa778 VA: 0x7595912778
	private Void <_ReceiveItems>b__37_0() { }
	// RVA: 0x32fa780 VA: 0x7595912780
	private Void <_TweenMoveAdapter>b__39_1(Single val) { }
	// RVA: 0x32fa7c0 VA: 0x75959127c0
	private Void <_TweenMoveAdapter>b__39_2() { }
	// RVA: 0x32fa7f4 VA: 0x75959127f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32fa7fc VA: 0x75959127fc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x32fa804 VA: 0x7595912804
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```