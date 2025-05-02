# RoguelikeCommonOuterBuffNormalNodeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _unlockLightAnim`

- `UIAnimationLocation _activeAnim`

- `UIAnimationLocation _activeLightAnim`

- `Single _activeAnimDelay`

- `Single _unlockAnimDelay`

- `Boolean m_isInited`

- `String m_buffId`

- `Boolean m_isUnlock`

- `Boolean m_isActive`

- `Tween m_nodeTween`

- `Tween m_lightTween`

- `AnimationSwitchTween m_selectSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _InitNodeStatus(RoguelikeCommonOuterBuffNormalNodeViewModel)`

- `Void _InitLightStatus(RoguelikeCommonOuterBuffNormalNodeViewModel)`

- `Void _PlayActiveAnim(RoguelikeCommonOuterBuffNormalNodeViewModel)`

- `Void _PlayUnlockAnim(RoguelikeCommonOuterBuffNormalNodeViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffNormalNodeView : RoguelikeCommonOuterBuffNodeBase
{
	private UIAnimationLocation _selectAnim; // 0x60
	private UIAnimationLocation _unlockLightAnim; // 0x70
	private UIAnimationLocation _activeAnim; // 0x80
	private UIAnimationLocation _activeLightAnim; // 0x90
	private Single _activeAnimDelay; // 0xa0
	private Single _unlockAnimDelay; // 0xa4
	private Boolean m_isInited; // 0xa8
	private String m_buffId; // 0xb0
	private Boolean m_isUnlock; // 0xb8
	private Boolean m_isActive; // 0xb9
	private Tween m_nodeTween; // 0xc0
	private Tween m_lightTween; // 0xc8
	private AnimationSwitchTween m_selectSwitchTween; // 0xd0
	private static DelegateBridge __Hotfix0_GetType; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__InitNodeStatus; // 0x20
	private static DelegateBridge __Hotfix0__InitLightStatus; // 0x28
	private static DelegateBridge __Hotfix0__PlayActiveAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayUnlockAnim; // 0x38
	private static DelegateBridge __Hotfix0_OnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x26627b0 VA: 0x7594c7a7b0
	public override RoguelikeCommonOuterBuffViewType GetType() { }
	// RVA: 0x2662814 VA: 0x7594c7a814
	protected override Void OnInit(RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x2662ce0 VA: 0x7594c7ace0
	protected override Void OnRender(String selectedBuffId, RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x2662998 VA: 0x7594c7a998
	private Void _InitIfNot() { }
	// RVA: 0x2662a6c VA: 0x7594c7aa6c
	private Void _InitNodeStatus(RoguelikeCommonOuterBuffNormalNodeViewModel model) { }
	// RVA: 0x2662b84 VA: 0x7594c7ab84
	private Void _InitLightStatus(RoguelikeCommonOuterBuffNormalNodeViewModel model) { }
	// RVA: 0x2662fc8 VA: 0x7594c7afc8
	private Void _PlayActiveAnim(RoguelikeCommonOuterBuffNormalNodeViewModel model) { }
	// RVA: 0x2662e30 VA: 0x7594c7ae30
	private Void _PlayUnlockAnim(RoguelikeCommonOuterBuffNormalNodeViewModel model) { }
	// RVA: 0x26631ec VA: 0x7594c7b1ec
	public Void OnClick() { }
	// RVA: 0x2663274 VA: 0x7594c7b274
	public Void .ctor() { }
}
```