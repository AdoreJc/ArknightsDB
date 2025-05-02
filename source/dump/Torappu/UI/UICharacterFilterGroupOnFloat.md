# UICharacterFilterGroupOnFloat

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _filterSelectArrow`

- `Image _arrowImg`

- `UILayoutDimensionListener _girdLayoutListener`

- `Boolean _singleMode`

- `CharacterFilterViewModel m_filterModel`

- `Boolean m_isInited`

- `Boolean m_layoutBuilt`

- `Boolean m_hasSelectArrow`

- `Tweener m_arrowTw`

- `Tweener m_arrowHideTw`

- `Tweener m_arrowShowTw`

- `Int32 m_currentFilterIdx`


## Properties

- `CharacterFilterViewModel filterModel`


## Methods

- `CharacterFilterViewModel get_filterModel()`

- `Void set_filterModel(CharacterFilterViewModel)`

- `Void _InitIfNot()`

- `Void OnFilterChanged(CharacterFilterElement, Boolean)`

- `Void _ProcessSingleFilterMode(CharacterFilterElement, Boolean)`

- `Void _ProcessMultiFilterMode(CharacterFilterElement, Boolean)`

- `Void _UpdateData2UI()`

- `Void _LayoutRebuilt()`

- `Void _TryUpdateArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterFilterGroupOnFloat : MonoBehaviour, IHotfixable
{
	private UICharacterFilterItemOnFloat[] _filterItems; // 0x18
	private RectTransform _filterSelectArrow; // 0x20
	private Image _arrowImg; // 0x28
	private UILayoutDimensionListener _girdLayoutListener; // 0x30
	private Boolean _singleMode; // 0x38
	private CharacterFilterViewModel m_filterModel; // 0x40
	private List`1 m_filterIdents; // 0x48
	private Boolean m_isInited; // 0x50
	private Boolean m_layoutBuilt; // 0x51
	private Boolean m_hasSelectArrow; // 0x52
	public Action`1 onFilterCallback; // 0x58
	private Tweener m_arrowTw; // 0x60
	private Tweener m_arrowHideTw; // 0x68
	private Tweener m_arrowShowTw; // 0x70
	private Int32 m_currentFilterIdx; // 0x78
	private static DelegateBridge __Hotfix0_get_filterModel; // 0x0
	private static DelegateBridge __Hotfix0_set_filterModel; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnFilterChanged; // 0x18
	private static DelegateBridge __Hotfix0__ProcessSingleFilterMode; // 0x20
	private static DelegateBridge __Hotfix0__ProcessMultiFilterMode; // 0x28
	private static DelegateBridge __Hotfix0__UpdateData2UI; // 0x30
	private static DelegateBridge __Hotfix0__LayoutRebuilt; // 0x38
	private static DelegateBridge __Hotfix0__TryUpdateArrow; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public CharacterFilterViewModel filterModel { get; set; }

	// RVA: 0x212e820 VA: 0x7594746820
	public CharacterFilterViewModel get_filterModel() { }
	// RVA: 0x212e888 VA: 0x7594746888
	public Void set_filterModel(CharacterFilterViewModel value) { }
	// RVA: 0x212eb64 VA: 0x7594746b64
	private Void _InitIfNot() { }
	// RVA: 0x212edb4 VA: 0x7594746db4
	public Void OnFilterChanged(CharacterFilterElement filter, Boolean isSelected) { }
	// RVA: 0x212ef3c VA: 0x7594746f3c
	private Void _ProcessSingleFilterMode(CharacterFilterElement filter, Boolean isSelected) { }
	// RVA: 0x212f0e8 VA: 0x75947470e8
	private Void _ProcessMultiFilterMode(CharacterFilterElement filter, Boolean isSelected) { }
	// RVA: 0x212eaa4 VA: 0x7594746aa4
	private Void _UpdateData2UI() { }
	// RVA: 0x212f8c0 VA: 0x75947478c0
	private Void _LayoutRebuilt() { }
	// RVA: 0x212f55c VA: 0x759474755c
	private Void _TryUpdateArrow() { }
	// RVA: 0x212f930 VA: 0x7594747930
	public Void .ctor() { }
}
```