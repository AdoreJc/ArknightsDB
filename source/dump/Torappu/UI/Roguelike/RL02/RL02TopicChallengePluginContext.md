# RL02TopicChallengePluginContext

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RL02TopicChallengeToggleGroup _topicChallengeTogglePrefab`

- `RL02TopicChallengeGroup _topicChallengeGroupPrefab`

- `RL02TopicChallengePluginModel m_viewModel`


## Methods

- `RoguelikeTopicChallengeGroup <>xLuaBaseProxy_get_topicChallengeGroupPrefab()`

- `Void <>xLuaBaseProxy_LoadData(RoguelikeTopicChallengeModeViewModel)`

- `Void <>xLuaBaseProxy_UpdateData(RoguelikeTopicChallengeModeViewModel)`

- `Int32 <>xLuaBaseProxy_GetSwitchPageCountByCurPageIndex(Int32)`

- `Int32 <>xLuaBaseProxy_GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel)`

- `Boolean <>xLuaBaseProxy_CheckIfNeedRefreshAllCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02TopicChallengePluginContext : RoguelikeTopicChallengePluginContext
{
	private RL02TopicChallengeToggleGroup _topicChallengeTogglePrefab; // 0x18
	private RL02TopicChallengeGroup _topicChallengeGroupPrefab; // 0x20
	private RL02TopicChallengePluginModel m_viewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_topicChallengeToggleGroupPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_topicChallengeGroupPrefab; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0_get_challengeGroupCountListDic; // 0x20
	private static DelegateBridge __Hotfix0_GetSwitchPageCountByCurPageIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetCurrChallengeGroupId; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfNeedRefreshAllCard; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override RoguelikeTopicChallengeToggleGroup topicChallengeToggleGroupPrefab { get; }
	public override RoguelikeTopicChallengeGroup topicChallengeGroupPrefab { get; }
	public override ListDict`2 challengeGroupCountListDic { get; }

	// RVA: 0x2b5a6e4 VA: 0x75951726e4
	public override RoguelikeTopicChallengeToggleGroup get_topicChallengeToggleGroupPrefab() { }
	// RVA: 0x2b5a74c VA: 0x759517274c
	public override RoguelikeTopicChallengeGroup get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b5a7b4 VA: 0x75951727b4
	public override Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b5af30 VA: 0x7595172f30
	public override Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b5b1a0 VA: 0x75951731a0
	public override ListDict`2 get_challengeGroupCountListDic() { }
	// RVA: 0x2b5b214 VA: 0x7595173214
	public override Int32 GetSwitchPageCountByCurPageIndex(Int32 curPageIndex) { }
	// RVA: 0x2b5b464 VA: 0x7595173464
	public override Int32 GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel modeViewModel) { }
	// RVA: 0x2b5b580 VA: 0x7595173580
	public override Boolean CheckIfNeedRefreshAllCard() { }
	// RVA: 0x2b5b8d0 VA: 0x75951738d0
	public Void .ctor() { }
	// RVA: 0x2b5ba90 VA: 0x7595173a90
	private RoguelikeTopicChallengeGroup <>xLuaBaseProxy_get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b5ba98 VA: 0x7595173a98
	private Void <>xLuaBaseProxy_LoadData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b5baa0 VA: 0x7595173aa0
	private Void <>xLuaBaseProxy_UpdateData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b5baa8 VA: 0x7595173aa8
	private ListDict`2 <>xLuaBaseProxy_get_challengeGroupCountListDic() { }
	// RVA: 0x2b5bab0 VA: 0x7595173ab0
	private Int32 <>xLuaBaseProxy_GetSwitchPageCountByCurPageIndex(Int32 P0) { }
	// RVA: 0x2b5bab8 VA: 0x7595173ab8
	private Int32 <>xLuaBaseProxy_GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b5bac0 VA: 0x7595173ac0
	private Boolean <>xLuaBaseProxy_CheckIfNeedRefreshAllCard() { }
}
```