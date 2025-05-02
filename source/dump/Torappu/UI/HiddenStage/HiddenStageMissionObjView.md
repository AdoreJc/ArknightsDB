# HiddenStageMissionObjView

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `GameObject _panelComplete`

- `GameObject _objLock`

- `GameObject _objUnlocked`

- `GameObject _panelRiddle`

- `Text _textRiddle`

- `Text _lockedDesc`

- `GameObject _lockInfoPanel`

- `GameObject _panelNotFinish`

- `Text _missionName`

- `Text _missionCode`

- `GameObject _switchBtn`

- `UIAnimationLocation _missionAnimLoc`

- `GameObject _panelDecode`

- `Text _missionDesc`

- `GameObject _panelToBattle`

- `AnimationWrapper _animWrapper`

- `Boolean m_inDecodePanel`

- `String m_missionStageId`

- `AnimationSwitchTween m_stateSwitchTween`

- `HiddenStageMissionViewModel m_cachedModel`


## Methods

- `Void RenderView(HiddenStageMissionViewModel, Int32)`

- `Void _RenderRiddle(HiddenStageMissionViewModel)`

- `Void _RenderDecode(HiddenStageMissionViewModel)`

- `Void EventOnSwitchPanel()`

- `Void _PlayDecodePanelAnim()`

- `Void _PlayRiddlePanelAnim()`

- `Void _RenderPanel()`

- `AnimationSwitchTween _EnsureSwitchTween()`

- `Void EventOnToBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageMissionObjView : MonoBehaviour, IHotfixable
{
	private GameObject _panelComplete; // 0x18
	private GameObject _objLock; // 0x20
	private GameObject _objUnlocked; // 0x28
	private GameObject _panelRiddle; // 0x30
	private Text _textRiddle; // 0x38
	private Text _lockedDesc; // 0x40
	private GameObject _lockInfoPanel; // 0x48
	private GameObject _panelNotFinish; // 0x50
	private Text _missionName; // 0x58
	private Text _missionCode; // 0x60
	private GameObject _switchBtn; // 0x68
	private UIAnimationLocation _missionAnimLoc; // 0x70
	private GameObject _panelDecode; // 0x80
	private Text _missionDesc; // 0x88
	private GameObject _panelToBattle; // 0x90
	private AnimationWrapper _animWrapper; // 0x98
	public Action`1 eventOnJumpToBattle; // 0xa0
	private const String ANIM_DECODE_PANEL; // 0x0
	private const String ANIM_RIDDLE_PANEL; // 0x0
	private Boolean m_inDecodePanel; // 0xa8
	private String m_missionStageId; // 0xb0
	private AnimationSwitchTween m_stateSwitchTween; // 0xb8
	private HiddenStageMissionViewModel m_cachedModel; // 0xc0
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__RenderRiddle; // 0x8
	private static DelegateBridge __Hotfix0__RenderDecode; // 0x10
	private static DelegateBridge __Hotfix0_EventOnSwitchPanel; // 0x18
	private static DelegateBridge __Hotfix0__PlayDecodePanelAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayRiddlePanelAnim; // 0x28
	private static DelegateBridge __Hotfix0__RenderPanel; // 0x30
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x38
	private static DelegateBridge __Hotfix0_EventOnToBattle; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x285bc94 VA: 0x7594e73c94
	public Void RenderView(HiddenStageMissionViewModel viewModel, Int32 position) { }
	// RVA: 0x285e694 VA: 0x7594e76694
	private Void _RenderRiddle(HiddenStageMissionViewModel viewModel) { }
	// RVA: 0x285e7b8 VA: 0x7594e767b8
	private Void _RenderDecode(HiddenStageMissionViewModel viewModel) { }
	// RVA: 0x285e884 VA: 0x7594e76884
	public Void EventOnSwitchPanel() { }
	// RVA: 0x285e8f8 VA: 0x7594e768f8
	private Void _PlayDecodePanelAnim() { }
	// RVA: 0x285e9c4 VA: 0x7594e769c4
	private Void _PlayRiddlePanelAnim() { }
	// RVA: 0x285e5e0 VA: 0x7594e765e0
	private Void _RenderPanel() { }
	// RVA: 0x285e4e4 VA: 0x7594e764e4
	private AnimationSwitchTween _EnsureSwitchTween() { }
	// RVA: 0x285ea90 VA: 0x7594e76a90
	public Void EventOnToBattle() { }
	// RVA: 0x285eb24 VA: 0x7594e76b24
	public Void .ctor() { }
}
```