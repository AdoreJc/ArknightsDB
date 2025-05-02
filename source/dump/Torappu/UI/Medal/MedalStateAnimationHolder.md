# MedalStateAnimationHolder

**Namespace:** `Torappu.UI.Medal`


## Fields

- `AnimationWrapper _animationWrapper`

- `CanvasGroup _canvasGroup`

- `Single m_cacheState`

- `Tween m_cacheTween`

- `FadeSwitchTween m_alphaSwitch`

- `Boolean m_renderFlag`


## Methods

- `Void _SetAlphaActiveFlag(Boolean)`

- `Void SetAvail(Boolean)`

- `Void Render(Boolean)`

- `Single <Render>b__8_0()`

- `Void <Render>b__8_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalStateAnimationHolder : MonoBehaviour, IHotfixable
{
	private AnimationWrapper _animationWrapper; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Single m_cacheState; // 0x28
	private Tween m_cacheTween; // 0x30
	private FadeSwitchTween m_alphaSwitch; // 0x38
	private Boolean m_renderFlag; // 0x40
	private const String DEFAULT_ANIM; // 0x0
	private static DelegateBridge __Hotfix0__SetAlphaActiveFlag; // 0x0
	private static DelegateBridge __Hotfix0_SetAvail; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x279d360 VA: 0x7594db5360
	private Void _SetAlphaActiveFlag(Boolean activeFlag) { }
	// RVA: 0x27923fc VA: 0x7594daa3fc
	public Void SetAvail(Boolean activeFlag) { }
	// RVA: 0x27924a4 VA: 0x7594daa4a4
	public Void Render(Boolean state) { }
	// RVA: 0x279d478 VA: 0x7594db5478
	public Void .ctor() { }
	// RVA: 0x279d4e8 VA: 0x7594db54e8
	private Single <Render>b__8_0() { }
	// RVA: 0x279d4f0 VA: 0x7594db54f0
	private Void <Render>b__8_1(Single val) { }
}
```