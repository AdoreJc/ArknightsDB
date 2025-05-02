# RoguelikeActivitySeedModePanelModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `String topicId`

- `String rlActId`

- `String seedStr`

- `Int32 seedGrade`

- `RoguelikeTopicMode validMode`

- `String seedGradeName`

- `Int32 curGrade`

- `Boolean isSeedGradeLock`

- `Boolean isPlaying`

- `String seedTips`

- `String endTime`

- `RoguelikeActivitySeedModeConstData constData`


## Methods

- `Void InitModel(String, String)`

- `Void UpdateModel()`

- `Void _UpdateGrade(OuterData, RoguelikeTopicDetail, RoguelikeActivityBasicData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedModePanelModel : IHotfixable
{
	private const String TIME_FORMAT; // 0x0
	public String topicId; // 0x10
	public String rlActId; // 0x18
	public String seedStr; // 0x20
	public Int32 seedGrade; // 0x28
	public RoguelikeTopicMode validMode; // 0x2c
	public String seedGradeName; // 0x30
	public Int32 curGrade; // 0x38
	public Boolean isSeedGradeLock; // 0x3c
	public Boolean isPlaying; // 0x3d
	public String seedTips; // 0x40
	public String endTime; // 0x48
	public RoguelikeActivitySeedModeConstData constData; // 0x50
	private static DelegateBridge __Hotfix0_InitModel; // 0x0
	private static DelegateBridge __Hotfix0_UpdateModel; // 0x8
	private static DelegateBridge __Hotfix0__UpdateGrade; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26de870 VA: 0x7594cf6870
	public Void InitModel(String inputTopicId, String inputRlActId) { }
	// RVA: 0x26de9c0 VA: 0x7594cf69c0
	public Void UpdateModel() { }
	// RVA: 0x26dfdf8 VA: 0x7594cf7df8
	private Void _UpdateGrade(OuterData outer, RoguelikeTopicDetail detailData, RoguelikeActivityBasicData activityBasicData) { }
	// RVA: 0x26e0064 VA: 0x7594cf8064
	public Void .ctor() { }
}
```