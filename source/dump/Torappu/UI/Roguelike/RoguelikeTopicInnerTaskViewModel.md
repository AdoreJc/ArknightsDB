# RoguelikeTopicInnerTaskViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTopicMode topicMode`

- `Boolean isCompleted`

- `Boolean isValid`


## Methods

- `Boolean _LoadChallengeTaskInfos(RoguelikeTopicChallenge, List`1, out)`

- `Boolean _LoadMonthTaskInfos(RoguelikeTopicMonthSquad, List`1, out)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTopicInnerTaskViewModel : RoguelikeMenuCompViewModel
{
	public List`1 taskInfos; // 0x18
	public RoguelikeTopicMode topicMode; // 0x20
	public Boolean isCompleted; // 0x24
	public Boolean isValid; // 0x25
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadChallengeTaskInfos; // 0x8
	private static DelegateBridge __Hotfix0__LoadMonthTaskInfos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a7e878 VA: 0x7595096878
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a7eb3c VA: 0x7595096b3c
	private Boolean _LoadChallengeTaskInfos(RoguelikeTopicChallenge challengeData, List`1 playerInnerTask, out Boolean isCompleted) { }
	// RVA: 0x2a7ef2c VA: 0x7595096f2c
	private Boolean _LoadMonthTaskInfos(RoguelikeTopicMonthSquad monthSquadData, List`1 playerInnerTask, out Boolean isCompleted) { }
	// RVA: 0x2a7f36c VA: 0x759509736c
	public Void .ctor() { }
	// RVA: 0x2a7f3d8 VA: 0x75950973d8
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```