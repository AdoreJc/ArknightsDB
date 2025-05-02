# UICooperateBattleSpeedPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UIAnimationLocation _mateLightShow`

- `UIAnimationLocation _meLightShow`

- `UIAnimationLocation _mateLightHide`

- `UIAnimationLocation _meLightHide`

- `UIAnimationLocation _mateSelect`

- `UIAnimationLocation _meSelect`

- `Image _playerSpeedUp`

- `Image _mateSpeedUp`

- `RectTransform _hint`

- `Image _speedImage`

- `Sprite _speedUp1x`

- `Sprite _speedUp2x`

- `Single _lightFadeDuration`

- `Boolean m_cacheSpeedUp`

- `Boolean m_cacheMateSpeedUp`

- `Boolean m_myLightOn`

- `Boolean m_mateLightOn`

- `Boolean m_hintState`

- `Tween m_myTweenSelect`

- `Tween m_myTweenLight`

- `Tween m_mateTweenSelect`

- `Tween m_mateTweenLight`

- `OnLineType m_mateOnline`


## Methods

- `Void UpdateSpeedHint()`

- `Void InitIfNot()`

- `Void SetSpeedColor(Boolean, Boolean)`

- `Void _OnMeEnterSpeedUp()`

- `Void _OnMeLightOn()`

- `Void _OnMeExitSpeedUp()`

- `Void _OnMeLightOff()`

- `Void _OnMateEnterSpeedUp()`

- `Void _OnMateLightOn()`

- `Void _OnMateExitSpeedUp()`

- `Void _OnMateLightOff()`

- `Void _UpdateLightStatus()`

- `Void _ShowHintByOnline(Object)`

- `Void _HideHintWhenDie(Object)`

- `Void _ShowHintWhenRevive(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleSpeedPanel : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _mateLightShow; // 0x18
	private UIAnimationLocation _meLightShow; // 0x28
	private UIAnimationLocation _mateLightHide; // 0x38
	private UIAnimationLocation _meLightHide; // 0x48
	private UIAnimationLocation _mateSelect; // 0x58
	private UIAnimationLocation _meSelect; // 0x68
	private Image _playerSpeedUp; // 0x78
	private Image _mateSpeedUp; // 0x80
	private RectTransform _hint; // 0x88
	private Image _speedImage; // 0x90
	private Sprite _speedUp1x; // 0x98
	private Sprite _speedUp2x; // 0xa0
	private Single _lightFadeDuration; // 0xa8
	private Boolean m_cacheSpeedUp; // 0xac
	private Boolean m_cacheMateSpeedUp; // 0xad
	private Boolean m_myLightOn; // 0xae
	private Boolean m_mateLightOn; // 0xaf
	private Boolean m_hintState; // 0xb0
	private Tween m_myTweenSelect; // 0xb8
	private Tween m_myTweenLight; // 0xc0
	private Tween m_mateTweenSelect; // 0xc8
	private Tween m_mateTweenLight; // 0xd0
	private OnLineType m_mateOnline; // 0xd8
	private static DelegateBridge __Hotfix0_UpdateSpeedHint; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_SetSpeedColor; // 0x10
	private static DelegateBridge __Hotfix0__OnMeEnterSpeedUp; // 0x18
	private static DelegateBridge __Hotfix0__OnMeLightOn; // 0x20
	private static DelegateBridge __Hotfix0__OnMeExitSpeedUp; // 0x28
	private static DelegateBridge __Hotfix0__OnMeLightOff; // 0x30
	private static DelegateBridge __Hotfix0__OnMateEnterSpeedUp; // 0x38
	private static DelegateBridge __Hotfix0__OnMateLightOn; // 0x40
	private static DelegateBridge __Hotfix0__OnMateExitSpeedUp; // 0x48
	private static DelegateBridge __Hotfix0__OnMateLightOff; // 0x50
	private static DelegateBridge __Hotfix0__UpdateLightStatus; // 0x58
	private static DelegateBridge __Hotfix0__ShowHintByOnline; // 0x60
	private static DelegateBridge __Hotfix0__HideHintWhenDie; // 0x68
	private static DelegateBridge __Hotfix0__ShowHintWhenRevive; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x20c8440 VA: 0x75946e0440
	public Void UpdateSpeedHint() { }
	// RVA: 0x20c84d0 VA: 0x75946e04d0
	public Void InitIfNot() { }
	// RVA: 0x20c8624 VA: 0x75946e0624
	public Void SetSpeedColor(Boolean speedUp, Boolean mateSpeedUp) { }
	// RVA: 0x20c87bc VA: 0x75946e07bc
	private Void _OnMeEnterSpeedUp() { }
	// RVA: 0x20c8d0c VA: 0x75946e0d0c
	private Void _OnMeLightOn() { }
	// RVA: 0x20c8a04 VA: 0x75946e0a04
	private Void _OnMeExitSpeedUp() { }
	// RVA: 0x20c8e50 VA: 0x75946e0e50
	private Void _OnMeLightOff() { }
	// RVA: 0x20c88e0 VA: 0x75946e08e0
	private Void _OnMateEnterSpeedUp() { }
	// RVA: 0x20c8f30 VA: 0x75946e0f30
	private Void _OnMateLightOn() { }
	// RVA: 0x20c8b28 VA: 0x75946e0b28
	private Void _OnMateExitSpeedUp() { }
	// RVA: 0x20c9074 VA: 0x75946e1074
	private Void _OnMateLightOff() { }
	// RVA: 0x20c8c4c VA: 0x75946e0c4c
	private Void _UpdateLightStatus() { }
	// RVA: 0x20c9154 VA: 0x75946e1154
	private Void _ShowHintByOnline(Object arg) { }
	// RVA: 0x20c9220 VA: 0x75946e1220
	private Void _HideHintWhenDie(Object arg) { }
	// RVA: 0x20c929c VA: 0x75946e129c
	private Void _ShowHintWhenRevive(Object arg) { }
	// RVA: 0x20c9324 VA: 0x75946e1324
	public Void .ctor() { }
}
```