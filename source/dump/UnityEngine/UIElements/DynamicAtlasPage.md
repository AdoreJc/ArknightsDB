# DynamicAtlasPage

**Namespace:** `UnityEngine.UIElements`


## Fields

- `TextureId <textureId>k__BackingField`

- `RenderTexture <atlas>k__BackingField`

- `Allocator2D m_Allocator`

- `TextureBlitter m_Blitter`

- `Vector2Int m_CurrentSize`

- `Boolean <disposed>k__BackingField`


## Properties

- `TextureId textureId`

- `RenderTexture atlas`

- `RenderTextureFormat format`

- `FilterMode filterMode`

- `Boolean disposed`


## Methods

- `TextureId get_textureId()`

- `Void set_textureId(TextureId)`

- `RenderTexture get_atlas()`

- `Void set_atlas(RenderTexture)`

- `RenderTextureFormat get_format()`

- `FilterMode get_filterMode()`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Boolean TryAdd(Texture2D, out, out)`

- `Void Update(Texture2D, RectInt)`

- `Void Remove(Alloc2D)`

- `Void Commit()`

- `Void UpdateAtlasTexture()`

- `RenderTexture CreateAtlasTexture()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class DynamicAtlasPage : IDisposable
{
	private TextureId <textureId>k__BackingField; // 0x10
	private RenderTexture <atlas>k__BackingField; // 0x18
	private readonly RenderTextureFormat <format>k__BackingField; // 0x20
	private readonly FilterMode <filterMode>k__BackingField; // 0x24
	private readonly Vector2Int <minSize>k__BackingField; // 0x28
	private readonly Vector2Int <maxSize>k__BackingField; // 0x30
	private readonly Int32 m_1Padding; // 0x38
	private readonly Int32 m_2Padding; // 0x3c
	private Allocator2D m_Allocator; // 0x40
	private TextureBlitter m_Blitter; // 0x48
	private Vector2Int m_CurrentSize; // 0x50
	private static Int32 s_TextureCounter; // 0x0
	private Boolean <disposed>k__BackingField; // 0x58

	public TextureId textureId { get; set; }
	public RenderTexture atlas { get; set; }
	public RenderTextureFormat format { get; }
	public FilterMode filterMode { get; }
	protected Boolean disposed { get; set; }

	// RVA: 0x6a05038 VA: 0x759901d038
	public TextureId get_textureId() { }
	// RVA: 0x6a05040 VA: 0x759901d040
	private Void set_textureId(TextureId value) { }
	// RVA: 0x6a05048 VA: 0x759901d048
	public RenderTexture get_atlas() { }
	// RVA: 0x6a05050 VA: 0x759901d050
	private Void set_atlas(RenderTexture value) { }
	// RVA: 0x6a05058 VA: 0x759901d058
	public RenderTextureFormat get_format() { }
	// RVA: 0x6a05060 VA: 0x759901d060
	public FilterMode get_filterMode() { }
	// RVA: 0x6a05068 VA: 0x759901d068
	public Void .ctor(RenderTextureFormat format, FilterMode filterMode, Vector2Int minSize, Vector2Int maxSize) { }
	// RVA: 0x6a051f0 VA: 0x759901d1f0
	protected Boolean get_disposed() { }
	// RVA: 0x6a051f8 VA: 0x759901d1f8
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6a05204 VA: 0x759901d204
	public Void Dispose() { }
	// RVA: 0x6a05270 VA: 0x759901d270
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6a05784 VA: 0x759901d784
	public Boolean TryAdd(Texture2D image, out Alloc2D alloc, out RectInt rect) { }
	// RVA: 0x6a05998 VA: 0x759901d998
	public Void Update(Texture2D image, RectInt rect) { }
	// RVA: 0x6a05b38 VA: 0x759901db38
	public Void Remove(Alloc2D alloc) { }
	// RVA: 0x6a05c34 VA: 0x759901dc34
	public Void Commit() { }
	// RVA: 0x6a05c78 VA: 0x759901dc78
	private Void UpdateAtlasTexture() { }
	// RVA: 0x6a0605c VA: 0x759901e05c
	private RenderTexture CreateAtlasTexture() { }
}
```