# SandboxV2EventChoiceView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Group _activeGroup`

- `GameObject _panelActive`

- `Group _inactiveGroup`

- `GameObject _panelInactive`

- `GameObject _panelSelectHotspot`

- `GameObject _panelConfirmHotspot`

- `Single _enterAnimIntervalDelay`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _selectedAnim`

- `UIAnimationLocation _loopAnim`

- `Button _selectHotspot`

- `Button _confirmHotspot`

- `Boolean m_isInited`

- `String m_cachedChoiceId`

- `Tween m_animTween`

- `Tween m_loopTween`

- `AnimationSwitchTween m_selectedTween`

- `UIStateFinder m_stateFinder`


## Properties

- `Boolean isPlayingEnterAnim`


## Methods

- `Boolean get_isPlayingEnterAnim()`

- `Void Render(Int32, SandboxV2EventChoiceViewModel, Boolean, Boolean, Boolean)`

- `Void _PlayAnimIfNeeded(Int32, Boolean)`

- `Void _InitIfNot()`

- `Void OnSelectAndConfirm()`

- `Void OnInactive()`

- `Void _TutorialOnly_TryRaiseAVGSignal()`

- `Void TutorialOnly_RegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EventChoiceView : MonoBehaviour, IHotfixable
{
	private Group _activeGroup; // 0x18
	private GameObject _panelActive; // 0x20
	private Group _inactiveGroup; // 0x28
	private GameObject _panelInactive; // 0x30
	private GameObject _panelSelectHotspot; // 0x38
	private GameObject _panelConfirmHotspot; // 0x40
	private Single _enterAnimIntervalDelay; // 0x48
	private UIAnimationLocation _enterAnim; // 0x50
	private UIAnimationLocation _selectedAnim; // 0x60
	private UIAnimationLocation _loopAnim; // 0x70
	private Button _selectHotspot; // 0x80
	private Button _confirmHotspot; // 0x88
	private Boolean m_isInited; // 0x90
	private String m_cachedChoiceId; // 0x98
	private Tween m_animTween; // 0xa0
	private Tween m_loopTween; // 0xa8
	private AnimationSwitchTween m_selectedTween; // 0xb0
	private UIStateFinder m_stateFinder; // 0xb8
	private static DelegateBridge __Hotfix0_get_isPlayingEnterAnim; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnimIfNeeded; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnSelectAndConfirm; // 0x20
	private static DelegateBridge __Hotfix0_OnInactive; // 0x28
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x30
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isPlayingEnterAnim { get; }

	// RVA: 0x255dc68 VA: 0x7594b75c68
	public Boolean get_isPlayingEnterAnim() { }
	// RVA: 0x255dce4 VA: 0x7594b75ce4
	public Void Render(Int32 index, SandboxV2EventChoiceViewModel viewModel, Boolean isSelected, Boolean playAnim, Boolean isEnter) { }
	// RVA: 0x255e1a0 VA: 0x7594b761a0
	private Void _PlayAnimIfNeeded(Int32 index, Boolean playAnim) { }
	// RVA: 0x255de9c VA: 0x7594b75e9c
	private Void _InitIfNot() { }
	// RVA: 0x255e320 VA: 0x7594b76320
	public Void OnSelectAndConfirm() { }
	// RVA: 0x255e428 VA: 0x7594b76428
	public Void OnInactive() { }
	// RVA: 0x255e53c VA: 0x7594b7653c
	private Void _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x255e62c VA: 0x7594b7662c
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x255e6f0 VA: 0x7594b766f0
	public Void .ctor() { }
}
```