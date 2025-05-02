# TaskTimer

**Namespace:** `Torappu`


## Fields

- `Int64 m_startTime`

- `Int64 m_endTime`

- `Options options`

- `Int64 startTime`

- `Int64 endTime`

- `Boolean m_isInited`

- `Int64 m_lastUpdateTime`

- `Value m_lastValue`

- `Boolean m_isTaskEnd`


## Properties

- `Value latestValue`

- `Boolean isTaskEnd`


## Methods

- `Value get_latestValue()`

- `Void ResetTime(Int64, Int64)`

- `Boolean get_isTaskEnd()`

- `Void Interrupt()`

- `Void Tick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TaskTimer`1
{
	private Int64 m_startTime; // 0x0
	private Int64 m_endTime; // 0x0
	protected Options options; // 0x0
	protected Int64 startTime; // 0x0
	protected Int64 endTime; // 0x0
	private Boolean m_isInited; // 0x0
	private Int64 m_lastUpdateTime; // 0x0
	private Value m_lastValue; // 0x0
	private Boolean m_isTaskEnd; // 0x0

	public Value latestValue { get; }
	public Boolean isTaskEnd { get; }

	// RVA: 0x VA: 0x0
	public Value get_latestValue() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int64 startTime, Int64 endTime, Options options) { }
	// RVA: 0x VA: 0x0
	public Void ResetTime(Int64 startTime, Int64 endTime) { }
	// RVA: 0x VA: 0x0
	public Boolean get_isTaskEnd() { }
	// RVA: 0x VA: 0x0
	public Void Interrupt() { }
	// RVA: 0x VA: 0x0
	public Void Tick() { }
}
```