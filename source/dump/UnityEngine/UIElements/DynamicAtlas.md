# DynamicAtlas

**Namespace:** `UnityEngine.UIElements`


## Fields

- `DynamicAtlasPage m_PointPage`

- `DynamicAtlasPage m_BilinearPage`

- `ColorSpace m_ColorSpace`

- `Int32 m_MinAtlasSize`

- `Int32 m_MaxAtlasSize`

- `Int32 m_MaxSubTextureSize`

- `DynamicAtlasFilters m_ActiveFilters`

- `DynamicAtlasCustomFilter m_CustomFilter`


## Properties

- `Int32 minAtlasSize`

- `Int32 maxAtlasSize`

- `DynamicAtlasFilters activeFilters`

- `Int32 maxSubTextureSize`

- `DynamicAtlasCustomFilter customFilter`


## Methods

- `Void InitPages()`

- `Void DestroyPages()`

- `Void set_minAtlasSize(Int32)`

- `Void set_maxAtlasSize(Int32)`

- `Void set_activeFilters(DynamicAtlasFilters)`

- `Int32 get_maxSubTextureSize()`

- `Void set_maxSubTextureSize(Int32)`

- `Void set_customFilter(DynamicAtlasCustomFilter)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DynamicAtlas : AtlasBase
{
	private Dictionary`2 m_Database; // 0x18
	private DynamicAtlasPage m_PointPage; // 0x20
	private DynamicAtlasPage m_BilinearPage; // 0x28
	private ColorSpace m_ColorSpace; // 0x30
	private List`1 m_Panels; // 0x38
	private Int32 m_MinAtlasSize; // 0x40
	private Int32 m_MaxAtlasSize; // 0x44
	private Int32 m_MaxSubTextureSize; // 0x48
	private DynamicAtlasFilters m_ActiveFilters; // 0x4c
	private DynamicAtlasCustomFilter m_CustomFilter; // 0x50

	internal Boolean isInitialized { get; }
	public Int32 minAtlasSize { set; }
	public Int32 maxAtlasSize { set; }
	public static DynamicAtlasFilters defaultFilters { get; }
	public DynamicAtlasFilters activeFilters { set; }
	public Int32 maxSubTextureSize { get; set; }
	public DynamicAtlasCustomFilter customFilter { set; }

	// RVA: 0x692d944 VA: 0x7598f45944
	internal Boolean get_isInitialized() { }
	// RVA: 0x692d964 VA: 0x7598f45964
	protected override Void OnAssignedToPanel(IPanel panel) { }
	// RVA: 0x692da40 VA: 0x7598f45a40
	protected override Void OnRemovedFromPanel(IPanel panel) { }
	// RVA: 0x692db70 VA: 0x7598f45b70
	public override Void Reset() { }
	// RVA: 0x692dc1c VA: 0x7598f45c1c
	private Void InitPages() { }
	// RVA: 0x692dad8 VA: 0x7598f45ad8
	private Void DestroyPages() { }
	// RVA: 0x692dd38 VA: 0x7598f45d38
	public override Boolean TryGetAtlas(VisualElement ve, Texture2D src, out TextureId atlas, out RectInt atlasRect) { }
	// RVA: 0x692e0dc VA: 0x7598f460dc
	public override Void ReturnAtlas(VisualElement ve, Texture2D src, TextureId atlas) { }
	// RVA: 0x692e218 VA: 0x7598f46218
	protected override Void OnUpdateDynamicTextures(IPanel panel) { }
	// RVA: 0x692e280 VA: 0x7598f46280
	internal static Boolean IsTextureFormatSupported(TextureFormat format) { }
	// RVA: 0x692e2b4 VA: 0x7598f462b4
	public virtual Boolean IsTextureValid(Texture2D texture, FilterMode atlasFilterMode) { }
	// RVA: 0x692e3dc VA: 0x7598f463dc
	public Void set_minAtlasSize(Int32 value) { }
	// RVA: 0x692e3fc VA: 0x7598f463fc
	public Void set_maxAtlasSize(Int32 value) { }
	// RVA: 0x692e41c VA: 0x7598f4641c
	public static DynamicAtlasFilters get_defaultFilters() { }
	// RVA: 0x692e424 VA: 0x7598f46424
	public Void set_activeFilters(DynamicAtlasFilters value) { }
	// RVA: 0x692e3d4 VA: 0x7598f463d4
	public Int32 get_maxSubTextureSize() { }
	// RVA: 0x692e444 VA: 0x7598f46444
	public Void set_maxSubTextureSize(Int32 value) { }
	// RVA: 0x692e464 VA: 0x7598f46464
	public Void set_customFilter(DynamicAtlasCustomFilter value) { }
	// RVA: 0x692e4bc VA: 0x7598f464bc
	public Void .ctor() { }
}
```