# RL02OuterBuffSummaryRawTextNodeItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `SimpleLayoutContent _textContent`

- `GameObject _panelBkg`

- `Image _imgGroupIcon`

- `Text _firstText`

- `CanvasGroup _canvasGroupText`

- `CanvasGroup _canvasGroupIcon`

- `Single _alphaUnlock`

- `Single _alphaLockedText`

- `Single _alphaLockedIcon`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(String, Int32, RL02OuterBuffListRawTextGroupItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffSummaryRawTextNodeItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _textContent; // 0x18
	private GameObject _panelBkg; // 0x20
	private Image _imgGroupIcon; // 0x28
	private Text _firstText; // 0x30
	private CanvasGroup _canvasGroupText; // 0x38
	private CanvasGroup _canvasGroupIcon; // 0x40
	private Single _alphaUnlock; // 0x48
	private Single _alphaLockedText; // 0x4c
	private Single _alphaLockedIcon; // 0x50
	private GameObject[] _iconLevelGroup; // 0x58
	private Boolean m_hasInited; // 0x60
	private List`1 m_itemViewList; // 0x68
	private Adapter m_adapter; // 0x70
	private UIPage <page>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private UIPage page { get; set; }

	// RVA: 0x26c526c VA: 0x7594cdd26c
	private UIPage get_page() { }
	// RVA: 0x26c4f20 VA: 0x7594cdcf20
	public Void set_page(UIPage value) { }
	// RVA: 0x26c4fa4 VA: 0x7594cdcfa4
	public Void Render(String topicId, Int32 position, RL02OuterBuffListRawTextGroupItemModel model) { }
	// RVA: 0x26c52d4 VA: 0x7594cdd2d4
	private Void _InitIfNot() { }
	// RVA: 0x26c5530 VA: 0x7594cdd530
	public Void .ctor() { }
}
```