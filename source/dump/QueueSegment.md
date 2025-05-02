# QueueSegment

**Namespace:** ` `


## Fields

- `Int32 indexes`

- `QueueSegment Next`


## Methods

- `Void GetIndexes(out, out)`

- `Boolean CompareExchangeIndexes(ref, Int32, ref, Int32)`

- `Boolean IsUsedUp()`

- `Boolean TryEnqueue(IThreadPoolWorkItem)`

- `Boolean TryDequeue(out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class QueueSegment
{
	internal readonly IThreadPoolWorkItem[] nodes; // 0x10
	private Int32 indexes; // 0x18
	public QueueSegment Next; // 0x20


	// RVA: 0x61266dc VA: 0x759873e6dc
	private Void GetIndexes(out Int32 upper, out Int32 lower) { }
	// RVA: 0x6126710 VA: 0x759873e710
	private Boolean CompareExchangeIndexes(ref Int32 prevUpper, Int32 newUpper, ref Int32 prevLower, Int32 newLower) { }
	// RVA: 0x6124a4c VA: 0x759873ca4c
	public Void .ctor() { }
	// RVA: 0x6125e24 VA: 0x759873de24
	public Boolean IsUsedUp() { }
	// RVA: 0x612538c VA: 0x759873d38c
	public Boolean TryEnqueue(IThreadPoolWorkItem node) { }
	// RVA: 0x6125ce0 VA: 0x759873dce0
	public Boolean TryDequeue(out IThreadPoolWorkItem node) { }
}
```