# ArchiveRelicListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Text _titleText`

- `Image _imgIcon`

- `GameObject _panelSelected`

- `CanvasGroup _canvasGroupSelected`

- `GameObject _panelLocked`

- `GameObject _panelNormalBg`

- `GameObject _panelSpBg`

- `GameObject _panelNew`

- `Button _button`

- `RelicItemModel m_cachedModel`

- `Boolean m_hasInited`

- `ArchiveRelicListItemSwitchTween m_switchTween`

- `ArchiveRelicController <controller>k__BackingField`


## Properties

- `ArchiveRelicController controller`


## Methods

- `ArchiveRelicController get_controller()`

- `Void set_controller(ArchiveRelicController)`

- `Void _InitIfNot()`

- `Void OnRelicItemClicked()`

- `Void Render(RelicItemModel, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicListItemView : MonoBehaviour, IHotfixable
{
	public static readonly Color UNATTAIN_COLOR; // 0x0
	public static readonly Color ATTAIN_COLOR; // 0x10
	public static readonly Color LOCKED_COLOR; // 0x20
	private Text _titleText; // 0x18
	private Image _imgIcon; // 0x20
	private GameObject _panelSelected; // 0x28
	private CanvasGroup _canvasGroupSelected; // 0x30
	private GameObject _panelLocked; // 0x38
	private GameObject _panelNormalBg; // 0x40
	private GameObject _panelSpBg; // 0x48
	private GameObject _panelNew; // 0x50
	private Button _button; // 0x58
	private RelicItemModel m_cachedModel; // 0x60
	private Boolean m_hasInited; // 0x68
	private ArchiveRelicListItemSwitchTween m_switchTween; // 0x70
	private ArchiveRelicController <controller>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_controller; // 0x30
	private static DelegateBridge __Hotfix0_set_controller; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_OnRelicItemClicked; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private ArchiveRelicController controller { get; set; }

	// RVA: 0x307aa10 VA: 0x7595692a10
	private ArchiveRelicController get_controller() { }
	// RVA: 0x307a14c VA: 0x759569214c
	public Void set_controller(ArchiveRelicController value) { }
	// RVA: 0x307aa88 VA: 0x7595692a88
	private Void _InitIfNot() { }
	// RVA: 0x307abfc VA: 0x7595692bfc
	public Void OnRelicItemClicked() { }
	// RVA: 0x307a648 VA: 0x7595692648
	public Void Render(RelicItemModel itemModel, String selectItemId, Boolean showAnim) { }
	// RVA: 0x307acf0 VA: 0x7595692cf0
	public Void .ctor() { }
	// RVA: 0x307ad70 VA: 0x7595692d70
	private static Void .cctor() { }
}
```