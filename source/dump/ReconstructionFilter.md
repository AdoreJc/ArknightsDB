# ReconstructionFilter

**Namespace:** ` `


## Fields

- `RenderTextureFormat m_VectorRTFormat`

- `RenderTextureFormat m_PackedRTFormat`


## Methods

- `Void CheckTextureFormatSupport()`

- `Boolean IsSupported()`

- `Void ProcessImage(PostProcessingContext, CommandBuffer, ref, RenderTargetIdentifier, RenderTargetIdentifier, Material)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class ReconstructionFilter
{
	private RenderTextureFormat m_VectorRTFormat; // 0x10
	private RenderTextureFormat m_PackedRTFormat; // 0x14


	// RVA: 0x666c4d0 VA: 0x7598c844d0
	public Void .ctor() { }
	// RVA: 0x666e310 VA: 0x7598c86310
	private Void CheckTextureFormatSupport() { }
	// RVA: 0x666c6b0 VA: 0x7598c846b0
	public Boolean IsSupported() { }
	// RVA: 0x666ce7c VA: 0x7598c84e7c
	public Void ProcessImage(PostProcessingContext context, CommandBuffer cb, ref Settings settings, RenderTargetIdentifier source, RenderTargetIdentifier destination, Material material) { }
}
```