# GameCityTopBarPanel

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `Text _scoretext`

- `GameCityScoreTitlePanel _scoreTitletextPanel`

- `AnimationWrapper _animationWrapper`

- `Image _scoreProgress`

- `Single _sliderSpeed`

- `CanvasGroup _timerCanvas`

- `Text _timerText`

- `Slider _timerSlider`

- `Single _waringTime`

- `AnimationWrapper _waringTimeWrapper`

- `Text _waveInfoCntText`

- `GameCityRestingPanel _restPanel`

- `CanvasGroup _restCanvas`

- `GameCityPauseButton _pauseButton`

- `GameCitySpeedSwitchButton _speedButton`

- `GameCityGameMode m_gamemode`

- `Rank m_curShownRank`

- `Single m_targetValue`

- `Single m_curValue`

- `Single m_curMaxValue`

- `Tween m_scoreTween`

- `Tween m_timerTween`

- `Boolean m_cachedInRest`

- `Int32 m_cachedValue`


## Properties

- `Boolean cachedRest`

- `Text scoretext`


## Methods

- `Void set_cachedRest(Boolean)`

- `Text get_scoretext()`

- `Void InitPanel(GameCityGameMode)`

- `Void OnGameReady()`

- `Void UpdateDisableMask(BattleFunctionDisableMask)`

- `Void UpdateTime(Single)`

- `Void SetScore(Int32)`

- `Void UpgradeRank(Rank, Single)`

- `Void OnWaveStart()`

- `Void OnUIStateChanged(IUIStateNode)`

- `Void _OnSpeedLevelChanged(IUIStateNode)`

- `Void Update()`

- `Void _StartLevelUp()`

- `Void _OnCompleteScoreAnim()`

- `Void _OnBackPressPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityTopBarPanel : MonoBehaviour, IHotfixable
{
	private const Single TIME_FADE; // 0x0
	private const String TIMER_FORMAT; // 0x0
	private const Char SHOW_SCORE_PADDING; // 0x0
	private const Int32 SHOW_SCORE_DIGIT_CNT; // 0x0
	private const String WARING_ANIMATION_KEY; // 0x0
	private Text _scoretext; // 0x18
	private GameCityScoreTitlePanel _scoreTitletextPanel; // 0x20
	private AnimationWrapper _animationWrapper; // 0x28
	private List`1 _animationKeys; // 0x30
	private Image _scoreProgress; // 0x38
	private Single _sliderSpeed; // 0x40
	private CanvasGroup _timerCanvas; // 0x48
	private Text _timerText; // 0x50
	private Slider _timerSlider; // 0x58
	private Single _waringTime; // 0x60
	private AnimationWrapper _waringTimeWrapper; // 0x68
	private Text _waveInfoCntText; // 0x70
	private GameCityRestingPanel _restPanel; // 0x78
	private CanvasGroup _restCanvas; // 0x80
	private GameCityPauseButton _pauseButton; // 0x88
	private GameCitySpeedSwitchButton _speedButton; // 0x90
	private GameCityGameMode m_gamemode; // 0x98
	private Rank m_curShownRank; // 0xa0
	private Single m_targetValue; // 0xa4
	private Single m_curValue; // 0xa8
	private Single m_curMaxValue; // 0xac
	private Tween m_scoreTween; // 0xb0
	private Tween m_timerTween; // 0xb8
	private Boolean m_cachedInRest; // 0xc0
	private Int32 m_cachedValue; // 0xc4
	private List`1 m_upgradeData; // 0xc8
	private static DelegateBridge __Hotfix0_set_cachedRest; // 0x0
	private static DelegateBridge __Hotfix0_get_scoretext; // 0x8
	private static DelegateBridge __Hotfix0_InitPanel; // 0x10
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x18
	private static DelegateBridge __Hotfix0_UpdateDisableMask; // 0x20
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x28
	private static DelegateBridge __Hotfix0_SetScore; // 0x30
	private static DelegateBridge __Hotfix0_UpgradeRank; // 0x38
	private static DelegateBridge __Hotfix0_OnWaveStart; // 0x40
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x48
	private static DelegateBridge __Hotfix0__OnSpeedLevelChanged; // 0x50
	private static DelegateBridge __Hotfix0_Update; // 0x58
	private static DelegateBridge __Hotfix0__StartLevelUp; // 0x60
	private static DelegateBridge __Hotfix0__OnCompleteScoreAnim; // 0x68
	private static DelegateBridge __Hotfix0__OnBackPressPause; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Boolean cachedRest { set; }
	public Text scoretext { get; }

	// RVA: 0x33eb39c VA: 0x7595a0339c
	private Void set_cachedRest(Boolean value) { }
	// RVA: 0x33e6be4 VA: 0x75959febe4
	public Text get_scoretext() { }
	// RVA: 0x33e52c8 VA: 0x75959fd2c8
	public Void InitPanel(GameCityGameMode gamemode) { }
	// RVA: 0x33e4f00 VA: 0x75959fcf00
	public Void OnGameReady() { }
	// RVA: 0x33e6294 VA: 0x75959fe294
	public Void UpdateDisableMask(BattleFunctionDisableMask mask) { }
	// RVA: 0x33e5698 VA: 0x75959fd698
	public Void UpdateTime(Single progress) { }
	// RVA: 0x33e6dbc VA: 0x75959fedbc
	public Void SetScore(Int32 value) { }
	// RVA: 0x33e6fc4 VA: 0x75959fefc4
	public Void UpgradeRank(Rank rank, Single score) { }
	// RVA: 0x33e718c VA: 0x75959ff18c
	public Void OnWaveStart() { }
	// RVA: 0x33e6888 VA: 0x75959fe888
	public Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x33eb600 VA: 0x7595a03600
	private Void _OnSpeedLevelChanged(IUIStateNode stateNode) { }
	// RVA: 0x33eb7e8 VA: 0x7595a037e8
	private Void Update() { }
	// RVA: 0x33eb9b4 VA: 0x7595a039b4
	private Void _StartLevelUp() { }
	// RVA: 0x33ebc58 VA: 0x7595a03c58
	private Void _OnCompleteScoreAnim() { }
	// RVA: 0x33ebd70 VA: 0x7595a03d70
	private Void _OnBackPressPause() { }
	// RVA: 0x33ebed4 VA: 0x7595a03ed4
	public Void .ctor() { }
}
```