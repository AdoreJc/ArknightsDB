# AvgProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void StartAvgAndBackToArchiveAvg(StoryData, DataBundle)`

- `UIPageControllerParam _SceneParamToState(DataBundle)`

- `Void _OnAvgItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AvgProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_InitComp; // 0x8
	private static DelegateBridge __Hotfix0_StartAvgAndBackToArchiveAvg; // 0x10
	private static DelegateBridge __Hotfix0__SceneParamToState; // 0x18
	private static DelegateBridge __Hotfix0__OnAvgItemClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String compType { get; }

	// RVA: 0x300d920 VA: 0x7595625920
	protected override String get_compType() { }
	// RVA: 0x300d99c VA: 0x759562599c
	protected override Void InitComp() { }
	// RVA: 0x300dc54 VA: 0x7595625c54
	public Void StartAvgAndBackToArchiveAvg(StoryData targetStory, DataBundle stateBundle) { }
	// RVA: 0x300de30 VA: 0x7595625e30
	private UIPageControllerParam _SceneParamToState(DataBundle bundleToState) { }
	// RVA: 0x300e094 VA: 0x7595626094
	private Void _OnAvgItemClicked(ActArchiveType type, String avgID) { }
	// RVA: 0x300e1ac VA: 0x75956261ac
	public Void .ctor() { }
}
```