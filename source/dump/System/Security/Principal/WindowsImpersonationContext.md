# WindowsImpersonationContext

**Namespace:** `System.Security.Principal`


## Fields

- `IntPtr _token`

- `Boolean undo`


## Methods

- `Void Dispose()`

- `Void Undo()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Principal
public class WindowsImpersonationContext : IDisposable
{
	private IntPtr _token; // 0x10
	private Boolean undo; // 0x18


	// RVA: 0x5f7850c VA: 0x759859050c
	internal Void .ctor(IntPtr token) { }
	// RVA: 0x5f78b08 VA: 0x7598590b08
	public Void Dispose() { }
	// RVA: 0x5f78b18 VA: 0x7598590b18
	public Void Undo() { }
	// RVA: 0x5f78be0 VA: 0x7598590be0
	private static Boolean CloseToken(IntPtr token) { }
	// RVA: 0x5f78b00 VA: 0x7598590b00
	private static IntPtr DuplicateToken(IntPtr token) { }
	// RVA: 0x5f78b04 VA: 0x7598590b04
	private static Boolean SetCurrentToken(IntPtr token) { }
	// RVA: 0x5f78bdc VA: 0x7598590bdc
	private static Boolean RevertToSelf() { }
}
```