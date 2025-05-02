# UIBattleDouququBetPanel

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `GameObject _baseElement`

- `Image _black`

- `GameObject _textMain`

- `Button _buttonBack`

- `GameObject _imgInteractable`

- `GameObject _imgNotInteractable`

- `GameObject _blocker`

- `Text _mainText`

- `GameObject _pageMan`

- `AVGTypeWriterText _contentTypeWriter`

- `RectTransform _pageVs`

- `Button _buttonDetails`

- `SimpleLayoutContent _leftEnemyList`

- `SimpleLayoutContent _rightEnemyList`

- `SimpleLayoutContent _leftNpcList`

- `SimpleLayoutContent _rightNpcList`

- `GameObject _pageTxt`

- `GameObject _txtBtn`

- `Text _leftTeamDetails`

- `Text _rightTeamDetails`

- `Text _leftChoiceText`

- `Text _rightChoiceText`

- `RectTransform _pageBet`

- `GameObject _choiceAll`

- `Text _balance`

- `Text _odds`

- `GameObject _streak`

- `Text _choiceText1`

- `Text _choiceText2`

- `Text _choiceText3`

- `Text _choiceText4`

- `RectTransform _pageInfo`

- `GameObject _chooseLeft`

- `GameObject _chooseRight`

- `Text _oddsInfo`

- `GameObject _streakInfo`

- `Text _investment`

- `GameObject _choose10`

- `GameObject _choose25`

- `GameObject _choose50`

- `GameObject _choose100`

- `GameObject _iconNormal`

- `GameObject _iconAll`

- `Text _bonus`

- `GameObject _chooseIconNotSelected`

- `GameObject _chooseIconProcessing`

- `GameObject _chooseIconDone`

- `GameObject _moneyIconNotSelected`

- `GameObject _moneyIconProcessing`

- `GameObject _moneyIconDone`

- `Text _chooseText`

- `Text _betText`

- `Color _notYetColor`

- `Color _ingColor`

- `Color _doneColor`

- `UIAnimationLocation _mainWrapper`

- `AnimationWrapper _downWrapper`

- `UIAnimationLocation _detailsWrapper`

- `UIAnimationLocation _txtWrapper`

- `AnimationWrapper _btnWrapper`

- `AnimationWrapper _btnWrapper2`

- `BetPage m_curPage`

- `DouququGameMode m_gameMode`

- `DouququUIPlugin m_plugin`

- `Boolean m_hasInitialized`

- `DouququNpcItemListAdapter m_leftNpcAdapter`

- `DouququNpcItemListAdapter m_rightNpcAdapter`

- `DouququEnemyItemListAdapter m_leftEnemyAdapter`

- `DouququEnemyItemListAdapter m_rightEnemyAdapter`


## Methods

- `Void Init(DouququUIPlugin, DouququGameMode)`

- `Void Show()`

- `Void _InitIfNotBeforeShow()`

- `IEnumerator _WaitForShow()`

- `Void _OnBetEnd()`

- `Void _ResetAnimationState()`

- `Void _OnManPageOn()`

- `Void _OnVsPageOn()`

- `Void _OnBetPageOn()`

- `Void _OnInfoPageOn()`

- `Void _UpdateUIVisibility()`

- `Void _UpdateBackBtnState(Boolean)`

- `Void _UpdateBackBtnIcon()`

- `Void OnBackBtnClick()`

- `Void OnTeamDetailsClick()`

- `Void OnCloseTeamDetails()`

- `Void OnChooseClick(Boolean)`

- `Void OnBetClick(Int32)`

- `Void OnBattleStartClick()`

- `Void <_WaitForShow>b__87_0()`

- `Void <_OnBetEnd>b__88_0()`

- `Void <_OnVsPageOn>b__91_0()`

- `Void <_OnVsPageOn>b__91_1()`

- `Void <_OnBetPageOn>b__92_0()`

- `Void <_OnBetPageOn>b__92_1()`

- `Void <_OnInfoPageOn>b__93_0()`

