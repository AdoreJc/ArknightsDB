# RoguelikeTopicMonthSquadModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `String topicId`

- `String monthTeamId`

- `String teamName`

- `String teamDes`

- `String teamColor`

- `String teamMonth`

- `String teamYear`

- `String descIndex`

- `String teamSubName`

- `String teamFlavorDesc`

- `Int32 tokenRewardNum`

- `Boolean hasReceivedAward`

- `Boolean hasUnlockedAllChat`

- `String chatId`

- `String monthSquadSystemName`

- `String targetZoneName`

- `Boolean hasTask`

- `String taskDesc`

- `Int32 taskCurrProgress`

- `Int32 taskTotalProgress`


## Methods

- `Void LoadData(String, String)`

- `Void _LoadMonthSquadTaskStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthSquadModel : IHotfixable
{
	public String topicId; // 0x10
	public String monthTeamId; // 0x18
	public String teamName; // 0x20
	public String teamDes; // 0x28
	public String teamColor; // 0x30
	public String teamMonth; // 0x38
	public String teamYear; // 0x40
	public String descIndex; // 0x48
	public String teamSubName; // 0x50
	public String teamFlavorDesc; // 0x58
	public List`1 teamChars; // 0x60
	public Int32 tokenRewardNum; // 0x68
	public List`1 items; // 0x70
	public Boolean hasReceivedAward; // 0x78
	public Boolean hasUnlockedAllChat; // 0x79
	public String chatId; // 0x80
	public String monthSquadSystemName; // 0x88
	public String targetZoneName; // 0x90
	public Boolean hasTask; // 0x98
	public String taskDesc; // 0xa0
	public Int32 taskCurrProgress; // 0xa8
	public Int32 taskTotalProgress; // 0xac
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadMonthSquadTaskStatus; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x267b5b4 VA: 0x7594c935b4
	public Void LoadData(String topic, String monthTeam) { }
	// RVA: 0x267b914 VA: 0x7594c93914
	private Void _LoadMonthSquadTaskStatus() { }
	// RVA: 0x267bbe4 VA: 0x7594c93be4
	public Void .ctor() { }
}
```