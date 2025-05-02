# DeepSeaRPTechTreeNodeView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `GameObject _objNormPart`

- `Text _txtTitleNorm`

- `Text _txtDesc`

- `UIAnimationLocation _toggleAnim`

- `Text _txtNode1Name`

- `Text _txtNode2Name`

- `GameObject _objActivePart`

- `Text _txtTitleActive`

- `GameObject _objSetPart`

- `Text _txtTitleSet`

- `GameObject _objLockedPart`

- `Text _txtLockInfo`

- `GameObject _objLineUnlock`

- `GameObject _objLineLocked`

- `CanvasGroup _canvasTreeOn`

- `CanvasGroup _canvasTreeSet`

- `GameObject _objTreeOn1`

- `GameObject _objTreeOn2`

- `GameObject _objTreeSet`

- `GameObject _objTreeActive`

- `GameObject _objTreeLocked`

- `AnimationSwitchTween m_toggleSwitch`

- `String m_techId`

- `Boolean m_hasInited`

- `FadeSwitchTween m_tweenTreeOn`

- `FadeSwitchTween m_tweenTreeSet`


## Methods

- `Void set_onUnsetClicked(Action`1)`

- `Void set_onActiveClicked(Action`1)`

- `Void set_onSetClicked(Action`1)`

- `Void set_onNodeToggleClicked(Action`1)`

- `Void Render(DeepSeaRPTechTreeNodeModel)`

- `Void _InitIfNot(Boolean)`

- `Void EventOnUnsetClick()`

- `Void EventOnActiveClick()`

- `Void EventOnSetClick()`

- `Void EventOnNodeToggleClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechTreeNodeView : MonoBehaviour, IHotfixable
{
	private GameObject _objNormPart; // 0x18
	private Text _txtTitleNorm; // 0x20
	private Text _txtDesc; // 0x28
	private UIAnimationLocation _toggleAnim; // 0x30
	private Text _txtNode1Name; // 0x40
	private Text _txtNode2Name; // 0x48
	private GameObject _objActivePart; // 0x50
	private Text _txtTitleActive; // 0x58
	private GameObject _objSetPart; // 0x60
	private Text _txtTitleSet; // 0x68
	private GameObject _objLockedPart; // 0x70
	private Text _txtLockInfo; // 0x78
	private GameObject _objLineUnlock; // 0x80
	private GameObject _objLineLocked; // 0x88
	private CanvasGroup _canvasTreeOn; // 0x90
	private CanvasGroup _canvasTreeSet; // 0x98
	private GameObject _objTreeOn1; // 0xa0
	private GameObject _objTreeOn2; // 0xa8
	private GameObject _objTreeSet; // 0xb0
	private GameObject _objTreeActive; // 0xb8
	private GameObject _objTreeLocked; // 0xc0
	private AnimationSwitchTween m_toggleSwitch; // 0xc8
	private Action`1 <onUnsetClicked>k__BackingField; // 0xd0
	private Action`1 <onActiveClicked>k__BackingField; // 0xd8
	private Action`1 <onSetClicked>k__BackingField; // 0xe0
	private Action`1 <onNodeToggleClicked>k__BackingField; // 0xe8
	private String m_techId; // 0xf0
	private Boolean m_hasInited; // 0xf8
	private FadeSwitchTween m_tweenTreeOn; // 0x100
	private FadeSwitchTween m_tweenTreeSet; // 0x108
	private const Single TREE_TWEEN_DUR; // 0x0
	private static DelegateBridge __Hotfix0_get_onUnsetClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onUnsetClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onActiveClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onActiveClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onSetClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onSetClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_onNodeToggleClicked; // 0x30
	private static DelegateBridge __Hotfix0_set_onNodeToggleClicked; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0_EventOnUnsetClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnActiveClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnSetClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnNodeToggleClick; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Action`1 onUnsetClicked { get; set; }
	private Action`1 onActiveClicked { get; set; }
	private Action`1 onSetClicked { get; set; }
	private Action`1 onNodeToggleClicked { get; set; }

	// RVA: 0x29e0be8 VA: 0x7594ff8be8
	private Action`1 get_onUnsetClicked() { }
	// RVA: 0x29e0c50 VA: 0x7594ff8c50
	public Void set_onUnsetClicked(Action`1 value) { }
	// RVA: 0x29e0cd4 VA: 0x7594ff8cd4
	private Action`1 get_onActiveClicked() { }
	// RVA: 0x29e0d3c VA: 0x7594ff8d3c
	public Void set_onActiveClicked(Action`1 value) { }
	// RVA: 0x29e0dc0 VA: 0x7594ff8dc0
	private Action`1 get_onSetClicked() { }
	// RVA: 0x29e0e28 VA: 0x7594ff8e28
	public Void set_onSetClicked(Action`1 value) { }
	// RVA: 0x29e0eac VA: 0x7594ff8eac
	private Action`1 get_onNodeToggleClicked() { }
	// RVA: 0x29e0f14 VA: 0x7594ff8f14
	public Void set_onNodeToggleClicked(Action`1 value) { }
	// RVA: 0x29e0f98 VA: 0x7594ff8f98
	public Void Render(DeepSeaRPTechTreeNodeModel model) { }
	// RVA: 0x29e1504 VA: 0x7594ff9504
	private Void _InitIfNot(Boolean togglePlay) { }
	// RVA: 0x29e18f4 VA: 0x7594ff98f4
	public Void EventOnUnsetClick() { }
	// RVA: 0x29e1994 VA: 0x7594ff9994
	public Void EventOnActiveClick() { }
	// RVA: 0x29e1a34 VA: 0x7594ff9a34
	public Void EventOnSetClick() { }
	// RVA: 0x29e1ad4 VA: 0x7594ff9ad4
	public Void EventOnNodeToggleClick() { }
	// RVA: 0x29e1b74 VA: 0x7594ff9b74
	public Void .ctor() { }
}
```