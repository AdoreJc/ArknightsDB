# Stopwatch

**Namespace:** `System.Diagnostics`


## Fields

- `Int64 elapsed`

- `Int64 started`

- `Boolean is_running`


## Properties

- `TimeSpan Elapsed`

- `Int64 ElapsedMilliseconds`

- `Int64 ElapsedTicks`

- `Boolean IsRunning`


## Methods

- `TimeSpan get_Elapsed()`

- `Int64 get_ElapsedMilliseconds()`

- `Int64 get_ElapsedTicks()`

- `Boolean get_IsRunning()`

- `Void Reset()`

- `Void Start()`

- `Void Stop()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public class Stopwatch
{
	public static readonly Int64 Frequency; // 0x0
	public static readonly Boolean IsHighResolution; // 0x8
	private Int64 elapsed; // 0x10
	private Int64 started; // 0x18
	private Boolean is_running; // 0x20

	public TimeSpan Elapsed { get; }
	public Int64 ElapsedMilliseconds { get; }
	public Int64 ElapsedTicks { get; }
	public Boolean IsRunning { get; }

	// RVA: 0x6396784 VA: 0x75989ae784
	public static Int64 GetTimestamp() { }
	// RVA: 0x639a6f4 VA: 0x75989b26f4
	public Void .ctor() { }
	// RVA: 0x639a6fc VA: 0x75989b26fc
	public TimeSpan get_Elapsed() { }
	// RVA: 0x639a864 VA: 0x75989b2864
	public Int64 get_ElapsedMilliseconds() { }
	// RVA: 0x639a7f4 VA: 0x75989b27f4
	public Int64 get_ElapsedTicks() { }
	// RVA: 0x639a9a8 VA: 0x75989b29a8
	public Boolean get_IsRunning() { }
	// RVA: 0x639a9b0 VA: 0x75989b29b0
	public Void Reset() { }
	// RVA: 0x639a9bc VA: 0x75989b29bc
	public Void Start() { }
	// RVA: 0x639aa24 VA: 0x75989b2a24
	public Void Stop() { }
	// RVA: 0x639aa9c VA: 0x75989b2a9c
	private static Void .cctor() { }
}
```