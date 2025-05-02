# SandboxV2DungeonLogisticsEffectFloatPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _rootCanvasGroup`

- `RectTransform _rootRectTrans`

- `Vector2 _detailShowPos`

- `Vector2 _detailHidePos`

- `SandboxV2DungeonLogisticsEffectView _viewPrefab`

- `Transform _viewContainer`

- `Boolean m_isInited`

- `FadeTranslationSwitchTween m_showTween`

- `SandboxV2DungeonLogisticsEffectView m_view`

- `SandboxV2DungeonMiscLogisticsEffectViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscLogisticsEffectViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonLogisticsEffectFloatPanel : SandboxV2FloatPanel
{
	private CanvasGroup _rootCanvasGroup; // 0x30
	private RectTransform _rootRectTrans; // 0x38
	private Vector2 _detailShowPos; // 0x40
	private Vector2 _detailHidePos; // 0x48
	private SandboxV2DungeonLogisticsEffectView _viewPrefab; // 0x50
	private Transform _viewContainer; // 0x58
	private Boolean m_isInited; // 0x60
	private FadeTranslationSwitchTween m_showTween; // 0x68
	private SandboxV2DungeonLogisticsEffectView m_view; // 0x70
	private SandboxV2DungeonMiscLogisticsEffectViewModel m_cachedViewModel; // 0x78
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x254b734 VA: 0x7594b63734
	protected override Void SetShowStatus(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x254b978 VA: 0x7594b63978
	public Void Render(SandboxV2DungeonMiscLogisticsEffectViewModel logisticsViewModel) { }
	// RVA: 0x254b7e4 VA: 0x7594b637e4
	private Void _InitIfNot() { }
	// RVA: 0x254bc70 VA: 0x7594b63c70
	public Void .ctor() { }
}
```