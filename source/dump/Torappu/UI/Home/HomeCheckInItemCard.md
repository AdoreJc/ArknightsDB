# HomeCheckInItemCard

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _itemIcon`

- `Text _textTitle`

- `Text _textCount`

- `Graphic _raycastBtn`

- `GameObject _targetGameObject`

- `UIItemViewModel m_cachedModel`

- `Boolean m_isClickable`


## Properties

- `Boolean isCardClickable`


## Methods

- `Boolean get_isCardClickable()`

- `Void set_isCardClickable(Boolean)`

- `Void Render(ISharedItemModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInItemCard : MonoBehaviour, IItemCard, IHotfixable
{
	private Image _itemIcon; // 0x18
	private Text _textTitle; // 0x20
	private Text _textCount; // 0x28
	private Graphic _raycastBtn; // 0x30
	private GameObject _targetGameObject; // 0x38
	private UIItemViewModel m_cachedModel; // 0x40
	private Boolean m_isClickable; // 0x48
	private static DelegateBridge __Hotfix0_get_isCardClickable; // 0x0
	private static DelegateBridge __Hotfix0_set_isCardClickable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isCardClickable { get; set; }

	// RVA: 0x28306f8 VA: 0x7594e486f8
	public Boolean get_isCardClickable() { }
	// RVA: 0x282f210 VA: 0x7594e47210
	public Void set_isCardClickable(Boolean value) { }
	// RVA: 0x282f2ac VA: 0x7594e472ac
	public Void Render(ISharedItemModel itemModel) { }
	// RVA: 0x2830760 VA: 0x7594e48760
	public Void OnClick() { }
	// RVA: 0x2830844 VA: 0x7594e48844
	public Void .ctor() { }
}
```