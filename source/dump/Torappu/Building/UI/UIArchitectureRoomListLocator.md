# UIArchitectureRoomListLocator

**Namespace:** `Torappu.Building.UI`


## Fields

- `Single _easeMoveDuration`

- `Single _locationFactor`

- `Single m_timer`

- `Single m_basePosition`

- `Single m_targetPosition`

- `Boolean m_easeMoving`


## Methods

- `Single _EaseMoveConvert(Single)`

- `Void Update()`

- `Int32 SetFocusIndex(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureRoomListLocator : MonoBehaviour
{
	private Single _easeMoveDuration; // 0x18
	private Single _locationFactor; // 0x1c
	private Single m_timer; // 0x20
	private Single m_basePosition; // 0x24
	private Single m_targetPosition; // 0x28
	private Boolean m_easeMoving; // 0x2c


	// RVA: 0x3d4b998 VA: 0x7596363998
	private Single _EaseMoveConvert(Single src) { }
	// RVA: 0x3d4b9b0 VA: 0x75963639b0
	private Void Update() { }
	// RVA: 0x3d4bafc VA: 0x7596363afc
	public Int32 SetFocusIndex(Int32 index, Boolean easeMove) { }
	// RVA: 0x3d4bc64 VA: 0x7596363c64
	public Void .ctor() { }
}
```