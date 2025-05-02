# TraceEventCache

**Namespace:** `System.Diagnostics`


## Fields

- `Int64 timeStamp`

- `DateTime dateTime`

- `String stackTrace`


## Properties

- `String Callstack`

- `Stack LogicalOperationStack`

- `DateTime DateTime`

- `Int32 ProcessId`

- `String ThreadId`

- `Int64 Timestamp`


## Methods

- `String get_Callstack()`

- `Stack get_LogicalOperationStack()`

- `DateTime get_DateTime()`

- `Int32 get_ProcessId()`

- `String get_ThreadId()`

- `Int64 get_Timestamp()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Diagnostics
public class TraceEventCache
{
	private static Int32 processId; // 0x0
	private static String processName; // 0x8
	private Int64 timeStamp; // 0x10
	private DateTime dateTime; // 0x18
	private String stackTrace; // 0x20

	public String Callstack { get; }
	public Stack LogicalOperationStack { get; }
	public DateTime DateTime { get; }
	public Int32 ProcessId { get; }
	public String ThreadId { get; }
	public Int64 Timestamp { get; }

	// RVA: 0x639655c VA: 0x75989ae55c
	public String get_Callstack() { }
	// RVA: 0x639658c VA: 0x75989ae58c
	public Stack get_LogicalOperationStack() { }
	// RVA: 0x63965a4 VA: 0x75989ae5a4
	public DateTime get_DateTime() { }
	// RVA: 0x6396638 VA: 0x75989ae638
	public Int32 get_ProcessId() { }
	// RVA: 0x6396690 VA: 0x75989ae690
	public String get_ThreadId() { }
	// RVA: 0x6396720 VA: 0x75989ae720
	public Int64 get_Timestamp() { }
	// RVA: 0x6396788 VA: 0x75989ae788
	private static Void InitProcessInfo() { }
	// RVA: 0x639663c VA: 0x75989ae63c
	internal static Int32 GetProcessId() { }
	// RVA: 0x6396700 VA: 0x75989ae700
	internal static Int32 GetThreadId() { }
	// RVA: 0x6396ba8 VA: 0x75989aeba8
	public Void .ctor() { }
}
```