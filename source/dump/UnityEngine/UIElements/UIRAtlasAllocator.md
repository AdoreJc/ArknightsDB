# UIRAtlasAllocator

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 <virtualWidth>k__BackingField`

- `Int32 <virtualHeight>k__BackingField`

- `Int32 <physicalWidth>k__BackingField`

- `Int32 <physicalHeight>k__BackingField`

- `AreaNode m_FirstUnpartitionedArea`

- `Int32 m_1SidePadding`

- `Int32 m_2SidePadding`

- `Boolean <disposed>k__BackingField`


## Properties

- `Int32 maxAtlasSize`

- `Int32 maxImageWidth`

- `Int32 maxImageHeight`

- `Int32 virtualWidth`

- `Int32 virtualHeight`

- `Int32 physicalWidth`

- `Int32 physicalHeight`

- `Boolean disposed`


## Methods

- `Int32 get_maxAtlasSize()`

- `Int32 get_maxImageWidth()`

- `Int32 get_maxImageHeight()`

- `Int32 get_virtualWidth()`

- `Void set_virtualWidth(Int32)`

- `Int32 get_virtualHeight()`

- `Void set_virtualHeight(Int32)`

- `Int32 get_physicalWidth()`

- `Void set_physicalWidth(Int32)`

- `Int32 get_physicalHeight()`

- `Void set_physicalHeight(Int32)`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Boolean TryAllocate(Int32, Int32, out)`

- `Boolean TryPartitionArea(AreaNode, Int32, Int32, Int32)`

- `Void BuildAreas()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class UIRAtlasAllocator : IDisposable
{
	private readonly Int32 <maxAtlasSize>k__BackingField; // 0x10
	private readonly Int32 <maxImageWidth>k__BackingField; // 0x14
	private readonly Int32 <maxImageHeight>k__BackingField; // 0x18
	private Int32 <virtualWidth>k__BackingField; // 0x1c
	private Int32 <virtualHeight>k__BackingField; // 0x20
	private Int32 <physicalWidth>k__BackingField; // 0x24
	private Int32 <physicalHeight>k__BackingField; // 0x28
	private AreaNode m_FirstUnpartitionedArea; // 0x30
	private Row[] m_OpenRows; // 0x38
	private Int32 m_1SidePadding; // 0x40
	private Int32 m_2SidePadding; // 0x44
	private static ProfilerMarker s_MarkerTryAllocate; // 0x0
	private Boolean <disposed>k__BackingField; // 0x48

	public Int32 maxAtlasSize { get; }
	public Int32 maxImageWidth { get; }
	public Int32 maxImageHeight { get; }
	public Int32 virtualWidth { get; set; }
	public Int32 virtualHeight { get; set; }
	public Int32 physicalWidth { get; set; }
	public Int32 physicalHeight { get; set; }
	protected Boolean disposed { get; set; }

	// RVA: 0x6a03ef4 VA: 0x759901bef4
	public Int32 get_maxAtlasSize() { }
	// RVA: 0x6a03efc VA: 0x759901befc
	public Int32 get_maxImageWidth() { }
	// RVA: 0x6a03f04 VA: 0x759901bf04
	public Int32 get_maxImageHeight() { }
	// RVA: 0x6a03f0c VA: 0x759901bf0c
	public Int32 get_virtualWidth() { }
	// RVA: 0x6a03f14 VA: 0x759901bf14
	private Void set_virtualWidth(Int32 value) { }
	// RVA: 0x6a03f1c VA: 0x759901bf1c
	public Int32 get_virtualHeight() { }
	// RVA: 0x6a03f24 VA: 0x759901bf24
	private Void set_virtualHeight(Int32 value) { }
	// RVA: 0x6a03f2c VA: 0x759901bf2c
	public Int32 get_physicalWidth() { }
	// RVA: 0x6a03f34 VA: 0x759901bf34
	private Void set_physicalWidth(Int32 value) { }
	// RVA: 0x6a03f3c VA: 0x759901bf3c
	public Int32 get_physicalHeight() { }
	// RVA: 0x6a03f44 VA: 0x759901bf44
	private Void set_physicalHeight(Int32 value) { }
	// RVA: 0x6a03f4c VA: 0x759901bf4c
	protected Boolean get_disposed() { }
	// RVA: 0x6a03f54 VA: 0x759901bf54
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6a03f60 VA: 0x759901bf60
	public Void Dispose() { }
	// RVA: 0x6a03fcc VA: 0x759901bfcc
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6a0418c VA: 0x759901c18c
	private static Int32 GetLog2OfNextPower(Int32 n) { }
	// RVA: 0x6a042bc VA: 0x759901c2bc
	public Void .ctor(Int32 initialAtlasSize, Int32 maxAtlasSize, Int32 sidePadding) { }
	// RVA: 0x6a04664 VA: 0x759901c664
	public Boolean TryAllocate(Int32 width, Int32 height, out RectInt location) { }
	// RVA: 0x6a04a44 VA: 0x759901ca44
	private Boolean TryPartitionArea(AreaNode areaNode, Int32 rowIndex, Int32 rowHeight, Int32 minWidth) { }
	// RVA: 0x6a04558 VA: 0x759901c558
	private Void BuildAreas() { }
	// RVA: 0x6a04e44 VA: 0x759901ce44
	private static Void .cctor() { }
}
```