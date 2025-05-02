# DynamicAtlasSettings

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_MinAtlasSize`

- `Int32 m_MaxAtlasSize`

- `Int32 m_MaxSubTextureSize`

- `DynamicAtlasFiltersInternal m_ActiveFilters`

- `DynamicAtlasCustomFilter m_CustomFilter`


## Properties

- `Int32 minAtlasSize`

- `Int32 maxAtlasSize`

- `Int32 maxSubTextureSize`

- `DynamicAtlasFilters activeFilters`

- `DynamicAtlasCustomFilter customFilter`


## Methods

- `Int32 get_minAtlasSize()`

- `Void set_minAtlasSize(Int32)`

- `Int32 get_maxAtlasSize()`

- `Void set_maxAtlasSize(Int32)`

- `Int32 get_maxSubTextureSize()`

- `Void set_maxSubTextureSize(Int32)`

- `DynamicAtlasFilters get_activeFilters()`

- `Void set_activeFilters(DynamicAtlasFilters)`

- `DynamicAtlasCustomFilter get_customFilter()`

- `Void set_customFilter(DynamicAtlasCustomFilter)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class DynamicAtlasSettings
{
	private Int32 m_MinAtlasSize; // 0x10
	private Int32 m_MaxAtlasSize; // 0x14
	private Int32 m_MaxSubTextureSize; // 0x18
	private DynamicAtlasFiltersInternal m_ActiveFilters; // 0x1c
	private DynamicAtlasCustomFilter m_CustomFilter; // 0x20

	public Int32 minAtlasSize { get; set; }
	public Int32 maxAtlasSize { get; set; }
	public Int32 maxSubTextureSize { get; set; }
	public DynamicAtlasFilters activeFilters { get; set; }
	public static DynamicAtlasFilters defaultFilters { get; }
	public DynamicAtlasCustomFilter customFilter { get; set; }
	public static DynamicAtlasSettings defaults { get; }

	// RVA: 0x69ff3b0 VA: 0x75990173b0
	public Int32 get_minAtlasSize() { }
	// RVA: 0x69ff3b8 VA: 0x75990173b8
	public Void set_minAtlasSize(Int32 value) { }
	// RVA: 0x69ff3c0 VA: 0x75990173c0
	public Int32 get_maxAtlasSize() { }
	// RVA: 0x69ff3c8 VA: 0x75990173c8
	public Void set_maxAtlasSize(Int32 value) { }
	// RVA: 0x69ff3d0 VA: 0x75990173d0
	public Int32 get_maxSubTextureSize() { }
	// RVA: 0x69ff3d8 VA: 0x75990173d8
	public Void set_maxSubTextureSize(Int32 value) { }
	// RVA: 0x69ff3e0 VA: 0x75990173e0
	public DynamicAtlasFilters get_activeFilters() { }
	// RVA: 0x69ff3e8 VA: 0x75990173e8
	public Void set_activeFilters(DynamicAtlasFilters value) { }
	// RVA: 0x69ff3f0 VA: 0x75990173f0
	public static DynamicAtlasFilters get_defaultFilters() { }
	// RVA: 0x69ff3f8 VA: 0x75990173f8
	public DynamicAtlasCustomFilter get_customFilter() { }
	// RVA: 0x69ff400 VA: 0x7599017400
	public Void set_customFilter(DynamicAtlasCustomFilter value) { }
	// RVA: 0x69ff408 VA: 0x7599017408
	public static DynamicAtlasSettings get_defaults() { }
	// RVA: 0x69ff494 VA: 0x7599017494
	public Void .ctor() { }
}
```