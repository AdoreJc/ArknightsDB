# SandboxV2AdminMainScienceView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainScienceNodeGroupView _nodeGroupView`

- `SandboxV2AdminMainScienceLineGroupView _lineGroupView`

- `CanvasGroup _contentGroup`

- `RectTransform _rectScrollContent`

- `UIWrappedScrollRect _scrollRect`

- `Single _fadeDuration`

- `Ease _fadeEase`

- `SandboxV2AdminMainSciencePanelModelProperty m_cachedProp`

- `SandboxV2AdminMainScienceType m_cachedType`

- `String m_cachedNodeId`

- `Tweener m_cacheTween`


## Methods

- `Void _InitScrollContent(Single)`

- `Void _ShowContent()`

- `Void _EventOnNodeSelect(String)`

- `Void _RenderContent(SandboxV2AdminMainSciencePanelModel)`

- `Void CleanSelect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceView : SandboxV2AdminMainContentViewBase`1
{
	private SandboxV2AdminMainScienceNodeGroupView _nodeGroupView; // 0x38
	private SandboxV2AdminMainScienceLineGroupView _lineGroupView; // 0x40
	private CanvasGroup _contentGroup; // 0x48
	private RectTransform _rectScrollContent; // 0x50
	private UIWrappedScrollRect _scrollRect; // 0x58
	private Single _fadeDuration; // 0x60
	private Ease _fadeEase; // 0x64
	private SandboxV2AdminMainSciencePanelModelProperty m_cachedProp; // 0x68
	private SandboxV2AdminMainScienceType m_cachedType; // 0x70
	private String m_cachedNodeId; // 0x78
	private Tweener m_cacheTween; // 0x80
	private static readonly Single SCROLL_SPEED; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitScrollContent; // 0x10
	private static DelegateBridge __Hotfix0__ShowContent; // 0x18
	private static DelegateBridge __Hotfix0__EventOnNodeSelect; // 0x20
	private static DelegateBridge __Hotfix0__RenderContent; // 0x28
	private static DelegateBridge __Hotfix0_CleanSelect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x24e7bd8 VA: 0x7594affbd8
	public override Void OnValueChanged(SandboxV2AdminMainSciencePanelModelProperty property) { }
	// RVA: 0x24e7f5c VA: 0x7594afff5c
	private Void _InitScrollContent(Single xWidth) { }
	// RVA: 0x24e806c VA: 0x7594b0006c
	private Void _ShowContent() { }
	// RVA: 0x24e8274 VA: 0x7594b00274
	private Void _EventOnNodeSelect(String nodeId) { }
	// RVA: 0x24e7df0 VA: 0x7594affdf0
	private Void _RenderContent(SandboxV2AdminMainSciencePanelModel viewModel) { }
	// RVA: 0x24e8360 VA: 0x7594b00360
	public Void CleanSelect() { }
	// RVA: 0x24e8434 VA: 0x7594b00434
	public Void .ctor() { }
	// RVA: 0x24e8510 VA: 0x7594b00510
	private static Void .cctor() { }
}
```