# WorkStealingQueue

**Namespace:** ` `


## Fields

- `Int32 m_mask`

- `Int32 m_headIndex`

- `Int32 m_tailIndex`

- `SpinLock m_foreignLock`


## Methods

- `Void LocalPush(IThreadPoolWorkItem)`

- `Boolean LocalFindAndPop(IThreadPoolWorkItem)`

- `Boolean LocalPop(out)`

- `Boolean TrySteal(out, ref)`

- `Boolean TrySteal(out, ref, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class WorkStealingQueue
{
	internal IThreadPoolWorkItem[] m_array; // 0x10
	private Int32 m_mask; // 0x18
	private Int32 m_headIndex; // 0x1c
	private Int32 m_tailIndex; // 0x20
	private SpinLock m_foreignLock; // 0x24


	// RVA: 0x6124e98 VA: 0x759873ce98
	public Void LocalPush(IThreadPoolWorkItem obj) { }
	// RVA: 0x61254b8 VA: 0x759873d4b8
	public Boolean LocalFindAndPop(IThreadPoolWorkItem obj) { }
	// RVA: 0x61259c0 VA: 0x759873d9c0
	public Boolean LocalPop(out IThreadPoolWorkItem obj) { }
	// RVA: 0x6125e68 VA: 0x759873de68
	public Boolean TrySteal(out IThreadPoolWorkItem obj, ref Boolean missedSteal) { }
	// RVA: 0x6126354 VA: 0x759873e354
	private Boolean TrySteal(out IThreadPoolWorkItem obj, ref Boolean missedSteal, Int32 millisecondsTimeout) { }
	// RVA: 0x612663c VA: 0x759873e63c
	public Void .ctor() { }
}
```