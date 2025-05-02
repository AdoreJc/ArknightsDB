# IOSelectorJob

**Namespace:** `System`


## Fields

- `IOOperation operation`

- `IOAsyncCallback callback`

- `IOAsyncResult state`


## Methods

- `Void MarkDisposed()`


## Dump
```C#
// Dll : System.dll
// Namespace : System
internal class IOSelectorJob : IThreadPoolWorkItem
{
	private IOOperation operation; // 0x10
	private IOAsyncCallback callback; // 0x18
	private IOAsyncResult state; // 0x20


	// RVA: 0x637490c VA: 0x759898c90c
	public Void .ctor(IOOperation operation, IOAsyncCallback callback, IOAsyncResult state) { }
	// RVA: 0x6374960 VA: 0x759898c960
	private Void System.Threading.IThreadPoolWorkItem.ExecuteWorkItem() { }
	// RVA: 0x6374988 VA: 0x759898c988
	private Void System.Threading.IThreadPoolWorkItem.MarkAborted(ThreadAbortException tae) { }
	// RVA: 0x637498c VA: 0x759898c98c
	public Void MarkDisposed() { }
}
```