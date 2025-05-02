# RoguelikeActivityHistorySeedItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `String bandId`

- `String bandName`

- `String modeGradeName`

- `Int32 modeGrade`

- `String endingName`

- `String endTime`

- `String topicId`

- `RoguelikeGameEndingData endingData`

- `Int64 m_ts`


## Methods

- `Void LoadData(String, History)`

- `Void _LoadEndingDataWhenSuccess(RoguelikeTopicDetail, String)`

- `Void _LoadEndingDataWhenFail(RoguelikeTopicDetail)`

- `Boolean _TryLoadFailEndingData(RoguelikeTopicDetail, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivityHistorySeedItemModel : RoguelikeActivitySeedItemModel
{
	public static readonly RoguelikeActivityHistorySeedItemModel EMPTY_ITEM; // 0x0
	private const String DATE_TIME_FORMAT; // 0x0
	public String bandId; // 0x20
	public String bandName; // 0x28
	public String modeGradeName; // 0x30
	public Int32 modeGrade; // 0x38
	public String endingName; // 0x40
	public String endTime; // 0x48
	public String topicId; // 0x50
	public RoguelikeGameEndingData endingData; // 0x58
	private Int64 m_ts; // 0x60
	private static DelegateBridge __Hotfix0_get_seedItemType; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__LoadEndingDataWhenSuccess; // 0x20
	private static DelegateBridge __Hotfix0__LoadEndingDataWhenFail; // 0x28
	private static DelegateBridge __Hotfix0__TryLoadFailEndingData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SeedItemType seedItemType { get; }
	public override Int64 sortId { get; }

	// RVA: 0x26e3090 VA: 0x7594cfb090
	public override SeedItemType get_seedItemType() { }
	// RVA: 0x26e3108 VA: 0x7594cfb108
	public override Int64 get_sortId() { }
	// RVA: 0x26e2b38 VA: 0x7594cfab38
	public Void LoadData(String topicId, History history) { }
	// RVA: 0x26e3180 VA: 0x7594cfb180
	private Void _LoadEndingDataWhenSuccess(RoguelikeTopicDetail detailData, String endingId) { }
	// RVA: 0x26e3350 VA: 0x7594cfb350
	private Void _LoadEndingDataWhenFail(RoguelikeTopicDetail detailData) { }
	// RVA: 0x26e3274 VA: 0x7594cfb274
	private Boolean _TryLoadFailEndingData(RoguelikeTopicDetail detailData, String failEndingId) { }
	// RVA: 0x26e2abc VA: 0x7594cfaabc
	public Void .ctor() { }
	// RVA: 0x26e3404 VA: 0x7594cfb404
	private static Void .cctor() { }
}
```