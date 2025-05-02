# Act5D0MissionStateBean

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Int32 curStoneToken`


## Methods

- `Void InitInfo()`

- `Void _InitStoneTokenCount()`

- `Void _InitMissionList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public List`1 missionList; // 0x18
	public Int32 curStoneToken; // 0x20
	private static DelegateBridge __Hotfix0_InitInfo; // 0x0
	private static DelegateBridge __Hotfix0__InitStoneTokenCount; // 0x8
	private static DelegateBridge __Hotfix0__InitMissionList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31be7b8 VA: 0x75957d67b8
	public Void InitInfo() { }
	// RVA: 0x31c1f68 VA: 0x75957d9f68
	private Void _InitStoneTokenCount() { }
	// RVA: 0x31c2070 VA: 0x75957da070
	private Void _InitMissionList() { }
	// RVA: 0x31c25f0 VA: 0x75957da5f0
	public Void .ctor() { }
}
```