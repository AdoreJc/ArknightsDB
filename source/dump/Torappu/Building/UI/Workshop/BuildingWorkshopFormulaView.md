# BuildingWorkshopFormulaView

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `BuildingWorkshopFormulaAdapter _adapter`

- `ThreeStateToggle _raritySortToggle`

- `ThreeStateToggle _priceSortToggle`

- `ThreeStateToggle _idSortToggle`

- `GameObject _emptyFurniturePanel`

- `CanvasGroup _canvasGroupBar`

- `CanvasGroup _canvasGroupRarityFilter`

- `TwoStateToggle _rarityFilterToggle`

- `SimpleLayoutContent _layoutContentRarityFilter`

- `Text _textCurRarity`

- `Image _colorBarCurRarity`

- `Boolean m_isInited`

- `FadeSwitchTween m_barSwitchTween`

- `FadeSwitchTween m_rarityFilterSwitchTween`

- `WorkshopFilterListAdapter m_filterListAdapter`

- `WorkshopFormulaSorter m_sorter`

- `BuildingWorkshopFormulaViewModel m_viewModel`

- `BuildingWorkshopFilterIndex m_prefFilterIndex`


## Methods

- `Void set_formulaClickAction(Action`1)`

- `Void _InitIfNot()`

- `Void _RenderTabs(BuildingWorkshopFormulaViewModel)`

- `Void _RenderBar(BuildingWorkshopFormulaViewModel)`

- `Void _RenderFormulaItems(BuildingWorkshopFormulaViewModel)`

- `Void _OnFormulaClicked(IWorkshopFormula)`

- `Int32 <_RenderFormulaItems>b__30_0(IWorkshopFormula, IWorkshopFormula)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFormulaView : DataBinder`1
{
	private const Single DURATION_FADE; // 0x0
	private BuildingWorkshopFormulaAdapter _adapter; // 0x20
	private TwoStateToggle[] _tabButtons; // 0x28
	private ThreeStateToggle _raritySortToggle; // 0x30
	private ThreeStateToggle _priceSortToggle; // 0x38
	private ThreeStateToggle _idSortToggle; // 0x40
	private GameObject _emptyFurniturePanel; // 0x48
	private CanvasGroup _canvasGroupBar; // 0x50
	private CanvasGroup _canvasGroupRarityFilter; // 0x58
	private TwoStateToggle _rarityFilterToggle; // 0x60
	private SimpleLayoutContent _layoutContentRarityFilter; // 0x68
	private Text _textCurRarity; // 0x70
	private Image _colorBarCurRarity; // 0x78
	private Boolean m_isInited; // 0x80
	private FadeSwitchTween m_barSwitchTween; // 0x88
	private FadeSwitchTween m_rarityFilterSwitchTween; // 0x90
	private WorkshopFilterListAdapter m_filterListAdapter; // 0x98
	private WorkshopFormulaSorter m_sorter; // 0xa0
	private Func`3 m_currentSortFunc; // 0xa8
	private BuildingWorkshopFormulaViewModel m_viewModel; // 0xb0
	private BuildingWorkshopFilterIndex m_prefFilterIndex; // 0xb8
	private Action`1 <formulaClickAction>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_set_formulaClickAction; // 0x0
	private static DelegateBridge __Hotfix0_get_formulaClickAction; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderTabs; // 0x20
	private static DelegateBridge __Hotfix0__RenderBar; // 0x28
	private static DelegateBridge __Hotfix0__RenderFormulaItems; // 0x30
	private static DelegateBridge __Hotfix0__OnFormulaClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 formulaClickAction { get; set; }

	// RVA: 0x3d68874 VA: 0x7596380874
	public Void set_formulaClickAction(Action`1 value) { }
	// RVA: 0x3d6de2c VA: 0x7596385e2c
	private Action`1 get_formulaClickAction() { }
	// RVA: 0x3d6de94 VA: 0x7596385e94
	public override Void OnValueChanged(BuildingWorkshopFormulaProperty property) { }
	// RVA: 0x3d6df90 VA: 0x7596385f90
	private Void _InitIfNot() { }
	// RVA: 0x3d6e1fc VA: 0x75963861fc
	private Void _RenderTabs(BuildingWorkshopFormulaViewModel viewModel) { }
	// RVA: 0x3d6e2d8 VA: 0x75963862d8
	private Void _RenderBar(BuildingWorkshopFormulaViewModel viewModel) { }
	// RVA: 0x3d6e500 VA: 0x7596386500
	private Void _RenderFormulaItems(BuildingWorkshopFormulaViewModel viewModel) { }
	// RVA: 0x3d6e714 VA: 0x7596386714
	private Void _OnFormulaClicked(IWorkshopFormula formula) { }
	// RVA: 0x3d6e7cc VA: 0x75963867cc
	public Void .ctor() { }
	// RVA: 0x3d6e898 VA: 0x7596386898
	private Int32 <_RenderFormulaItems>b__30_0(IWorkshopFormula lhs, IWorkshopFormula rhs) { }
}
```