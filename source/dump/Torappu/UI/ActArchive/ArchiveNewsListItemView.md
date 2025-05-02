# ArchiveNewsListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _nodeCurrent`

- `Image _nodeCurrentArray`

- `GameObject _nodeNew`

- `GameObject _nodeLocked`

- `CanvasGroup _canvasLocked`

- `Vector2 _nodeCurrentArrayStartPos`

- `Vector2 _nodeCurrentArrayEndPos`

- `Vector3 _nodeCurrentStartScale`

- `CanvasGroup _currNodeCanvasGroup`

- `CanvasGroup _textTitleCanvasGroup`

- `Text _textTitle`

- `Text _textNewspaper`

- `Image _imgNewspaper`

- `Button _picSelectBtn`

- `NewsItemModel m_cachedModel`

- `Boolean m_isFocus`

- `Sequence m_sequence`

- `ArchiveNewsListItemSwitchTween m_switchTween`

- `ArchiveNewsController <controller>k__BackingField`


## Properties

- `ArchiveNewsController controller`


## Methods

- `ArchiveNewsController get_controller()`

- `Void set_controller(ArchiveNewsController)`

- `Void Render(String, NewsItemModel, Boolean)`

- `Void EventOnItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveNewsListItemView : MonoBehaviour, IHotfixable
{
	private Image _nodeCurrent; // 0x18
	private Image _nodeCurrentArray; // 0x20
	private GameObject _nodeNew; // 0x28
	private GameObject _nodeLocked; // 0x30
	private CanvasGroup _canvasLocked; // 0x38
	private Vector2 _nodeCurrentArrayStartPos; // 0x40
	private Vector2 _nodeCurrentArrayEndPos; // 0x48
	private Vector3 _nodeCurrentStartScale; // 0x50
	private CanvasGroup _currNodeCanvasGroup; // 0x60
	private CanvasGroup _textTitleCanvasGroup; // 0x68
	private Text _textTitle; // 0x70
	private Text _textNewspaper; // 0x78
	private Image _imgNewspaper; // 0x80
	private Button _picSelectBtn; // 0x88
	private NewsItemModel m_cachedModel; // 0x90
	private Boolean m_isFocus; // 0x98
	private Sequence m_sequence; // 0xa0
	private ArchiveNewsListItemSwitchTween m_switchTween; // 0xa8
	private ArchiveNewsController <controller>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveNewsController controller { get; set; }

	// RVA: 0x3065be8 VA: 0x759567dbe8
	private ArchiveNewsController get_controller() { }
	// RVA: 0x306566c VA: 0x759567d66c
	public Void set_controller(ArchiveNewsController value) { }
	// RVA: 0x30656f0 VA: 0x759567d6f0
	public Void Render(String selectedItem, NewsItemModel itemModel, Boolean isInit) { }
	// RVA: 0x3065ce4 VA: 0x759567dce4
	public Void EventOnItemClicked() { }
	// RVA: 0x3065e04 VA: 0x759567de04
	public Void .ctor() { }
}
```