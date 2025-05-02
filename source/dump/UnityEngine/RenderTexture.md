# RenderTexture

**Namespace:** `UnityEngine`


## Properties

- `GraphicsFormat graphicsFormat`

- `Boolean useMipMap`

- `Boolean sRGB`

- `RenderTextureFormat format`

- `GraphicsFormat depthStencilFormat`

- `Boolean autoGenerateMips`

- `Int32 volumeDepth`

- `Boolean enableRandomWrite`

- `Boolean useDynamicScale`

- `Boolean isPowerOfTwo`

- `RenderBuffer colorBuffer`

- `RenderBuffer depthBuffer`

- `Int32 depth`

- `RenderTextureDescriptor descriptor`


## Methods

- `GraphicsFormat get_graphicsFormat()`

- `Void set_graphicsFormat(GraphicsFormat)`

- `Void set_useMipMap(Boolean)`

- `Boolean get_sRGB()`

- `RenderTextureFormat get_format()`

- `Void set_depthStencilFormat(GraphicsFormat)`

- `Void set_autoGenerateMips(Boolean)`

- `Int32 get_volumeDepth()`

- `Void set_volumeDepth(Int32)`

- `Boolean get_enableRandomWrite()`

- `Void set_enableRandomWrite(Boolean)`

- `Boolean get_useDynamicScale()`

- `Void set_useDynamicScale(Boolean)`

- `Void set_isPowerOfTwo(Boolean)`

- `RenderBuffer GetColorBuffer()`

- `RenderBuffer GetDepthBuffer()`

- `Void SetMipMapCount(Int32)`

- `RenderBuffer get_colorBuffer()`

- `RenderBuffer get_depthBuffer()`

- `Void DiscardContents(Boolean, Boolean)`

- `Void MarkRestoreExpected()`

- `Void DiscardContents()`

- `Boolean Create()`

- `Void Release()`

- `Boolean IsCreated()`

- `Void SetRenderTextureDescriptor(RenderTextureDescriptor)`

- `RenderTextureDescriptor GetDescriptor()`

- `Int32 get_depth()`

- `Void Initialize(Int32, Int32, Int32, RenderTextureFormat, RenderTextureReadWrite, Int32)`

- `RenderTextureDescriptor get_descriptor()`

- `Void GetColorBuffer_Injected(out)`

- `Void GetDepthBuffer_Injected(out)`

- `Void SetRenderTextureDescriptor_Injected(ref)`

