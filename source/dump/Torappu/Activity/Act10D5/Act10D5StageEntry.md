# Act10D5StageEntry

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `Act10D5EntryView _view`

- `Act10D5CoinView _coinView`

- `Act10D5EntryZoneGroupView _zoneGroupView`

- `UICommonTrackPoint _favorUpTrackPoint`

- `Button _buttonShop`

- `Button _buttonStory`

- `RectTransform _topMenuContainer`

- `GameObject _favorUpObj`

- `Boolean _useCommonFavorState`

- `CommonTopMenu m_topMenu`

- `Boolean m_isLoaded`

- `Boolean m_isAnimPlayed`


## Methods

- `Void _EventOnStageTimeout()`

- `Void _EventOnRewardTimeout()`

- `Void EventOnShopClicked()`

- `Void EventOnStoryClicked()`

- `Void EventOnFavorUpClicked()`

- `Void EventOnUngroupedMedalClicked()`

- `Void EventOnZoneAllTimeoutClicked()`

- `Void OnEnable()`

- `Void _InitTopMenu()`

- `IEnumerator _TryStartAnim()`

- `Boolean <_TryStartAnim>b__26_0()`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StageEntry : ActivityStageSingleComponent
{
	private const String ANIM_NORMAL_START_KEY; // 0x0
	private const String ANIM_ALL_TIMEOUT_START_KEY; // 0x0
	private const String ANIM_SKIP_KEY; // 0x0
	private List`1 _animatorList; // 0x20
	private Act10D5EntryView _view; // 0x28
	private Act10D5CoinView _coinView; // 0x30
	private Act10D5EntryZoneGroupView _zoneGroupView; // 0x38
	private UICommonTrackPoint _favorUpTrackPoint; // 0x40
	private Button _buttonShop; // 0x48
	private Button _buttonStory; // 0x50
	private RectTransform _topMenuContainer; // 0x58
	private GameObject _favorUpObj; // 0x60
	private Boolean _useCommonFavorState; // 0x68
	private CommonTopMenu m_topMenu; // 0x70
	private Boolean m_isLoaded; // 0x78
	private Boolean m_isAnimPlayed; // 0x79
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0__EventOnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0__EventOnRewardTimeout; // 0x10
	private static DelegateBridge __Hotfix0_EventOnShopClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnStoryClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnFavorUpClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnUngroupedMedalClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnZoneAllTimeoutClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnEnable; // 0x40
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x48
	private static DelegateBridge __Hotfix0__TryStartAnim; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3480548 VA: 0x7595a98548
	protected override Void OnLoaded() { }
	// RVA: 0x3480a44 VA: 0x7595a98a44
	private Void _EventOnStageTimeout() { }
	// RVA: 0x3480aa8 VA: 0x7595a98aa8
	private Void _EventOnRewardTimeout() { }
	// RVA: 0x3480b34 VA: 0x7595a98b34
	public Void EventOnShopClicked() { }
	// RVA: 0x3480ca8 VA: 0x7595a98ca8
	public Void EventOnStoryClicked() { }
	// RVA: 0x3480dc8 VA: 0x7595a98dc8
	public Void EventOnFavorUpClicked() { }
	// RVA: 0x3480ecc VA: 0x7595a98ecc
	public Void EventOnUngroupedMedalClicked() { }
	// RVA: 0x3481000 VA: 0x7595a99000
	public Void EventOnZoneAllTimeoutClicked() { }
	// RVA: 0x34810b4 VA: 0x7595a990b4
	private Void OnEnable() { }
	// RVA: 0x34808bc VA: 0x7595a988bc
	private Void _InitTopMenu() { }
	// RVA: 0x348112c VA: 0x7595a9912c
	private IEnumerator _TryStartAnim() { }
	// RVA: 0x3481200 VA: 0x7595a99200
	public Void .ctor() { }
	// RVA: 0x3481270 VA: 0x7595a99270
	private Boolean <_TryStartAnim>b__26_0() { }
	// RVA: 0x3481350 VA: 0x7595a99350
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```