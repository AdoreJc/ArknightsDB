# CharacterLvlupItemCard

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _itemScale`

- `RectTransform _itemContainer`

- `Image _imgSelectedCountBkg`

- `Text _txtSelectedCount`

- `GameObject _panelDisplay`

- `Image _imgDisplayCountBkg`

- `Text _txtDisplayCount`

- `GameObject _panelCounting`

- `Color _colorNormalCount`

- `Color _colorExceedCount`

- `Color _colorEmptyItem`

- `Int32 m_itemIndexCache`

- `Int64 m_selectedCountCache`

- `Mode m_mode`

- `UIItemCard m_itemCard`

- `Boolean m_needDescOnly`


## Methods

- `Void set_onModifyingCardNum(Action`2)`

- `Void Render(Int32, CharacterLvlupItemCardViewModel)`

- `Void EventOnReduceBtnClick()`

- `Void _OnItemClicked(Int32)`

- `Boolean _OnItemLongPressed(Int32)`

- `Void _ShowItemDesc()`

- `Void _CallbackIncreaseWithSound(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupItemCard : MonoBehaviour, IHotfixable
{
	private const Int32 LONG_PRESS_ADD_STEP; // 0x0
	private Single _itemScale; // 0x18
	private RectTransform _itemContainer; // 0x20
	private GameObject[] _panelSelected; // 0x28
	private Image _imgSelectedCountBkg; // 0x30
	private Text _txtSelectedCount; // 0x38
	private GameObject _panelDisplay; // 0x40
	private Image _imgDisplayCountBkg; // 0x48
	private Text _txtDisplayCount; // 0x50
	private GameObject _panelCounting; // 0x58
	private Color _colorNormalCount; // 0x60
	private Color _colorExceedCount; // 0x70
	private Color _colorEmptyItem; // 0x80
	private Action`2 <onModifyingCardNum>k__BackingField; // 0x90
	private Int32 m_itemIndexCache; // 0x98
	private Int64 m_selectedCountCache; // 0xa0
	private Mode m_mode; // 0xa8
	private UIItemCard m_itemCard; // 0xb0
	private Boolean m_needDescOnly; // 0xb8
	private static DelegateBridge __Hotfix0_get_onModifyingCardNum; // 0x0
	private static DelegateBridge __Hotfix0_set_onModifyingCardNum; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnReduceBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnItemLongPressed; // 0x28
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x30
	private static DelegateBridge __Hotfix0__CallbackIncreaseWithSound; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Action`2 onModifyingCardNum { get; set; }

	// RVA: 0x2d76f40 VA: 0x759538ef40
	public Action`2 get_onModifyingCardNum() { }
	// RVA: 0x2d76fa8 VA: 0x759538efa8
	public Void set_onModifyingCardNum(Action`2 value) { }
	// RVA: 0x2d7702c VA: 0x759538f02c
	public Void Render(Int32 index, CharacterLvlupItemCardViewModel viewModel) { }
	// RVA: 0x2d77624 VA: 0x759538f624
	public Void EventOnReduceBtnClick() { }
	// RVA: 0x2d776d0 VA: 0x759538f6d0
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x2d779d4 VA: 0x759538f9d4
	private Boolean _OnItemLongPressed(Int32 index) { }
	// RVA: 0x2d77790 VA: 0x759538f790
	private Void _ShowItemDesc() { }
	// RVA: 0x2d77880 VA: 0x759538f880
	private Void _CallbackIncreaseWithSound(Int32 index, Int32 count) { }
	// RVA: 0x2d77a78 VA: 0x759538fa78
	public Void .ctor() { }
}
```