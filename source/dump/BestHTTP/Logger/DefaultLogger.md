# DefaultLogger

**Namespace:** `BestHTTP.Logger`


## Fields

- `Loglevels <Level>k__BackingField`

- `String <FormatVerbose>k__BackingField`

- `String <FormatInfo>k__BackingField`

- `String <FormatWarn>k__BackingField`

- `String <FormatErr>k__BackingField`

- `String <FormatEx>k__BackingField`


## Properties

- `Loglevels Level`

- `String FormatVerbose`

- `String FormatInfo`

- `String FormatWarn`

- `String FormatErr`

- `String FormatEx`


## Methods

- `Loglevels get_Level()`

- `Void set_Level(Loglevels)`

- `String get_FormatVerbose()`

- `Void set_FormatVerbose(String)`

- `String get_FormatInfo()`

- `Void set_FormatInfo(String)`

- `String get_FormatWarn()`

- `Void set_FormatWarn(String)`

- `String get_FormatErr()`

- `Void set_FormatErr(String)`

- `String get_FormatEx()`

- `Void set_FormatEx(String)`

- `Void Verbose(String, String)`

- `Void Information(String, String)`

- `Void Warning(String, String)`

- `Void Error(String, String)`

- `Void Exception(String, String, Exception)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Logger
public class DefaultLogger : ILogger
{
	private Loglevels <Level>k__BackingField; // 0x10
	private String <FormatVerbose>k__BackingField; // 0x18
	private String <FormatInfo>k__BackingField; // 0x20
	private String <FormatWarn>k__BackingField; // 0x28
	private String <FormatErr>k__BackingField; // 0x30
	private String <FormatEx>k__BackingField; // 0x38

	public Loglevels Level { get; set; }
	public String FormatVerbose { get; set; }
	public String FormatInfo { get; set; }
	public String FormatWarn { get; set; }
	public String FormatErr { get; set; }
	public String FormatEx { get; set; }

	// RVA: 0x66189f0 VA: 0x7598c309f0
	public Loglevels get_Level() { }
	// RVA: 0x66189f8 VA: 0x7598c309f8
	public Void set_Level(Loglevels value) { }
	// RVA: 0x6618a00 VA: 0x7598c30a00
	public String get_FormatVerbose() { }
	// RVA: 0x6618a08 VA: 0x7598c30a08
	public Void set_FormatVerbose(String value) { }
	// RVA: 0x6618a10 VA: 0x7598c30a10
	public String get_FormatInfo() { }
	// RVA: 0x6618a18 VA: 0x7598c30a18
	public Void set_FormatInfo(String value) { }
	// RVA: 0x6618a20 VA: 0x7598c30a20
	public String get_FormatWarn() { }
	// RVA: 0x6618a28 VA: 0x7598c30a28
	public Void set_FormatWarn(String value) { }
	// RVA: 0x6618a30 VA: 0x7598c30a30
	public String get_FormatErr() { }
	// RVA: 0x6618a38 VA: 0x7598c30a38
	public Void set_FormatErr(String value) { }
	// RVA: 0x6618a40 VA: 0x7598c30a40
	public String get_FormatEx() { }
	// RVA: 0x6618a48 VA: 0x7598c30a48
	public Void set_FormatEx(String value) { }
	// RVA: 0x6618a50 VA: 0x7598c30a50
	public Void .ctor() { }
	// RVA: 0x6618b90 VA: 0x7598c30b90
	public Void Verbose(String division, String verb) { }
	// RVA: 0x6618c94 VA: 0x7598c30c94
	public Void Information(String division, String info) { }
	// RVA: 0x6618d9c VA: 0x7598c30d9c
	public Void Warning(String division, String warn) { }
	// RVA: 0x6618ea4 VA: 0x7598c30ea4
	public Void Error(String division, String err) { }
	// RVA: 0x6618fac VA: 0x7598c30fac
	public Void Exception(String division, String msg, Exception ex) { }
}
```