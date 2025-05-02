# DiagnosticsTraceWriter

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `TraceLevel <LevelFilter>k__BackingField`


## Properties

- `TraceLevel LevelFilter`


## Methods

- `TraceLevel get_LevelFilter()`

- `TraceEventType GetTraceEventType(TraceLevel)`

- `Void Trace(TraceLevel, String, Exception)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
public class DiagnosticsTraceWriter : ITraceWriter
{
	private TraceLevel <LevelFilter>k__BackingField; // 0x10

	public TraceLevel LevelFilter { get; }

	// RVA: 0x61640dc VA: 0x759877c0dc
	public TraceLevel get_LevelFilter() { }
	// RVA: 0x61640e4 VA: 0x759877c0e4
	private TraceEventType GetTraceEventType(TraceLevel level) { }
	// RVA: 0x6164154 VA: 0x759877c154
	public Void Trace(TraceLevel level, String message, Exception ex) { }
	// RVA: 0x61645c4 VA: 0x759877c5c4
	public Void .ctor() { }
}
```