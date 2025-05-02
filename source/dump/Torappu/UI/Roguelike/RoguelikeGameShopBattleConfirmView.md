# RoguelikeGameShopBattleConfirmView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAnimationLocation _animShow`

- `UIAnimationLocation _animConfirm`

- `UIAnimationLocation _animReject`

- `Tween m_tween`

- `Boolean m_isInteractable`

- `RoguelikeGameBattleShopControllerBindings m_battleShopControllerBindings`


## Methods

- `Void BindShopController(RoguelikeGameBattleShopControllerBindings)`

- `Void PlayShowAnim()`

- `Void PlayConfirmAnim()`

- `Boolean IsPlayingAnim()`

- `Void _PlayRejectAnim()`

- `Void _OnConfirmCallback()`

- `Void _OnRejectCallback()`

- `Void OnBattleConfirmClick()`

- `Void OnBattleRejectClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGameShopBattleConfirmView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animShow; // 0x18
	private UIAnimationLocation _animConfirm; // 0x28
	private UIAnimationLocation _animReject; // 0x38
	private Tween m_tween; // 0x48
	private Boolean m_isInteractable; // 0x50
	private RoguelikeGameBattleShopControllerBindings m_battleShopControllerBindings; // 0x58
	private static DelegateBridge __Hotfix0_BindShopController; // 0x0
	private static DelegateBridge __Hotfix0_PlayShowAnim; // 0x8
	private static DelegateBridge __Hotfix0_PlayConfirmAnim; // 0x10
	private static DelegateBridge __Hotfix0_IsPlayingAnim; // 0x18
	private static DelegateBridge __Hotfix0__PlayRejectAnim; // 0x20
	private static DelegateBridge __Hotfix0__OnConfirmCallback; // 0x28
	private static DelegateBridge __Hotfix0__OnRejectCallback; // 0x30
	private static DelegateBridge __Hotfix0_OnBattleConfirmClick; // 0x38
	private static DelegateBridge __Hotfix0_OnBattleRejectClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2ada1b8 VA: 0x75950f21b8
	public Void BindShopController(RoguelikeGameBattleShopControllerBindings bindings) { }
	// RVA: 0x2ada668 VA: 0x75950f2668
	public Void PlayShowAnim() { }
	// RVA: 0x2adb498 VA: 0x75950f3498
	public Void PlayConfirmAnim() { }
	// RVA: 0x2adb5fc VA: 0x75950f35fc
	public Boolean IsPlayingAnim() { }
	// RVA: 0x2ae1298 VA: 0x75950f9298
	private Void _PlayRejectAnim() { }
	// RVA: 0x2ae13fc VA: 0x75950f93fc
	private Void _OnConfirmCallback() { }
	// RVA: 0x2ae1484 VA: 0x75950f9484
	private Void _OnRejectCallback() { }
	// RVA: 0x2ae150c VA: 0x75950f950c
	public Void OnBattleConfirmClick() { }
	// RVA: 0x2ae1584 VA: 0x75950f9584
	public Void OnBattleRejectClick() { }
	// RVA: 0x2ae15ec VA: 0x75950f95ec
	public Void .ctor() { }
}
```