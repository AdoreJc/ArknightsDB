# BestFitAllocator

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `Block m_FirstBlock`

- `Block m_FirstAvailableBlock`

- `BlockPool m_BlockPool`

- `UInt32 m_HighWatermark`


## Properties

- `UInt32 totalSize`

- `UInt32 highWatermark`


## Methods

- `UInt32 get_totalSize()`

- `UInt32 get_highWatermark()`

- `Alloc Allocate(UInt32)`

- `Void Free(Alloc)`

- `Block CoalesceBlockWithPrevious(Block)`

- `Block BestFitFindAvailableBlock(UInt32)`

- `Void SplitBlock(Block, UInt32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class BestFitAllocator
{
	private readonly UInt32 <totalSize>k__BackingField; // 0x10
	private Block m_FirstBlock; // 0x18
	private Block m_FirstAvailableBlock; // 0x20
	private BlockPool m_BlockPool; // 0x28
	private UInt32 m_HighWatermark; // 0x30

	public UInt32 totalSize { get; }
	public UInt32 highWatermark { get; }

	// RVA: 0x6964860 VA: 0x7598f7c860
	public Void .ctor(UInt32 size) { }
	// RVA: 0x6964a30 VA: 0x7598f7ca30
	public UInt32 get_totalSize() { }
	// RVA: 0x6964a38 VA: 0x7598f7ca38
	public UInt32 get_highWatermark() { }
	// RVA: 0x6964a40 VA: 0x7598f7ca40
	public Alloc Allocate(UInt32 size) { }
	// RVA: 0x6964e10 VA: 0x7598f7ce10
	public Void Free(Alloc alloc) { }
	// RVA: 0x696509c VA: 0x7598f7d09c
	private Block CoalesceBlockWithPrevious(Block block) { }
	// RVA: 0x6964c50 VA: 0x7598f7cc50
	private Block BestFitFindAvailableBlock(UInt32 size) { }
	// RVA: 0x6964c9c VA: 0x7598f7cc9c
	private Void SplitBlock(Block block, UInt32 size) { }
}
```