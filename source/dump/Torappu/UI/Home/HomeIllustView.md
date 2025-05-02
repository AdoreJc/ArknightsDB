# HomeIllustView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Camera _targetCamera`

- `Canvas _rootCanvas`

- `RectTransform _container`

- `RectTransform _illustRect`

- `RectTransform _illustMask`

- `Text _illustText`

- `UIAutoSlideRect _illustTextSlideRect`

- `Animator _illustTextAnim`

- `Single _dialogueMaxHeight`

- `Single _dialoguePaddingHeight`

- `CanvasGroup _canvasGroup`

- `LayoutElement _illustTextLayoutElement`

- `UICharacterIllust m_illust`

- `CharUISkinStruct m_skinData`

- `String m_illustId`

- `LoadStrategy m_loadStrategy`

- `CharQuery m_lastVoiceChar`

- `ICharWordData m_lastVoiceData`

- `PeriodicTimer m_idleTimer`

- `IllustHandler m_handler`

- `DisplayHandler m_DisplayHandler`

- `CharWordData m_homeIllustCharWord`

- `Single m_lastExistIllustTextTime`

- `Boolean m_dialogExistFlag`

- `UISwitchTween m_canvasFadeTween`

- `Boolean m_hideIllust`

- `TextGenerator m_textGenerator`


## Properties

- `Boolean isHomeIllustDialogExist`


## Methods

- `Boolean get_isHomeIllustDialogExist()`

- `Void set_isHomeIllustDialogExist(Boolean)`

- `Void SyncPreferredIllutLayout()`

- `Void PlayOpenVoice()`

- `Void PlayHomeVoice(CharWordData)`

- `Void PlayDynEntranceVoice(CharUISkinStruct)`

- `Void PlayDynEntranceStart(CharUISkinStruct)`

- `Boolean IsDynamicIllust()`

- `Void SetIllustHideState(Boolean)`

- `IllustHandler GetIllustHandler()`

- `DisplayHandler GetDisplayHandler()`

- `Void ExistIllustText()`

- `Void HideIllustText()`

- `Void _PlayHomeInteraction()`

- `Void _PlayHomeStart()`

- `Boolean _IsPlayingHomeInteraction()`

- `Boolean _IsPlayingHomeStart()`

- `PlayResult _LoadOpenCharWordAndPlayVoice(VoiceQuery, CharWordShowType, Boolean, out)`

- `PlayResult _LoadRandomCharWordAndPlayVoice(VoiceQuery, CharWordShowType, Boolean, out)`

- `Void OnEnable()`

- `Void Update()`

- `UIIllustLayoutInfo _GetCurIllustDefaultLayout()`

- `UIIllustLayoutInfo _GetCurIllustUsingLayout()`

- `Void _LoadTargetText(CharWordData)`

- `Void _LoadHomeShowIllustText()`

- `Void _UpdateTextRectLayout()`

- `Void _CheckIfReloadIllust(CharUISkinStruct, LoadStrategy, out, out)`

- `Void _LoadIllustLogic(CharUISkinStruct, LoadStrategy)`

- `Void _ActivateIllust()`

- `Void _ResetCanvas(Boolean)`

- `Void _FadeCanvas(Boolean)`

