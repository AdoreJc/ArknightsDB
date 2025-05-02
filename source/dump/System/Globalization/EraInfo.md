# EraInfo

**Namespace:** `System.Globalization`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class EraInfo
{
	internal Int32 era; // 0x10
	internal Int64 ticks; // 0x18
	internal Int32 yearOffset; // 0x20
	internal Int32 minEraYear; // 0x24
	internal Int32 maxEraYear; // 0x28
	internal String eraName; // 0x30
	internal String abbrevEraName; // 0x38
	internal String englishEraName; // 0x40


	// RVA: 0x605c568 VA: 0x7598674568
	internal Void .ctor(Int32 era, Int32 startYear, Int32 startMonth, Int32 startDay, Int32 yearOffset, Int32 minEraYear, Int32 maxEraYear) { }
	// RVA: 0x605c648 VA: 0x7598674648
	internal Void .ctor(Int32 era, Int32 startYear, Int32 startMonth, Int32 startDay, Int32 yearOffset, Int32 minEraYear, Int32 maxEraYear, String eraName, String abbrevEraName, String englishEraName) { }
}
```