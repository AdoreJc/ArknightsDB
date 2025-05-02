# DaylightTime

**Namespace:** `System.Globalization`


## Properties

- `DateTime Start`

- `DateTime End`

- `TimeSpan Delta`


## Methods

- `DateTime get_Start()`

- `DateTime get_End()`

- `TimeSpan get_Delta()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class DaylightTime
{
	private readonly DateTime _start; // 0x10
	private readonly DateTime _end; // 0x18
	private readonly TimeSpan _delta; // 0x20

	public DateTime Start { get; }
	public DateTime End { get; }
	public TimeSpan Delta { get; }

	// RVA: 0x604d848 VA: 0x7598665848
	public Void .ctor(DateTime start, DateTime end, TimeSpan delta) { }
	// RVA: 0x604d884 VA: 0x7598665884
	public DateTime get_Start() { }
	// RVA: 0x604d88c VA: 0x759866588c
	public DateTime get_End() { }
	// RVA: 0x604d894 VA: 0x7598665894
	public TimeSpan get_Delta() { }
}
```