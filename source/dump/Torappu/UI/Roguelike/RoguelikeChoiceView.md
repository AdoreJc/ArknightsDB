# RoguelikeChoiceView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Single _backgroundFadeSpeed`

- `Text _dialogTitle`

- `AVGTypeWriterText _dialogContentTypewriter`

- `SimpleLayoutContent _choiceLayoutContent`

- `RectTransform _dialogContentTargetRect`

- `GameObject _leavingPanel`

- `ScrollRect _choiceScroll`

- `CanvasGroup _mainViewCanvasGroup`

- `Single _introTweenDuration`

- `Single _introTweenContentPosX0`

- `Single _introTweenContentPosX1`

- `Single _introTweenChoicePosX0`

- `Single _introTweenChoicePosX1`

- `Boolean _introClickBlock`

- `Boolean _introClickBlockUseMaxDuration`

- `Single _introClickBlockMaxTimeDurationValue`

- `CanvasGroup _choiceCanvasGroup`

- `UIAtlasImage _imgTitleIcon`

- `UIAtlasObject _atlas`

- `RoguelikeChoiceEffectBase _effectPrefab`

- `RoguelikeChoicePlugin _choicePlugin`

- `IntroStep m_introStep`

- `Boolean m_introClick`

- `Coroutine m_coroutine`

- `Boolean m_hasInited`

- `ChoiceAdapter m_adapter`

- `Boolean m_isSwitching`

- `Int32 m_totalAnimCount`

- `Int32 m_completeAnimCount`

- `RoguelikeChoiceScene m_choiceScene`

- `String m_topicId`

- `UIPage m_page`


## Properties

- `RoguelikeChoicePlugin choicePlugin`

- `RoguelikeChoiceEffectBase effectPrefab`


## Methods

