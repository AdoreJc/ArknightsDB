# GradientSettingsAtlas

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `BestFitAllocator m_Allocator`

- `Texture2D m_Atlas`

- `RawTexture m_RawAtlas`

- `Boolean <disposed>k__BackingField`

- `Boolean <MustCommit>k__BackingField`


## Properties

- `Boolean disposed`

- `Texture2D atlas`

- `Boolean MustCommit`


## Methods

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void Reset()`

- `Texture2D get_atlas()`

- `Alloc Add(Int32)`

- `Void Write(Alloc, GradientSettings[], GradientRemap)`

- `Boolean get_MustCommit()`

- `Void set_MustCommit(Boolean)`

- `Void Commit()`

- `Void PrepareAtlas()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class GradientSettingsAtlas : IDisposable
{
	private static ProfilerMarker s_MarkerWrite; // 0x0
	private static ProfilerMarker s_MarkerCommit; // 0x8
	private readonly Int32 m_Length; // 0x10
	private readonly Int32 m_ElemWidth; // 0x14
	private BestFitAllocator m_Allocator; // 0x18
	private Texture2D m_Atlas; // 0x20
	private RawTexture m_RawAtlas; // 0x28
	private static Int32 s_TextureCounter; // 0x10
	private Boolean <disposed>k__BackingField; // 0x38
	private Boolean <MustCommit>k__BackingField; // 0x39

	internal Int32 length { get; }
	protected Boolean disposed { get; set; }
	public Texture2D atlas { get; }
	public Boolean MustCommit { get; set; }

	// RVA: 0x6a28a9c VA: 0x7599040a9c
	internal Int32 get_length() { }
	// RVA: 0x6a28aa4 VA: 0x7599040aa4
	protected Boolean get_disposed() { }
	// RVA: 0x6a28aac VA: 0x7599040aac
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6a28ab8 VA: 0x7599040ab8
	public Void Dispose() { }
	// RVA: 0x6a28b24 VA: 0x7599040b24
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6a28b9c VA: 0x7599040b9c
	public Void .ctor(Int32 length) { }
	// RVA: 0x6a28bcc VA: 0x7599040bcc
	public Void Reset() { }
	// RVA: 0x6a28ca8 VA: 0x7599040ca8
	public Texture2D get_atlas() { }
	// RVA: 0x6a28cb0 VA: 0x7599040cb0
	public Alloc Add(Int32 count) { }
	// RVA: 0x6a28d9c VA: 0x7599040d9c
	public Void Write(Alloc alloc, GradientSettings[] settings, GradientRemap remap) { }
	// RVA: 0x6a293f4 VA: 0x75990413f4
	public Boolean get_MustCommit() { }
	// RVA: 0x6a293fc VA: 0x75990413fc
	private Void set_MustCommit(Boolean value) { }
	// RVA: 0x6a29408 VA: 0x7599041408
	public Void Commit() { }
	// RVA: 0x6a294d8 VA: 0x75990414d8
	private Void PrepareAtlas() { }
	// RVA: 0x6a29650 VA: 0x7599041650
	private static Void .cctor() { }
}
```