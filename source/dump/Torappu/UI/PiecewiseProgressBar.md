# PiecewiseProgressBar

**Namespace:** `Torappu.UI`


## Fields

- `Single m_progress`

- `Int32 m_activeCountCache`

- `Boolean m_isInit`


## Properties

- `Single progress`


## Methods

- `Single get_progress()`

- `Void set_progress(Single)`

- `Void _SetProgressInternal(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PiecewiseProgressBar : MonoBehaviour
{
	private GameObject[] _progressSlots; // 0x18
	private Single m_progress; // 0x20
	private Int32 m_activeCountCache; // 0x24
	private Boolean m_isInit; // 0x28

	public Single progress { get; set; }

	// RVA: 0x2236560 VA: 0x759484e560
	public Single get_progress() { }
	// RVA: 0x2236568 VA: 0x759484e568
	public Void set_progress(Single value) { }
	// RVA: 0x223656c VA: 0x759484e56c
	private Void _SetProgressInternal(Single value) { }
	// RVA: 0x22366c8 VA: 0x759484e6c8
	public Void .ctor() { }
}
```