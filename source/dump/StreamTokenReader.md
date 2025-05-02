# StreamTokenReader

**Namespace:** ` `


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class StreamTokenReader : ITokenReader
{
	internal StreamReader _in; // 0x10
	internal Int32 _numCharRead; // 0x18

	internal Int32 NumCharEncountered { get; }

	// RVA: 0x5f45328 VA: 0x759855d328
	internal Void .ctor(StreamReader input) { }
	// RVA: 0x5f45790 VA: 0x759855d790
	public virtual Int32 Read() { }
	// RVA: 0x5f457cc VA: 0x759855d7cc
	internal Int32 get_NumCharEncountered() { }
}
```