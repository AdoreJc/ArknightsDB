# RoguelikeLocalCache

**Namespace:** `Torappu.UI.Roguelike`


## Methods

- `Data _EnsureMemCacheData()`

- `Void _SaveData(Data)`

- `Boolean CheckFragmentHeavyDialogDisable(String)`

- `Void SaveFragmentHeavyDialogDisable(String)`

- `Boolean CheckFragmentWeightCharConfirmed(String)`

- `Void SaveFragmentWeightCharConfirmed(String)`

- `RoguelikeFragmentDialogListType GetFragmentBagListType(String)`

- `Void SaveFragmentBagListType(String, RoguelikeFragmentDialogListType)`

- `Void TrySyncDifficultyFromPlayerData()`

- `RoguelikeTopicDifficultyID GetTopicPrefDifficulty(String)`

- `Void SaveTopicPrefDifficulty(String, RoguelikeTopicDifficultyID)`

- `String GetTopicModePredefineId(String, RoguelikeTopicMode)`

- `Void SaveTopicModePredefineId(String, RoguelikeTopicMode, String)`

- `String GetTopicKeyVisual(String)`

- `Boolean SaveTopicKeyVisual(String, String)`

- `String GetPreAutoSetKV(String)`

- `Boolean SaveAutoSetKV(String, String)`

