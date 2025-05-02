# RL03TopicChallengeToggleGroup

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RoguelikeTopicToggleDotWithLock _toggleDotPrefab`

- `GameObject _toggleLinePrefab`


## Methods

- `ROGUELIKE_TOPIC_TOGGLE_DOT_STATE _TryGetToggleDotState(PlayerRoguelikeChallengeStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TopicChallengeToggleGroup : RoguelikeTopicChallengeToggleGroup
{
	private RoguelikeTopicToggleDotWithLock _toggleDotPrefab; // 0x18
	private GameObject _toggleLinePrefab; // 0x20
	private List`1 m_dots; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_RefreshToggles; // 0x8
	private static DelegateBridge __Hotfix0__TryGetToggleDotState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b8fd28 VA: 0x75951a7d28
	public override Void Init(RoguelikeTopicChallengeModeViewModel challengeModeViewModel, RoguelikeTopicChallengePluginContext pluginContext) { }
	// RVA: 0x2b902d0 VA: 0x75951a82d0
	public override Void RefreshToggles(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b904cc VA: 0x75951a84cc
	private ROGUELIKE_TOPIC_TOGGLE_DOT_STATE _TryGetToggleDotState(PlayerRoguelikeChallengeStatus challengeStatus) { }
	// RVA: 0x2b90554 VA: 0x75951a8554
	public Void .ctor() { }
}
```