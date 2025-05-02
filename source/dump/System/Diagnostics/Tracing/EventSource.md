# EventSource

**Namespace:** `System.Diagnostics.Tracing`


## Fields

- `String <Name>k__BackingField`


## Properties

- `String Name`


## Methods

- `Void set_Name(String)`

- `Boolean IsEnabled()`

- `Boolean IsEnabled(EventLevel, EventKeywords)`

- `Void Dispose()`

- `Void WriteEvent(Int32, Int32)`

- `Void WriteEvent(Int32, Int32, Int32)`

- `Void WriteEvent(Int32, Int32, Int32, Int32)`

- `Void WriteEvent(Int32, Object[])`

- `Void WriteEvent(Int32, String, String, String)`

- `Void WriteEventCore(Int32, Int32, EventData*)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Diagnostics.Tracing
public class EventSource : IDisposable
{
	private String <Name>k__BackingField; // 0x10

	private String Name { set; }

	// RVA: 0x607b170 VA: 0x7598693170
	protected Void .ctor() { }
	// RVA: 0x607b1b4 VA: 0x75986931b4
	public Void .ctor(String eventSourceName) { }
	// RVA: 0x607b1e4 VA: 0x75986931e4
	internal Void .ctor(Guid eventSourceGuid, String eventSourceName) { }
	// RVA: 0x607b214 VA: 0x7598693214
	protected override Void Finalize() { }
	// RVA: 0x607b2b4 VA: 0x75986932b4
	private Void set_Name(String value) { }
	// RVA: 0x607b2bc VA: 0x75986932bc
	public Boolean IsEnabled() { }
	// RVA: 0x607b2c4 VA: 0x75986932c4
	public Boolean IsEnabled(EventLevel level, EventKeywords keywords) { }
	// RVA: 0x607b2cc VA: 0x75986932cc
	public Void Dispose() { }
	// RVA: 0x607b338 VA: 0x7598693338
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x607b33c VA: 0x759869333c
	protected Void WriteEvent(Int32 eventId, Int32 arg1) { }
	// RVA: 0x607b408 VA: 0x7598693408
	protected Void WriteEvent(Int32 eventId, Int32 arg1, Int32 arg2) { }
	// RVA: 0x607b524 VA: 0x7598693524
	protected Void WriteEvent(Int32 eventId, Int32 arg1, Int32 arg2, Int32 arg3) { }
	// RVA: 0x607b404 VA: 0x7598693404
	protected Void WriteEvent(Int32 eventId, Object[] args) { }
	// RVA: 0x607b694 VA: 0x7598693694
	protected Void WriteEvent(Int32 eventId, String arg1, String arg2, String arg3) { }
	// RVA: 0x607b7a0 VA: 0x75986937a0
	protected Void WriteEventCore(Int32 eventId, Int32 eventDataCount, EventData* data) { }
}
```