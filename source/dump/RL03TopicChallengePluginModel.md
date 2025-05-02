# RL03TopicChallengePluginModel

**Namespace:** ` `


## Methods

- `Void LoadData(RoguelikeTopicChallengeModeViewModel)`

- `Void UpdateData(RoguelikeTopicChallengeModeViewModel)`

- `Boolean CheckIfNeedRefreshAllCard()`

- `Int32 GetSwitchPageCountByCurPageIndex(Int32)`

- `Int32 _GetGroupFocusChallengeIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL03TopicChallengePluginModel : IHotfixable
{
	public ListDict`2 challengeGroupInfoListDic; // 0x10
	public ListDict`2 challengeGroupCountListDic; // 0x18
	private Dictionary`2 m_cachedChallengeStatus; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfNeedRefreshAllCard; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchPageCountByCurPageIndex; // 0x18
	private static DelegateBridge __Hotfix0__GetGroupFocusChallengeIndex; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b8eba4 VA: 0x75951a6ba4
	public Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b8f298 VA: 0x75951a7298
	public Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b8f474 VA: 0x75951a7474
	public Boolean CheckIfNeedRefreshAllCard() { }
	// RVA: 0x2b8f754 VA: 0x75951a7754
	public Int32 GetSwitchPageCountByCurPageIndex(Int32 curChallengeIndex) { }
	// RVA: 0x2b8f91c VA: 0x75951a791c
	private Int32 _GetGroupFocusChallengeIndex(Int32 groupId) { }
	// RVA: 0x2b8f9e4 VA: 0x75951a79e4
	public Void .ctor() { }
}
```