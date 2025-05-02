# DIYSortPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `CanvasGroup _canvasGroup`

- `Image _background`

- `SortAndFilterState m_currentState`


## Methods

- `Void Setup()`

- `Void ShowPanel(Action`1)`

- `Void _Hide()`

- `Void OnCancelButtonPressed()`

- `Void OnOkButtonPressed()`

- `Void _SetupSortIndex(Int32, SortingMethod)`

- `Void _RemoveAllFilter()`

- `Void _ToggleFilter(Int32)`

- `Void _OnSortButton(DIYSortButton)`

- `Void _OnFilterButton(DIYFilterButton)`

- `Void OnDestroy()`

- `Void <_Hide>b__14_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYSortPanel : MonoBehaviour
{
	private SortButtonItem[] _sortButtons; // 0x18
	private FilterButtonItem[] _filterButtons; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private Image _background; // 0x30
	private SortAndFilterState m_currentState; // 0x38
	private Action`1 onOkButtonPressed; // 0x40


	// RVA: 0x38095b4 VA: 0x7595e215b4
	public Void Setup() { }
	// RVA: 0x380a6bc VA: 0x7595e226bc
	public Void ShowPanel(Action`1 resultHandler) { }
	// RVA: 0x380cad4 VA: 0x7595e24ad4
	private Void _Hide() { }
	// RVA: 0x380a23c VA: 0x7595e2223c
	public Void OnCancelButtonPressed() { }
	// RVA: 0x380cbac VA: 0x7595e24bac
	public Void OnOkButtonPressed() { }
	// RVA: 0x380c918 VA: 0x7595e24918
	private Void _SetupSortIndex(Int32 index, SortingMethod method) { }
	// RVA: 0x380ca00 VA: 0x7595e24a00
	private Void _RemoveAllFilter() { }
	// RVA: 0x380cbe0 VA: 0x7595e24be0
	private Void _ToggleFilter(Int32 index) { }
	// RVA: 0x380cfcc VA: 0x7595e24fcc
	private Void _OnSortButton(DIYSortButton button) { }
	// RVA: 0x380d0c0 VA: 0x7595e250c0
	private Void _OnFilterButton(DIYFilterButton button) { }
	// RVA: 0x380d1a4 VA: 0x7595e251a4
	private Void OnDestroy() { }
	// RVA: 0x380d330 VA: 0x7595e25330
	public Void .ctor() { }
	// RVA: 0x380d428 VA: 0x7595e25428
	private Void <_Hide>b__14_0() { }
}
```