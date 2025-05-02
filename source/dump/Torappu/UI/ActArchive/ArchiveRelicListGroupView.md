# ArchiveRelicListGroupView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `UIAtlasImage _imgTitle`

- `Transform _panelItem`

- `Text _textAttainNum`

- `ArchiveRelicListItemView _relicItemView`

- `GameObject _panelAttainNum`

- `UIAtlasObject _titleImage`

- `Boolean m_hasInited`

- `ArchiveRelicController <controller>k__BackingField`


## Properties

- `ArchiveRelicController controller`


## Methods

- `ArchiveRelicController get_controller()`

- `Void set_controller(ArchiveRelicController)`

- `Void _InitIfNot()`

- `Void Render(ArchiveRelicItemGroupModel, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicListGroupView : MonoBehaviour, IHotfixable
{
	private const Int32 NUM_ITEM_PER_LINE; // 0x0
	private UIAtlasImage _imgTitle; // 0x18
	private Transform _panelItem; // 0x20
	private Text _textAttainNum; // 0x28
	private ArchiveRelicListItemView _relicItemView; // 0x30
	private GameObject _panelAttainNum; // 0x38
	private List`1 _titleImageName; // 0x40
	private UIAtlasObject _titleImage; // 0x48
	private Boolean m_hasInited; // 0x50
	private List`1 m_itemGroup; // 0x58
	private ArchiveRelicController <controller>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveRelicController controller { get; set; }

	// RVA: 0x3079ecc VA: 0x7595691ecc
	private ArchiveRelicController get_controller() { }
	// RVA: 0x3079f34 VA: 0x7595691f34
	public Void set_controller(ArchiveRelicController value) { }
	// RVA: 0x3079fb8 VA: 0x7595691fb8
	public Void _InitIfNot() { }
	// RVA: 0x307a1e0 VA: 0x75956921e0
	public Void Render(ArchiveRelicItemGroupModel groupModel, String selectItemId, Boolean showAnim) { }
	// RVA: 0x307a94c VA: 0x759569294c
	public Void .ctor() { }
}
```