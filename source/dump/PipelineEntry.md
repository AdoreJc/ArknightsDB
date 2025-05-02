# PipelineEntry

**Namespace:** ` `


## Dump
```C#
// Dll : System.dll
// Namespace : 
internal class PipelineEntry
{
	internal String Command; // 0x10
	internal PipelineEntryFlags Flags; // 0x18


	// RVA: 0x641b210 VA: 0x7598a33210
	internal Void .ctor(String command) { }
	// RVA: 0x641b240 VA: 0x7598a33240
	internal Void .ctor(String command, PipelineEntryFlags flags) { }
	// RVA: 0x6419e08 VA: 0x7598a31e08
	internal Boolean HasFlag(PipelineEntryFlags flags) { }
}
```