# MixStoryAVGAdapter

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `StageStateBean _stageStateBean`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Boolean _ExecuteFocusStoryline(Command)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class MixStoryAVGAdapter : ExecutorComponent
{
	private StageStateBean _stageStateBean; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteFocusStoryline; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fe30b4 VA: 0x75955fb0b4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2fe3254 VA: 0x75955fb254
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2fe32b8 VA: 0x75955fb2b8
	private Void Start() { }
	// RVA: 0x2fe3374 VA: 0x75955fb374
	private Void OnDestroy() { }
	// RVA: 0x2fe3430 VA: 0x75955fb430
	private Boolean _ExecuteFocusStoryline(Command command) { }
	// RVA: 0x2fe3740 VA: 0x75955fb740
	public Void .ctor() { }
}
```