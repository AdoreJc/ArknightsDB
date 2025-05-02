# Act1VAutoChessChessShopMenuView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `SimpleLayoutContent _layoutMenuLevelList`

- `CanvasGroup _canvasGroupToggleParent`

- `CanvasGroup _canvasGroupToggleMask`

- `CanvasGroup _canvasSwitchShopTypeTogglePart`

- `UIAnimationLocation _shopTypeSwitchAnim`

- `CanvasGroup _canvasConfirmQuickSkillAndModulePart`

- `GameObject _objTrapTab`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Act1VAutoChessChessShopViewModel m_viewModel`

- `ShopMenuLevelListAdapter m_shopMenuLevelListAdapter`

- `FadeSwitchTween m_tweenSwitchShopTypeTogglePart`

- `FadeSwitchTween m_tweenConfirmQuickSkillAndModulePart`

- `AnimationSwitchTween m_shopTypeSwitchTween`

- `Act1VAutoChessShopStatus m_cachedShopStatus`

- `Tween m_tweenSwitchShopTypeToggleParent`

- `FadeSwitchTween m_tweenSwitchShopTypeToggleMask`


## Methods

- `Void _InitIfNot()`

- `Void _RefreshToggleClickState(Boolean)`

- `Void Render(Act1VAutoChessChessShopViewModel)`

- `Void TutorialOnly_RegisterTutorialGo()`

- `Act1VAutoChessChessShopMenuLevelItemView GetMenuLevelItemView(Int32)`

- `Void OnConfirmQuickSkillAndModuleClick()`

- `Void OnShopTypeToggleClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopMenuView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _layoutMenuLevelList; // 0x18
	private CanvasGroup _canvasGroupToggleParent; // 0x20
	private CanvasGroup _canvasGroupToggleMask; // 0x28
	private CanvasGroup _canvasSwitchShopTypeTogglePart; // 0x30
	private UIAnimationLocation _shopTypeSwitchAnim; // 0x38
	private CanvasGroup _canvasConfirmQuickSkillAndModulePart; // 0x48
	private GameObject _objTrapTab; // 0x50
	private Boolean m_hasInited; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private Act1VAutoChessChessShopViewModel m_viewModel; // 0x70
	private ShopMenuLevelListAdapter m_shopMenuLevelListAdapter; // 0x78
	private FadeSwitchTween m_tweenSwitchShopTypeTogglePart; // 0x80
	private FadeSwitchTween m_tweenConfirmQuickSkillAndModulePart; // 0x88
	private AnimationSwitchTween m_shopTypeSwitchTween; // 0x90
	private Act1VAutoChessShopStatus m_cachedShopStatus; // 0x98
	private Tween m_tweenSwitchShopTypeToggleParent; // 0xa0
	private FadeSwitchTween m_tweenSwitchShopTypeToggleMask; // 0xa8
	private const Single TOGGLE_PARENT_ALPHA_DURATION; // 0x0
	private const Single TOGGLE_PARENT_SHOW_ALPHA_VAL; // 0x0
	private const Single TOGGLE_PARENT_FADE_ALPHA_VAL; // 0x0
	private const Int32 TUTORIAL_FIVE_LEVEL_MENU_ITEM_POS; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RefreshToggleClickState; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x18
	private static DelegateBridge __Hotfix0_GetMenuLevelItemView; // 0x20
	private static DelegateBridge __Hotfix0_OnConfirmQuickSkillAndModuleClick; // 0x28
	private static DelegateBridge __Hotfix0_OnShopTypeToggleClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x33160f0 VA: 0x759592e0f0
	private Void _InitIfNot() { }
	// RVA: 0x33163e4 VA: 0x759592e3e4
	private Void _RefreshToggleClickState(Boolean isToggleCanClick) { }
	// RVA: 0x331476c VA: 0x759592c76c
	public Void Render(Act1VAutoChessChessShopViewModel shopViewModel) { }
	// RVA: 0x33154c8 VA: 0x759592d4c8
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x33165e4 VA: 0x759592e5e4
	private Act1VAutoChessChessShopMenuLevelItemView GetMenuLevelItemView(Int32 position) { }
	// RVA: 0x33166e8 VA: 0x759592e6e8
	public Void OnConfirmQuickSkillAndModuleClick() { }
	// RVA: 0x331678c VA: 0x759592e78c
	public Void OnShopTypeToggleClick() { }
	// RVA: 0x33168a0 VA: 0x759592e8a0
	public Void .ctor() { }
}
```