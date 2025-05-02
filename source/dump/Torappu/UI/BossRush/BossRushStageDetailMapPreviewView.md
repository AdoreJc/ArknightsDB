# BossRushStageDetailMapPreviewView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `SimpleLayoutContent _mapContent`

- `HorizontalLayoutGroup _layoutGroup`

- `GameObject _hideMapButton`

- `BossRushStageDetailMapCache m_cacheData`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `TweenWrapper m_tweenWrapper`

- `Single m_currPosition`

- `Action <onHideMapClick>k__BackingField`


## Properties

- `Action onHideMapClick`


## Methods

- `Void set_onMapItemClick(Action`1)`

- `Action get_onHideMapClick()`

- `Void set_onHideMapClick(Action)`

- `Void set_onShowMapPreviewPanelClick(Action`1)`

- `Void OnHideMapBtnClick()`

- `Void _RenderMapView(Single)`

- `Void _InitIfNot()`

- `Single <OnValueChanged>b__27_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailMapPreviewView : DataBinder`1, IHotfixable
{
	private const Single SPACING_NORMAL; // 0x0
	private const Single SPACING_HIDE; // 0x0
	private const Single MAP_TWEEN_FADETIME; // 0x0
	private const Single MAP_HIDE_POSITION; // 0x0
	private SimpleLayoutContent _mapContent; // 0x20
	private HorizontalLayoutGroup _layoutGroup; // 0x28
	private GameObject _hideMapButton; // 0x30
	private BossRushStageDetailMapCache m_cacheData; // 0x38
	private Boolean m_hasInited; // 0x60
	private Adapter m_adapter; // 0x68
	private TweenWrapper m_tweenWrapper; // 0x70
	private Single m_currPosition; // 0x78
	private Action`1 <onMapItemClick>k__BackingField; // 0x80
	private Action <onHideMapClick>k__BackingField; // 0x88
	private Action`1 <onShowMapPreviewPanelClick>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_onMapItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onMapItemClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onHideMapClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onHideMapClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onShowMapPreviewPanelClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onShowMapPreviewPanelClick; // 0x28
	private static DelegateBridge __Hotfix0_OnHideMapBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0__RenderMapView; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onMapItemClick { get; set; }
	private Action onHideMapClick { get; set; }
	private Action`1 onShowMapPreviewPanelClick { get; set; }

	// RVA: 0x2e74ce4 VA: 0x759548cce4
	private Action`1 get_onMapItemClick() { }
	// RVA: 0x2e74d4c VA: 0x759548cd4c
	public Void set_onMapItemClick(Action`1 value) { }
	// RVA: 0x2e74dd0 VA: 0x759548cdd0
	private Action get_onHideMapClick() { }
	// RVA: 0x2e74e38 VA: 0x759548ce38
	public Void set_onHideMapClick(Action value) { }
	// RVA: 0x2e74ebc VA: 0x759548cebc
	private Action`1 get_onShowMapPreviewPanelClick() { }
	// RVA: 0x2e74f24 VA: 0x759548cf24
	public Void set_onShowMapPreviewPanelClick(Action`1 value) { }
	// RVA: 0x2e74fa8 VA: 0x759548cfa8
	public Void OnHideMapBtnClick() { }
	// RVA: 0x2e75044 VA: 0x759548d044
	public override Void OnValueChanged(BossRushStageDetailProperty property) { }
	// RVA: 0x2e7556c VA: 0x759548d56c
	private Void _RenderMapView(Single value) { }
	// RVA: 0x2e75330 VA: 0x759548d330
	private Void _InitIfNot() { }
	// RVA: 0x2e756e8 VA: 0x759548d6e8
	public Void .ctor() { }
	// RVA: 0x2e75778 VA: 0x759548d778
	private Single <OnValueChanged>b__27_0() { }
}
```