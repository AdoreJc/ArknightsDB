# RL02TopicChallengeToggleGroup

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RoguelikeTopicToggleDotWithLock _toggleDotPrefab`

- `GameObject _toggleLinePrefab`


## Methods

- `ROGUELIKE_TOPIC_TOGGLE_DOT_STATE _TryGetToggleDotState(PlayerRoguelikeChallengeStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02TopicChallengeToggleGroup : RoguelikeTopicChallengeToggleGroup
{
	private RoguelikeTopicToggleDotWithLock _toggleDotPrefab; // 0x18
	private GameObject _toggleLinePrefab; // 0x20
	private List`1 m_dots; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_RefreshToggles; // 0x8
	private static DelegateBridge __Hotfix0__TryGetToggleDotState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b5c2fc VA: 0x75951742fc
	public override Void Init(RoguelikeTopicChallengeModeViewModel challengeModeViewModel, RoguelikeTopicChallengePluginContext pluginContext) { }
	// RVA: 0x2b5c8a4 VA: 0x75951748a4
	public override Void RefreshToggles(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b5caa0 VA: 0x7595174aa0
	private ROGUELIKE_TOPIC_TOGGLE_DOT_STATE _TryGetToggleDotState(PlayerRoguelikeChallengeStatus challengeStatus) { }
	// RVA: 0x2b5cb28 VA: 0x7595174b28
	public Void .ctor() { }
}
```