- `Void set_onChoiceSelect(Action`1)`

- `Void set_onShowMenu(Action`1)`

- `RoguelikeChoicePlugin get_choicePlugin()`

- `RoguelikeChoiceEffectBase get_effectPrefab()`

- `Single _Cubic01(Single)`

- `Void Render(RoguelikeChoiceScene, Boolean)`

- `Void HideMainView()`

- `Boolean IsSceneEmpty()`

- `Void _InitIfNot()`

- `Void _ChoiceActiveControl(Func`2)`

- `Void Init(RoguelikeDungeonPage)`

- `Void _IncrementAnimCount()`

- `Void _UnactiveAllChoice()`

- `Boolean _IsOnlyLeaveOption()`

- `Void _RefreshView(Boolean)`

- `IEnumerator _IntroCoroutine(Boolean)`

- `Void _ChoiceActived(IRoguelikeGameChoice)`

- `Void _ChoiceSelected(IRoguelikeGameChoice)`

- `Void OnLeaveButtonPressed()`

- `Void OnBackgroundPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceView : MonoBehaviour, IHotfixable
{
	private Single _backgroundFadeSpeed; // 0x18
	private Text _dialogTitle; // 0x20
	private AVGTypeWriterText _dialogContentTypewriter; // 0x28
	private SimpleLayoutContent _choiceLayoutContent; // 0x30
	private RectTransform _dialogContentTargetRect; // 0x38
	private GameObject _leavingPanel; // 0x40
	private ScrollRect _choiceScroll; // 0x48
	private CanvasGroup _mainViewCanvasGroup; // 0x50
	private Single _introTweenDuration; // 0x58
	private Single _introTweenContentPosX0; // 0x5c
	private Single _introTweenContentPosX1; // 0x60
	private Single _introTweenChoicePosX0; // 0x64
	private Single _introTweenChoicePosX1; // 0x68
	private Boolean _introClickBlock; // 0x6c
	private Boolean _introClickBlockUseMaxDuration; // 0x6d
	private Single _introClickBlockMaxTimeDurationValue; // 0x70
	private CanvasGroup _choiceCanvasGroup; // 0x78
	private UIAtlasImage _imgTitleIcon; // 0x80
	private UIAtlasObject _atlas; // 0x88
	private RoguelikeChoiceEffectBase _effectPrefab; // 0x90
	private RoguelikeChoicePlugin _choicePlugin; // 0x98
	private const String DEFAULT_TITLE_ICON; // 0x0
	private IntroStep m_introStep; // 0xa0
	private Boolean m_introClick; // 0xa4
	private Coroutine m_coroutine; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private ChoiceAdapter m_adapter; // 0xb8
	private Boolean m_isSwitching; // 0xc0
	private Int32 m_totalAnimCount; // 0xc4
	private Int32 m_completeAnimCount; // 0xc8
	private List`1 m_animItemList; // 0xd0
	private RoguelikeChoiceScene m_choiceScene; // 0xd8
	private String m_topicId; // 0xe0
	private UIPage m_page; // 0xe8
	private Action`1 <onChoiceSelect>k__BackingField; // 0xf0
	private Action`1 <onShowMenu>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_onChoiceSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onChoiceSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onShowMenu; // 0x10
	private static DelegateBridge __Hotfix0_set_onShowMenu; // 0x18
	private static DelegateBridge __Hotfix0_get_choicePlugin; // 0x20
	private static DelegateBridge __Hotfix0_get_effectPrefab; // 0x28
	private static DelegateBridge __Hotfix0__Cubic01; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0_HideMainView; // 0x40
	private static DelegateBridge __Hotfix0_IsSceneEmpty; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__ChoiceActiveControl; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x60
	private static DelegateBridge __Hotfix0__IncrementAnimCount; // 0x68
	private static DelegateBridge __Hotfix0__UnactiveAllChoice; // 0x70
	private static DelegateBridge __Hotfix0__IsOnlyLeaveOption; // 0x78
	private static DelegateBridge __Hotfix0__RefreshView; // 0x80
	private static DelegateBridge __Hotfix0__IntroCoroutine; // 0x88
	private static DelegateBridge __Hotfix0__ChoiceActived; // 0x90
	private static DelegateBridge __Hotfix0__ChoiceSelected; // 0x98
	private static DelegateBridge __Hotfix0_OnLeaveButtonPressed; // 0xa0
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	private Action`1 onChoiceSelect { get; set; }
	private Action`1 onShowMenu { get; set; }
	public RoguelikeChoicePlugin choicePlugin { get; }
	public RoguelikeChoiceEffectBase effectPrefab { get; }

	// RVA: 0x29f2a34 VA: 0x759500aa34
	private Action`1 get_onChoiceSelect() { }
	// RVA: 0x29f2a9c VA: 0x759500aa9c
	public Void set_onChoiceSelect(Action`1 value) { }
	// RVA: 0x29f2b20 VA: 0x759500ab20
	private Action`1 get_onShowMenu() { }
	// RVA: 0x29f2b88 VA: 0x759500ab88
	public Void set_onShowMenu(Action`1 value) { }
	// RVA: 0x29f2c0c VA: 0x759500ac0c
	public RoguelikeChoicePlugin get_choicePlugin() { }
	// RVA: 0x29f2c74 VA: 0x759500ac74
	public RoguelikeChoiceEffectBase get_effectPrefab() { }
	// RVA: 0x29f2cdc VA: 0x759500acdc
	private Single _Cubic01(Single val) { }
	// RVA: 0x29f2d74 VA: 0x759500ad74
	public Void Render(RoguelikeChoiceScene choiceScene, Boolean fade) { }
	// RVA: 0x29f34c4 VA: 0x759500b4c4
	public Void HideMainView() { }
	// RVA: 0x29f3540 VA: 0x759500b540
	public Boolean IsSceneEmpty() { }
	// RVA: 0x29f2e5c VA: 0x759500ae5c
	private Void _InitIfNot() { }
	// RVA: 0x29f3644 VA: 0x759500b644
	private Void _ChoiceActiveControl(Func`2 pred) { }
	// RVA: 0x29f3988 VA: 0x759500b988
	public Void Init(RoguelikeDungeonPage page) { }
	// RVA: 0x29f3a0c VA: 0x759500ba0c
	private Void _IncrementAnimCount() { }
	// RVA: 0x29f3a88 VA: 0x759500ba88
	private Void _UnactiveAllChoice() { }
	// RVA: 0x29f3af4 VA: 0x759500baf4
	private Boolean _IsOnlyLeaveOption() { }
	// RVA: 0x29f2f2c VA: 0x759500af2c
	private Void _RefreshView(Boolean fade) { }
	// RVA: 0x29f3c24 VA: 0x759500bc24
	private IEnumerator _IntroCoroutine(Boolean onlyLeaveChoice) { }
	// RVA: 0x29f3d14 VA: 0x759500bd14
	private Void _ChoiceActived(IRoguelikeGameChoice choice) { }
	// RVA: 0x29f3e3c VA: 0x759500be3c
	private Void _ChoiceSelected(IRoguelikeGameChoice choice) { }
	// RVA: 0x29f3fd0 VA: 0x759500bfd0
	public Void OnLeaveButtonPressed() { }
	// RVA: 0x29f4168 VA: 0x759500c168
	public Void OnBackgroundPressed() { }
	// RVA: 0x29f4254 VA: 0x759500c254
	public Void .ctor() { }
}
```