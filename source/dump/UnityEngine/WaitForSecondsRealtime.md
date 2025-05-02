# WaitForSecondsRealtime

**Namespace:** `UnityEngine`


## Fields

- `Single <waitTime>k__BackingField`

- `Single m_WaitUntilTime`


## Properties

- `Single waitTime`


## Methods

- `Single get_waitTime()`

- `Void set_waitTime(Single)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class WaitForSecondsRealtime : CustomYieldInstruction
{
	private Single <waitTime>k__BackingField; // 0x10
	private Single m_WaitUntilTime; // 0x14

	public Single waitTime { get; set; }
	public override Boolean keepWaiting { get; }

	// RVA: 0x688a978 VA: 0x7598ea2978
	public Single get_waitTime() { }
	// RVA: 0x688a980 VA: 0x7598ea2980
	public Void set_waitTime(Single value) { }
	// RVA: 0x688a988 VA: 0x7598ea2988
	public override Boolean get_keepWaiting() { }
	// RVA: 0x688aa4c VA: 0x7598ea2a4c
	public Void .ctor(Single time) { }
	// RVA: 0x688aa7c VA: 0x7598ea2a7c
	public override Void Reset() { }
}
```