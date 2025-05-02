# Act42D0ChallengePage

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0ChallengeStageDetailView _stageDetailView`

- `RectTransform _stageDetailRect`

- `RectTransform _rectMapPreview`

- `ActivityStageMapPreviewView _mapPreview`

- `RectTransform _rectChallengeMapRect`

- `Act42d0ChallengeAreaGroupView _challengeViewPrefab`

- `Transform _topBarContainer`

- `Boolean m_hasInited`

- `String m_actId`

- `Act42D0ChallengeStageGroupProperty m_prop`

- `Act42D0ChallengeStageDetailView m_stageDetailView`

- `ActivityStageMapPreviewView m_stageMapPreviewView`

- `Act42d0ChallengeAreaGroupView m_stageMapView`


## Methods

- `DataBundle _CreateRecoverDataBundleForBattle()`

- `Void _TriggerTutorialAVG()`

- `Void _InitIfNot()`

- `Void _OnBackClick()`

- `Void EventOnBackClick()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnClickMap(String)`

- `Void _OnClickEnemy(String)`

- `Void _OnStartBattle()`

- `Void _OnStageClick(String)`

- `IEnumerator <>n__0(Boolean)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengePage : StateEnginePage, IValueMsgReceiver
{
	private Act42D0ChallengeStageDetailView _stageDetailView; // 0xe8
	private RectTransform _stageDetailRect; // 0xf0
	private RectTransform _rectMapPreview; // 0xf8
	private ActivityStageMapPreviewView _mapPreview; // 0x100
	private RectTransform _rectChallengeMapRect; // 0x108
	private Act42d0ChallengeAreaGroupView _challengeViewPrefab; // 0x110
	private Transform _topBarContainer; // 0x118
	public const String KEY_PARAM_BUNDLE; // 0x0
	private Boolean m_hasInited; // 0x120
	private String m_actId; // 0x128
	private Act42D0ChallengeStageGroupProperty m_prop; // 0x130
	private Act42D0ChallengeStageDetailView m_stageDetailView; // 0x138
	private ActivityStageMapPreviewView m_stageMapPreviewView; // 0x140
	private Act42d0ChallengeAreaGroupView m_stageMapView; // 0x148
	public const Int32 MSG_CLICK_MAP; // 0x0
	public const Int32 MSG_CLICK_ENEMY; // 0x0
	public const Int32 MSG_CLICK_START_BATTLE; // 0x0
	public const Int32 MSG_CLICK_STAGE; // 0x0
	private static DelegateBridge __Hotfix0__CreateRecoverDataBundleForBattle; // 0x0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x10
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnBackClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnClickMap; // 0x40
	private static DelegateBridge __Hotfix0__OnClickEnemy; // 0x48
	private static DelegateBridge __Hotfix0__OnStartBattle; // 0x50
	private static DelegateBridge __Hotfix0__OnStageClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x31e4178 VA: 0x75957fc178
	private DataBundle _CreateRecoverDataBundleForBattle() { }
	// RVA: 0x31e42c0 VA: 0x75957fc2c0
	protected override Void OnStart() { }
	// RVA: 0x31e45b8 VA: 0x75957fc5b8
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x31e461c VA: 0x75957fc61c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x31e4334 VA: 0x75957fc334
	private Void _InitIfNot() { }
	// RVA: 0x31e46e4 VA: 0x75957fc6e4
	private Void _OnBackClick() { }
	// RVA: 0x31e4750 VA: 0x75957fc750
	public Void EventOnBackClick() { }
	// RVA: 0x31e47b8 VA: 0x75957fc7b8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x31e48cc VA: 0x75957fc8cc
	private Void _OnClickMap(String stageId) { }
	// RVA: 0x31e49e4 VA: 0x75957fc9e4
	private Void _OnClickEnemy(String levelId) { }
	// RVA: 0x31e4af8 VA: 0x75957fcaf8
	private Void _OnStartBattle() { }
	// RVA: 0x31e4e9c VA: 0x75957fce9c
	private Void _OnStageClick(String stageId) { }
	// RVA: 0x31e4fc4 VA: 0x75957fcfc4
	public Void .ctor() { }
	// RVA: 0x31e50ac VA: 0x75957fd0ac
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x31e50b8 VA: 0x75957fd0b8
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x31e50c0 VA: 0x75957fd0c0
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
}
```