# PerformanceStoryMiddleware

**Namespace:** ` `


## Fields

- `AVG m_context`


## Methods

- `Void StartStoryById(String, StoryParam, Action`1)`

- `Boolean _ShouldSyncStoryVariant(String)`

- `Void _StartStoryByIdImpl(String, StoryParam, Action`1)`

- `Void _SyncPerformanceStoryStatus(String, Action)`

- `TextAsset _LoadStoryText(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PerformanceStoryMiddleware : IHotfixable
{
	private AVG m_context; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_StartStoryById; // 0x8
	private static DelegateBridge __Hotfix0__ShouldSyncStoryVariant; // 0x10
	private static DelegateBridge __Hotfix0__StartStoryByIdImpl; // 0x18
	private static DelegateBridge __Hotfix0__SyncPerformanceStoryStatus; // 0x20
	private static DelegateBridge __Hotfix0__LoadStoryText; // 0x28
	private static DelegateBridge __Hotfix0__SelectUnlockedVariant; // 0x30


	// RVA: 0x3e4707c VA: 0x759645f07c
	public Void .ctor(AVG context) { }
	// RVA: 0x3e47298 VA: 0x759645f298
	public Void StartStoryById(String storyId, StoryParam param, Action`1 onStoryEnd) { }
	// RVA: 0x3e488bc VA: 0x75964608bc
	private Boolean _ShouldSyncStoryVariant(String storyId) { }
	// RVA: 0x3e48d94 VA: 0x7596460d94
	private Void _StartStoryByIdImpl(String storyId, StoryParam param, Action`1 onStoryEnd) { }
	// RVA: 0x3e48b2c VA: 0x7596460b2c
	private Void _SyncPerformanceStoryStatus(String storyId, Action nextStep) { }
	// RVA: 0x3e48ea8 VA: 0x7596460ea8
	private TextAsset _LoadStoryText(String originStoryId, out String spStoryId) { }
	// RVA: 0x3e49110 VA: 0x7596461110
	private static StoryVariantData _SelectUnlockedVariant(String storyId) { }
}
```