# RL03TotemBuffMapNodeView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RoguelikeNodeViewData _viewData`

- `UIAtlasImage _imgBkg`

- `UIAtlasImage _imgCantReachBkg`

- `Image _imgIcon`

- `Graphic _graphicBoss`

- `UIAtlasImage _imgCurrent`

- `GameObject _verticalLine`

- `Graphic _graphicVerticalLine`

- `CanvasGroup _canvasGroupSingleSelect`

- `CanvasGroup _canvasGroupMultiSelect`

- `Button _btnNode`

- `Color _colorSelectableIcon`

- `Color _colorNormalIcon`

- `Color _colorReachableCurve`

- `Color _colorCantReachCurve`

- `Color _colorNormalBoss`

- `Color _colorFinalBoss`

- `RectTransform _rectTransformBuffNode`

- `Single _buffNodeStep`

- `UIAnimationLocation _singleSelectableAnim`

- `RoguelikeDungeonNode m_node`

- `Boolean m_isInited`

- `Tween m_singleSelectableTween`

- `FadeSwitchTween m_singleSelectTween`

- `FadeSwitchTween m_multiSelectTween`


## Methods

- `Void set_onNodeClicked(Action`2)`

- `Void Render(RL03TotemBuffMapNodeViewModel, Boolean)`

- `RoguelikeCurve GetCurve(Int32)`

- `RectTransform GetConnector(Boolean, Int32)`

- `Void _InitIfNot()`

- `Void _RenderNodeInfo(RL03TotemBuffMapNodeViewModel, RoguelikeDungeonNode, Boolean)`

- `Void _RenderCurves(RoguelikeDungeonNode)`

- `Void _DealWithSingleSelectable(Boolean)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffMapNodeView : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_BUFF_COUNT; // 0x0
	private RoguelikeNodeViewData _viewData; // 0x18
	private UIAtlasImage _imgBkg; // 0x20
	private UIAtlasImage _imgCantReachBkg; // 0x28
	private Image _imgIcon; // 0x30
	private Graphic _graphicBoss; // 0x38
	private UIAtlasImage _imgCurrent; // 0x40
	private List`1 _curves; // 0x48
	private List`1 _fromConnectors; // 0x50
	private List`1 _toConnectors; // 0x58
	private GameObject _verticalLine; // 0x60
	private Graphic _graphicVerticalLine; // 0x68
	private CanvasGroup _canvasGroupSingleSelect; // 0x70
	private CanvasGroup _canvasGroupMultiSelect; // 0x78
	private Button _btnNode; // 0x80
	private Color _colorSelectableIcon; // 0x88
	private Color _colorNormalIcon; // 0x98
	private Color _colorReachableCurve; // 0xa8
	private Color _colorCantReachCurve; // 0xb8
	private Color _colorNormalBoss; // 0xc8
	private Color _colorFinalBoss; // 0xd8
	private RectTransform _rectTransformBuffNode; // 0xe8
	private Single _buffNodeStep; // 0xf0
	private UIAnimationLocation _singleSelectableAnim; // 0xf8
	private Action`2 <onNodeClicked>k__BackingField; // 0x108
	private RoguelikeDungeonNode m_node; // 0x110
	private Boolean m_isInited; // 0x118
	private Tween m_singleSelectableTween; // 0x120
	private FadeSwitchTween m_singleSelectTween; // 0x128
	private FadeSwitchTween m_multiSelectTween; // 0x130
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_GetCurve; // 0x18
	private static DelegateBridge __Hotfix0_GetConnector; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__RenderNodeInfo; // 0x30
	private static DelegateBridge __Hotfix0__RenderCurves; // 0x38
	private static DelegateBridge __Hotfix0__DealWithSingleSelectable; // 0x40
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`2 onNodeClicked { get; set; }

	// RVA: 0x2ba8b60 VA: 0x75951c0b60
	private Action`2 get_onNodeClicked() { }
	// RVA: 0x2ba8bc8 VA: 0x75951c0bc8
	public Void set_onNodeClicked(Action`2 value) { }
	// RVA: 0x2ba8c4c VA: 0x75951c0c4c
	public Void Render(RL03TotemBuffMapNodeViewModel nodeViewModel, Boolean hasNodeSelected) { }
	// RVA: 0x2ba94a0 VA: 0x75951c14a0
	public RoguelikeCurve GetCurve(Int32 index) { }
	// RVA: 0x2ba957c VA: 0x75951c157c
	public RectTransform GetConnector(Boolean isFromConnector, Int32 index) { }
	// RVA: 0x2ba8d14 VA: 0x75951c0d14
	private Void _InitIfNot() { }
	// RVA: 0x2ba8e90 VA: 0x75951c0e90
	private Void _RenderNodeInfo(RL03TotemBuffMapNodeViewModel nodeViewModel, RoguelikeDungeonNode node, Boolean hasNodeSelected) { }
	// RVA: 0x2ba9680 VA: 0x75951c1680
	private Void _RenderCurves(RoguelikeDungeonNode node) { }
	// RVA: 0x2ba99c0 VA: 0x75951c19c0
	private Void _DealWithSingleSelectable(Boolean needShow) { }
	// RVA: 0x2ba9ad8 VA: 0x75951c1ad8
	public Void EventOnClick() { }
	// RVA: 0x2ba9b88 VA: 0x75951c1b88
	public Void .ctor() { }
}
```