# Act24sideMeldingItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Image _icon`

- `Image _bg`

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

- `Void Render(Act24sideMeldingItemViewModel, String)`

- `Void Render(Act24sideMeldingItemViewModel, ILoadAsset, String)`

- `Void BattleFinishOnly_Render(Act24sideMeldingItemViewModel, String)`

- `Void _ShowItemDesc()`

- `Void _RenderItemView(Act24sideMeldingItemViewModel, Sprite, Sprite)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingItemView : MonoBehaviour, IItemCard, IHotfixable
{
	private Image _icon; // 0x18
	private Image _bg; // 0x20
	private GameObject _objCountPart; // 0x28
	private Text _count; // 0x30
	private Graphic _cardRaycaster; // 0x38
	private String m_itemId; // 0x40
	private Boolean m_canClick; // 0x48
	private UIItemViewModel m_itemViewModel; // 0x50
	private UIStateFinder m_finder; // 0x58
	private static DelegateBridge __Hotfix0_get_isCardClickable; // 0x0
	private static DelegateBridge __Hotfix0_set_isCardClickable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix1_Render; // 0x18
	private static DelegateBridge __Hotfix0_BattleFinishOnly_Render; // 0x20
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x28
	private static DelegateBridge __Hotfix0__RenderItemView; // 0x30
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isCardClickable { get; set; }

	// RVA: 0x32b3348 VA: 0x75958cb348
	public Boolean get_isCardClickable() { }
	// RVA: 0x32b33c4 VA: 0x75958cb3c4
	public Void set_isCardClickable(Boolean value) { }
	// RVA: 0x32b3458 VA: 0x75958cb458
	public Void Render(Act24sideMeldingItemViewModel viewModel, String actId) { }
	// RVA: 0x32b36c4 VA: 0x75958cb6c4
	public Void Render(Act24sideMeldingItemViewModel viewModel, ILoadAsset assetLoader, String actId) { }
	// RVA: 0x32b37d0 VA: 0x75958cb7d0
	public Void BattleFinishOnly_Render(Act24sideMeldingItemViewModel viewModel, String actId) { }
	// RVA: 0x32b38bc VA: 0x75958cb8bc
	private Void _ShowItemDesc() { }
	// RVA: 0x32b3578 VA: 0x75958cb578
	private Void _RenderItemView(Act24sideMeldingItemViewModel viewModel, Sprite spriteIcon, Sprite spriteBg) { }
	// RVA: 0x32b39d8 VA: 0x75958cb9d8
	public Void EventOnItemClick() { }
	// RVA: 0x32b3a40 VA: 0x75958cba40
	public Void .ctor() { }
}
```