# DefaultTraceListener

**Namespace:** `System.Diagnostics`


## Fields

- `String logFileName`


## Properties

- `String LogFileName`


## Methods

- `String get_LogFileName()`

- `Void WriteDebugString(String)`

- `Void WriteMonoTrace(String)`

- `Void WritePrefix()`

- `Void WriteImpl(String)`

- `Void WriteLogFile(String, String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public class DefaultTraceListener : TraceListener
{
	private static readonly Boolean OnWin32; // 0x0
	private static readonly String MonoTracePrefix; // 0x8
	private static readonly String MonoTraceFile; // 0x10
	private String logFileName; // 0x38

	public String LogFileName { get; }

	// RVA: 0x6399e24 VA: 0x75989b1e24
	private static Void .cctor() { }
	// RVA: 0x6399f94 VA: 0x75989b1f94
	private static String GetPrefix(String var, String target) { }
	// RVA: 0x6396cc0 VA: 0x75989aecc0
	public Void .ctor() { }
	// RVA: 0x639a010 VA: 0x75989b2010
	public String get_LogFileName() { }
	// RVA: 0x639a018 VA: 0x75989b2018
	private static Void WriteWindowsDebugString(Char* message) { }
	// RVA: 0x639a01c VA: 0x75989b201c
	private Void WriteDebugString(String message) { }
	// RVA: 0x639a0cc VA: 0x75989b20cc
	private Void WriteMonoTrace(String message) { }
	// RVA: 0x639a4f4 VA: 0x75989b24f4
	private Void WritePrefix() { }
	// RVA: 0x639a57c VA: 0x75989b257c
	private Void WriteImpl(String message) { }
	// RVA: 0x639a278 VA: 0x75989b2278
	private Void WriteLogFile(String message, String logFile) { }
	// RVA: 0x639a638 VA: 0x75989b2638
	public override Void Write(String message) { }
	// RVA: 0x639a63c VA: 0x75989b263c
	public override Void WriteLine(String message) { }
}
```