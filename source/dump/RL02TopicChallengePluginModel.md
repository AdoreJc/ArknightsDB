# RL02TopicChallengePluginModel

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
private class RL02TopicChallengePluginModel : IHotfixable
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


	// RVA: 0x2b5a83c VA: 0x759517283c
	public Void LoadData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b5afb8 VA: 0x7595172fb8
	public Void UpdateData(RoguelikeTopicChallengeModeViewModel challengeModeViewModel) { }
	// RVA: 0x2b5b5f0 VA: 0x75951735f0
	public Boolean CheckIfNeedRefrushAllCard() { }
	// RVA: 0x2b5b29c VA: 0x759517329c
	public Int32 GetSwitchPageCountByCurPageIndex(Int32 curChallengeIndex) { }
	// RVA: 0x2b5c004 VA: 0x7595174004
	private Int32 _GetGroupFocusChallengeIndex(Int32 groupId) { }
	// RVA: 0x2b5b97c VA: 0x759517397c
	public Void .ctor() { }
}
```