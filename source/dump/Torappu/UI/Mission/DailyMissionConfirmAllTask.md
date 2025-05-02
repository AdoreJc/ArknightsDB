# DailyMissionConfirmAllTask

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Text _describeText`

- `Text _buttonText`

- `MissionType m_missionType`


## Methods

- `Void InitData(DailyOrWeekly)`

- `Void ApplyAllReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class DailyMissionConfirmAllTask : MonoBehaviour, IHotfixable
{
	private Text _describeText; // 0x18
	private Text _buttonText; // 0x20
	private MissionType m_missionType; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_ApplyAllReward; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2739ee4 VA: 0x7594d51ee4
	public Void InitData(DailyOrWeekly dataType) { }
	// RVA: 0x2739ff8 VA: 0x7594d51ff8
	public Void ApplyAllReward() { }
	// RVA: 0x273a070 VA: 0x7594d52070
	public Void .ctor() { }
}
```