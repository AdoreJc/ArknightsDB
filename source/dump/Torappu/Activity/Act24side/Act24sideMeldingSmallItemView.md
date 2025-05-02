# Act24sideMeldingSmallItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Image _icon`

- `GameObject _objBgWhite`

- `GameObject _objBgGray`

- `GameObject _objCountPart`

- `Text _count`

- `Graphic _cardRaycaster`

- `String m_itemId`

- `Boolean m_canClick`

- `UIItemViewModel m_itemViewModel`

- `UIStateFinder m_finder`


## Properties

- `Boolean isCardClickable`


## Methods

- `Boolean get_isCardClickable()`

- `Void set_isCardClickable(Boolean)`

- `Void Render(Act24sideMeldingSmallItemViewModel, String)`

- `Void Render(Act24sideMeldingSmallItemViewModel, ILoadAsset, String)`

- `Void _RenderItemView(Act24sideMeldingSmallItemViewModel, ILoadAsset, String)`

- `Void _ShowItemDesc()`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingSmallItemView : MonoBehaviour, IItemCard, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _objBgWhite; // 0x20
	private GameObject _objBgGray; // 0x28
	private GameObject _objCountPart; // 0x30
	private Text _count; // 0x38
	private Graphic _cardRaycaster; // 0x40
	private String m_itemId; // 0x48
	private Boolean m_canClick; // 0x50
	private UIItemViewModel m_itemViewModel; // 0x58
	private UIStateFinder m_finder; // 0x60
	private static DelegateBridge __Hotfix0_get_isCardClickable; // 0x0
	private static DelegateBridge __Hotfix0_set_isCardClickable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix1_Render; // 0x18
	private static DelegateBridge __Hotfix0__RenderItemView; // 0x20
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x28
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isCardClickable { get; set; }

	// RVA: 0x32b4414 VA: 0x75958cc414
	public Boolean get_isCardClickable() { }
	// RVA: 0x32b4490 VA: 0x75958cc490
	public Void set_isCardClickable(Boolean value) { }
	// RVA: 0x32b4524 VA: 0x75958cc524
	public Void Render(Act24sideMeldingSmallItemViewModel viewModel, String actId) { }
	// RVA: 0x32b4840 VA: 0x75958cc840
	public Void Render(Act24sideMeldingSmallItemViewModel viewModel, ILoadAsset assetLoader, String actId) { }
	// RVA: 0x32b45ec VA: 0x75958cc5ec
	private Void _RenderItemView(Act24sideMeldingSmallItemViewModel viewModel, ILoadAsset assetLoader, String actId) { }
	// RVA: 0x32b48e4 VA: 0x75958cc8e4
	private Void _ShowItemDesc() { }
	// RVA: 0x32b4984 VA: 0x75958cc984
	public Void EventOnItemClick() { }
	// RVA: 0x32b49ec VA: 0x75958cc9ec
	public Void .ctor() { }
}
```