- `Void SaveSquad(List`1)`

- `String GetPendingChatId()`

- `Void SavePendingChatId(String)`

- `Boolean CheckMonthChatRead(String)`

- `Void SaveMonthChatRead(String)`

- `String _CurGameID()`

- `DataInGame _EnsureDataInGame()`

- `Void _ConfirmDataInGame(DataInGame, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__SaveData; // 0x10
	private static DelegateBridge __Hotfix0_CheckFragmentHeavyDialogDisable; // 0x18
	private static DelegateBridge __Hotfix0_SaveFragmentHeavyDialogDisable; // 0x20
	private static DelegateBridge __Hotfix0_CheckFragmentWeightCharConfirmed; // 0x28
	private static DelegateBridge __Hotfix0_SaveFragmentWeightCharConfirmed; // 0x30
	private static DelegateBridge __Hotfix0_GetFragmentBagListType; // 0x38
	private static DelegateBridge __Hotfix0_SaveFragmentBagListType; // 0x40
	private static DelegateBridge __Hotfix0_TrySyncDifficultyFromPlayerData; // 0x48
	private static DelegateBridge __Hotfix0_GetTopicPrefDifficulty; // 0x50
	private static DelegateBridge __Hotfix0_SaveTopicPrefDifficulty; // 0x58
	private static DelegateBridge __Hotfix0_GetTopicModePredefineId; // 0x60
	private static DelegateBridge __Hotfix0_SaveTopicModePredefineId; // 0x68
	private static DelegateBridge __Hotfix0_GetTopicKeyVisual; // 0x70
	private static DelegateBridge __Hotfix0_SaveTopicKeyVisual; // 0x78
	private static DelegateBridge __Hotfix0_GetPreAutoSetKV; // 0x80
	private static DelegateBridge __Hotfix0_SaveAutoSetKV; // 0x88
	private static DelegateBridge __Hotfix0_LoadSquad; // 0x90
	private static DelegateBridge __Hotfix0_SaveSquad; // 0x98
	private static DelegateBridge __Hotfix0_GetPendingChatId; // 0xa0
	private static DelegateBridge __Hotfix0_SavePendingChatId; // 0xa8
	private static DelegateBridge __Hotfix0_CheckMonthChatRead; // 0xb0
	private static DelegateBridge __Hotfix0_SaveMonthChatRead; // 0xb8
	private static DelegateBridge __Hotfix0__EnsureChatReadList; // 0xc0
	private static DelegateBridge __Hotfix0_CheckIfRogueActivityTrackPoint; // 0xc8
	private static DelegateBridge __Hotfix0_SetRogueActivityChecked; // 0xd0
	private static DelegateBridge __Hotfix0__CurGameID; // 0xd8
	private static DelegateBridge __Hotfix0__EnsureDataInGame; // 0xe0
	private static DelegateBridge __Hotfix0__ConfirmDataInGame; // 0xe8


	// RVA: 0x2ab3ee8 VA: 0x75950cbee8
	private Void .ctor() { }
	// RVA: 0x2ab3f78 VA: 0x75950cbf78
	private Data _EnsureMemCacheData() { }
	// RVA: 0x2ab40dc VA: 0x75950cc0dc
	private Void _SaveData(Data data) { }
	// RVA: 0x2ab4188 VA: 0x75950cc188
	public Boolean CheckFragmentHeavyDialogDisable(String topicId) { }
	// RVA: 0x2ab4340 VA: 0x75950cc340
	public Void SaveFragmentHeavyDialogDisable(String topicId) { }
	// RVA: 0x2ab4438 VA: 0x75950cc438
	public Boolean CheckFragmentWeightCharConfirmed(String topicId) { }
	// RVA: 0x2ab452c VA: 0x75950cc52c
	public Void SaveFragmentWeightCharConfirmed(String topicId) { }
	// RVA: 0x2ab4624 VA: 0x75950cc624
	public RoguelikeFragmentDialogListType GetFragmentBagListType(String topicId) { }
	// RVA: 0x2ab4724 VA: 0x75950cc724
	public Void SaveFragmentBagListType(String topicId, RoguelikeFragmentDialogListType type) { }
	// RVA: 0x2ab48a4 VA: 0x75950cc8a4
	public Void TrySyncDifficultyFromPlayerData() { }
	// RVA: 0x2ab4af4 VA: 0x75950ccaf4
	public RoguelikeTopicDifficultyID GetTopicPrefDifficulty(String topicId) { }
	// RVA: 0x2ab4994 VA: 0x75950cc994
	public Void SaveTopicPrefDifficulty(String topicId, RoguelikeTopicDifficultyID difficultyID) { }
	// RVA: 0x2ab4bf0 VA: 0x75950ccbf0
	public String GetTopicModePredefineId(String topicId, RoguelikeTopicMode mode) { }
	// RVA: 0x2ab4d14 VA: 0x75950ccd14
	public Void SaveTopicModePredefineId(String topicId, RoguelikeTopicMode mode, String predefineId) { }
	// RVA: 0x2ab4f10 VA: 0x75950ccf10
	public String GetTopicKeyVisual(String topicId) { }
	// RVA: 0x2ab4fe4 VA: 0x75950ccfe4
	public Boolean SaveTopicKeyVisual(String topicId, String kv) { }
	// RVA: 0x2ab5118 VA: 0x75950cd118
	public String GetPreAutoSetKV(String topicId) { }
	// RVA: 0x2ab51d4 VA: 0x75950cd1d4
	public Boolean SaveAutoSetKV(String topicId, String kv) { }
	// RVA: 0x2ab52f4 VA: 0x75950cd2f4
	public List`1 LoadSquad() { }
	// RVA: 0x2ab54c4 VA: 0x75950cd4c4
	public Void SaveSquad(List`1 squad) { }
	// RVA: 0x2ab5684 VA: 0x75950cd684
	public String GetPendingChatId() { }
	// RVA: 0x2ab56f8 VA: 0x75950cd6f8
	public Void SavePendingChatId(String chatId) { }
	// RVA: 0x2ab5814 VA: 0x75950cd814
	public Boolean CheckMonthChatRead(String chatStoryId) { }
	// RVA: 0x2ab5a08 VA: 0x75950cda08
	public Void SaveMonthChatRead(String chatStoryId) { }
	// RVA: 0x2ab58b8 VA: 0x75950cd8b8
	private List`1 _EnsureChatReadList() { }
	// RVA: 0x2ab5de8 VA: 0x75950cdde8
	public static Boolean CheckIfRogueActivityTrackPoint(String rlActId) { }
	// RVA: 0x2ab5eb0 VA: 0x75950cdeb0
	public static Void SetRogueActivityChecked(String rlActId) { }
	// RVA: 0x2ab427c VA: 0x75950cc27c
	private String _CurGameID() { }
	// RVA: 0x2ab53b4 VA: 0x75950cd3b4
	private DataInGame _EnsureDataInGame() { }
	// RVA: 0x2ab55a0 VA: 0x75950cd5a0
	private Void _ConfirmDataInGame(DataInGame data, Boolean triggerSave) { }
}
```