# RL04TopicChallengePluginContext

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04TopicChallengeToggleGroup _topicChallengeTogglePrefab`

- `RL04TopicChallengeGroup _topicChallengeGroupPrefab`

- `RL04TopicChallengePluginModel m_viewModel`


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
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04TopicChallengePluginContext : RoguelikeTopicChallengePluginContext
{
	private RL04TopicChallengeToggleGroup _topicChallengeTogglePrefab; // 0x18
	private RL04TopicChallengeGroup _topicChallengeGroupPrefab; // 0x20
	private RL04TopicChallengePluginModel m_viewModel; // 0x28
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

	// RVA: 0x2b0de80 VA: 0x7595125e80
	public override RoguelikeTopicChallengeToggleGroup get_topicChallengeToggleGroupPrefab() { }
	// RVA: 0x2b0dee8 VA: 0x7595125ee8
	public override RoguelikeTopicChallengeGroup get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b0df50 VA: 0x7595125f50
	public override Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b0dfdc VA: 0x7595125fdc
	public override Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b0e068 VA: 0x7595126068
	public override ListDict`2 get_challengeGroupCountListDic() { }
	// RVA: 0x2b0e0dc VA: 0x75951260dc
	public override Int32 GetSwitchPageCountByCurPageIndex(Int32 curPageIndex) { }
	// RVA: 0x2b0e168 VA: 0x7595126168
	public override Int32 GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel modeViewModel) { }
	// RVA: 0x2b0e284 VA: 0x7595126284
	public override Boolean CheckIfNeedRefreshAllCard() { }
	// RVA: 0x2b0e2f8 VA: 0x75951262f8
	public Void .ctor() { }
	// RVA: 0x2b0e3a8 VA: 0x75951263a8
	private RoguelikeTopicChallengeGroup <>xLuaBaseProxy_get_topicChallengeGroupPrefab() { }
	// RVA: 0x2b0e3b0 VA: 0x75951263b0
	private Void <>xLuaBaseProxy_LoadData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b0e3b8 VA: 0x75951263b8
	private Void <>xLuaBaseProxy_UpdateData(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b0e3c0 VA: 0x75951263c0
	private ListDict`2 <>xLuaBaseProxy_get_challengeGroupCountListDic() { }
	// RVA: 0x2b0e3c8 VA: 0x75951263c8
	private Int32 <>xLuaBaseProxy_GetSwitchPageCountByCurPageIndex(Int32 P0) { }
	// RVA: 0x2b0e3d0 VA: 0x75951263d0
	private Int32 <>xLuaBaseProxy_GetCurrChallengeGroupId(RoguelikeTopicChallengeModeViewModel P0) { }
	// RVA: 0x2b0e3d8 VA: 0x75951263d8
	private Boolean <>xLuaBaseProxy_CheckIfNeedRefreshAllCard() { }
}
```