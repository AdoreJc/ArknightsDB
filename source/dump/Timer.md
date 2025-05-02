# Timer

**Namespace:** ` `


## Fields

- `Int32 id`

- `TimerStatus status`

- `Int32 loopCount`

- `Single expireTime`

- `Single interval`

- `Action callback`

- `Action callbackOnRemoved`


## Methods

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Int32 CompareTo(Timer)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Timer : IComparable`1
{
	private static Int32 s_uniqueId; // 0x0
	public Int32 id; // 0x10
	public TimerStatus status; // 0x14
	public Int32 loopCount; // 0x18
	public Single expireTime; // 0x1c
	public Single interval; // 0x20
	public Action callback; // 0x28
	public Action callbackOnRemoved; // 0x30


	// RVA: 0x678f624 VA: 0x7598da7624
	public Void OnAllocate() { }
	// RVA: 0x678f8ac VA: 0x7598da78ac
	public Void OnRecycle() { }
	// RVA: 0x678f8dc VA: 0x7598da78dc
	public Int32 CompareTo(Timer other) { }
	// RVA: 0x678f8fc VA: 0x7598da78fc
	public Void .ctor() { }
}
```