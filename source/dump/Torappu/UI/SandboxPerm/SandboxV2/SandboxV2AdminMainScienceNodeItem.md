# SandboxV2AdminMainScienceNodeItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _selfRect`

- `CanvasGroup _canvasSelect`

- `GameObject _objDevelopCanLight`

- `CanvasGroup _canvasDevelopCanLight`

- `Image _imgIcon`

- `UIAtlasImage _imgBg`

- `Text _txtNodeTitle`

- `GameObject _objIconGrayMask`

- `UIAnimationLocation _nodeSelectAnim`

- `AnimationWrapper _nodeLightOnAnimWrapper`

- `Single _nodeGlowDuration`

- `Single _nodeGlowAlpha`

- `Boolean m_hasInited`

- `String m_cachedNodeId`

- `SANDBOX_DEVELOP_NODE_LIGHT_STATE m_cachedNodeLightState`

- `AnimationSwitchTween m_selectSwitchTween`

- `GlowingLoopTween m_developGlowingTween`

- `Tweener m_glowloopTween`

- `UIStateFinder m_finder`


## Methods

- `Void set_eventOnNodeClick(Action`1)`

- `Void Render(SandboxV2AdminMainScienceItemViewModel, Boolean, String)`

- `Void _InitIfNot(Boolean)`

- `Void _SetBaseInfo(SandboxV2AdminMainScienceItemViewModel, String)`

- `Void _TryPlayLightOnAnim(SANDBOX_DEVELOP_NODE_LIGHT_STATE)`

- `Void _SetInfoByState(SANDBOX_DEVELOP_NODE_LIGHT_STATE)`

- `Void _PlayNodeLightOnAnim()`

- `Void _ResetNodeAnim()`

- `AnimationSwitchTween _EnsureSwitchTween()`

- `Tweener _EnsureGlowLoop()`

- `Void _StopGlowloop()`

- `Void OnNodeClick()`

- `Void <_EnsureSwitchTween>b__34_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceNodeItem : MonoBehaviour, IHotfixable
{
	private static readonly Color NODE_BG_GRAY_COL; // 0x0
	private static readonly Color NODE_ICON_GRAY_COL; // 0x10
	private const String NODE_LIGHT_ON_ANIM_PARAM; // 0x0
	private RectTransform _selfRect; // 0x18
	private CanvasGroup _canvasSelect; // 0x20
	private GameObject _objDevelopCanLight; // 0x28
	private CanvasGroup _canvasDevelopCanLight; // 0x30
	private Image _imgIcon; // 0x38
	private UIAtlasImage _imgBg; // 0x40
	private Text _txtNodeTitle; // 0x48
	private GameObject _objIconGrayMask; // 0x50
	private UIAnimationLocation _nodeSelectAnim; // 0x58
	private AnimationWrapper _nodeLightOnAnimWrapper; // 0x68
	private Single _nodeGlowDuration; // 0x70
	private Single _nodeGlowAlpha; // 0x74
	private Boolean m_hasInited; // 0x78
	private String m_cachedNodeId; // 0x80
	private SANDBOX_DEVELOP_NODE_LIGHT_STATE m_cachedNodeLightState; // 0x88
	private AnimationSwitchTween m_selectSwitchTween; // 0x90
	private GlowingLoopTween m_developGlowingTween; // 0x98
	private Tweener m_glowloopTween; // 0xa0
	private UIStateFinder m_finder; // 0xa8
	private Action`1 <eventOnNodeClick>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_eventOnNodeClick; // 0x20
	private static DelegateBridge __Hotfix0_set_eventOnNodeClick; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__SetBaseInfo; // 0x40
	private static DelegateBridge __Hotfix0__TryPlayLightOnAnim; // 0x48
	private static DelegateBridge __Hotfix0__SetInfoByState; // 0x50
	private static DelegateBridge __Hotfix0__PlayNodeLightOnAnim; // 0x58
	private static DelegateBridge __Hotfix0__ResetNodeAnim; // 0x60
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x68
	private static DelegateBridge __Hotfix0__EnsureGlowLoop; // 0x70
	private static DelegateBridge __Hotfix0__StopGlowloop; // 0x78
	private static DelegateBridge __Hotfix0_OnNodeClick; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	private Action`1 eventOnNodeClick { get; set; }

	// RVA: 0x24e12b4 VA: 0x7594af92b4
	private Action`1 get_eventOnNodeClick() { }
	// RVA: 0x24e0ee0 VA: 0x7594af8ee0
	public Void set_eventOnNodeClick(Action`1 value) { }
	// RVA: 0x24e0f74 VA: 0x7594af8f74
	public Void Render(SandboxV2AdminMainScienceItemViewModel itemViewModel, Boolean isSelecting, String topicId) { }
	// RVA: 0x24e132c VA: 0x7594af932c
	private Void _InitIfNot(Boolean forceRefresh) { }
	// RVA: 0x24e13dc VA: 0x7594af93dc
	private Void _SetBaseInfo(SandboxV2AdminMainScienceItemViewModel itemViewModel, String topicId) { }
	// RVA: 0x24e16cc VA: 0x7594af96cc
	private Void _TryPlayLightOnAnim(SANDBOX_DEVELOP_NODE_LIGHT_STATE lightState) { }
	// RVA: 0x24e1774 VA: 0x7594af9774
	private Void _SetInfoByState(SANDBOX_DEVELOP_NODE_LIGHT_STATE lightState) { }
	// RVA: 0x24e1a38 VA: 0x7594af9a38
	private Void _PlayNodeLightOnAnim() { }
	// RVA: 0x24e1954 VA: 0x7594af9954
	private Void _ResetNodeAnim() { }
	// RVA: 0x24e1540 VA: 0x7594af9540
	private AnimationSwitchTween _EnsureSwitchTween() { }
	// RVA: 0x24e1b30 VA: 0x7594af9b30
	private Tweener _EnsureGlowLoop() { }
	// RVA: 0x24e1c44 VA: 0x7594af9c44
	private Void _StopGlowloop() { }
	// RVA: 0x24e1cd8 VA: 0x7594af9cd8
	public Void OnNodeClick() { }
	// RVA: 0x24e1d88 VA: 0x7594af9d88
	public Void .ctor() { }
	// RVA: 0x24e1e4c VA: 0x7594af9e4c
	private static Void .cctor() { }
	// RVA: 0x24e1eb0 VA: 0x7594af9eb0
	private Void <_EnsureSwitchTween>b__34_0() { }
}
```