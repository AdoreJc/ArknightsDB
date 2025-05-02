# ReaderWriterCount

**Namespace:** `System.Threading`


## Fields

- `Int64 lockID`

- `Int32 readercount`

- `Int32 writercount`

- `Int32 upgradecount`

- `ReaderWriterCount next`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Threading
internal class ReaderWriterCount
{
	public Int64 lockID; // 0x10
	public Int32 readercount; // 0x18
	public Int32 writercount; // 0x1c
	public Int32 upgradecount; // 0x20
	public ReaderWriterCount next; // 0x28


	// RVA: 0x624e854 VA: 0x7598866854
	public Void .ctor() { }
}
```