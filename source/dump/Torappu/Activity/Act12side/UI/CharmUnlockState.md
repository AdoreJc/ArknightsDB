# CharmUnlockState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `CharmCard _cardPrefab`

- `RectTransform _listRoot`

- `GridLayoutGroup _layout`

- `Text _coin`

- `AnimationWrapper _animWrapper`

- `String m_activityId`


## Methods

- `Void _Refresh()`

- `Void _InitIfNot()`

- `Void EventOnGet()`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `String _GetTheActivityOpenedMe()`

- `Act12sideStageController _FindController()`

- `Void <EventOnGet>b__14_0(GetCharmFirstRewardResponse)`

- `Boolean <EventOnGet>b__14_1(ResponseError)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmUnlockState : PopupFloatState
{
	private CharmCard _cardPrefab; // 0x70
	private RectTransform _listRoot; // 0x78
	private GridLayoutGroup _layout; // 0x80
	private Text _coin; // 0x88
	private AnimationWrapper _animWrapper; // 0x90
	private const String ANIM_ENTRY; // 0x0
	private String m_activityId; // 0x98
	private List`1 m_cards; // 0xa0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnPause; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__Refresh; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_EventOnGet; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__GetTheActivityOpenedMe; // 0x40
	private static DelegateBridge __Hotfix0__FindController; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x345a814 VA: 0x7595a72814
	protected override Void OnEnter() { }
	// RVA: 0x345a9a0 VA: 0x7595a729a0
	protected override Void OnPause() { }
	// RVA: 0x345aa2c VA: 0x7595a72a2c
	protected override Void OnResume() { }
	// RVA: 0x345aac0 VA: 0x7595a72ac0
	private Void _Refresh() { }
	// RVA: 0x345aeec VA: 0x7595a72eec
	private Void _InitIfNot() { }
	// RVA: 0x345af7c VA: 0x7595a72f7c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x345afe0 VA: 0x7595a72fe0
	public Void EventOnGet() { }
	// RVA: 0x345b24c VA: 0x7595a7324c
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x345a8b8 VA: 0x7595a728b8
	private String _GetTheActivityOpenedMe() { }
	// RVA: 0x345b34c VA: 0x7595a7334c
	private Act12sideStageController _FindController() { }
	// RVA: 0x345b4f0 VA: 0x7595a734f0
	public Void .ctor() { }
	// RVA: 0x345b560 VA: 0x7595a73560
	private Void <EventOnGet>b__14_0(GetCharmFirstRewardResponse response) { }
	// RVA: 0x345b678 VA: 0x7595a73678
	private Boolean <EventOnGet>b__14_1(ResponseError error) { }
	// RVA: 0x345b698 VA: 0x7595a73698
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x345b6a0 VA: 0x7595a736a0
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x345b6a8 VA: 0x7595a736a8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```