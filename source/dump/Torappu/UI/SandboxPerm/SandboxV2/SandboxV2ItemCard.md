# SandboxV2ItemCard

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _rarityBkg`

- `Image _icon`

- `Text _num`

- `GameObject _numNode`

- `UILongPressButtonEx _pressBtn`

- `Graphic _pressRaycaster`

- `UIScaler _scaler`

- `GameObject _existGour`

- `GameObject _existIngred`

- `GameObject _prodNumNode`

- `Text _prodNum`

- `GameObject _emptyLabel`

- `GameObject _emptyLine`

- `Image _selectNode`

- `GameObject _reduceBtn`

- `Text _selectNum`

- `Sprite _rarity_none`

- `Sprite _rarity_t1`

- `Sprite _rarity_t2`

- `Sprite _rarity_t3`

- `Sprite _rarity_t4`

- `Sprite _rarity_t5`

- `Sprite _rarity_sp`

- `Boolean m_init`

- `Option m_option`

- `UIItemViewModel m_cachedModel`

- `Int32 <index>k__BackingField`


## Properties

- `Int32 index`

- `Single scale`

- `Boolean isCardClickable`


## Methods

- `Int32 get_index()`

- `Void set_index(Int32)`

- `Void Render(Int32, UIItemViewModel)`

- `Void SetOption(Option)`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Boolean get_isCardClickable()`

- `Void set_isCardClickable(Boolean)`

- `Sprite _GetRarityBkg(ItemRarity)`

- `Void _InitIfNot()`

- `Void EventReduceBtnClick()`

- `Void _EventOnClick()`

- `Boolean _EventOnLongClick()`

- `GameObject TutorialOnly_GetButtonGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ItemCard : MonoBehaviour, IItemCard, IHotfixable
{
	private Image _rarityBkg; // 0x18
	private Image _icon; // 0x20
	private Text _num; // 0x28
	private GameObject _numNode; // 0x30
	private UILongPressButtonEx _pressBtn; // 0x38
	private Graphic _pressRaycaster; // 0x40
	private UIScaler _scaler; // 0x48
	private GameObject _existGour; // 0x50
	private GameObject _existIngred; // 0x58
	private GameObject _prodNumNode; // 0x60
	private Text _prodNum; // 0x68
	private GameObject _emptyLabel; // 0x70
	private GameObject _emptyLine; // 0x78
	private Image _selectNode; // 0x80
	private GameObject _reduceBtn; // 0x88
	private Text _selectNum; // 0x90
	private Sprite _rarity_none; // 0x98
	private Sprite _rarity_t1; // 0xa0
	private Sprite _rarity_t2; // 0xa8
	private Sprite _rarity_t3; // 0xb0
	private Sprite _rarity_t4; // 0xb8
	private Sprite _rarity_t5; // 0xc0
	private Sprite _rarity_sp; // 0xc8
	private Boolean m_init; // 0xd0
	private Option m_option; // 0xd8
	private UIItemViewModel m_cachedModel; // 0xf8
	public Action`1 onItemClick; // 0x100
	public Func`2 onItemLongClick; // 0x108
	public Action`1 onReduceClick; // 0x110
	private const String RED; // 0x0
	private const String NEED_COUNT_HTML_ENOUGH; // 0x0
	private const String NEED_COUNT_HTML_SHORT; // 0x0
	private const String PROD_COUNT_HTML_SHORT; // 0x0
	private const Int32 MAX_COUNT; // 0x0
	private Int32 <index>k__BackingField; // 0x118
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_set_index; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SetOption; // 0x18
	private static DelegateBridge __Hotfix0_get_scale; // 0x20
	private static DelegateBridge __Hotfix0_set_scale; // 0x28
	private static DelegateBridge __Hotfix0_get_isCardClickable; // 0x30
	private static DelegateBridge __Hotfix0_set_isCardClickable; // 0x38
	private static DelegateBridge __Hotfix0__GetRarityBkg; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0_EventReduceBtnClick; // 0x50
	private static DelegateBridge __Hotfix0__EventOnClick; // 0x58
	private static DelegateBridge __Hotfix0__EventOnLongClick; // 0x60
	private static DelegateBridge __Hotfix0_TutorialOnly_GetButtonGO; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Int32 index { get; set; }
	public Single scale { get; set; }
	public Boolean isCardClickable { get; set; }

	// RVA: 0x25007b8 VA: 0x7594b187b8
	public Int32 get_index() { }
	// RVA: 0x2500820 VA: 0x7594b18820
	private Void set_index(Int32 value) { }
	// RVA: 0x250089c VA: 0x7594b1889c
	public Void Render(Int32 idx, UIItemViewModel itemViewModel) { }
	// RVA: 0x2501144 VA: 0x7594b19144
	public Void SetOption(Option option) { }
	// RVA: 0x25012d4 VA: 0x7594b192d4
	public Single get_scale() { }
	// RVA: 0x2501348 VA: 0x7594b19348
	public Void set_scale(Single value) { }
	// RVA: 0x25013d4 VA: 0x7594b193d4
	public Boolean get_isCardClickable() { }
	// RVA: 0x2501450 VA: 0x7594b19450
	public Void set_isCardClickable(Boolean value) { }
	// RVA: 0x2501018 VA: 0x7594b19018
	private Sprite _GetRarityBkg(ItemRarity rarity) { }
	// RVA: 0x2500e38 VA: 0x7594b18e38
	private Void _InitIfNot() { }
	// RVA: 0x25014e4 VA: 0x7594b194e4
	public Void EventReduceBtnClick() { }
	// RVA: 0x2501578 VA: 0x7594b19578
	private Void _EventOnClick() { }
	// RVA: 0x250160c VA: 0x7594b1960c
	private Boolean _EventOnLongClick() { }
	// RVA: 0x25016a4 VA: 0x7594b196a4
	public GameObject TutorialOnly_GetButtonGO() { }
	// RVA: 0x2501718 VA: 0x7594b19718
	public Void .ctor() { }
}
```