# Act9D0StageEntry

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0CustomTopMenuBase _customTopMenu`

- `Act9D0EntryView _view`

- `Act9D0CoinView _coinView`

- `Act9D0EntryZoneGroupView _zoneGroupView`

- `UICommonTrackPoint _favorUpTrackPoint`

- `UIActTrackPoint _missionTrackPoint`

- `UICommonTrackPoint _templateTrapTrackPoint`

- `Button _buttonShop`

- `Button _buttonMission`

- `RectTransform _topMenuContainer`

- `GameObject _favorUpObj`

- `GameObject _noFavorUpObj`

- `CommonTopMenu m_topMenu`

- `Boolean m_isLoaded`

- `Boolean m_isAnimPlayed`

- `Boolean m_isBindToParent`


## Methods

- `Boolean CanPlayAudio()`

- `Void _EventOnStageTimeout()`

- `Void _EventOnRewardTimeout()`

- `Void EventOnShopClicked()`

- `Void EventOnTrapClicked()`

- `Void EventOnMissionClicked()`

- `Void EventOnReplicateClicked()`

- `Void EventOnMedalGroupClicked()`

- `Void EventOnFavorUpClicked()`

- `Void EventOnZoneAllTimeoutClicked()`

- `Void EventOnReplayEntryAVG()`

- `Void Awake()`

- `Void OnEnable()`

- `Void _InitTopMenu()`

- `Void _OnBackClicked()`

- `Boolean _TryResetAnim()`

- `IEnumerator _TryStartAnim()`

- `Void _UpdateBindToParentStatus()`

- `Void _OnZoneViewClicked(String)`

- `Boolean <_TryStartAnim>b__37_0()`

- `IEnumerator <>xLuaBaseProxy_LoadCoroutine()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnBindToParent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0StageEntry : ActivityStageSingleComponent, IAudioAnimationPlayerConditionProvider, IHotfixable
{
	private List`1 _animatorList; // 0x20
	private Act9D0CustomTopMenuBase _customTopMenu; // 0x28
	private Act9D0EntryView _view; // 0x30
	private Act9D0CoinView _coinView; // 0x38
	private Act9D0EntryZoneGroupView _zoneGroupView; // 0x40
	private UICommonTrackPoint _favorUpTrackPoint; // 0x48
	private UIActTrackPoint _missionTrackPoint; // 0x50
	private UICommonTrackPoint _templateTrapTrackPoint; // 0x58
	private Button _buttonShop; // 0x60
	private Button _buttonMission; // 0x68
	private RectTransform _topMenuContainer; // 0x70
	private GameObject _favorUpObj; // 0x78
	private GameObject _noFavorUpObj; // 0x80
	private GameObject[] _enableWhenBinded; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_isLoaded; // 0x98
	private Boolean m_isAnimPlayed; // 0x99
	private Boolean m_isBindToParent; // 0x9a
	private static DelegateBridge __Hotfix0_CanPlayAudio; // 0x0
	private static DelegateBridge __Hotfix0_LoadCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_OnBindToParent; // 0x18
	private static DelegateBridge __Hotfix0__EventOnStageTimeout; // 0x20
	private static DelegateBridge __Hotfix0__EventOnRewardTimeout; // 0x28
	private static DelegateBridge __Hotfix0_EventOnShopClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnTrapClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnMissionClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnReplicateClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnMedalGroupClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnFavorUpClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnZoneAllTimeoutClicked; // 0x60
	private static DelegateBridge __Hotfix0_EventOnReplayEntryAVG; // 0x68
	private static DelegateBridge __Hotfix0_Awake; // 0x70
	private static DelegateBridge __Hotfix0_OnEnable; // 0x78
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x80
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x88
	private static DelegateBridge __Hotfix0__TryResetAnim; // 0x90
	private static DelegateBridge __Hotfix0__TryStartAnim; // 0x98
	private static DelegateBridge __Hotfix0__UpdateBindToParentStatus; // 0xa0
	private static DelegateBridge __Hotfix0__OnZoneViewClicked; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x319c6f0 VA: 0x75957b46f0
	public Boolean CanPlayAudio() { }
	// RVA: 0x319c818 VA: 0x75957b4818
	public override IEnumerator LoadCoroutine() { }
	// RVA: 0x319c8ec VA: 0x75957b48ec
	protected override Void OnLoaded() { }
	// RVA: 0x319d66c VA: 0x75957b566c
	protected override Void OnBindToParent() { }
	// RVA: 0x319d7b8 VA: 0x75957b57b8
	private Void _EventOnStageTimeout() { }
	// RVA: 0x319d81c VA: 0x75957b581c
	private Void _EventOnRewardTimeout() { }
	// RVA: 0x319d8a8 VA: 0x75957b58a8
	public Void EventOnShopClicked() { }
	// RVA: 0x319da34 VA: 0x75957b5a34
	public Void EventOnTrapClicked() { }
	// RVA: 0x319dbac VA: 0x75957b5bac
	public Void EventOnMissionClicked() { }
	// RVA: 0x319dce8 VA: 0x75957b5ce8
	public Void EventOnReplicateClicked() { }
	// RVA: 0x319ddcc VA: 0x75957b5dcc
	public Void EventOnMedalGroupClicked() { }
	// RVA: 0x319deb0 VA: 0x75957b5eb0
	public Void EventOnFavorUpClicked() { }
	// RVA: 0x319dfd0 VA: 0x75957b5fd0
	public Void EventOnZoneAllTimeoutClicked() { }
	// RVA: 0x319e084 VA: 0x75957b6084
	public Void EventOnReplayEntryAVG() { }
	// RVA: 0x319e26c VA: 0x75957b626c
	private Void Awake() { }
	// RVA: 0x319e2d4 VA: 0x75957b62d4
	private Void OnEnable() { }
	// RVA: 0x319ce34 VA: 0x75957b4e34
	private Void _InitTopMenu() { }
	// RVA: 0x319e590 VA: 0x75957b6590
	private Void _OnBackClicked() { }
	// RVA: 0x319e350 VA: 0x75957b6350
	private Boolean _TryResetAnim() { }
	// RVA: 0x319e624 VA: 0x75957b6624
	private IEnumerator _TryStartAnim() { }
	// RVA: 0x319d6e8 VA: 0x75957b56e8
	private Void _UpdateBindToParentStatus() { }
	// RVA: 0x319e6f8 VA: 0x75957b66f8
	private Void _OnZoneViewClicked(String zoneId) { }
	// RVA: 0x319e820 VA: 0x75957b6820
	public Void .ctor() { }
	// RVA: 0x319e890 VA: 0x75957b6890
	private Boolean <_TryStartAnim>b__37_0() { }
	// RVA: 0x319e974 VA: 0x75957b6974
	private IEnumerator <>xLuaBaseProxy_LoadCoroutine() { }
	// RVA: 0x319e97c VA: 0x75957b697c
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x319e984 VA: 0x75957b6984
	private Void <>xLuaBaseProxy_OnBindToParent() { }
}
```