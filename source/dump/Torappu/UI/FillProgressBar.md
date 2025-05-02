# FillProgressBar

**Namespace:** `Torappu.UI`


## Fields

- `Image _imageProgress`

- `Single m_progress`


## Properties

- `Single progress`


## Methods

- `Single get_progress()`

- `Void set_progress(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class FillProgressBar : MonoBehaviour
{
	private Image _imageProgress; // 0x18
	private Single m_progress; // 0x20

	public Single progress { get; set; }

	// RVA: 0x221d620 VA: 0x7594835620
	public Single get_progress() { }
	// RVA: 0x221d628 VA: 0x7594835628
	public Void set_progress(Single value) { }
	// RVA: 0x221d6d8 VA: 0x75948356d8
	public Void .ctor() { }
}
```