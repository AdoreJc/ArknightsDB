# RL03TotemBuffBottomDescView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Text _txtDesc`

- `CanvasGroup _canvasGroupFocus`

- `FadeSwitchTween m_focusTween`

- `Tween m_timerTween`

- `Boolean m_isFocusInited`

- `String m_cachedDesc`


## Methods

- `Void Render(String)`

- `Void OnDestroy()`

- `Void _InitFocusStatusIfNot()`

- `Void _TweenFocusState()`

- `Void _TweenUnfocusState()`

- `Void _ClearTimerTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffBottomDescView : MonoBehaviour, IHotfixable
{
	private const Single FOCUS_STAY_DUR; // 0x0
	private const Single FOCUS_FADE_IN_DUR; // 0x0
	private const Single FOCUS_FADE_OUT_DUR; // 0x0
	private Text _txtDesc; // 0x18
	private CanvasGroup _canvasGroupFocus; // 0x20
	private FadeSwitchTween m_focusTween; // 0x28
	private Tween m_timerTween; // 0x30
	private Boolean m_isFocusInited; // 0x38
	private String m_cachedDesc; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__InitFocusStatusIfNot; // 0x10
	private static DelegateBridge __Hotfix0__TweenFocusState; // 0x18
	private static DelegateBridge __Hotfix0__TweenUnfocusState; // 0x20
	private static DelegateBridge __Hotfix0__ClearTimerTween; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2ba615c VA: 0x75951be15c
	public Void Render(String desc) { }
	// RVA: 0x2ba65f4 VA: 0x75951be5f4
	protected Void OnDestroy() { }
	// RVA: 0x2ba625c VA: 0x75951be25c
	private Void _InitFocusStatusIfNot() { }
	// RVA: 0x2ba6340 VA: 0x75951be340
	private Void _TweenFocusState() { }
	// RVA: 0x2ba6720 VA: 0x75951be720
	private Void _TweenUnfocusState() { }
	// RVA: 0x2ba6680 VA: 0x75951be680
	private Void _ClearTimerTween() { }
	// RVA: 0x2ba67c8 VA: 0x75951be7c8
	public Void .ctor() { }
}
```