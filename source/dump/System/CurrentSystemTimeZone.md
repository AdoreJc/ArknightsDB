# CurrentSystemTimeZone

**Namespace:** `System`


## Fields

- `Int64 m_ticksOffset`

- `String m_standardName`

- `String m_daylightName`


## Methods

- `DaylightTime GetCachedDaylightChanges(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class CurrentSystemTimeZone : TimeZone
{
	private Int64 m_ticksOffset; // 0x10
	private String m_standardName; // 0x18
	private String m_daylightName; // 0x20
	private readonly Hashtable m_CachedDaylightChanges; // 0x28


	// RVA: 0x608ca40 VA: 0x75986a4a40
	internal Void .ctor() { }
	// RVA: 0x608cb4c VA: 0x75986a4b4c
	public override DaylightTime GetDaylightChanges(Int32 year) { }
	// RVA: 0x608ce08 VA: 0x75986a4e08
	private static DaylightTime CreateDaylightChanges(Int32 year) { }
	// RVA: 0x608d0fc VA: 0x75986a50fc
	public override TimeSpan GetUtcOffset(DateTime time) { }
	// RVA: 0x608d270 VA: 0x75986a5270
	public static Boolean GetTimeZoneData(Int32 year, out Int64[] data, out String[] names, out Boolean daylight_inverted) { }
	// RVA: 0x608cc1c VA: 0x75986a4c1c
	private DaylightTime GetCachedDaylightChanges(Int32 year) { }
}
```