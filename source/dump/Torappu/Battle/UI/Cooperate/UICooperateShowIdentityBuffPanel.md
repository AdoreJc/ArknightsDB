# UICooperateShowIdentityBuffPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Text _selfIdentityTitle`

- `Text _oppositeIdentityTitle`

- `Image _selfIdentityIcon`

- `Image _oppositeIdentityIcon`

- `UIAtlasImage _selfIdentityChangeColor`

- `UIAtlasImage _oppositeIdentityChangeColor`

- `UIAtlasImage _gameModeColor`

- `UIAnimationLocation _normalAnim`

- `UIAnimationLocation _inverseAnim`

- `Action m_callback`

- `Sequence m_sequence`

- `FP m_curTime`

- `IdentityRenderData m_selfRD`

- `IdentityRenderData m_oppositeRD`

- `Boolean m_isInversed`


## Methods

- `Void RenderPanel(IdentityRenderData, IdentityRenderData, Boolean, String)`

- `Void PlayAnim(Action)`

- `Void RunAnim(FP)`

- `Void _PlayAnimation(UIAnimationLocation)`

- `Void _SetGameModeRenderData(String)`

- `Void _RenderSelfIdentity(String)`

- `Void _RenderOppositeIdentity(String)`

- `Void _RenderConstIdentity(String, Sprite, String, Sprite)`

- `Void _OnSetInverseText()`

- `Void _OnTimerStopped()`

- `Void <_PlayAnimation>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateShowIdentityBuffPanel : MonoBehaviour, IHotfixable
{
	private Text _selfIdentityTitle; // 0x18
	private Text _oppositeIdentityTitle; // 0x20
	private Image _selfIdentityIcon; // 0x28
	private Image _oppositeIdentityIcon; // 0x30
	private UIAtlasImage _selfIdentityChangeColor; // 0x38
	private UIAtlasImage _oppositeIdentityChangeColor; // 0x40
	private UIAtlasImage _gameModeColor; // 0x48
	private UIAnimationLocation _normalAnim; // 0x50
	private UIAnimationLocation _inverseAnim; // 0x60
	private const Single INVERSE_TIMER_PERIOD; // 0x0
	private const Single STOP_TIMER_PERIOD; // 0x0
	private Action m_callback; // 0x70
	private Sequence m_sequence; // 0x78
	private FP m_curTime; // 0x80
	private IdentityRenderData m_selfRD; // 0x88
	private IdentityRenderData m_oppositeRD; // 0x90
	private Boolean m_isInversed; // 0x98
	private List`1 m_inverseCallbackData; // 0xa0
	private static DelegateBridge __Hotfix0_RenderPanel; // 0x0
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0_RunAnim; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x18
	private static DelegateBridge __Hotfix0__SetGameModeRenderData; // 0x20
	private static DelegateBridge __Hotfix0__RenderSelfIdentity; // 0x28
	private static DelegateBridge __Hotfix0__RenderOppositeIdentity; // 0x30
	private static DelegateBridge __Hotfix0__RenderConstIdentity; // 0x38
	private static DelegateBridge __Hotfix0__OnSetInverseText; // 0x40
	private static DelegateBridge __Hotfix0__OnTimerStopped; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x20d1368 VA: 0x75946e9368
	public Void RenderPanel(IdentityRenderData selfRD, IdentityRenderData oppositeRD, Boolean isInversed, String gmColor) { }
	// RVA: 0x20d182c VA: 0x75946e982c
	public Void PlayAnim(Action callback) { }
	// RVA: 0x20d1d88 VA: 0x75946e9d88
	public Void RunAnim(FP deltaTime) { }
	// RVA: 0x20d18e8 VA: 0x75946e98e8
	private Void _PlayAnimation(UIAnimationLocation animLocation) { }
	// RVA: 0x20d1768 VA: 0x75946e9768
	private Void _SetGameModeRenderData(String gameModeColor) { }
	// RVA: 0x20d1508 VA: 0x75946e9508
	private Void _RenderSelfIdentity(String name) { }
	// RVA: 0x20d159c VA: 0x75946e959c
	private Void _RenderOppositeIdentity(String name) { }
	// RVA: 0x20d1630 VA: 0x75946e9630
	private Void _RenderConstIdentity(String selfColor, Sprite selfIdentityIcon, String oppositeColor, Sprite oppositeIdentityIcon) { }
	// RVA: 0x20d1f44 VA: 0x75946e9f44
	private Void _OnSetInverseText() { }
	// RVA: 0x20d2020 VA: 0x75946ea020
	private Void _OnTimerStopped() { }
	// RVA: 0x20d209c VA: 0x75946ea09c
	public Void .ctor() { }
	// RVA: 0x20d2160 VA: 0x75946ea160
	private Void <_PlayAnimation>b__23_0() { }
}
```