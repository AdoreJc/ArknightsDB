# RoguelikeRewardItemHolder

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _container`

- `AnimationWrapper _animationWrapper`

- `CanvasGroup _alphaHandler`

- `RoguelikeRewardItem m_cachedItem`

- `Boolean m_entryAnimPlayed`

- `UIIntEvent <onClickEvent>k__BackingField`


## Properties

- `UIIntEvent onClickEvent`

- `CanvasGroup alphaHandler`


## Methods

- `UIIntEvent get_onClickEvent()`

- `Void set_onClickEvent(UIIntEvent)`

- `CanvasGroup get_alphaHandler()`

- `Void ApplyAnimation()`

- `Void ToAnimationBegin()`

- `Void ToAnimationEnd()`

- `Void Render(RoguelikeRewardItemViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardItemHolder : MonoBehaviour, IHotfixable
{
	private RoguelikeRewardItem[] _rewardItemList; // 0x18
	private Transform _container; // 0x20
	private AnimationWrapper _animationWrapper; // 0x28
	private CanvasGroup _alphaHandler; // 0x30
	private RoguelikeRewardItem m_cachedItem; // 0x38
	private Boolean m_entryAnimPlayed; // 0x40
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x10
	private static DelegateBridge __Hotfix0_ApplyAnimation; // 0x18
	private static DelegateBridge __Hotfix0_ToAnimationBegin; // 0x20
	private static DelegateBridge __Hotfix0_ToAnimationEnd; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private UIIntEvent onClickEvent { get; set; }
	public CanvasGroup alphaHandler { get; }

	// RVA: 0x2a9a934 VA: 0x75950b2934
	private UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9a99c VA: 0x75950b299c
	public Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9aa20 VA: 0x75950b2a20
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x2a9aa88 VA: 0x75950b2a88
	public Void ApplyAnimation() { }
	// RVA: 0x2a9ab30 VA: 0x75950b2b30
	public Void ToAnimationBegin() { }
	// RVA: 0x2a9abbc VA: 0x75950b2bbc
	public Void ToAnimationEnd() { }
	// RVA: 0x2a9ac50 VA: 0x75950b2c50
	public Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2a9aef8 VA: 0x75950b2ef8
	public Void .ctor() { }
}
```