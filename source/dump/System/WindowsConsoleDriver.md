# WindowsConsoleDriver

**Namespace:** `System`


## Fields

- `IntPtr inputHandle`

- `IntPtr outputHandle`

- `Int16 defaultAttribute`


## Methods

- `ConsoleKeyInfo ReadKey(Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class WindowsConsoleDriver : IConsoleDriver
{
	private IntPtr inputHandle; // 0x10
	private IntPtr outputHandle; // 0x18
	private Int16 defaultAttribute; // 0x20


	// RVA: 0x611023c VA: 0x759872823c
	public Void .ctor() { }
	// RVA: 0x61103a8 VA: 0x75987283a8
	public ConsoleKeyInfo ReadKey(Boolean intercept) { }
	// RVA: 0x61105f0 VA: 0x75987285f0
	private static Boolean IsModifierKey(Int16 virtualKeyCode) { }
	// RVA: 0x6110290 VA: 0x7598728290
	private static extern IntPtr GetStdHandle(Handles handle) { }
	// RVA: 0x6110314 VA: 0x7598728314
	private static extern Boolean GetConsoleScreenBufferInfo(IntPtr handle, out ConsoleScreenBufferInfo info) { }
	// RVA: 0x61104e8 VA: 0x75987284e8
	private static extern Boolean ReadConsoleInput(IntPtr handle, out InputRecord record, Int32 length, out Int32 nread) { }
}
```