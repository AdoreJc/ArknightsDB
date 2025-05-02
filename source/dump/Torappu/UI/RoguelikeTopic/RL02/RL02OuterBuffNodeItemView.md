# RL02OuterBuffNodeItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RL02DevelopmentNodeType _nodeType`

- `Image _imgIcon`

- `RectTransform _rectSelf`

- `Text _textNodeName`

- `TwoStateFadeSwitcher _bgSwitcher`

- `CanvasGroup _canvasGroupTextTitle`

- `CanvasGroup _canvasGroupOutline`

- `RectTransform _rectSelectPanel`

- `CanvasGroup _canvasGroupSelectPanel`

- `Single _selectLoopTime`

- `UIColorGraphic _imgIconGroup`

- `Color _colorIconUnlock`

- `Color _colorIconLocked`

- `Color _colorTextUnlock`

- `Color _colorTextLocked`

- `Boolean m_hasInited`

- `String m_cachedNodeId`

- `FadeSwitchTween m_textTitleSwitchTween`

- `SelectSwitchTween m_selectSwitchTween`

- `Tween m_outlineLoopTween`

- `UIPage <page>k__BackingField`


## Properties

- `RL02DevelopmentNodeType nodeType`

- `UIPage page`


## Methods

- `RL02DevelopmentNodeType get_nodeType()`

- `Void set_onNodeClicked(Action`1)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(RL02OuterBuffItemModel, RenderConfig)`

- `Void OnClick()`

- `Void _InitIfNot()`

- `Void _GenerateUnlockOutlineLoopTween()`

- `Void _ClearUnlockOutlineLoopTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffNodeItemView : MonoBehaviour, IHotfixable
{
	private const Single OUTLINE_LOOP_TIME; // 0x0
	private RL02DevelopmentNodeType _nodeType; // 0x18
	private Image _imgIcon; // 0x20
	private RectTransform _rectSelf; // 0x28
	private Text _textNodeName; // 0x30
	private TwoStateFadeSwitcher _bgSwitcher; // 0x38
	private CanvasGroup _canvasGroupTextTitle; // 0x40
	private CanvasGroup _canvasGroupOutline; // 0x48
	private RectTransform _rectSelectPanel; // 0x50
	private CanvasGroup _canvasGroupSelectPanel; // 0x58
	private Single _selectLoopTime; // 0x60
	private UIColorGraphic _imgIconGroup; // 0x68
	private Color _colorIconUnlock; // 0x70
	private Color _colorIconLocked; // 0x80
	private Color _colorTextUnlock; // 0x90
	private Color _colorTextLocked; // 0xa0
	private Boolean m_hasInited; // 0xb0
	private String m_cachedNodeId; // 0xb8
	private FadeSwitchTween m_textTitleSwitchTween; // 0xc0
	private SelectSwitchTween m_selectSwitchTween; // 0xc8
	private Tween m_outlineLoopTween; // 0xd0
	private Action`1 <onNodeClicked>k__BackingField; // 0xd8
	private UIPage <page>k__BackingField; // 0xe0
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x0
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x8
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x10
	private static DelegateBridge __Hotfix0_get_page; // 0x18
	private static DelegateBridge __Hotfix0_set_page; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnClick; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__GenerateUnlockOutlineLoopTween; // 0x40
	private static DelegateBridge __Hotfix0__ClearUnlockOutlineLoopTween; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public RL02DevelopmentNodeType nodeType { get; }
	private Action`1 onNodeClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x26c29ac VA: 0x7594cda9ac
	public RL02DevelopmentNodeType get_nodeType() { }
	// RVA: 0x26c30d4 VA: 0x7594cdb0d4
	private Action`1 get_onNodeClicked() { }
	// RVA: 0x26c2b68 VA: 0x7594cdab68
	public Void set_onNodeClicked(Action`1 value) { }
	// RVA: 0x26c313c VA: 0x7594cdb13c
	private UIPage get_page() { }
	// RVA: 0x26c2ae4 VA: 0x7594cdaae4
	public Void set_page(UIPage value) { }
	// RVA: 0x26c2bec VA: 0x7594cdabec
	public Void Render(RL02OuterBuffItemModel nodeModel, RenderConfig config) { }
	// RVA: 0x26c3594 VA: 0x7594cdb594
	public Void OnClick() { }
	// RVA: 0x26c31a4 VA: 0x7594cdb1a4
	private Void _InitIfNot() { }
	// RVA: 0x26c32fc VA: 0x7594cdb2fc
	private Void _GenerateUnlockOutlineLoopTween() { }
	// RVA: 0x26c34c8 VA: 0x7594cdb4c8
	private Void _ClearUnlockOutlineLoopTween() { }
	// RVA: 0x26c36d8 VA: 0x7594cdb6d8
	public Void .ctor() { }
}
```