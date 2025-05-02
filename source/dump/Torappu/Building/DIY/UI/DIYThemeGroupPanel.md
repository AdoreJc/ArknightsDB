# DIYThemeGroupPanel

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

- `Void set_onFurnitureInfoPressed(Action`1)`

- `Void _OnFurnitureSelected(IDIYItem)`

- `Void _RemoveAllGroupView()`

- `IEnumerator _SwitchFadeCoroutine(String, IFurnitureDataProvider, IDIYRoomModifierDataProvider, IFurnitureProvider, IDIYRoomModifierProvider)`

- `Void _UpdateLayout()`

- `Void Update()`

- `Boolean _OnFurnitureInfoPressed(DIYItemViewData)`

- `Void _SetupView(String, IFurnitureDataProvider, IDIYRoomModifierDataProvider, IFurnitureProvider, IDIYRoomModifierProvider)`

- `Void Setup(String, IFurnitureDataProvider, IDIYRoomModifierDataProvider, IFurnitureProvider, IDIYRoomModifierProvider)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYThemeGroupPanel : MonoBehaviour
{
	private RectTransform _contentParent; // 0x18
	private RectTransform _positionHandler; // 0x20
	private GameObject _groupViewProto; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private Single _fadeDuration; // 0x38
	private IFurnitureGroupDataProvider m_groupDataProvider; // 0x40
	private Coroutine m_fadeCoroutine; // 0x48
	private Action`1 m_onFurnitureSelected; // 0x50
	private Action`1 m_onFurnitureInfoPressed; // 0x58

	public Action`1 onFurnitureSelected { set; }
	public Action`1 onFurnitureInfoPressed { set; }

	// RVA: 0x380edec VA: 0x7595e26dec
	public Void set_onFurnitureSelected(Action`1 value) { }
	// RVA: 0x380edf4 VA: 0x7595e26df4
	public Void set_onFurnitureInfoPressed(Action`1 value) { }
	// RVA: 0x380edfc VA: 0x7595e26dfc
	private Void _OnFurnitureSelected(IDIYItem item) { }
	// RVA: 0x380ee18 VA: 0x7595e26e18
	private Void _RemoveAllGroupView() { }
	// RVA: 0x380f224 VA: 0x7595e27224
	private IEnumerator _SwitchFadeCoroutine(String themeId, IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider, IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider) { }
	// RVA: 0x380f33c VA: 0x7595e2733c
	private Void _UpdateLayout() { }
	// RVA: 0x380f694 VA: 0x7595e27694
	private Void Update() { }
	// RVA: 0x380f698 VA: 0x7595e27698
	private Boolean _OnFurnitureInfoPressed(DIYItemViewData data) { }
	// RVA: 0x380f6c0 VA: 0x7595e276c0
	private Void _SetupView(String themeId, IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider, IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider) { }
	// RVA: 0x380fc78 VA: 0x7595e27c78
	public Void Setup(String themeId, IFurnitureDataProvider furnitureDataProvider, IDIYRoomModifierDataProvider modifierDataProvider, IFurnitureProvider furnitureProvider, IDIYRoomModifierProvider modifierProvider) { }
	// RVA: 0x380fd08 VA: 0x7595e27d08
	public Void .ctor() { }
}
```