- `Void GetDescriptor_Injected(out)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class RenderTexture : Texture
{

	public override Int32 width { get; set; }
	public override Int32 height { get; set; }
	public override TextureDimension dimension { get; set; }
	public GraphicsFormat graphicsFormat { get; set; }
	public Boolean useMipMap { set; }
	public Boolean sRGB { get; }
	public RenderTextureFormat format { get; }
	public GraphicsFormat depthStencilFormat { set; }
	public Boolean autoGenerateMips { set; }
	public Int32 volumeDepth { get; set; }
	public Boolean enableRandomWrite { get; set; }
	public Boolean useDynamicScale { get; set; }
	public Boolean isPowerOfTwo { set; }
	public static RenderTexture active { get; set; }
	public RenderBuffer colorBuffer { get; }
	public RenderBuffer depthBuffer { get; }
	public Int32 depth { get; }
	public RenderTextureDescriptor descriptor { get; }

	// RVA: 0x687050c VA: 0x7598e8850c
	public override Int32 get_width() { }
	// RVA: 0x6870548 VA: 0x7598e88548
	public override Void set_width(Int32 value) { }
	// RVA: 0x687058c VA: 0x7598e8858c
	public override Int32 get_height() { }
	// RVA: 0x68705c8 VA: 0x7598e885c8
	public override Void set_height(Int32 value) { }
	// RVA: 0x687060c VA: 0x7598e8860c
	public override TextureDimension get_dimension() { }
	// RVA: 0x6870648 VA: 0x7598e88648
	public override Void set_dimension(TextureDimension value) { }
	// RVA: 0x687068c VA: 0x7598e8868c
	public GraphicsFormat get_graphicsFormat() { }
	// RVA: 0x68706c8 VA: 0x7598e886c8
	public Void set_graphicsFormat(GraphicsFormat value) { }
	// RVA: 0x687070c VA: 0x7598e8870c
	public Void set_useMipMap(Boolean value) { }
	// RVA: 0x6870750 VA: 0x7598e88750
	public Boolean get_sRGB() { }
	// RVA: 0x687078c VA: 0x7598e8878c
	public RenderTextureFormat get_format() { }
	// RVA: 0x6870918 VA: 0x7598e88918
	public Void set_depthStencilFormat(GraphicsFormat value) { }
	// RVA: 0x687095c VA: 0x7598e8895c
	public Void set_autoGenerateMips(Boolean value) { }
	// RVA: 0x68709a0 VA: 0x7598e889a0
	public Int32 get_volumeDepth() { }
	// RVA: 0x68709dc VA: 0x7598e889dc
	public Void set_volumeDepth(Int32 value) { }
	// RVA: 0x6870a20 VA: 0x7598e88a20
	public Boolean get_enableRandomWrite() { }
	// RVA: 0x6870a5c VA: 0x7598e88a5c
	public Void set_enableRandomWrite(Boolean value) { }
	// RVA: 0x6870aa0 VA: 0x7598e88aa0
	public Boolean get_useDynamicScale() { }
	// RVA: 0x6870adc VA: 0x7598e88adc
	public Void set_useDynamicScale(Boolean value) { }
	// RVA: 0x6870b20 VA: 0x7598e88b20
	public Void set_isPowerOfTwo(Boolean value) { }
	// RVA: 0x6870b24 VA: 0x7598e88b24
	private static RenderTexture GetActive() { }
	// RVA: 0x6870b4c VA: 0x7598e88b4c
	private static Void SetActive(RenderTexture rt) { }
	// RVA: 0x6870b88 VA: 0x7598e88b88
	public static RenderTexture get_active() { }
	// RVA: 0x6870bb0 VA: 0x7598e88bb0
	public static Void set_active(RenderTexture value) { }
	// RVA: 0x6870bec VA: 0x7598e88bec
	private RenderBuffer GetColorBuffer() { }
	// RVA: 0x6870c84 VA: 0x7598e88c84
	private RenderBuffer GetDepthBuffer() { }
	// RVA: 0x6870d1c VA: 0x7598e88d1c
	private Void SetMipMapCount(Int32 count) { }
	// RVA: 0x685e550 VA: 0x7598e76550
	public RenderBuffer get_colorBuffer() { }
	// RVA: 0x685e554 VA: 0x7598e76554
	public RenderBuffer get_depthBuffer() { }
	// RVA: 0x6870d60 VA: 0x7598e88d60
	public Void DiscardContents(Boolean discardColor, Boolean discardDepth) { }
	// RVA: 0x6870db4 VA: 0x7598e88db4
	public Void MarkRestoreExpected() { }
	// RVA: 0x6870df0 VA: 0x7598e88df0
	public Void DiscardContents() { }
	// RVA: 0x6870e34 VA: 0x7598e88e34
	public Boolean Create() { }
	// RVA: 0x6870e70 VA: 0x7598e88e70
	public Void Release() { }
	// RVA: 0x6870eac VA: 0x7598e88eac
	public Boolean IsCreated() { }
	// RVA: 0x6870ee8 VA: 0x7598e88ee8
	internal Void SetSRGBReadWrite(Boolean srgb) { }
	// RVA: 0x6870f2c VA: 0x7598e88f2c
	private static Void Internal_Create(RenderTexture rt) { }
	// RVA: 0x6870f68 VA: 0x7598e88f68
	private Void SetRenderTextureDescriptor(RenderTextureDescriptor desc) { }
	// RVA: 0x68708a0 VA: 0x7598e888a0
	private RenderTextureDescriptor GetDescriptor() { }
	// RVA: 0x6871034 VA: 0x7598e89034
	private static RenderTexture GetTemporary_Internal(RenderTextureDescriptor desc) { }
	// RVA: 0x68710ac VA: 0x7598e890ac
	public static Void ReleaseTemporary(RenderTexture temp) { }
	// RVA: 0x68710e8 VA: 0x7598e890e8
	public Int32 get_depth() { }
	// RVA: 0x6871124 VA: 0x7598e89124
	protected internal Void .ctor() { }
	// RVA: 0x6871178 VA: 0x7598e89178
	public Void .ctor(RenderTextureDescriptor desc) { }
	// RVA: 0x68716c0 VA: 0x7598e896c0
	public Void .ctor(RenderTexture textureToCopy) { }
	// RVA: 0x68718bc VA: 0x7598e898bc
	public Void .ctor(Int32 width, Int32 height, Int32 depth, DefaultFormat format) { }
	// RVA: 0x6871be4 VA: 0x7598e89be4
	public Void .ctor(Int32 width, Int32 height, Int32 depth, GraphicsFormat format) { }
	// RVA: 0x6871c74 VA: 0x7598e89c74
	public Void .ctor(Int32 width, Int32 height, Int32 depth, GraphicsFormat format, Int32 mipCount) { }
	// RVA: 0x68719e0 VA: 0x7598e899e0
	public Void .ctor(Int32 width, Int32 height, GraphicsFormat colorFormat, GraphicsFormat depthStencilFormat, Int32 mipCount) { }
	// RVA: 0x6871f0c VA: 0x7598e89f0c
	public Void .ctor(Int32 width, Int32 height, GraphicsFormat colorFormat, GraphicsFormat depthStencilFormat) { }
	// RVA: 0x6871f9c VA: 0x7598e89f9c
	public Void .ctor(Int32 width, Int32 height, Int32 depth, RenderTextureFormat format, RenderTextureReadWrite readWrite) { }
	// RVA: 0x6872224 VA: 0x7598e8a224
	public Void .ctor(Int32 width, Int32 height, Int32 depth, RenderTextureFormat format) { }
	// RVA: 0x6872354 VA: 0x7598e8a354
	public Void .ctor(Int32 width, Int32 height, Int32 depth) { }
	// RVA: 0x68722b4 VA: 0x7598e8a2b4
	public Void .ctor(Int32 width, Int32 height, Int32 depth, RenderTextureFormat format, Int32 mipCount) { }
	// RVA: 0x6872044 VA: 0x7598e8a044
	private Void Initialize(Int32 width, Int32 height, Int32 depth, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 mipCount) { }
	// RVA: 0x6871e88 VA: 0x7598e89e88
	internal static GraphicsFormat GetDepthStencilFormatLegacy(Int32 depthBits, GraphicsFormat colorFormat) { }
	// RVA: 0x68724ac VA: 0x7598e8a4ac
	internal static GraphicsFormat GetDepthStencilFormatLegacy(Int32 depthBits, RenderTextureFormat format) { }
	// RVA: 0x6872538 VA: 0x7598e8a538
	internal static GraphicsFormat GetDepthStencilFormatLegacy(Int32 depthBits, DefaultFormat format) { }
	// RVA: 0x68724b8 VA: 0x7598e8a4b8
	internal static GraphicsFormat GetDepthStencilFormatLegacy(Int32 depthBits, Boolean requestedShadowMap) { }
	// RVA: 0x687182c VA: 0x7598e8982c
	public RenderTextureDescriptor get_descriptor() { }
	// RVA: 0x6871270 VA: 0x7598e89270
	private static Void ValidateRenderTextureDesc(RenderTextureDescriptor desc) { }
	// RVA: 0x6871990 VA: 0x7598e89990
	internal static GraphicsFormat GetDefaultColorFormat(DefaultFormat format) { }
	// RVA: 0x68719b8 VA: 0x7598e899b8
	internal static GraphicsFormat GetDefaultDepthStencilFormat(DefaultFormat format, Int32 depth) { }
	// RVA: 0x687235c VA: 0x7598e8a35c
	internal static GraphicsFormat GetCompatibleFormat(RenderTextureFormat renderTextureFormat, RenderTextureReadWrite readWrite) { }
	// RVA: 0x687254c VA: 0x7598e8a54c
	public static RenderTexture GetTemporary(RenderTextureDescriptor desc) { }
	// RVA: 0x68725e8 VA: 0x7598e8a5e8
	private static RenderTexture GetTemporaryImpl(Int32 width, Int32 height, GraphicsFormat depthStencilFormat, GraphicsFormat colorFormat, Int32 antiAliasing, RenderTextureMemoryless memorylessMode, VRTextureUsage vrUsage, Boolean useDynamicScale) { }
	// RVA: 0x6872754 VA: 0x7598e8a754
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, RenderTextureMemoryless memorylessMode, VRTextureUsage vrUsage, Boolean useDynamicScale) { }
	// RVA: 0x68727e0 VA: 0x7598e8a7e0
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, RenderTextureMemoryless memorylessMode, VRTextureUsage vrUsage) { }
	// RVA: 0x68727fc VA: 0x7598e8a7fc
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing, RenderTextureMemoryless memorylessMode) { }
	// RVA: 0x687281c VA: 0x7598e8a81c
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format, RenderTextureReadWrite readWrite, Int32 antiAliasing) { }
	// RVA: 0x6872840 VA: 0x7598e8a840
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format, RenderTextureReadWrite readWrite) { }
	// RVA: 0x6872868 VA: 0x7598e8a868
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer, RenderTextureFormat format) { }
	// RVA: 0x6872894 VA: 0x7598e8a894
	public static RenderTexture GetTemporary(Int32 width, Int32 height, Int32 depthBuffer) { }
	// RVA: 0x68728c4 VA: 0x7598e8a8c4
	public static RenderTexture GetTemporary(Int32 width, Int32 height) { }
	// RVA: 0x6870c40 VA: 0x7598e88c40
	private Void GetColorBuffer_Injected(out RenderBuffer ret) { }
	// RVA: 0x6870cd8 VA: 0x7598e88cd8
	private Void GetDepthBuffer_Injected(out RenderBuffer ret) { }
	// RVA: 0x6870fac VA: 0x7598e88fac
	private Void SetRenderTextureDescriptor_Injected(ref RenderTextureDescriptor desc) { }
	// RVA: 0x6870ff0 VA: 0x7598e88ff0
	private Void GetDescriptor_Injected(out RenderTextureDescriptor ret) { }
	// RVA: 0x6871070 VA: 0x7598e89070
	private static RenderTexture GetTemporary_Internal_Injected(ref RenderTextureDescriptor desc) { }
}
```