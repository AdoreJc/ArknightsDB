# ExceptionHandlingClause

**Namespace:** `System.Reflection`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class ExceptionHandlingClause
{
	internal Type catch_type; // 0x10
	internal Int32 filter_offset; // 0x18
	internal ExceptionHandlingClauseOptions flags; // 0x1c
	internal Int32 try_offset; // 0x20
	internal Int32 try_length; // 0x24
	internal Int32 handler_offset; // 0x28
	internal Int32 handler_length; // 0x2c


	// RVA: 0x5ff1b3c VA: 0x7598609b3c
	protected Void .ctor() { }
	// RVA: 0x5ff1b44 VA: 0x7598609b44
	public override String ToString() { }
}
```