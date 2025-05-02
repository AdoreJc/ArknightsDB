# CharacterInfoPotentialLevelUpItem

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `RectTransform _itemCardContainer`

- `Single _itemCardScale`

- `GameObject _selected`

- `Text _itemName`

- `Text _textCount`

- `UIIntEvent _onClick`

- `Int32 m_index`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel itemViewModel`

- `RequireViewModel requireItem`


## Properties

- `String itemName`


## Methods

- `String get_itemName()`

- `Void Render(PotentialItemViewModel)`

- `Void SetIndex(Int32)`

- `Void OnClick()`

- `Void _InitIfNot()`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialLevelUpItem : MonoBehaviour
{
	private const String ITEM_COUNT_FORMAT; // 0x0
	private RectTransform _itemCardContainer; // 0x18
	private Single _itemCardScale; // 0x20
	private GameObject _selected; // 0x28
	private Text _itemName; // 0x30
	private Text _textCount; // 0x38
	private UIIntEvent _onClick; // 0x40
	private Int32 m_index; // 0x48
	private Boolean m_isInited; // 0x4c
	private UIItemCard m_itemCard; // 0x50
	public UIItemViewModel itemViewModel; // 0x58
	public RequireViewModel requireItem; // 0x60

	public String itemName { get; }

	// RVA: 0x2d7f49c VA: 0x759539749c
	public String get_itemName() { }
	// RVA: 0x2d7f4f8 VA: 0x75953974f8
	public Void Render(PotentialItemViewModel model) { }
	// RVA: 0x2d7f908 VA: 0x7595397908
	public Void SetIndex(Int32 index) { }
	// RVA: 0x2d7f93c VA: 0x759539793c
	public Void OnClick() { }
	// RVA: 0x2d7f6d4 VA: 0x75953976d4
	private Void _InitIfNot() { }
	// RVA: 0x2d7f9a0 VA: 0x75953979a0
	private Void _OnItemCardClicked(Int32 index) { }
	// RVA: 0x2d7fa58 VA: 0x7595397a58
	public Void .ctor() { }
}
```