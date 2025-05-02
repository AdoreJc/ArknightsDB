# SandboxV2DungeonRiftEffectFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _rootCanvasGroup`

- `RectTransform _rootRectTrans`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `SandboxV2DungeonRiftEffectView _viewPrefab`

- `Transform _viewContainer`

- `CanvasGroup _canvasSelectTag`

- `Boolean m_isInited`

- `FadeTranslationSwitchTween m_showTween`

- `SandboxV2DungeonRiftEffectView m_view`

- `FadeSwitchTween m_tweenSelectTag`


## Methods

- `Void Render(SandboxV2DungeonMiscRiftViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonRiftEffectFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _rootCanvasGroup; // 0x30
	private RectTransform _rootRectTrans; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private SandboxV2DungeonRiftEffectView _viewPrefab; // 0x50
	private Transform _viewContainer; // 0x58
	private CanvasGroup _canvasSelectTag; // 0x60
	private Boolean m_isInited; // 0x68
	private FadeTranslationSwitchTween m_showTween; // 0x70
	private SandboxV2DungeonRiftEffectView m_view; // 0x78
	private FadeSwitchTween m_tweenSelectTag; // 0x80
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x254c278 VA: 0x7594b64278
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x254c560 VA: 0x7594b64560
	public Void Render(SandboxV2DungeonMiscRiftViewModel viewModel) { }
	// RVA: 0x254c354 VA: 0x7594b64354
	private Void _InitIfNot() { }
	// RVA: 0x254c7a8 VA: 0x7594b647a8
	public Void .ctor() { }
}
```