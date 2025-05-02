# DIYFurniturePanelSortItem

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Image _background`

- `Text _sortMethodName`

- `UIAtlasImage _imgAscending`

- `UIAtlasImage _imgDescending`

- `GameObject _selected`

- `Int32 m_cachedIndex`

- `DiySortType m_cachedDiySortType`


## Methods

- `Void Render(DIYSortMethodModel, Int32)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurniturePanelSortItem : MonoBehaviour, IHotfixable
{
	private static Color BKG_COLOR_1; // 0x0
	private static Color BKG_COLOR_2; // 0x10
	private static Color ARROW_COLOR_ACTIVE; // 0x20
	private static Color ARROW_COLOR_INACTIVE; // 0x30
	private static Color TEXT_COLOR_SELECTED; // 0x40
	private static Color TEXT_COLOR_NORMAL; // 0x50
	private Image _background; // 0x18
	private Text _sortMethodName; // 0x20
	private UIAtlasImage _imgAscending; // 0x28
	private UIAtlasImage _imgDescending; // 0x30
	private GameObject _selected; // 0x38
	private Int32 m_cachedIndex; // 0x40
	private DiySortType m_cachedDiySortType; // 0x44
	public Action`2 eventOnClicked; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x60
	private static DelegateBridge __Hotfix0_OnClicked; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x381afc0 VA: 0x7595e32fc0
	public Void Render(DIYSortMethodModel sortMethodModel, Int32 selectedIndex) { }
	// RVA: 0x381b72c VA: 0x7595e3372c
	public Void OnClicked() { }
	// RVA: 0x381b7c4 VA: 0x7595e337c4
	public Void .ctor() { }
	// RVA: 0x381b844 VA: 0x7595e33844
	private static Void .cctor() { }
}
```