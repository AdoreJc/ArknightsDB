# GraphicsFormatUtility

**Namespace:** `UnityEngine.Experimental.Rendering`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Experimental.Rendering
public class GraphicsFormatUtility
{
	private static readonly GraphicsFormat[] tableNoStencil; // 0x0
	private static readonly GraphicsFormat[] tableStencil; // 0x8


	// RVA: 0x68a8708 VA: 0x7598ec0708
	internal static GraphicsFormat GetFormat(Texture texture) { }
	// RVA: 0x68a8744 VA: 0x7598ec0744
	public static GraphicsFormat GetGraphicsFormat(TextureFormat format, Boolean isSRGB) { }
	// RVA: 0x68a87c8 VA: 0x7598ec07c8
	private static GraphicsFormat GetGraphicsFormat_Native_TextureFormat(TextureFormat format, Boolean isSRGB) { }
	// RVA: 0x68a880c VA: 0x7598ec080c
	public static GraphicsFormat GetGraphicsFormat(RenderTextureFormat format, Boolean isSRGB) { }
	// RVA: 0x68a8890 VA: 0x7598ec0890
	private static GraphicsFormat GetGraphicsFormat_Native_RenderTextureFormat(RenderTextureFormat format, Boolean isSRGB) { }
	// RVA: 0x68a88d4 VA: 0x7598ec08d4
	public static GraphicsFormat GetGraphicsFormat(RenderTextureFormat format, RenderTextureReadWrite readWrite) { }
	// RVA: 0x68a895c VA: 0x7598ec095c
	private static GraphicsFormat GetDepthStencilFormatFromBitsLegacy_Native(Int32 minimumDepthBits) { }
	// RVA: 0x68a8998 VA: 0x7598ec0998
	internal static GraphicsFormat GetDepthStencilFormat(Int32 minimumDepthBits) { }
	// RVA: 0x68a8a0c VA: 0x7598ec0a0c
	public static Int32 GetDepthBits(GraphicsFormat format) { }
	// RVA: 0x68a8a48 VA: 0x7598ec0a48
	public static GraphicsFormat GetDepthStencilFormat(Int32 minimumDepthBits, Int32 minimumStencilBits) { }
	// RVA: 0x68a8c3c VA: 0x7598ec0c3c
	public static Boolean IsSRGBFormat(GraphicsFormat format) { }
	// RVA: 0x68a8c78 VA: 0x7598ec0c78
	public static GraphicsFormat GetSRGBFormat(GraphicsFormat format) { }
	// RVA: 0x68a8cb4 VA: 0x7598ec0cb4
	public static GraphicsFormat GetLinearFormat(GraphicsFormat format) { }
	// RVA: 0x68a8cf0 VA: 0x7598ec0cf0
	public static RenderTextureFormat GetRenderTextureFormat(GraphicsFormat format) { }
	// RVA: 0x68a8d2c VA: 0x7598ec0d2c
	internal static Boolean IsCompressedTextureFormat(TextureFormat format) { }
	// RVA: 0x68a8d68 VA: 0x7598ec0d68
	private static Boolean CanDecompressFormat(GraphicsFormat format, Boolean wholeImage) { }
	// RVA: 0x68a8dac VA: 0x7598ec0dac
	internal static Boolean CanDecompressFormat(GraphicsFormat format) { }
	// RVA: 0x68a8e24 VA: 0x7598ec0e24
	public static Boolean IsDepthFormat(GraphicsFormat format) { }
	// RVA: 0x68a8e60 VA: 0x7598ec0e60
	public static Boolean IsStencilFormat(GraphicsFormat format) { }
	// RVA: 0x68a8e9c VA: 0x7598ec0e9c
	public static Boolean IsPVRTCFormat(GraphicsFormat format) { }
	// RVA: 0x68a8ed8 VA: 0x7598ec0ed8
	public static Boolean IsCrunchFormat(TextureFormat format) { }
	// RVA: 0x68a8efc VA: 0x7598ec0efc
	private static Void .cctor() { }
}
```