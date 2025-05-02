# StageStorylineMainlineChapterViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Methods

- `Void RefreshMainlineChapterData(Dictionary`2, Dictionary`2)`

- `Void _RefreshChapterCurGoingMainlineStageId(Dictionary`2)`

- `ChapterViewModel _CreateChapterViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineMainlineChapterViewModel : IHotfixable
{
	private List`1 m_chapterList; // 0x10
	private Dictionary`2 m_chapterId2ZoneListMap; // 0x18
	private static DelegateBridge __Hotfix0_get_chapterList; // 0x0
	private static DelegateBridge __Hotfix0_get_chapterId2ZoneListMap; // 0x8
	private static DelegateBridge __Hotfix0_RefreshMainlineChapterData; // 0x10
	private static DelegateBridge __Hotfix0__RefreshChapterCurGoingMainlineStageId; // 0x18
	private static DelegateBridge __Hotfix0__CreateChapterViewModel; // 0x20
	private static DelegateBridge __Hotfix0_GetMainlineZoneIdFromModel; // 0x28
	private static DelegateBridge __Hotfix0_GetMainlineRetroZoneIdFromModel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 chapterList { get; }
	public Dictionary`2 chapterId2ZoneListMap { get; }

	// RVA: 0x2ff0d60 VA: 0x7595608d60
	public List`1 get_chapterList() { }
	// RVA: 0x2ff0dc8 VA: 0x7595608dc8
	public Dictionary`2 get_chapterId2ZoneListMap() { }
	// RVA: 0x2ff0e30 VA: 0x7595608e30
	public Void RefreshMainlineChapterData(Dictionary`2 storySets, Dictionary`2 zoneDict) { }
	// RVA: 0x2ff17e8 VA: 0x75956097e8
	private Void _RefreshChapterCurGoingMainlineStageId(Dictionary`2 zoneDict) { }
	// RVA: 0x2ff1620 VA: 0x7595609620
	private ChapterViewModel _CreateChapterViewModel(String chapterId) { }
	// RVA: 0x2ff1528 VA: 0x7595609528
	public static String GetMainlineZoneIdFromModel(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2ff1c50 VA: 0x7595609c50
	private static String GetMainlineRetroZoneIdFromModel(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2ff1da8 VA: 0x7595609da8
	public Void .ctor() { }
}
```