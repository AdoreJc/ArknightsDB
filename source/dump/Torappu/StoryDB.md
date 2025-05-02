# StoryDB

**Namespace:** `Torappu`


## Methods

- `StoryData GetFirstStoryToTrig(TriggerType, String, Boolean, Boolean)`

- `StoryData GetFirstStoryForResPreference(TriggerType, String)`

- `StoryData GetFirstStoryOnPageLoaded(AVGPageKey, Boolean)`

- `Boolean CheckStoryWithoutConsiderTrigger(String, Boolean)`

- `Void _AddTrigger(Trigger, StoryData)`

- `Boolean _TryGetCandidates(TriggerType, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoryDB : SimpleKVTable`2
{
	private const Char KEY_SEPARATOR; // 0x0
	private Dictionary`2 m_triggerToStories; // 0x68
	private List`1[] m_regexStories; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetFirstStoryToTrig; // 0x8
	private static DelegateBridge __Hotfix0_GetFirstStoryForResPreference; // 0x10
	private static DelegateBridge __Hotfix0_GetFirstStoryOnPageLoaded; // 0x18
	private static DelegateBridge __Hotfix0_GetAllStoryToTrig; // 0x20
	private static DelegateBridge __Hotfix0_CheckStoryWithoutConsiderTrigger; // 0x28
	private static DelegateBridge __Hotfix0__AddTrigger; // 0x30
	private static DelegateBridge __Hotfix0__TryGetCandidates; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31fb510 VA: 0x7595813510
	protected override Void OnInit() { }
	// RVA: 0x31fbc90 VA: 0x7595813c90
	public StoryData GetFirstStoryToTrig(TriggerType trigType, String key, Boolean forceRepeatableAndOmitCommitAndStageCond, Boolean fetchEvenIfAvgIsRunning) { }
	// RVA: 0x31fc178 VA: 0x7595814178
	public StoryData GetFirstStoryForResPreference(TriggerType trigType, String key) { }
	// RVA: 0x31fc29c VA: 0x759581429c
	public StoryData GetFirstStoryOnPageLoaded(AVGPageKey avgPage, Boolean forceRepeatableAndOmitCommit) { }
	// RVA: 0x31fc37c VA: 0x759581437c
	public StoryData[] GetAllStoryToTrig(TriggerType trigType, String key) { }
	// RVA: 0x31fc604 VA: 0x7595814604
	public Boolean CheckStoryWithoutConsiderTrigger(String storyId, Boolean allowMissing) { }
	// RVA: 0x31fba14 VA: 0x7595813a14
	private Void _AddTrigger(Trigger trigger, StoryData story) { }
	// RVA: 0x31fbe7c VA: 0x7595813e7c
	private Boolean _TryGetCandidates(TriggerType trigType, String key, out List`1 candidates) { }
	// RVA: 0x31fc744 VA: 0x7595814744
	public Void .ctor() { }
}
```