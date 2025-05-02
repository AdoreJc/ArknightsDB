# DIYFilterGroup

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Transform _container`

- `DIYFilterToggleView _filterView`

- `DIYFilterToggleView _allFilterView`

- `DIYFilterPressedEvent _onFilterPressed`

- `DIYSubTypePressedEvent _onSubTypePressed`

- `CanvasGroup _filterCanvasGroup`

- `Boolean m_isInit`


## Methods

- `Void _InitIfNot(DIYFilterGroupModel)`

- `Void _InitALLFilter(DIYFilterGroupModel)`

- `Void _InitFilters(DIYFilterGroupModel)`

- `Void <_InitALLFilter>b__11_0(DIYFilterType)`

- `Void <_InitALLFilter>b__11_1(FurnitureSubType)`

- `Void <_InitFilters>b__12_0(DIYFilterType)`

- `Void <_InitFilters>b__12_1(FurnitureSubType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterGroup : DataBinder`1
{
	private Transform _container; // 0x20
	private DIYFilterToggleView _filterView; // 0x28
	private DIYFilterToggleView _allFilterView; // 0x30
	private DIYFilterPressedEvent _onFilterPressed; // 0x38
	private DIYSubTypePressedEvent _onSubTypePressed; // 0x40
	private CanvasGroup _filterCanvasGroup; // 0x48
	private List`1 m_filters; // 0x50
	private Boolean m_isInit; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__InitALLFilter; // 0x8
	private static DelegateBridge __Hotfix0__InitFilters; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x38152e4 VA: 0x7595e2d2e4
	private Void _InitIfNot(DIYFilterGroupModel filterGroupModel) { }
	// RVA: 0x3815384 VA: 0x7595e2d384
	private Void _InitALLFilter(DIYFilterGroupModel filterGroupModel) { }
	// RVA: 0x3815594 VA: 0x7595e2d594
	private Void _InitFilters(DIYFilterGroupModel filterGroupModel) { }
	// RVA: 0x3815910 VA: 0x7595e2d910
	public override Void OnValueChanged(DIYFilterGroupProperty property) { }
	// RVA: 0x3815dc4 VA: 0x7595e2ddc4
	public Void .ctor() { }
	// RVA: 0x3815ea8 VA: 0x7595e2dea8
	private Void <_InitALLFilter>b__11_0(DIYFilterType filterType) { }
	// RVA: 0x3815f00 VA: 0x7595e2df00
	private Void <_InitALLFilter>b__11_1(FurnitureSubType filterSubType) { }
	// RVA: 0x3815f58 VA: 0x7595e2df58
	private Void <_InitFilters>b__12_0(DIYFilterType filterType) { }
	// RVA: 0x3815fb0 VA: 0x7595e2dfb0
	private Void <_InitFilters>b__12_1(FurnitureSubType filterSubType) { }
}
```