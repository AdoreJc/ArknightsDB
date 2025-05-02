# SandboxV2DungeonExpeditionEffectFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _rootCanvasGroup`

- `RectTransform _rootRectTrans`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `SandboxV2DungeonExpeditionEffectView _viewPrefab`

- `Transform _viewContainer`

- `Boolean m_isInited`

- `FadeTranslationSwitchTween m_showTween`

- `SandboxV2DungeonExpeditionEffectView m_view`

- `SandboxV2DungeonMiscExpeditionViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscExpeditionViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonExpeditionEffectFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _rootCanvasGroup; // 0x30
	private RectTransform _rootRectTrans; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private SandboxV2DungeonExpeditionEffectView _viewPrefab; // 0x50
	private Transform _viewContainer; // 0x58
	private Boolean m_isInited; // 0x60
	private FadeTranslationSwitchTween m_showTween; // 0x68
	private SandboxV2DungeonExpeditionEffectView m_view; // 0x70
	private SandboxV2DungeonMiscExpeditionViewModel m_cachedViewModel; // 0x78
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x254a740 VA: 0x7594b62740
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x254a984 VA: 0x7594b62984
	public Void Render(SandboxV2DungeonMiscExpeditionViewModel expeditionViewModel) { }
	// RVA: 0x254a7f0 VA: 0x7594b627f0
	private Void _InitIfNot() { }
	// RVA: 0x254ab34 VA: 0x7594b62b34
	public Void .ctor() { }
}
```