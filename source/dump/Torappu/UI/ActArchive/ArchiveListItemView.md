# ArchiveListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Image _nodeCurrent`

- `Image _nodeCurrentArray`

- `GameObject _nodeNew`

- `Vector2 _nodeCurrentArrayStartPos`

- `Vector2 _nodeCurrentArrayEndPos`

- `Vector3 _nodeCurrentStartScale`

- `CanvasGroup _currNodeCanvasGroup`

- `CanvasGroup _imgTitleNormalCanvasGroup`

- `CanvasGroup _textTitleCanvasGroup`

- `Image _imgTitleNormal`

- `Image _imgTitleLocked`

- `Text _textTitle`

- `Button _picSelectBtn`

- `ArchiveItemModel m_cachedModel`

- `Boolean m_isFocus`

- `Sequence m_sequence`

- `ArchiveListItemSwitchTween m_switchTween`

- `ActArchiveController <controller>k__BackingField`


## Properties

- `ActArchiveController controller`


## Methods

- `Void SetTitleSprite(Sprite)`

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void Render(String, ArchiveItemModel, Boolean)`

- `Void EventOnItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveListItemView : MonoBehaviour, IHotfixable
{
	private Image _nodeCurrent; // 0x18
	private Image _nodeCurrentArray; // 0x20
	private GameObject _nodeNew; // 0x28
	private Vector2 _nodeCurrentArrayStartPos; // 0x30
	private Vector2 _nodeCurrentArrayEndPos; // 0x38
	private Vector3 _nodeCurrentStartScale; // 0x40
	private CanvasGroup _currNodeCanvasGroup; // 0x50
	private CanvasGroup _imgTitleNormalCanvasGroup; // 0x58
	private CanvasGroup _textTitleCanvasGroup; // 0x60
	private Image _imgTitleNormal; // 0x68
	private Image _imgTitleLocked; // 0x70
	private Text _textTitle; // 0x78
	private Button _picSelectBtn; // 0x80
	private ArchiveItemModel m_cachedModel; // 0x88
	private Boolean m_isFocus; // 0x90
	private Sequence m_sequence; // 0x98
	private ArchiveListItemSwitchTween m_switchTween; // 0xa0
	private ActArchiveController <controller>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_SetTitleSprite; // 0x0
	private static DelegateBridge __Hotfix0_get_controller; // 0x8
	private static DelegateBridge __Hotfix0_set_controller; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private ActArchiveController controller { get; set; }

	// RVA: 0x303339c VA: 0x759564b39c
	public Void SetTitleSprite(Sprite sprite) { }
	// RVA: 0x3033474 VA: 0x759564b474
	private ActArchiveController get_controller() { }
	// RVA: 0x30334dc VA: 0x759564b4dc
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x3033560 VA: 0x759564b560
	public Void Render(String selectedItem, ArchiveItemModel itemModel, Boolean isInit) { }
	// RVA: 0x3033830 VA: 0x759564b830
	public Void EventOnItemClicked() { }
	// RVA: 0x3033950 VA: 0x759564b950
	public Void .ctor() { }
}
```