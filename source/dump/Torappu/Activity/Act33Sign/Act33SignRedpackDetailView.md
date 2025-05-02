# Act33SignRedpackDetailView

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `Act33SignRedpackItemView _redpack`

- `AnimationWrapper _wrapper`

- `CanvasGroup _canvasGroup`

- `UIBlurFloatPanel _blurPanel`

- `Act33SignRedpackViewModel m_viewModel`

- `Act33SignRedpackItemViewModel m_currentPack`

- `Boolean m_consumed`

- `FadeSwitchTween m_switchTween`


## Methods

- `FadeSwitchTween _EnsureSwitchTween()`

- `Void _Render(Act33SignRedpackViewModel)`

- `Void _InitRedpackStack()`

- `Void _PlayEntryAnim()`

- `Void _PlayLoopAnim()`

- `Void _SendOpenRedpackWithTween()`

- `Void _ClearAnim()`

- `Void _RefreshPanel()`

- `Void OnRedpackCheckIn()`

- `Void _SendOpenRedpack()`

- `Boolean _JudgeViewClosed(UISwitchTween)`

- `Void CloseView()`

- `Void Show(Act33SignRedpackViewModel)`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignRedpackDetailView : MonoBehaviour, IHotfixable
{
	private Act33SignRedpackItemView _redpack; // 0x18
	private AnimationWrapper _wrapper; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private UIBlurFloatPanel _blurPanel; // 0x30
	private const String ANIM_LOOP; // 0x0
	private const String ANIM_ENTRY; // 0x0
	private const String ANIM_CHECKIN; // 0x0
	private const String EXTRA_REDPACK_CODE; // 0x0
	private const Single ALPHA_ONE; // 0x0
	private const Single ALPHA_ZERO; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private Act33SignRedpackViewModel m_viewModel; // 0x38
	private Act33SignRedpackItemViewModel m_currentPack; // 0x40
	private Queue`1 m_redpackQueue; // 0x48
	private Boolean m_consumed; // 0x50
	private FadeSwitchTween m_switchTween; // 0x58
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__InitRedpackStack; // 0x10
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x18
	private static DelegateBridge __Hotfix0__PlayLoopAnim; // 0x20
	private static DelegateBridge __Hotfix0__SendOpenRedpackWithTween; // 0x28
	private static DelegateBridge __Hotfix0__ClearAnim; // 0x30
	private static DelegateBridge __Hotfix0__RefreshPanel; // 0x38
	private static DelegateBridge __Hotfix0_OnRedpackCheckIn; // 0x40
	private static DelegateBridge __Hotfix0__SendOpenRedpack; // 0x48
	private static DelegateBridge __Hotfix0__JudgeViewClosed; // 0x50
	private static DelegateBridge __Hotfix0_CloseView; // 0x58
	private static DelegateBridge __Hotfix0_Show; // 0x60
	private static DelegateBridge __Hotfix0_Hide; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x3255310 VA: 0x759586d310
	private FadeSwitchTween _EnsureSwitchTween() { }
	// RVA: 0x3255448 VA: 0x759586d448
	private Void _Render(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3255624 VA: 0x759586d624
	private Void _InitRedpackStack() { }
	// RVA: 0x3255880 VA: 0x759586d880
	private Void _PlayEntryAnim() { }
	// RVA: 0x32559cc VA: 0x759586d9cc
	private Void _PlayLoopAnim() { }
	// RVA: 0x3255af0 VA: 0x759586daf0
	private Void _SendOpenRedpackWithTween() { }
	// RVA: 0x3255c20 VA: 0x759586dc20
	private Void _ClearAnim() { }
	// RVA: 0x3255790 VA: 0x759586d790
	private Void _RefreshPanel() { }
	// RVA: 0x3255f80 VA: 0x759586df80
	public Void OnRedpackCheckIn() { }
	// RVA: 0x3255ffc VA: 0x759586dffc
	private Void _SendOpenRedpack() { }
	// RVA: 0x3256118 VA: 0x759586e118
	private Boolean _JudgeViewClosed(UISwitchTween switchTw) { }
	// RVA: 0x3256230 VA: 0x759586e230
	public Void CloseView() { }
	// RVA: 0x3254f70 VA: 0x759586cf70
	public Void Show(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3254974 VA: 0x759586c974
	public Void Hide() { }
	// RVA: 0x32562dc VA: 0x759586e2dc
	public Void .ctor() { }
}
```