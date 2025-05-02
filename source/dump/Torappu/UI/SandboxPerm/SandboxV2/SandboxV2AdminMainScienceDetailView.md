# SandboxV2AdminMainScienceDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _detailPanel`

- `Text _nodeName`

- `Text _nodeCode`

- `Image _nodeIcon`

- `Text _nodeDesc`

- `Button _developBtn`

- `Text _pointsCost`

- `Text _textBtn`

- `UIColorGraphic _btnGraphicGroup`

- `GameObject _finishedPanel`

- `UIColorGraphic _graphics`

- `UIAnimationLocation _detailAnimLoc`

- `Ease _animEase`

- `Color _developableTextColor`

- `Color _undevelopableTextColor`

- `Color _developableGraphicColor`

- `Color _undevelopableGraphicColor`

- `String m_cachedNodeId`

- `UIStateFinder m_finder`

- `SandboxV2AdminMainScienceItemViewModel m_cacheItemViewModel`

- `SandboxV2AdminMainSciencePanelModelProperty m_prop`

- `AnimationSwitchTween m_switchTw`


## Methods

- `Void _RefreshDetail()`

- `Void _HidePanel(Action)`

- `Void _ShowPanel()`

- `AnimationSwitchTween _EnsureSwitchTween()`

- `Void EventOnDevelop()`

- `Void EventOnHide()`

- `Void <_EnsureSwitchTween>b__27_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceDetailView : DataBinder`1
{
	private GameObject _detailPanel; // 0x20
	private Text _nodeName; // 0x28
	private Text _nodeCode; // 0x30
	private Image _nodeIcon; // 0x38
	private Text _nodeDesc; // 0x40
	private Button _developBtn; // 0x48
	private Text _pointsCost; // 0x50
	private Text _textBtn; // 0x58
	private UIColorGraphic _btnGraphicGroup; // 0x60
	private GameObject _finishedPanel; // 0x68
	private UIColorGraphic _graphics; // 0x70
	private UIAnimationLocation _detailAnimLoc; // 0x78
	private Ease _animEase; // 0x88
	private Color _developableTextColor; // 0x8c
	private Color _undevelopableTextColor; // 0x9c
	private Color _developableGraphicColor; // 0xac
	private Color _undevelopableGraphicColor; // 0xbc
	public Action`1 onNodeDevelop; // 0xd0
	private String m_cachedNodeId; // 0xd8
	private UIStateFinder m_finder; // 0xe0
	private SandboxV2AdminMainScienceItemViewModel m_cacheItemViewModel; // 0xf0
	private SandboxV2AdminMainSciencePanelModelProperty m_prop; // 0xf8
	private AnimationSwitchTween m_switchTw; // 0x100
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RefreshDetail; // 0x8
	private static DelegateBridge __Hotfix0__HidePanel; // 0x10
	private static DelegateBridge __Hotfix0__ShowPanel; // 0x18
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x20
	private static DelegateBridge __Hotfix0_EventOnDevelop; // 0x28
	private static DelegateBridge __Hotfix0_EventOnHide; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x24dd450 VA: 0x7594af5450
	public override Void OnValueChanged(SandboxV2AdminMainSciencePanelModelProperty property) { }
	// RVA: 0x24dd710 VA: 0x7594af5710
	private Void _RefreshDetail() { }
	// RVA: 0x24dd5a0 VA: 0x7594af55a0
	private Void _HidePanel(Action cb) { }
	// RVA: 0x24dda68 VA: 0x7594af5a68
	private Void _ShowPanel() { }
	// RVA: 0x24ddb64 VA: 0x7594af5b64
	private AnimationSwitchTween _EnsureSwitchTween() { }
	// RVA: 0x24ddcd0 VA: 0x7594af5cd0
	public Void EventOnDevelop() { }
	// RVA: 0x24dde5c VA: 0x7594af5e5c
	public Void EventOnHide() { }
	// RVA: 0x24ddfd0 VA: 0x7594af5fd0
	public Void .ctor() { }
	// RVA: 0x24de060 VA: 0x7594af6060
	private Void <_EnsureSwitchTween>b__27_0() { }
}
```