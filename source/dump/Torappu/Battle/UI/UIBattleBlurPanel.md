# UIBattleBlurPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Boolean _raycastTarget`

- `UIRenderTextureImage _blurBkg`

- `Shader _blurShader`

- `Boolean m_isInited`

- `UIRenderTextureImage m_bkgImage`

- `CanvasGroup m_alphaHandler`

- `FadeSwitchTween m_fadeTween`


## Properties

- `FadeSwitchTween fadeTween`


## Methods

- `FadeSwitchTween get_fadeTween()`

- `Void ShowBattleBlur()`

- `Void HideBattleBlur()`

- `Void _ShotBlurBackground()`

- `Void _InitIfNot()`

- `Void <get_fadeTween>b__8_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleBlurPanel : MonoBehaviour, IHotfixable
{
	private Boolean _raycastTarget; // 0x18
	private UIRenderTextureImage _blurBkg; // 0x20
	private Shader _blurShader; // 0x28
	private Boolean m_isInited; // 0x30
	private UIRenderTextureImage m_bkgImage; // 0x38
	private CanvasGroup m_alphaHandler; // 0x40
	private FadeSwitchTween m_fadeTween; // 0x48
	private static DelegateBridge __Hotfix0_get_fadeTween; // 0x0
	private static DelegateBridge __Hotfix0_ShowBattleBlur; // 0x8
	private static DelegateBridge __Hotfix0_HideBattleBlur; // 0x10
	private static DelegateBridge __Hotfix0__ShotBlurBackground; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected FadeSwitchTween fadeTween { get; }

	// RVA: 0x207b1e4 VA: 0x75946931e4
	protected FadeSwitchTween get_fadeTween() { }
	// RVA: 0x207b6dc VA: 0x75946936dc
	public Void ShowBattleBlur() { }
	// RVA: 0x207b98c VA: 0x759469398c
	public Void HideBattleBlur() { }
	// RVA: 0x207b79c VA: 0x759469379c
	private Void _ShotBlurBackground() { }
	// RVA: 0x207b378 VA: 0x7594693378
	private Void _InitIfNot() { }
	// RVA: 0x207ba08 VA: 0x7594693a08
	public Void .ctor() { }
	// RVA: 0x207ba80 VA: 0x7594693a80
	private Void <get_fadeTween>b__8_0() { }
}
```