# Act1LockMainView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Text _pointCntLabel`

- `Text _missionPrgLabel`

- `Text _timeDescLabel`

- `Text _timeLabel`

- `Button _enterBtn`

- `GameObject _finalUnlock`

- `GameObject _defendList`

- `GameObject _battleEndMask`

- `GameObject _btnLight`


## Methods

- `Void EventOnEnterClick()`

- `Void EventOnEnterMissionState()`

- `Void EventOnEnterMilestoneState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMainView : DataBinder`1
{
	private Text _pointCntLabel; // 0x20
	private Text _missionPrgLabel; // 0x28
	private Text _timeDescLabel; // 0x30
	private Text _timeLabel; // 0x38
	private Button _enterBtn; // 0x40
	private GameObject _finalUnlock; // 0x48
	private GameObject _defendList; // 0x50
	private Button[] _defendFlags; // 0x58
	private GameObject _battleEndMask; // 0x60
	private GameObject _btnLight; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnEnterClick; // 0x8
	private static DelegateBridge __Hotfix0_EventOnEnterMissionState; // 0x10
	private static DelegateBridge __Hotfix0_EventOnEnterMilestoneState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x33cda2c VA: 0x75959e5a2c
	public override Void OnValueChanged(Act1LockMainProperty property) { }
	// RVA: 0x33cde74 VA: 0x75959e5e74
	public Void EventOnEnterClick() { }
	// RVA: 0x33cdef4 VA: 0x75959e5ef4
	public Void EventOnEnterMissionState() { }
	// RVA: 0x33cdfcc VA: 0x75959e5fcc
	public Void EventOnEnterMilestoneState() { }
	// RVA: 0x33ce0a4 VA: 0x75959e60a4
	public Void .ctor() { }
}
```