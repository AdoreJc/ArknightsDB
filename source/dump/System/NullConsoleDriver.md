# NullConsoleDriver

**Namespace:** `System`


## Methods

- `ConsoleKeyInfo ReadKey(Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class NullConsoleDriver : IConsoleDriver
{
	private static readonly ConsoleKeyInfo EmptyConsoleKeyInfo; // 0x0


	// RVA: 0x6105418 VA: 0x759871d418
	public ConsoleKeyInfo ReadKey(Boolean intercept) { }
	// RVA: 0x60fdd44 VA: 0x7598715d44
	public Void .ctor() { }
	// RVA: 0x6105474 VA: 0x759871d474
	private static Void .cctor() { }
}
```