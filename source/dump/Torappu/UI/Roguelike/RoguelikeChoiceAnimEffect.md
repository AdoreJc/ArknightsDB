# RoguelikeChoiceAnimEffect

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _leaveAnim`

- `GameObject _effectObject`

- `Boolean m_isActive`

- `Tween m_playingTween`


## Methods

- `Void _OnLeaveAnimEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceAnimEffect : RoguelikeChoiceEffectBase, IHotfixable
{
	private UIAnimationLocation _enterAnim; // 0x28
	private UIAnimationLocation _leaveAnim; // 0x38
	private GameObject _effectObject; // 0x48
	private Boolean m_isActive; // 0x50
	private Tween m_playingTween; // 0x58
	private static DelegateBridge __Hotfix0_SetChoiceBgEffectVisible; // 0x0
	private static DelegateBridge __Hotfix0__OnLeaveAnimEnd; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29ea354 VA: 0x7595002354
	public override Void SetChoiceBgEffectVisible(Boolean isActive, String assetName) { }
	// RVA: 0x29ea520 VA: 0x7595002520
	private Void _OnLeaveAnimEnd() { }
	// RVA: 0x29ea590 VA: 0x7595002590
	public Void .ctor() { }
}
```