- `Void <OnCloseTeamDetails>b__99_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class UIBattleDouququBetPanel : MonoBehaviour, IHotfixable
{
	private GameObject _baseElement; // 0x18
	private Image _black; // 0x20
	private GameObject _textMain; // 0x28
	private Button _buttonBack; // 0x30
	private GameObject _imgInteractable; // 0x38
	private GameObject _imgNotInteractable; // 0x40
	private GameObject _blocker; // 0x48
	private Text _mainText; // 0x50
	private GameObject _pageMan; // 0x58
	private AVGTypeWriterText _contentTypeWriter; // 0x60
	private RectTransform _pageVs; // 0x68
	private Button _buttonDetails; // 0x70
	private SimpleLayoutContent _leftEnemyList; // 0x78
	private SimpleLayoutContent _rightEnemyList; // 0x80
	private SimpleLayoutContent _leftNpcList; // 0x88
	private SimpleLayoutContent _rightNpcList; // 0x90
	private GameObject _pageTxt; // 0x98
	private GameObject _txtBtn; // 0xa0
	private Text _leftTeamDetails; // 0xa8
	private Text _rightTeamDetails; // 0xb0
	private Text _leftChoiceText; // 0xb8
	private Text _rightChoiceText; // 0xc0
	private RectTransform _pageBet; // 0xc8
	private GameObject _choiceAll; // 0xd0
	private Text _balance; // 0xd8
	private Text _odds; // 0xe0
	private GameObject _streak; // 0xe8
	private Text _choiceText1; // 0xf0
	private Text _choiceText2; // 0xf8
	private Text _choiceText3; // 0x100
	private Text _choiceText4; // 0x108
	private RectTransform _pageInfo; // 0x110
	private GameObject _chooseLeft; // 0x118
	private GameObject _chooseRight; // 0x120
	private Text _oddsInfo; // 0x128
	private GameObject _streakInfo; // 0x130
	private Text _investment; // 0x138
	private GameObject _choose10; // 0x140
	private GameObject _choose25; // 0x148
	private GameObject _choose50; // 0x150
	private GameObject _choose100; // 0x158
	private GameObject _iconNormal; // 0x160
	private GameObject _iconAll; // 0x168
	private Text _bonus; // 0x170
	private GameObject _chooseIconNotSelected; // 0x178
	private GameObject _chooseIconProcessing; // 0x180
	private GameObject _chooseIconDone; // 0x188
	private GameObject _moneyIconNotSelected; // 0x190
	private GameObject _moneyIconProcessing; // 0x198
	private GameObject _moneyIconDone; // 0x1a0
	private Text _chooseText; // 0x1a8
	private Text _betText; // 0x1b0
	private Color _notYetColor; // 0x1b8
	private Color _ingColor; // 0x1c8
	private Color _doneColor; // 0x1d8
	private UIAnimationLocation _mainWrapper; // 0x1e8
	private AnimationWrapper _downWrapper; // 0x1f8
	private UIAnimationLocation _detailsWrapper; // 0x200
	private UIAnimationLocation _txtWrapper; // 0x210
	private AnimationWrapper _btnWrapper; // 0x220
	private AnimationWrapper _btnWrapper2; // 0x228
	private BetPage m_curPage; // 0x230
	private DouququGameMode m_gameMode; // 0x238
	private DouququUIPlugin m_plugin; // 0x240
	private readonly List`1 m_posList; // 0x248
	private Boolean m_hasInitialized; // 0x250
	private DouququNpcItemListAdapter m_leftNpcAdapter; // 0x258
	private DouququNpcItemListAdapter m_rightNpcAdapter; // 0x260
	private DouququEnemyItemListAdapter m_leftEnemyAdapter; // 0x268
	private DouququEnemyItemListAdapter m_rightEnemyAdapter; // 0x270
	private const String DOUQUQU_UI_ANIMATION_ENTRY; // 0x0
	private const String DOUQUQU_BET_DOWN_ENTRY; // 0x0
	private const String DOUQUQU_BET_DOWN_PAGE_SWITCH_BAT_TO_VS; // 0x0
	private const String DOUQUQU_BET_DOWN_PAGE_SWITCH_BET_TO_INFO; // 0x0
	private const String DOUQUQU_BET_DOWN_PAGE_SWITCH_INFO_TO_BET; // 0x0
	private const String DOUQUQU_BET_DOWN_PAGE_SWITCH_VS_TO_BET; // 0x0
	private const String DOUQUQU_BATTLE_BTN_DETAILS_ENTRY; // 0x0
	private const String DOUQUQU_BATTLE_PAGE_TXT_ENTRY; // 0x0
	private const String DOUQUQU_TEXT_CHOICE_ROTATION_LOOP; // 0x0
	private const Int32 ENEMY_ITEM_COUNT; // 0x0
	private const Int32 MAX_CHOICE_CNT; // 0x0
	private const Single MAIN_PAGE_WAIT_TIME; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNotBeforeShow; // 0x10
	private static DelegateBridge __Hotfix0__WaitForShow; // 0x18
	private static DelegateBridge __Hotfix0__OnBetEnd; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimationState; // 0x28
	private static DelegateBridge __Hotfix0__OnManPageOn; // 0x30
	private static DelegateBridge __Hotfix0__OnVsPageOn; // 0x38
	private static DelegateBridge __Hotfix0__OnBetPageOn; // 0x40
	private static DelegateBridge __Hotfix0__OnInfoPageOn; // 0x48
	private static DelegateBridge __Hotfix0__UpdateUIVisibility; // 0x50
	private static DelegateBridge __Hotfix0__UpdateBackBtnState; // 0x58
	private static DelegateBridge __Hotfix0__UpdateBackBtnIcon; // 0x60
	private static DelegateBridge __Hotfix0_OnBackBtnClick; // 0x68
	private static DelegateBridge __Hotfix0_OnTeamDetailsClick; // 0x70
	private static DelegateBridge __Hotfix0_OnCloseTeamDetails; // 0x78
	private static DelegateBridge __Hotfix0_OnChooseClick; // 0x80
	private static DelegateBridge __Hotfix0_OnBetClick; // 0x88
	private static DelegateBridge __Hotfix0_OnBattleStartClick; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x1dd0260 VA: 0x75943e8260
	public Void Init(DouququUIPlugin plugin, DouququGameMode gameMode) { }
	// RVA: 0x1dd0360 VA: 0x75943e8360
	public Void Show() { }
	// RVA: 0x1dd0478 VA: 0x75943e8478
	private Void _InitIfNotBeforeShow() { }
	// RVA: 0x1dd0a04 VA: 0x75943e8a04
	private IEnumerator _WaitForShow() { }
	// RVA: 0x1dd0bb8 VA: 0x75943e8bb8
	private Void _OnBetEnd() { }
	// RVA: 0x1dd0e34 VA: 0x75943e8e34
	private Void _ResetAnimationState() { }
	// RVA: 0x1dd0988 VA: 0x75943e8988
	private Void _OnManPageOn() { }
	// RVA: 0x1dd103c VA: 0x75943e903c
	private Void _OnVsPageOn() { }
	// RVA: 0x1dd1358 VA: 0x75943e9358
	private Void _OnBetPageOn() { }
	// RVA: 0x1dd1800 VA: 0x75943e9800
	private Void _OnInfoPageOn() { }
	// RVA: 0x1dd0f74 VA: 0x75943e8f74
	private Void _UpdateUIVisibility() { }
	// RVA: 0x1dd1c18 VA: 0x75943e9c18
	private Void _UpdateBackBtnState(Boolean isInteractable) { }
	// RVA: 0x1dd1cd4 VA: 0x75943e9cd4
	private Void _UpdateBackBtnIcon() { }
	// RVA: 0x1dd203c VA: 0x75943ea03c
	public Void OnBackBtnClick() { }
	// RVA: 0x1dd20d4 VA: 0x75943ea0d4
	public Void OnTeamDetailsClick() { }
	// RVA: 0x1dd227c VA: 0x75943ea27c
	public Void OnCloseTeamDetails() { }
	// RVA: 0x1dd2468 VA: 0x75943ea468
	public Void OnChooseClick(Boolean isLeft) { }
	// RVA: 0x1dd2504 VA: 0x75943ea504
	public Void OnBetClick(Int32 selection) { }
	// RVA: 0x1dd25a0 VA: 0x75943ea5a0
	public Void OnBattleStartClick() { }
	// RVA: 0x1dd2608 VA: 0x75943ea608
	public Void .ctor() { }
	// RVA: 0x1dd26cc VA: 0x75943ea6cc
	private Void <_WaitForShow>b__87_0() { }
	// RVA: 0x1dd2730 VA: 0x75943ea730
	private Void <_OnBetEnd>b__88_0() { }
	// RVA: 0x1dd276c VA: 0x75943ea76c
	private Void <_OnVsPageOn>b__91_0() { }
	// RVA: 0x1dd277c VA: 0x75943ea77c
	private Void <_OnVsPageOn>b__91_1() { }
	// RVA: 0x1dd279c VA: 0x75943ea79c
	private Void <_OnBetPageOn>b__92_0() { }
	// RVA: 0x1dd27ac VA: 0x75943ea7ac
	private Void <_OnBetPageOn>b__92_1() { }
	// RVA: 0x1dd27d4 VA: 0x75943ea7d4
	private Void <_OnInfoPageOn>b__93_0() { }
	// RVA: 0x1dd27e4 VA: 0x75943ea7e4
	private Void <OnCloseTeamDetails>b__99_0() { }
}
```