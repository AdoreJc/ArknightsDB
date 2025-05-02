# Page

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `Boolean <disposed>k__BackingField`

- `Page next`

- `Int32 framesEmpty`


## Properties

- `Boolean disposed`

- `Boolean isEmpty`


## Methods

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Boolean get_isEmpty()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class Page : IDisposable
{
	private Boolean <disposed>k__BackingField; // 0x10
	public DataSet`1 vertices; // 0x18
	public DataSet`1 indices; // 0x20
	public Page next; // 0x28
	public Int32 framesEmpty; // 0x30

	protected Boolean disposed { get; set; }
	public Boolean isEmpty { get; }

	// RVA: 0x6960378 VA: 0x7598f78378
	public Void .ctor(UInt32 vertexMaxCount, UInt32 indexMaxCount, UInt32 maxQueuedFrameCount, Boolean mockPage) { }
	// RVA: 0x6965380 VA: 0x7598f7d380
	protected Boolean get_disposed() { }
	// RVA: 0x6965388 VA: 0x7598f7d388
	private Void set_disposed(Boolean value) { }
	// RVA: 0x69643e0 VA: 0x7598f7c3e0
	public Void Dispose() { }
	// RVA: 0x6965394 VA: 0x7598f7d394
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x69604d8 VA: 0x7598f784d8
	public Boolean get_isEmpty() { }
}
```