# RoguelikeCommonOuterBuffDifficultyNodeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _activeAnim`

- `Single _animDelay`

- `Boolean m_isInited`

- `String m_buffId`

- `Boolean m_isActive`

- `Tween m_tween`

- `AnimationSwitchTween m_selectSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _PlayActiveAnim(RoguelikeCommonOuterBuffDifficultyNodeViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffDifficultyNodeView : RoguelikeCommonOuterBuffNodeBase
{
	private UIAnimationLocation _selectAnim; // 0x60
	private UIAnimationLocation _activeAnim; // 0x70
	private Single _animDelay; // 0x80
	private Boolean m_isInited; // 0x84
	private String m_buffId; // 0x88
	private Boolean m_isActive; // 0x90
	private Tween m_tween; // 0x98
	private AnimationSwitchTween m_selectSwitchTween; // 0xa0
	private static DelegateBridge __Hotfix0_GetType; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayActiveAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x26610fc VA: 0x7594c790fc
	public override RoguelikeCommonOuterBuffViewType GetType() { }
	// RVA: 0x2661164 VA: 0x7594c79164
	protected override Void OnInit(RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x266178c VA: 0x7594c7978c
	protected override Void OnRender(String selectedBuffId, RoguelikeCommonOuterBuffNodeBaseViewModel model) { }
	// RVA: 0x2661398 VA: 0x7594c79398
	private Void _InitIfNot() { }
	// RVA: 0x2661acc VA: 0x7594c79acc
	private Void _PlayActiveAnim(RoguelikeCommonOuterBuffDifficultyNodeViewModel model) { }
	// RVA: 0x2661c64 VA: 0x7594c79c64
	public Void OnClick() { }
	// RVA: 0x2661cec VA: 0x7594c79cec
	public Void .ctor() { }
}
```