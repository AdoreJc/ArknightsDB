# StageZoneTabGroup

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneTabView _homeTab`

- `StageZoneTabView _mixStoryTab`

- `StageZoneTabView _crisisTab`

- `StageZoneTabView _weeklyTab`

- `StageZoneTabView _campaignTab`

- `StageZoneTabView _permModeTab`

- `Image _backImage`

- `SimpleLayoutContent _barLayout`

- `Adapter m_adapter`

- `UIPageListener m_pageListener`

- `Boolean m_isInited`

- `StageZoneTabGroupViewModel m_viewModel`


## Methods

- `Void set_onZoneTabClicked(Action`1)`

- `Void _InitIfNot()`

- `Void _RenderTabIfAct(StageZoneTabView, StageZoneTabViewModel, Boolean)`

- `Void _TriggerTabClicked(ZoneViewType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneTabGroup : DataBinder`1, IHotfixable
{
	private StageZoneTabView _homeTab; // 0x20
	private StageZoneTabView _mixStoryTab; // 0x28
	private StageZoneTabView _crisisTab; // 0x30
	private StageZoneTabView _weeklyTab; // 0x38
	private StageZoneTabView _campaignTab; // 0x40
	private StageZoneTabView _permModeTab; // 0x48
	private Image _backImage; // 0x50
	private SimpleLayoutContent _barLayout; // 0x58
	private Adapter m_adapter; // 0x60
	private UIPageListener m_pageListener; // 0x68
	private Action`1 <onZoneTabClicked>k__BackingField; // 0x70
	private Boolean m_isInited; // 0x78
	private StageZoneTabGroupViewModel m_viewModel; // 0x80
	private static DelegateBridge __Hotfix0_get_onZoneTabClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onZoneTabClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__RenderTabIfAct; // 0x20
	private static DelegateBridge __Hotfix0__TriggerTabClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onZoneTabClicked { get; set; }

	// RVA: 0x2fbc7d8 VA: 0x75955d47d8
	public Action`1 get_onZoneTabClicked() { }
	// RVA: 0x2fbc840 VA: 0x75955d4840
	public Void set_onZoneTabClicked(Action`1 value) { }
	// RVA: 0x2fbc8c4 VA: 0x75955d48c4
	private Void _InitIfNot() { }
	// RVA: 0x2fbcf78 VA: 0x75955d4f78
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fbd270 VA: 0x75955d5270
	private Void _RenderTabIfAct(StageZoneTabView tabView, StageZoneTabViewModel viewModel, Boolean isBlack) { }
	// RVA: 0x2fbd778 VA: 0x75955d5778
	private Void _TriggerTabClicked(ZoneViewType viewType) { }
	// RVA: 0x2fbd830 VA: 0x75955d5830
	public Void .ctor() { }
}
```