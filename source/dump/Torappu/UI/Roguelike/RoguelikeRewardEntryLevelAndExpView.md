# RoguelikeRewardEntryLevelAndExpView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _currentExp`

- `Text _currentLevel`

- `CanvasGroup _addExpPart`

- `Text _addExp`

- `CanvasGroup _levelUpPart`

- `GameObject _levelUpEffect`

- `RoguelikeRewardEntryPopListAdapter _popListAdapter`

- `AnimationWrapper _levelUpAnimationWrapper`

- `Tween m_effectTween`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardEntryLevelAndExpView : RLRewardEntryLevelPartView
{
	protected const Single CONST_ALPHA; // 0x0
	protected Text _currentExp; // 0x18
	protected Text _currentLevel; // 0x20
	protected CanvasGroup _addExpPart; // 0x28
	protected Text _addExp; // 0x30
	protected CanvasGroup _levelUpPart; // 0x38
	protected GameObject _levelUpEffect; // 0x40
	protected RoguelikeRewardEntryPopListAdapter _popListAdapter; // 0x48
	protected AnimationWrapper _levelUpAnimationWrapper; // 0x50
	protected Tween m_effectTween; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DealWithAnimation; // 0x8
	private static DelegateBridge __Hotfix0_get_stateRelatedEffect; // 0x10
	private static DelegateBridge __Hotfix0__RenderExp; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override GameObject stateRelatedEffect { get; }

	// RVA: 0x2a952b0 VA: 0x75950ad2b0
	public override Void Init(RoguelikeRewardEarnViewModel earnViewModel) { }
	// RVA: 0x2a953f4 VA: 0x75950ad3f4
	public override IEnumerator DealWithAnimation(RoguelikeRewardEarnViewModel earnViewModel, String stageId, String topicId) { }
	// RVA: 0x2a95518 VA: 0x75950ad518
	public override GameObject get_stateRelatedEffect() { }
	// RVA: 0x2a95580 VA: 0x75950ad580
	protected virtual Void _RenderExp(Int32 maxLevel, Int32 level, Int32 exp, String topicId, RoguelikeRewardEarnViewModel earnViewModel) { }
	// RVA: 0x2a95720 VA: 0x75950ad720
	public Void .ctor() { }
}
```