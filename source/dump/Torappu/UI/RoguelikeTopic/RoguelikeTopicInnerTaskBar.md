# RoguelikeTopicInnerTaskBar

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicInnerTaskBar : RoguelikeMenuBar
{
	private const Single TWEEN_DURATION; // 0x0
	private static readonly Type[] ENABLE_STATES; // 0x0
	private static DelegateBridge __Hotfix0_GenerateUISwitchTween; // 0x8
	private static DelegateBridge __Hotfix0_RefreshMenuBar; // 0x10
	private static DelegateBridge __Hotfix0_AchieveShowStatus; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2632b48 VA: 0x7594c4ab48
	protected override UISwitchTween GenerateUISwitchTween() { }
	// RVA: 0x2632c24 VA: 0x7594c4ac24
	protected override Void RefreshMenuBar(StateTransitionParam transitionParam, RoguelikeMenuAdapter topAdapter, Boolean fastMode) { }
	// RVA: 0x2632cc8 VA: 0x7594c4acc8
	protected override Boolean AchieveShowStatus(StateTransitionParam transitionParam, RoguelikeMenuAdapter topAdapter) { }
	// RVA: 0x2632dc8 VA: 0x7594c4adc8
	public Void .ctor() { }
	// RVA: 0x2632e48 VA: 0x7594c4ae48
	private static Void .cctor() { }
}
```