# Act42D0MapPage

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42d0MapView _mapView`

- `RectTransform _topMenuContainer`

- `Act42D0EffectRayCastBlockerView _effectRayCastBlocker`

- `Act42D0EffectView _effectViewPrefab`

- `Transform _effectContainer`

- `Act42D0MapAreaView _mapAreaView`

- `RectTransform _rectMapAreaView`

- `RectTransform _rectMapPreview`

- `ActivityStageMapPreviewView _mapPreview`

- `UIAnimationLocation _entryAnim`

- `GameObject _animPanel`

- `Boolean m_hasInited`

- `String m_actId`

- `Act42D0EffectProperty m_effectProp`

- `Act42d0AreaMapProperty m_mapProp`

- `Act42D0MapAreaView m_mapAreaView`

- `ActivityStageMapPreviewView m_stageMapPreviewView`

- `Act42D0EffectView m_effectView`

- `Tween m_entryTw`


## Properties

- `Act42d0AreaMapProperty mapProp`


## Methods

- `Act42d0AreaMapProperty get_mapProp()`

- `DataBundle _CreateRecoverDataBundleForBattle()`

- `Void _TriggerTutorialAVG()`

- `Void _OnEnterAnimComplete()`

- `Void _InitIfNot()`

- `Void _InitMap()`

- `Boolean _CheckCachedEffectShow(String, String, Boolean)`

- `Void _OnBackClick()`

- `Void NotifyAreaUnlock(String)`

- `Void EventOnBackClick()`

- `Void EventOnNextAreaClick()`

- `Void EventOnPrevAreaClick()`

- `Void EventOnBossClick()`

- `Void _JumpToDiffGroup(Act42D0AreaDifficulty)`

- `Void EventOnBlanckClick()`

- `Void EventOnRewardClick()`

- `Void EventOnLastProgressClick()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnEffectViewShown()`

- `Void _OnAreaSelected()`

- `Void _OnFirstStageSelected()`

- `Void _OnEffectSelectShow()`

- `Void _TriggerEffectTutorial()`

- `Void _EffectShowImpl()`

- `Void _EffectHideImpl()`

- `Void _OnEffectSelectHide()`

- `Void _OnAddEffect(String)`

- `Void _OnRemoveEffect(String)`

- `Void _OnClearEffect()`

- `Void _OnAreaClick(String)`

- `Void _OnSelectStage(Int32)`

- `Void _OnClickMap(String)`

- `Void _OnClickEnemy(String)`

- `Void _OnClickBoss(String)`

- `Void _OnBattleStart()`

- `Void _OnClickBlank()`

- `Void _OnRewardClick()`

- `IEnumerator <>n__0(Boolean)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0MapPage : StateEnginePage, IValueMsgReceiver
{
	private Act42d0MapView _mapView; // 0xe8
	private RectTransform _topMenuContainer; // 0xf0
	private Act42D0EffectRayCastBlockerView _effectRayCastBlocker; // 0xf8
	private Act42D0EffectView _effectViewPrefab; // 0x100
	private Transform _effectContainer; // 0x108
	private Act42D0MapAreaView _mapAreaView; // 0x110
	private RectTransform _rectMapAreaView; // 0x118
	private RectTransform _rectMapPreview; // 0x120
	private ActivityStageMapPreviewView _mapPreview; // 0x128
	private UIAnimationLocation _entryAnim; // 0x130
	private GameObject _animPanel; // 0x140
	private UICommonPageEffectHolder[] _effectHolders; // 0x148
	public const String KEY_PARAM_BUNDLE; // 0x0
	private const String SQUAD_SAVE_KEY; // 0x0
	private Boolean m_hasInited; // 0x150
	private String m_actId; // 0x158
	private Act42D0EffectProperty m_effectProp; // 0x160
	private Act42d0AreaMapProperty m_mapProp; // 0x168
	private Act42D0MapAreaView m_mapAreaView; // 0x170
	private ActivityStageMapPreviewView m_stageMapPreviewView; // 0x178
	private Act42D0EffectView m_effectView; // 0x180
	private Tween m_entryTw; // 0x188
	public const Int32 MSG_ADD_EFFECT; // 0x0
	public const Int32 MSG_REMOVE_EFFECT; // 0x0
	public const Int32 MSG_CLEAR_EFFECT; // 0x0
	public const Int32 MSG_SHOW_EFFECT; // 0x0
	public const Int32 MSG_HIDE_EFFECT; // 0x0
	public const Int32 MSG_AREA_CLICK; // 0x0
	public const Int32 MSG_SELECT_STAGE; // 0x0
	public const Int32 MSG_CLICK_MAP; // 0x0
	public const Int32 MSG_CLICK_ENEMY; // 0x0
	public const Int32 MSG_CLICK_BOSS; // 0x0
	public const Int32 MSG_BATTLE_START; // 0x0
	public const Int32 MSG_REWARD_CLICK; // 0x0
	public const Int32 MSG_FIRST_STAGE_CLICK; // 0x0
	public const Int32 MSG_AREA_SELECTED; // 0x0
	public const Int32 MSG_EFFECT_VIEW_SHOWN; // 0x0
	private static DelegateBridge __Hotfix0_get_mapProp; // 0x0
	private static DelegateBridge __Hotfix0__CreateRecoverDataBundleForBattle; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x20
	private static DelegateBridge __Hotfix0__OnEnterAnimComplete; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__InitMap; // 0x38
	private static DelegateBridge __Hotfix0__CheckCachedEffectShow; // 0x40
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x48
	private static DelegateBridge __Hotfix0_NotifyAreaUnlock; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnNextAreaClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnPrevAreaClick; // 0x68
	private static DelegateBridge __Hotfix0_EventOnBossClick; // 0x70
	private static DelegateBridge __Hotfix0__JumpToDiffGroup; // 0x78
	private static DelegateBridge __Hotfix0_EventOnBlanckClick; // 0x80
	private static DelegateBridge __Hotfix0_EventOnRewardClick; // 0x88
	private static DelegateBridge __Hotfix0_EventOnLastProgressClick; // 0x90
	private static DelegateBridge __Hotfix0_OnMessage; // 0x98
	private static DelegateBridge __Hotfix0__OnEffectViewShown; // 0xa0
	private static DelegateBridge __Hotfix0__OnAreaSelected; // 0xa8
	private static DelegateBridge __Hotfix0__OnFirstStageSelected; // 0xb0
	private static DelegateBridge __Hotfix0__OnEffectSelectShow; // 0xb8
	private static DelegateBridge __Hotfix0__TriggerEffectTutorial; // 0xc0
	private static DelegateBridge __Hotfix0__EffectShowImpl; // 0xc8
	private static DelegateBridge __Hotfix0__EffectHideImpl; // 0xd0
	private static DelegateBridge __Hotfix0__OnEffectSelectHide; // 0xd8
	private static DelegateBridge __Hotfix0__OnAddEffect; // 0xe0
	private static DelegateBridge __Hotfix0__OnRemoveEffect; // 0xe8
	private static DelegateBridge __Hotfix0__OnClearEffect; // 0xf0
	private static DelegateBridge __Hotfix0__OnAreaClick; // 0xf8
	private static DelegateBridge __Hotfix0__OnSelectStage; // 0x100
	private static DelegateBridge __Hotfix0__OnClickMap; // 0x108
	private static DelegateBridge __Hotfix0__OnClickEnemy; // 0x110
	private static DelegateBridge __Hotfix0__OnClickBoss; // 0x118
	private static DelegateBridge __Hotfix0__OnBattleStart; // 0x120
	private static DelegateBridge __Hotfix0__OnClickBlank; // 0x128
	private static DelegateBridge __Hotfix0__OnRewardClick; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	public Act42d0AreaMapProperty mapProp { get; }

	// RVA: 0x31ff574 VA: 0x7595817574
	public Act42d0AreaMapProperty get_mapProp() { }
	// RVA: 0x31ff5dc VA: 0x75958175dc
	private DataBundle _CreateRecoverDataBundleForBattle() { }
	// RVA: 0x31ff8cc VA: 0x75958178cc
	protected override Void OnStart() { }
	// RVA: 0x31ffa90 VA: 0x7595817a90
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x31ffb4c VA: 0x7595817b4c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x31ffc3c VA: 0x7595817c3c
	private Void _OnEnterAnimComplete() { }
	// RVA: 0x31ff940 VA: 0x7595817940
	private Void _InitIfNot() { }
	// RVA: 0x31ffe0c VA: 0x7595817e0c
	private Void _InitMap() { }
	// RVA: 0x32001a8 VA: 0x75958181a8
	private Boolean _CheckCachedEffectShow(String actId, String areaId, Boolean areaCanUseBuff) { }
	// RVA: 0x3200468 VA: 0x7595818468
	private Void _OnBackClick() { }
	// RVA: 0x3200674 VA: 0x7595818674
	public Void NotifyAreaUnlock(String areaId) { }
	// RVA: 0x3200834 VA: 0x7595818834
	public Void EventOnBackClick() { }
	// RVA: 0x320089c VA: 0x759581889c
	public Void EventOnNextAreaClick() { }
	// RVA: 0x32009b0 VA: 0x75958189b0
	public Void EventOnPrevAreaClick() { }
	// RVA: 0x3200ac4 VA: 0x7595818ac4
	public Void EventOnBossClick() { }
	// RVA: 0x3200754 VA: 0x7595818754
	private Void _JumpToDiffGroup(Act42D0AreaDifficulty diff) { }
	// RVA: 0x3200d74 VA: 0x7595818d74
	public Void EventOnBlanckClick() { }
	// RVA: 0x3200eb0 VA: 0x7595818eb0
	public Void EventOnRewardClick() { }
	// RVA: 0x3200fd0 VA: 0x7595818fd0
	public Void EventOnLastProgressClick() { }
	// RVA: 0x32010ac VA: 0x75958190ac
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x32023e8 VA: 0x759581a3e8
	private Void _OnEffectViewShown() { }
	// RVA: 0x3202384 VA: 0x759581a384
	private Void _OnAreaSelected() { }
	// RVA: 0x3202320 VA: 0x759581a320
	private Void _OnFirstStageSelected() { }
	// RVA: 0x32016f8 VA: 0x75958196f8
	private Void _OnEffectSelectShow() { }
	// RVA: 0x3202510 VA: 0x759581a510
	private Void _TriggerEffectTutorial() { }
	// RVA: 0x32002c0 VA: 0x75958182c0
	private Void _EffectShowImpl() { }
	// RVA: 0x32005b8 VA: 0x75958185b8
	private Void _EffectHideImpl() { }
	// RVA: 0x3201850 VA: 0x7595819850
	private Void _OnEffectSelectHide() { }
	// RVA: 0x32012d8 VA: 0x75958192d8
	private Void _OnAddEffect(String effectId) { }
	// RVA: 0x32014bc VA: 0x75958194bc
	private Void _OnRemoveEffect(String effectId) { }
	// RVA: 0x320160c VA: 0x759581960c
	private Void _OnClearEffect() { }
	// RVA: 0x320191c VA: 0x759581991c
	private Void _OnAreaClick(String areaId) { }
	// RVA: 0x3201af8 VA: 0x7595819af8
	private Void _OnSelectStage(Int32 index) { }
	// RVA: 0x3201c44 VA: 0x7595819c44
	private Void _OnClickMap(String stageId) { }
	// RVA: 0x3201d5c VA: 0x7595819d5c
	private Void _OnClickEnemy(String levelId) { }
	// RVA: 0x3200b7c VA: 0x7595818b7c
	private Void _OnClickBoss(String bossId) { }
	// RVA: 0x3201e70 VA: 0x7595819e70
	private Void _OnBattleStart() { }
	// RVA: 0x3200ddc VA: 0x7595818ddc
	private Void _OnClickBlank() { }
	// RVA: 0x3200f18 VA: 0x7595818f18
	private Void _OnRewardClick() { }
	// RVA: 0x32027e0 VA: 0x759581a7e0
	public Void .ctor() { }
	// RVA: 0x3202904 VA: 0x759581a904
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x3202910 VA: 0x759581a910
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3202918 VA: 0x759581a918
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
}
```