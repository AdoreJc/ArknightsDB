# StoryReviewDB

**Namespace:** `Torappu`


## Methods

- `Void _GenerateStoryBrief(StoryReviewGroupClientData)`

- `StoryReviewGroupClientData FindActivityStoryData(String)`

- `StoryReviewBriefData GetStoryBriefByStoryId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryReviewDB : SimpleKVTable`2
{
	private Dictionary`2 m_groupedStoryDict; // 0x68
	private Dictionary`2 m_storyBriefDict; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__GenerateStoryBrief; // 0x8
	private static DelegateBridge __Hotfix0_GetGroupedStoryReviewDict; // 0x10
	private static DelegateBridge __Hotfix0_FindActivityStoryData; // 0x18
	private static DelegateBridge __Hotfix0_GetStoryBriefByStoryId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31fc858 VA: 0x7595814858
	protected override Void OnInit() { }
	// RVA: 0x31fca88 VA: 0x7595814a88
	private Void _GenerateStoryBrief(StoryReviewGroupClientData groupedData) { }
	// RVA: 0x31fce50 VA: 0x7595814e50
	public Dictionary`2 GetGroupedStoryReviewDict() { }
	// RVA: 0x31fceb8 VA: 0x7595814eb8
	public StoryReviewGroupClientData FindActivityStoryData(String groupId) { }
	// RVA: 0x31fcff4 VA: 0x7595814ff4
	public StoryReviewBriefData GetStoryBriefByStoryId(String storyId) { }
	// RVA: 0x31fd0a4 VA: 0x75958150a4
	public Void .ctor() { }
}
```