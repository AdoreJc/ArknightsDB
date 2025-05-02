# TextureLerper

**Namespace:** `UnityEngine.Rendering.PostProcessing`


## Fields

- `CommandBuffer m_Command`

- `PropertySheetFactory m_PropertySheets`

- `PostProcessResources m_Resources`


## Methods

- `RenderTexture Get(RenderTextureFormat, Int32, Int32, Int32, Boolean, Boolean)`


## Dump
```C#
// Dll : Unity.Postprocessing.Runtime.dll
// Namespace : UnityEngine.Rendering.PostProcessing
internal class TextureLerper
{
	private static TextureLerper m_Instance; // 0x0
	private CommandBuffer m_Command; // 0x10
	private PropertySheetFactory m_PropertySheets; // 0x18
	private PostProcessResources m_Resources; // 0x20
	private List`1 m_Recycled; // 0x28
	private List`1 m_Actives; // 0x30

	internal static TextureLerper instance { get; }

	// RVA: 0x6819df8 VA: 0x7598e31df8
	internal static TextureLerper get_instance() { }
	// RVA: 0x6819e84 VA: 0x7598e31e84
	private Void .ctor() { }
	// RVA: 0x6819f3c VA: 0x7598e31f3c
	internal Void BeginFrame(PostProcessRenderContext context) { }
	// RVA: 0x6819f88 VA: 0x7598e31f88
	internal Void EndFrame() { }
	// RVA: 0x681a2ac VA: 0x7598e322ac
	private RenderTexture Get(RenderTextureFormat format, Int32 w, Int32 h, Int32 d, Boolean enableRandomWrite, Boolean force3D) { }
	// RVA: 0x681a5c8 VA: 0x7598e325c8
	internal Texture Lerp(Texture from, Texture to, Single t) { }
	// RVA: 0x681acb0 VA: 0x7598e32cb0
	internal Texture Lerp(Texture from, Color to, Single t) { }
	// RVA: 0x681b2c0 VA: 0x7598e332c0
	internal Void Clear() { }
}
```