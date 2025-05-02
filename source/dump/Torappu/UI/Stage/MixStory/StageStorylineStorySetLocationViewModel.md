# StageStorylineStorySetLocationViewModel

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `StageStorylineStorySetViewModel <relevantStorySet>k__BackingField`


## Properties

- `StageStorylineStorySetViewModel relevantStorySet`

- `Boolean isBlocked`


## Methods

- `StageStorylineStorySetViewModel get_relevantStorySet()`

- `Void set_relevantStorySet(StageStorylineStorySetViewModel)`

- `Boolean get_isBlocked()`

- `Void _LoadRelevantStorySet(StorylineLocationData, Dictionary`2)`

- `Void <>xLuaBaseProxy_LoadData(StorylineLocationData, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageStorylineStorySetLocationViewModel : StageStorylineLocationViewModel
{
	private StageStorylineStorySetViewModel <relevantStorySet>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_relevantStorySet; // 0x0
	private static DelegateBridge __Hotfix0_set_relevantStorySet; // 0x8
	private static DelegateBridge __Hotfix0_get_isBlocked; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__LoadRelevantStorySet; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public StageStorylineStorySetViewModel relevantStorySet { get; set; }
	public Boolean isBlocked { get; }

	// RVA: 0x2ff0488 VA: 0x7595608488
	public StageStorylineStorySetViewModel get_relevantStorySet() { }
	// RVA: 0x2ff04f0 VA: 0x75956084f0
	private Void set_relevantStorySet(StageStorylineStorySetViewModel value) { }
	// RVA: 0x2ff0574 VA: 0x7595608574
	public Boolean get_isBlocked() { }
	// RVA: 0x2ff066c VA: 0x759560866c
	public override Void LoadData(StorylineLocationData data, Dictionary`2 storySetDict) { }
	// RVA: 0x2ff0708 VA: 0x7595608708
	private Void _LoadRelevantStorySet(StorylineLocationData data, Dictionary`2 storySetDict) { }
	// RVA: 0x2ff09d4 VA: 0x75956089d4
	public Void .ctor() { }
	// RVA: 0x2ff0a40 VA: 0x7595608a40
	private Void <>xLuaBaseProxy_LoadData(StorylineLocationData P0, Dictionary`2 P1) { }
}
```