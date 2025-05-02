# RL04TopicChallengePluginModel

**Namespace:** ` `


## Methods

- `Void LoadData(RoguelikeTopicChallengeModeViewModel)`

- `Void UpdateData(RoguelikeTopicChallengeModeViewModel)`

- `Boolean CheckIfNeedRefrushAllCard()`

- `Int32 GetSwitchPageCountByCurPageIndex(Int32)`

- `Int32 _GetGroupFocusChallengeIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL04TopicChallengePluginModel : IHotfixable
{
	public ListDict`2 challengeGroupInfoListDic; // 0x10
	public ListDict`2 challengeGroupCountListDic; // 0x18
	private Dictionary`2 m_cachedChallengeStatus; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfNeedRefrushAllCard; // 0x10
	private static DelegateBridge __Hotfix0_GetSwitchPageCountByCurPageIndex; // 0x18
	private static DelegateBridge __Hotfix0__GetGroupFocusChallengeIndex; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b0e91c VA: 0x759512691c
	public Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b0f014 VA: 0x7595127014
	public Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b0f20c VA: 0x759512720c
	public Boolean CheckIfNeedRefrushAllCard() { }
	// RVA: 0x2b0f4f4 VA: 0x75951274f4
	public Int32 GetSwitchPageCountByCurPageIndex(Int32 curChallengeIndex) { }
	// RVA: 0x2b0f6bc VA: 0x75951276bc
	private Int32 _GetGroupFocusChallengeIndex(Int32 groupId) { }
	// RVA: 0x2b0f784 VA: 0x7595127784
	public Void .ctor() { }
}
```