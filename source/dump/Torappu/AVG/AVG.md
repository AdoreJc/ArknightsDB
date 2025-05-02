# AVG

**Namespace:** `Torappu.AVG`


## Fields

- `Object _prefab`

- `DirectAssetLoader _assetLoader`

- `AVGVariableConfig _variableConfig`

- `PerformanceStoryMiddleware m_performanceStory`


## Methods

- `PerformanceStoryMiddleware _GetOrCreatePerformanceStory()`

- `Void StartStory(String, Action`1)`

- `Void StartStory(String, Action`1, StoryParam)`

- `Void StartStory(TextAsset, Action`1, StoryParam)`

- `Void StartStoryByString(String, Action`1)`

- `Void StopStory()`

- `Void InterruptStory()`

- `Void ReloadCommonData()`

- `AVGVariableConfig GetVariableConfig()`

- `Void _StartStoryInternal(TextAsset, StoryParam, Action`1)`

- `Void _StartStoryInternalByString(String, StoryParam, Action`1, String)`

- `Void _OnStoryEnd(Object)`

- `Void _OnStoryFailed(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVG : SingletonMonoBehaviour`1
{
	private Object _prefab; // 0x18
	private Action`1 _onStoryEndCB; // 0x20
	private DirectAssetLoader _assetLoader; // 0x28
	private AVGVariableConfig _variableConfig; // 0x30
	private PerformanceStoryMiddleware m_performanceStory; // 0x38
	private static DelegateBridge __Hotfix0__GetOrCreatePerformanceStory; // 0x0
	private static DelegateBridge __Hotfix0_StartStory; // 0x8
	private static DelegateBridge __Hotfix1_StartStory; // 0x10
	private static DelegateBridge __Hotfix2_StartStory; // 0x18
	private static DelegateBridge __Hotfix0_StartStoryByString; // 0x20
	private static DelegateBridge __Hotfix0_StopStory; // 0x28
	private static DelegateBridge __Hotfix0_InterruptStory; // 0x30
	private static DelegateBridge __Hotfix0_ReloadCommonData; // 0x38
	private static DelegateBridge __Hotfix0_GetVariableConfig; // 0x40
	private static DelegateBridge __Hotfix0__StartStoryInternal; // 0x48
	private static DelegateBridge __Hotfix0__StartStoryInternalByString; // 0x50
	private static DelegateBridge __Hotfix0__OnStoryEnd; // 0x58
	private static DelegateBridge __Hotfix0__OnStoryFailed; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x3e46f68 VA: 0x759645ef68
	private PerformanceStoryMiddleware _GetOrCreatePerformanceStory() { }
	// RVA: 0x3e47110 VA: 0x759645f110
	public Void StartStory(String storyId, Action`1 onStoryEnd) { }
	// RVA: 0x3e471b8 VA: 0x759645f1b8
	public Void StartStory(String storyId, Action`1 onStoryEnd, StoryParam param) { }
	// RVA: 0x3e47464 VA: 0x759645f464
	public Void StartStory(TextAsset storyTextAsset, Action`1 onStoryEnd, StoryParam param) { }
	// RVA: 0x3e47628 VA: 0x759645f628
	public Void StartStoryByString(String storyContent, Action`1 onStoryEnd) { }
	// RVA: 0x3e4793c VA: 0x759645f93c
	public Void StopStory() { }
	// RVA: 0x3e47ab0 VA: 0x759645fab0
	public Void InterruptStory() { }
	// RVA: 0x3e47b54 VA: 0x759645fb54
	public Void ReloadCommonData() { }
	// RVA: 0x3e47bcc VA: 0x759645fbcc
	public AVGVariableConfig GetVariableConfig() { }
	// RVA: 0x3e47528 VA: 0x759645f528
	private Void _StartStoryInternal(TextAsset storyTextAsset, StoryParam param, Action`1 onStoryEnd) { }
	// RVA: 0x3e476d4 VA: 0x759645f6d4
	private Void _StartStoryInternalByString(String storyContent, StoryParam param, Action`1 onStoryEnd, String hintName) { }
	// RVA: 0x3e47ca4 VA: 0x759645fca4
	private Void _OnStoryEnd(Object arg) { }
	// RVA: 0x3e48290 VA: 0x7596460290
	private Void _OnStoryFailed(Object arg) { }
	// RVA: 0x3e4841c VA: 0x759646041c
	protected override Void OnInit() { }
	// RVA: 0x3e487a8 VA: 0x75964607a8
	public Void .ctor() { }
}
```