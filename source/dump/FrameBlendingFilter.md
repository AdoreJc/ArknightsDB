# FrameBlendingFilter

**Namespace:** ` `


## Fields

- `Boolean m_UseCompression`

- `RenderTextureFormat m_RawTextureFormat`

- `Int32 m_LastFrameCount`


## Methods

- `Void Dispose()`

- `Void PushFrame(CommandBuffer, RenderTargetIdentifier, Int32, Int32, Material)`

- `Void BlendFrames(CommandBuffer, Single, RenderTargetIdentifier, RenderTargetIdentifier, Material)`

- `Frame GetFrameRelative(Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class FrameBlendingFilter
{
	private Boolean m_UseCompression; // 0x10
	private RenderTextureFormat m_RawTextureFormat; // 0x14
	private Frame[] m_FrameList; // 0x18
	private Int32 m_LastFrameCount; // 0x20


	// RVA: 0x666c57c VA: 0x7598c8457c
	public Void .ctor() { }
	// RVA: 0x666c720 VA: 0x7598c84720
	public Void Dispose() { }
	// RVA: 0x666dcbc VA: 0x7598c85cbc
	public Void PushFrame(CommandBuffer cb, RenderTargetIdentifier source, Int32 width, Int32 height, Material material) { }
	// RVA: 0x666d7d8 VA: 0x7598c857d8
	public Void BlendFrames(CommandBuffer cb, Single strength, RenderTargetIdentifier source, RenderTargetIdentifier destination, Material material) { }
	// RVA: 0x666e334 VA: 0x7598c86334
	private static Boolean CheckSupportCompression() { }
	// RVA: 0x666e368 VA: 0x7598c86368
	private static RenderTextureFormat GetPreferredRenderTextureFormat() { }
	// RVA: 0x666e960 VA: 0x7598c86960
	private Frame GetFrameRelative(Int32 offset) { }
}
```