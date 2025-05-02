# Act5D0MissionView

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Act5D0MissionGridAdapter _adapter`

- `Text _passedMissionRate`

- `LoopScrollRect _rect`

- `Text _curMilestoneToken`


## Methods

- `Void RenderInfo(List`1, Int32)`

- `IEnumerator _ScrollToFirstSlot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionView : MonoBehaviour, IHotfixable
{
	private Act5D0MissionGridAdapter _adapter; // 0x18
	private Text _passedMissionRate; // 0x20
	private LoopScrollRect _rect; // 0x28
	private Text _curMilestoneToken; // 0x30
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x0
	private static DelegateBridge __Hotfix0__ScrollToFirstSlot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31be828 VA: 0x75957d6828
	public Void RenderInfo(List`1 missionList, Int32 curStoneToken) { }
	// RVA: 0x31c2660 VA: 0x75957da660
	private IEnumerator _ScrollToFirstSlot() { }
	// RVA: 0x31c2734 VA: 0x75957da734
	public Void .ctor() { }
}
```