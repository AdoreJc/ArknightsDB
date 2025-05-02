# MeetingClueRestTimeLabel

**Namespace:** `Torappu.Building.UI`


## Fields

- `Text _label`

- `Single _updateInterval`

- `Single m_timer`

- `Boolean m_setup`

- `DateTime m_expiredTime`

- `Action expiredUpdate`


## Methods

- `Void add_expiredUpdate(Action)`

- `Void remove_expiredUpdate(Action)`

- `Void Setup(DateTime)`

- `Void Unsetup()`

- `Void _RefreshRestTime()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class MeetingClueRestTimeLabel : MonoBehaviour
{
	private Text _label; // 0x18
	private Single _updateInterval; // 0x20
	private Single m_timer; // 0x24
	private Boolean m_setup; // 0x28
	private DateTime m_expiredTime; // 0x30
	private Action expiredUpdate; // 0x38


	// RVA: 0x3d3d020 VA: 0x7596355020
	public Void add_expiredUpdate(Action value) { }
	// RVA: 0x3d3d0bc VA: 0x75963550bc
	public Void remove_expiredUpdate(Action value) { }
	// RVA: 0x3d3d158 VA: 0x7596355158
	public Void Setup(DateTime expireTime) { }
	// RVA: 0x3d3d2b4 VA: 0x75963552b4
	public Void Unsetup() { }
	// RVA: 0x3d3d16c VA: 0x759635516c
	private Void _RefreshRestTime() { }
	// RVA: 0x3d3d2bc VA: 0x75963552bc
	private Void Update() { }
	// RVA: 0x3d3d314 VA: 0x7596355314
	public Void .ctor() { }
}
```