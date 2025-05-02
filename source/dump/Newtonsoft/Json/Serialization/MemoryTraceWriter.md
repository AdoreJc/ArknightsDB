# MemoryTraceWriter

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `TraceLevel <LevelFilter>k__BackingField`


## Properties

- `TraceLevel LevelFilter`


## Methods

- `TraceLevel get_LevelFilter()`

- `Void set_LevelFilter(TraceLevel)`

- `Void Trace(TraceLevel, String, Exception)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class MemoryTraceWriter : ITraceWriter
{
	private readonly Queue`1 _traceMessages; // 0x10
	private TraceLevel <LevelFilter>k__BackingField; // 0x18

	public TraceLevel LevelFilter { get; set; }

	// RVA: 0x616476c VA: 0x759877c76c
	public TraceLevel get_LevelFilter() { }
	// RVA: 0x6164774 VA: 0x759877c774
	public Void set_LevelFilter(TraceLevel value) { }
	// RVA: 0x616477c VA: 0x759877c77c
	public Void .ctor() { }
	// RVA: 0x616480c VA: 0x759877c80c
	public Void Trace(TraceLevel level, String message, Exception ex) { }
	// RVA: 0x6164a3c VA: 0x759877ca3c
	public override String ToString() { }
}
```