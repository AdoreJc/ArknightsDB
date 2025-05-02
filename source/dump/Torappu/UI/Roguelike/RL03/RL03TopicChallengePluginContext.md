# RL03TopicChallengePluginContext

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03TopicChallengeToggleGroup _topicChallengeTogglePrefab`

- `RL03TopicChallengeGroup _topicChallengeGroupPrefab`

- `RL03TopicChallengePluginModel m_viewModel`


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
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TopicChallengePluginContext : RoguelikeTopicChallengePluginContext
{
	private RL03TopicChallengeToggleGroup _topicChallengeTogglePrefab; // 0x18
	private RL03TopicChallengeGroup _topicChallengeGroupPrefab; // 0x20
	private RL03TopicChallengePluginModel m_viewModel; // 0x28
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

	// RVA: 0x2b8e108 VA: 0x75951a6108
	public override RoguelikeTopicChallengeToggleGroup get_topicChallengeToggleGroupPrefab() { }
	// RVA: 0x2b8e170 VA: 0x75951a6170
	public override RoguelikeTopicChallengeGroup get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b8e1d8 VA: 0x75951a61d8
	public override Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b8e264 VA: 0x75951a6264
	public override Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b8e2f0 VA: 0x75951a62f0
	public override ListDict`2 get_challengeGroupCountListDic() { }
	// RVA: 0x2b8e364 VA: 0x75951a6364
	public override Int32 GetSwitchPageCountByCurPageIndex(Int32 curPageIndex) { }
	// RVA: 0x2b8e3f0 VA: 0x75951a63f0
	public override Int32 GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel modeViewModel) { }
	// RVA: 0x2b8e50c VA: 0x75951a650c
	public override Boolean CheckIfNeedRefreshAllCard() { }
	// RVA: 0x2b8e580 VA: 0x75951a6580
	public Void .ctor() { }
	// RVA: 0x2b8e630 VA: 0x75951a6630
	private RoguelikeTopicChallengeGroup <>xLuaBaseProxy_get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b8e638 VA: 0x75951a6638
	private Void <>xLuaBaseProxy_LoadData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b8e640 VA: 0x75951a6640
	private Void <>xLuaBaseProxy_UpdateData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b8e648 VA: 0x75951a6648
	private ListDict`2 <>xLuaBaseProxy_get_challengeGroupCountListDic() { }
	// RVA: 0x2b8e650 VA: 0x75951a6650
	private Int32 <>xLuaBaseProxy_GetSwitchPageCountByCurPageIndex(Int32 P0) { }
	// RVA: 0x2b8e658 VA: 0x75951a6658
	private Int32 <>xLuaBaseProxy_GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b8e660 VA: 0x75951a6660
	private Boolean <>xLuaBaseProxy_CheckIfNeedRefreshAllCard() { }
}
```