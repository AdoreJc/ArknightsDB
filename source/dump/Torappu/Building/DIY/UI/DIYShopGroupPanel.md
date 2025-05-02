# DIYShopGroupPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `RectTransform _contentParent`

- `RectTransform _positionHandler`

- `GameObject _groupViewProto`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `IFurnitureGroupDataProvider m_groupDataProvider`

- `Coroutine m_fadeCoroutine`


## Methods

- `Void set_onFurnitureSelected(Action`1)`

- `Void _OnFurnitureSelected(DIYShopItemViewData)`

- `Void _RemoveAllGroupView()`

- `IEnumerator _SwitchFadeCoroutine(String, Predicate`1, Comparison`1)`

- `Void _UpdateLayout()`

- `Void Update()`

- `Void _SetupView(String, Predicate`1, Comparison`1)`

- `Void Setup(String, Predicate`1, Comparison`1)`

- `Void Refresh()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYShopGroupPanel : MonoBehaviour
{
	private RectTransform _contentParent; // 0x18
	private RectTransform _positionHandler; // 0x20
	private GameObject _groupViewProto; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private Single _fadeDuration; // 0x38
	private IFurnitureGroupDataProvider m_groupDataProvider; // 0x40
	private Coroutine m_fadeCoroutine; // 0x48
	private List`1 m_groupViews; // 0x50
	private Action`1 m_onFurnitureSelected; // 0x58

	public Action`1 onFurnitureSelected { set; }

	// RVA: 0x38039f0 VA: 0x7595e1b9f0
	public Void set_onFurnitureSelected(Action`1 value) { }
	// RVA: 0x38039f8 VA: 0x7595e1b9f8
	private Void _OnFurnitureSelected(DIYShopItemViewData item) { }
	// RVA: 0x3803a14 VA: 0x7595e1ba14
	private Void _RemoveAllGroupView() { }
	// RVA: 0x3803e20 VA: 0x7595e1be20
	private IEnumerator _SwitchFadeCoroutine(String themeId, Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x3803f08 VA: 0x7595e1bf08
	private Void _UpdateLayout() { }
	// RVA: 0x3804260 VA: 0x7595e1c260
	private Void Update() { }
	// RVA: 0x3804264 VA: 0x7595e1c264
	private Void _SetupView(String themeId, Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x38048c8 VA: 0x7595e1c8c8
	public Void Setup(String themeId, Predicate`1 filter, Comparison`1 sorter) { }
	// RVA: 0x3804978 VA: 0x7595e1c978
	public Void Refresh() { }
	// RVA: 0x3804a10 VA: 0x7595e1ca10
	public Void .ctor() { }
}
```