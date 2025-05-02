# RL04NodeUpgradeMuralView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _imgBgThemeColor`

- `Image _imgBgMural`

- `Image _iconCenterEye`

- `Single _glowFadeDuration`

- `CanvasGroup _permCompleteGroup`

- `GameObject _allCompleteIconGo`

- `UIAnimationLocation _completeEnterAnim`

- `Int32 m_muralTweenCount`

- `Tween m_completeEnterTween`

- `FadeSwitchTween m_permCompleteTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(RL04NodeUpgradeConfig, Input)`

- `Void _PlayCompleteAnimIfNeed(Input)`

- `Void _PlayShowAnimIfNeed(Input)`

- `Void _RenderView(RL04NodeUpgradeConfig, Input)`

- `Void _InitIfNot(Input)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeMuralView : MonoBehaviour, IHotfixable
{
	private Image _imgBgThemeColor; // 0x18
	private Image _imgBgMural; // 0x20
	private Image _iconCenterEye; // 0x28
	private Image[] _imgMuralList; // 0x30
	private CanvasGroup[] _selectGlowList; // 0x38
	private Single _glowFadeDuration; // 0x40
	private CanvasGroup _permCompleteGroup; // 0x48
	private GameObject _allCompleteIconGo; // 0x50
	private UIAnimationLocation _completeEnterAnim; // 0x58
	private UIAnimationLocation[] _muralShowAnimList; // 0x68
	private Int32 m_muralTweenCount; // 0x70
	private Tween[] m_muralTweenArray; // 0x78
	private Tween m_completeEnterTween; // 0x80
	private List`1 m_glowTweenList; // 0x88
	private FadeSwitchTween m_permCompleteTween; // 0x90
	private Boolean m_hasInited; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__PlayCompleteAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__PlayShowAnimIfNeed; // 0x10
	private static DelegateBridge __Hotfix0__RenderView; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b31e24 VA: 0x7595149e24
	public Void Render(RL04NodeUpgradeConfig config, Input input) { }
	// RVA: 0x2b32848 VA: 0x759514a848
	private Void _PlayCompleteAnimIfNeed(Input input) { }
	// RVA: 0x2b325ec VA: 0x759514a5ec
	private Void _PlayShowAnimIfNeed(Input input) { }
	// RVA: 0x2b32318 VA: 0x759514a318
	private Void _RenderView(RL04NodeUpgradeConfig config, Input input) { }
	// RVA: 0x2b31f20 VA: 0x7595149f20
	private Void _InitIfNot(Input input) { }
	// RVA: 0x2b32978 VA: 0x759514a978
	public Void .ctor() { }
}
```