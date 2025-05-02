# PostProcessingContext

**Namespace:** `UnityEngine.PostProcessing`


## Fields

- `PostProcessingProfile profile`

- `Camera camera`

- `MaterialFactory materialFactory`

- `RenderTextureFactory renderTextureFactory`

- `Boolean <interrupted>k__BackingField`


## Properties

- `Boolean interrupted`

- `Boolean isGBufferAvailable`

- `Boolean isHdr`

- `Int32 width`

- `Int32 height`

- `Rect viewport`


## Methods

- `Boolean get_interrupted()`

- `Void set_interrupted(Boolean)`

- `Void Interrupt()`

- `PostProcessingContext Reset()`

- `Boolean get_isGBufferAvailable()`

- `Boolean get_isHdr()`

- `Int32 get_width()`

- `Int32 get_height()`

- `Rect get_viewport()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : UnityEngine.PostProcessing
public class PostProcessingContext
{
	public PostProcessingProfile profile; // 0x10
	public Camera camera; // 0x18
	public MaterialFactory materialFactory; // 0x20
	public RenderTextureFactory renderTextureFactory; // 0x28
	private Boolean <interrupted>k__BackingField; // 0x30

	public Boolean interrupted { get; set; }
	public Boolean isGBufferAvailable { get; }
	public Boolean isHdr { get; }
	public Int32 width { get; }
	public Int32 height { get; }
	public Rect viewport { get; }

	// RVA: 0x6675910 VA: 0x7598c8d910
	public Boolean get_interrupted() { }
	// RVA: 0x6675918 VA: 0x7598c8d918
	private Void set_interrupted(Boolean value) { }
	// RVA: 0x66669a4 VA: 0x7598c7e9a4
	public Void Interrupt() { }
	// RVA: 0x6674494 VA: 0x7598c8c494
	public PostProcessingContext Reset() { }
	// RVA: 0x66661f4 VA: 0x7598c7e1f4
	public Boolean get_isGBufferAvailable() { }
	// RVA: 0x666b9e8 VA: 0x7598c839e8
	public Boolean get_isHdr() { }
	// RVA: 0x6665c6c VA: 0x7598c7dc6c
	public Int32 get_width() { }
	// RVA: 0x6665c88 VA: 0x7598c7dc88
	public Int32 get_height() { }
	// RVA: 0x6668eb4 VA: 0x7598c80eb4
	public Rect get_viewport() { }
	// RVA: 0x6673f14 VA: 0x7598c8bf14
	public Void .ctor() { }
}
```