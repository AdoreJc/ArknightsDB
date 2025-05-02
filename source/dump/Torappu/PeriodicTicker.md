# PeriodicTicker

**Namespace:** `Torappu`


## Fields

- `Int32 m_tickPeriod`

- `Int32 m_tickCount`


## Properties

- `Boolean isReady`


## Methods

- `Boolean get_isReady()`

- `Void Reset(Boolean)`

- `Void Reset(Int32, Boolean)`

- `Boolean Tick()`

- `Boolean Next()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PeriodicTicker : IPeriodicTicker
{
	private Int32 m_tickPeriod; // 0x10
	private Int32 m_tickCount; // 0x14

	public Boolean isReady { get; }

	// RVA: 0x3102fa8 VA: 0x759571afa8
	public Boolean get_isReady() { }
	// RVA: 0x3102fb8 VA: 0x759571afb8
	public Void .ctor(Int32 period, Boolean waitFirstPeriod) { }
	// RVA: 0x3102ffc VA: 0x759571affc
	public Void Reset(Boolean waitFirstPeriod) { }
	// RVA: 0x3102fec VA: 0x759571afec
	public Void Reset(Int32 newPeriod, Boolean waitFirstPeriod) { }
	// RVA: 0x3103024 VA: 0x759571b024
	public Boolean Tick() { }
	// RVA: 0x3103044 VA: 0x759571b044
	public Boolean Next() { }
}
```