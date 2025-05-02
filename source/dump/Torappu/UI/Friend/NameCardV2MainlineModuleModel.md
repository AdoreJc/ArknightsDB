# NameCardV2MainlineModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `String chapterEnName`

- `String stageCode`

- `String chapterTitleBgId`


## Methods

- `Void _LoadDataByStageData(StageData)`

- `MainlineZoneData _TryFindMainlineZoneData(String)`

- `ChapterData _GetLatestChapterData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2MainlineModuleModel : NameCardV2RemovableModuleBaseModel
{
	private const String CHAPTER_BG_FORMAT; // 0x0
	public String chapterEnName; // 0x50
	public String stageCode; // 0x58
	public String chapterTitleBgId; // 0x60
	private static DelegateBridge __Hotfix0_get_moduleSubType; // 0x0
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x8
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x10
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x18
	private static DelegateBridge __Hotfix0__LoadDataByStageData; // 0x20
	private static DelegateBridge __Hotfix0__TryFindMainlineZoneData; // 0x28
	private static DelegateBridge __Hotfix0__GetLatestChapterData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override NameCardV2ModuleSubType moduleSubType { get; }

	// RVA: 0x28c4524 VA: 0x7594edc524
	public override NameCardV2ModuleSubType get_moduleSubType() { }
	// RVA: 0x28c458c VA: 0x7594edc58c
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c4820 VA: 0x7594edc820
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c4890 VA: 0x7594edc890
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c4620 VA: 0x7594edc620
	private Void _LoadDataByStageData(StageData stageData) { }
	// RVA: 0x28c4bf4 VA: 0x7594edcbf4
	private MainlineZoneData _TryFindMainlineZoneData(String mainlineZoneId) { }
	// RVA: 0x28c48f4 VA: 0x7594edc8f4
	private ChapterData _GetLatestChapterData() { }
	// RVA: 0x28c4cdc VA: 0x7594edccdc
	public Void .ctor() { }
}
```