- `UISwitchTween _EnsureCanvasSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeIllustView : PageSingleComponent
{
	private const Single HOME_ILLUST_VOICE_CROSSFADE; // 0x0
	private const Single EXIST_ILLUST_TEXT_COOLDOWN; // 0x0
	private const String ILLUST_TEXT_EXIT_PARAM; // 0x0
	private Camera _targetCamera; // 0x20
	private Canvas _rootCanvas; // 0x28
	private RectTransform _container; // 0x30
	private RectTransform _illustRect; // 0x38
	private RectTransform _illustMask; // 0x40
	private Text _illustText; // 0x48
	private UIAutoSlideRect _illustTextSlideRect; // 0x50
	private Animator _illustTextAnim; // 0x58
	private Single _dialogueMaxHeight; // 0x60
	private Single _dialoguePaddingHeight; // 0x64
	private CanvasGroup _canvasGroup; // 0x68
	private LayoutElement _illustTextLayoutElement; // 0x70
	private UICharacterIllust m_illust; // 0x78
	private CharUISkinStruct m_skinData; // 0x80
	private String m_illustId; // 0x90
	private LoadStrategy m_loadStrategy; // 0x98
	private CharQuery m_lastVoiceChar; // 0xa0
	private ICharWordData m_lastVoiceData; // 0xb8
	private PeriodicTimer m_idleTimer; // 0xc0
	private IllustHandler m_handler; // 0xc8
	private DisplayHandler m_DisplayHandler; // 0xd0
	private CharWordData m_homeIllustCharWord; // 0xd8
	private Single m_lastExistIllustTextTime; // 0xe0
	private Boolean m_dialogExistFlag; // 0xe4
	private UISwitchTween m_canvasFadeTween; // 0xe8
	private Boolean m_hideIllust; // 0xf0
	private TextGenerator m_textGenerator; // 0xf8
	private const Single ILLUST_CANVAS_FADE_TIME; // 0x0
	private static DelegateBridge __Hotfix0_get_isHomeIllustDialogExist; // 0x0
	private static DelegateBridge __Hotfix0_set_isHomeIllustDialogExist; // 0x8
	private static DelegateBridge __Hotfix0_SyncPreferredIllutLayout; // 0x10
	private static DelegateBridge __Hotfix0_PlayOpenVoice; // 0x18
	private static DelegateBridge __Hotfix0_PlayHomeVoice; // 0x20
	private static DelegateBridge __Hotfix0_PlayDynEntranceVoice; // 0x28
	private static DelegateBridge __Hotfix0_PlayDynEntranceStart; // 0x30
	private static DelegateBridge __Hotfix0_IsDynamicIllust; // 0x38
	private static DelegateBridge __Hotfix0_SetIllustHideState; // 0x40
	private static DelegateBridge __Hotfix0_GetIllustHandler; // 0x48
	private static DelegateBridge __Hotfix0_GetDisplayHandler; // 0x50
	private static DelegateBridge __Hotfix0_ExistIllustText; // 0x58
	private static DelegateBridge __Hotfix0_HideIllustText; // 0x60
	private static DelegateBridge __Hotfix0__PlayHomeInteraction; // 0x68
	private static DelegateBridge __Hotfix0__PlayHomeStart; // 0x70
	private static DelegateBridge __Hotfix0__IsPlayingHomeInteraction; // 0x78
	private static DelegateBridge __Hotfix0__IsPlayingHomeStart; // 0x80
	private static DelegateBridge __Hotfix0__LoadOpenCharWordAndPlayVoice; // 0x88
	private static DelegateBridge __Hotfix0__LoadRandomCharWordAndPlayVoice; // 0x90
	private static DelegateBridge __Hotfix0_OnEnable; // 0x98
	private static DelegateBridge __Hotfix0_Update; // 0xa0
	private static DelegateBridge __Hotfix0__GetCurIllustDefaultLayout; // 0xa8
	private static DelegateBridge __Hotfix0__GetCurIllustUsingLayout; // 0xb0
	private static DelegateBridge __Hotfix0__LoadTargetText; // 0xb8
	private static DelegateBridge __Hotfix0__LoadHomeShowIllustText; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateTextRectLayout; // 0xc8
	private static DelegateBridge __Hotfix0__CheckIfReloadIllust; // 0xd0
	private static DelegateBridge __Hotfix0__LoadIllustLogic; // 0xd8
	private static DelegateBridge __Hotfix0__ActivateIllust; // 0xe0
	private static DelegateBridge __Hotfix0__ResetCanvas; // 0xe8
	private static DelegateBridge __Hotfix0__FadeCanvas; // 0xf0
	private static DelegateBridge __Hotfix0__EnsureCanvasSwitchTween; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	private Boolean isHomeIllustDialogExist { get; set; }

	// RVA: 0x2837f2c VA: 0x7594e4ff2c
	private Boolean get_isHomeIllustDialogExist() { }
	// RVA: 0x2837f94 VA: 0x7594e4ff94
	private Void set_isHomeIllustDialogExist(Boolean value) { }
	// RVA: 0x2838040 VA: 0x7594e50040
	public Void SyncPreferredIllutLayout() { }
	// RVA: 0x2838320 VA: 0x7594e50320
	public Void PlayOpenVoice() { }
	// RVA: 0x2838884 VA: 0x7594e50884
	public Void PlayHomeVoice(CharWordData data) { }
	// RVA: 0x283895c VA: 0x7594e5095c
	public Void PlayDynEntranceVoice(CharUISkinStruct charSkin) { }
	// RVA: 0x2838d9c VA: 0x7594e50d9c
	public Void PlayDynEntranceStart(CharUISkinStruct charSkin) { }
	// RVA: 0x2838b90 VA: 0x7594e50b90
	public Boolean IsDynamicIllust() { }
	// RVA: 0x2838e9c VA: 0x7594e50e9c
	public Void SetIllustHideState(Boolean hideFlag) { }
	// RVA: 0x2839048 VA: 0x7594e51048
	public IllustHandler GetIllustHandler() { }
	// RVA: 0x283913c VA: 0x7594e5113c
	public DisplayHandler GetDisplayHandler() { }
	// RVA: 0x2839320 VA: 0x7594e51320
	public Void ExistIllustText() { }
	// RVA: 0x2839820 VA: 0x7594e51820
	public Void HideIllustText() { }
	// RVA: 0x2839744 VA: 0x7594e51744
	private Void _PlayHomeInteraction() { }
	// RVA: 0x28386a4 VA: 0x7594e506a4
	private Void _PlayHomeStart() { }
	// RVA: 0x2839454 VA: 0x7594e51454
	private Boolean _IsPlayingHomeInteraction() { }
	// RVA: 0x2839534 VA: 0x7594e51534
	private Boolean _IsPlayingHomeStart() { }
	// RVA: 0x28385cc VA: 0x7594e505cc
	private PlayResult _LoadOpenCharWordAndPlayVoice(VoiceQuery query, CharWordShowType showType, Boolean overlapFlag, out CharWordData charWordData) { }
	// RVA: 0x2838c54 VA: 0x7594e50c54
	private PlayResult _LoadRandomCharWordAndPlayVoice(VoiceQuery query, CharWordShowType showType, Boolean overlapFlag, out CharWordData charWordData) { }
	// RVA: 0x283988c VA: 0x7594e5188c
	private Void OnEnable() { }
	// RVA: 0x2839c58 VA: 0x7594e51c58
	private Void Update() { }
	// RVA: 0x2839e70 VA: 0x7594e51e70
	private UIIllustLayoutInfo _GetCurIllustDefaultLayout() { }
	// RVA: 0x2838168 VA: 0x7594e50168
	private UIIllustLayoutInfo _GetCurIllustUsingLayout() { }
	// RVA: 0x2838780 VA: 0x7594e50780
	private Void _LoadTargetText(CharWordData charWord) { }
	// RVA: 0x2839614 VA: 0x7594e51614
	private Void _LoadHomeShowIllustText() { }
	// RVA: 0x28399d4 VA: 0x7594e519d4
	private Void _UpdateTextRectLayout() { }
	// RVA: 0x2839fbc VA: 0x7594e51fbc
	private Void _CheckIfReloadIllust(CharUISkinStruct skin, LoadStrategy loadStrategy, out Boolean shouldReload, out Boolean isSameSkinId) { }
	// RVA: 0x283a16c VA: 0x7594e5216c
	private Void _LoadIllustLogic(CharUISkinStruct skin, LoadStrategy loadStrategy) { }
	// RVA: 0x2838f20 VA: 0x7594e50f20
	private Void _ActivateIllust() { }
	// RVA: 0x2839944 VA: 0x7594e51944
	private Void _ResetCanvas(Boolean show) { }
	// RVA: 0x283a598 VA: 0x7594e52598
	private Void _FadeCanvas(Boolean show) { }
	// RVA: 0x283a4c0 VA: 0x7594e524c0
	private UISwitchTween _EnsureCanvasSwitchTween() { }
	// RVA: 0x283a628 VA: 0x7594e52628
	public Void .ctor() { }
}
```