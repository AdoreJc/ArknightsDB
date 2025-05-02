# DataSet

**Namespace:** ` `


## Fields

- `Boolean <disposed>k__BackingField`

- `GPUBufferAllocator allocator`

- `UInt32 m_ElemStride`

- `UInt32 m_UpdateRangeMin`

- `UInt32 m_UpdateRangeMax`

- `UInt32 m_UpdateRangesEnqueued`

- `UInt32 m_UpdateRangesBatchStart`

- `Boolean m_UpdateRangesSaturated`


## Properties

- `Boolean disposed`


## Methods

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void Dispose(Boolean)`

- `Void RegisterUpdate(UInt32, UInt32)`

- `Boolean HasMappedBufferRange()`

- `Void SendUpdates()`

- `Void SendFullRange()`

- `Void SendPartialRanges()`

- `Void ResetUpdateState()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
public class DataSet`1 : IDisposable
{
	private Boolean <disposed>k__BackingField; // 0x0
	public GPUBuffer`1 gpuData; // 0x0
	public NativeArray`1 cpuData; // 0x0
	public NativeArray`1 updateRanges; // 0x0
	public GPUBufferAllocator allocator; // 0x0
	private readonly UInt32 m_UpdateRangePoolSize; // 0x0
	private UInt32 m_ElemStride; // 0x0
	private UInt32 m_UpdateRangeMin; // 0x0
	private UInt32 m_UpdateRangeMax; // 0x0
	private UInt32 m_UpdateRangesEnqueued; // 0x0
	private UInt32 m_UpdateRangesBatchStart; // 0x0
	private Boolean m_UpdateRangesSaturated; // 0x0

	protected Boolean disposed { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(GPUBufferType bufferType, UInt32 totalCount, UInt32 maxQueuedFrameCount, UInt32 updateRangePoolSize, Boolean mockBuffer) { }
	// RVA: 0x VA: 0x0
	protected Boolean get_disposed() { }
	// RVA: 0x VA: 0x0
	private Void set_disposed(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Void Dispose(Boolean disposing) { }
	// RVA: 0x VA: 0x0
	public Void RegisterUpdate(UInt32 start, UInt32 size) { }
	// RVA: 0x VA: 0x0
	private Boolean HasMappedBufferRange() { }
	// RVA: 0x VA: 0x0
	public Void SendUpdates() { }
	// RVA: 0x VA: 0x0
	public Void SendFullRange() { }
	// RVA: 0x VA: 0x0
	public Void SendPartialRanges() { }
	// RVA: 0x VA: 0x0
	private Void ResetUpdateState() { }
}
```