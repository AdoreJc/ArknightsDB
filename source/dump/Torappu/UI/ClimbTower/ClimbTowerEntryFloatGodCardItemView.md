# ClimbTowerEntryFloatGodCardItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _cardComplete`

- `Image _imgCardIcon`

- `SimpleLayoutContent _towerContent`

- `String m_cardId`

- `Adapter m_adapter`

- `Boolean m_hasInited`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `Void set_onClicked(Action`1)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(String, ClimbTowerEntryGodCardModel)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatGodCardItemView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_SUB_CARD_EMPTY; // 0x0
	private const Single ALPHA_SUB_CARD_USED; // 0x0
	private const Single ALPHA_SUB_CARD_UNUSED; // 0x0
	private const Single ALPHA_SUB_CARD_ALPHABET_USED; // 0x0
	private const Single ALPHA_SUB_CARD_ALPHABET_UNUSED; // 0x0
	private GameObject _cardComplete; // 0x18
	private Image _imgCardIcon; // 0x20
	private List`1 _branchList; // 0x28
	private List`1 _branchAlphabetList; // 0x30
	private SimpleLayoutContent _towerContent; // 0x38
	private String m_cardId; // 0x40
	private Adapter m_adapter; // 0x48
	private Boolean m_hasInited; // 0x50
	private List`1 m_towerStatus; // 0x58
	private Action`1 <onClicked>k__BackingField; // 0x60
	private UIPage <page>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_set_page; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 onClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c6239c VA: 0x759527a39c
	private Action`1 get_onClicked() { }
	// RVA: 0x2c62404 VA: 0x759527a404
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2c62488 VA: 0x759527a488
	private UIPage get_page() { }
	// RVA: 0x2c624f0 VA: 0x759527a4f0
	public Void set_page(UIPage value) { }
	// RVA: 0x2c62574 VA: 0x759527a574
	public Void Render(String seasonId, ClimbTowerEntryGodCardModel viewModel) { }
	// RVA: 0x2c628d4 VA: 0x759527a8d4
	public Void OnClick() { }
	// RVA: 0x2c62804 VA: 0x759527a804
	private Void _InitIfNot() { }
	// RVA: 0x2c62a08 VA: 0x759527aa08
	public Void .ctor() { }
}
```