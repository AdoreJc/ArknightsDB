# ItemRepoOptionalVoucherChooseItemView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `GameObject _objSelectDec`

- `GameObject _objSelectBoard`

- `Image _imgIcon`

- `Text _txtItemName`

- `Text _txtItemHasCount`

- `Text _txtPickCount`

- `GameObject _objPerPickCount`

- `Text _txtPerPickCount`

- `GameObject _objAddPart`

- `GameObject _objMinusPart`

- `UIStringEvent onAddItemClickEvent`

- `UIStringEvent onDetailClickEvent`

- `UIStringEvent onMinusItemClickEvent`

- `String m_cacheItemId`

- `Boolean m_chosing`

- `Single ALPHA_ICON_UNSELECT`


## Methods

- `Void ApplyData(ItemRepoOptionalVoucherChooseItemViewModel)`

- `Boolean ShowItemHasCount(ItemType)`

- `Void OnAddItemClick()`

- `Void OnDetailClick()`

- `Void OnMinusItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherChooseItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objSelectDec; // 0x18
	private GameObject _objSelectBoard; // 0x20
	private Image _imgIcon; // 0x28
	private Text _txtItemName; // 0x30
	private Text _txtItemHasCount; // 0x38
	private Text _txtPickCount; // 0x40
	private GameObject _objPerPickCount; // 0x48
	private Text _txtPerPickCount; // 0x50
	private GameObject _objAddPart; // 0x58
	private GameObject _objMinusPart; // 0x60
	public UIStringEvent onAddItemClickEvent; // 0x68
	public UIStringEvent onDetailClickEvent; // 0x70
	public UIStringEvent onMinusItemClickEvent; // 0x78
	private String m_cacheItemId; // 0x80
	private Boolean m_chosing; // 0x88
	private const String PER_PICK_COUNT; // 0x0
	private Single ALPHA_ICON_UNSELECT; // 0x8c
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_ShowItemHasCount; // 0x8
	private static DelegateBridge __Hotfix0_OnAddItemClick; // 0x10
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x18
	private static DelegateBridge __Hotfix0_OnMinusItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d35cd4 VA: 0x759534dcd4
	public Void ApplyData(ItemRepoOptionalVoucherChooseItemViewModel chooseItemViewModel) { }
	// RVA: 0x2d35fd8 VA: 0x759534dfd8
	private Boolean ShowItemHasCount(ItemType itemType) { }
	// RVA: 0x2d36064 VA: 0x759534e064
	public Void OnAddItemClick() { }
	// RVA: 0x2d360f8 VA: 0x759534e0f8
	public Void OnDetailClick() { }
	// RVA: 0x2d3618c VA: 0x759534e18c
	public Void OnMinusItemClick() { }
	// RVA: 0x2d36220 VA: 0x759534e220
	public Void .ctor() { }
}
```