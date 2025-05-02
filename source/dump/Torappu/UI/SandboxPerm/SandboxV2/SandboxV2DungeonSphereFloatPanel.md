# SandboxV2DungeonSphereFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _rootCanvasGroup`

- `RectTransform _rootRectTrans`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `SandboxV2DungeonSphereFloatView _viewPrefab`

- `Transform _viewContainer`

- `CanvasGroup _sphereButtonCanvasGroup`

- `Boolean m_isInited`

- `FadeSwitchTween m_buttonTween`

- `FadeTranslationSwitchTween m_showTween`

- `SandboxV2DungeonSphereFloatView m_view`

- `SandboxV2DungeonViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _SetShowButton(SandboxV2DungeonViewModel, Boolean, Boolean)`

- `Void _InitIfNot()`

- `Void _TutorialOnly_TryRaiseAVGSignalOnShown()`

- `Void _TutorialOnly_TryRaiseAVGSignalOnHidden()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSphereFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _rootCanvasGroup; // 0x30
	private RectTransform _rootRectTrans; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private SandboxV2DungeonSphereFloatView _viewPrefab; // 0x50
	private Transform _viewContainer; // 0x58
	private CanvasGroup _sphereButtonCanvasGroup; // 0x60
	private Boolean m_isInited; // 0x68
	private FadeSwitchTween m_buttonTween; // 0x70
	private FadeTranslationSwitchTween m_showTween; // 0x78
	private SandboxV2DungeonSphereFloatView m_view; // 0x80
	private SandboxV2DungeonViewModel m_cachedViewModel; // 0x88
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__SetShowButton; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignalOnShown; // 0x20
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignalOnHidden; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x25501c8 VA: 0x7594b681c8
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2550650 VA: 0x7594b68650
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x255055c VA: 0x7594b6855c
	private Void _SetShowButton(SandboxV2DungeonViewModel viewModel, Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2550284 VA: 0x7594b68284
	private Void _InitIfNot() { }
	// RVA: 0x2550850 VA: 0x7594b68850
	private Void _TutorialOnly_TryRaiseAVGSignalOnShown() { }
	// RVA: 0x2550970 VA: 0x7594b68970
	private Void _TutorialOnly_TryRaiseAVGSignalOnHidden() { }
	// RVA: 0x2550a14 VA: 0x7594b68a14
	public Void .ctor() { }
}
```