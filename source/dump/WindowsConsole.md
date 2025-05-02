# WindowsConsole

**Namespace:** ` `


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class WindowsConsole
{
	public static Boolean ctrlHandlerAdded; // 0x0
	private static WindowsCancelHandler cancelHandler; // 0x8


	// RVA: 0x60fd8b0 VA: 0x75987158b0
	private static extern Int32 GetConsoleCP() { }
	// RVA: 0x60fd918 VA: 0x7598715918
	private static extern Int32 GetConsoleOutputCP() { }
	// RVA: 0x60fd984 VA: 0x7598715984
	private static Boolean DoWindowsConsoleCancelEvent(Int32 keyCode) { }
	// RVA: 0x60fc898 VA: 0x7598714898
	public static Int32 GetInputCodePage() { }
	// RVA: 0x60fc8e4 VA: 0x75987148e4
	public static Int32 GetOutputCodePage() { }
	// RVA: 0x60fd9e4 VA: 0x75987159e4
	private static Void .cctor() { }
}
```