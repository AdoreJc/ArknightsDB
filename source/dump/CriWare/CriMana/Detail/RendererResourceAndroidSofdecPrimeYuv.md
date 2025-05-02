# RendererResourceAndroidSofdecPrimeYuv

**Namespace:** `CriWare.CriMana.Detail`


## Fields

- `Int32 width`

- `Int32 height`

- `Int32 chromaWidth`

- `Int32 chromaHeight`

- `Int32 alphaWidth`

- `Int32 alphaHeight`

- `Boolean useUserShader`

- `CodecType codecType`

- `Vector4 movieTextureST`

- `Vector4 movieChromaTextureST`

- `Vector4 movieAlphaTextureST`

- `Int32 numImages`

- `Int32 numImagesForYUV`

- `Int32 playerID`

- `Boolean areTexturesUpdated`

- `Boolean isFrameUpdated`

- `Boolean isStoppingForSeek`

- `Boolean isStartTriggered`


## Methods

- `Void forceUpdateMaterialTextures(Texture[])`

- `Void UpdateMovieTextureST(UInt32, UInt32)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana.Detail
public class RendererResourceAndroidSofdecPrimeYuv : RendererResource
{
	private Int32 width; // 0x2c
	private Int32 height; // 0x30
	private Int32 chromaWidth; // 0x34
	private Int32 chromaHeight; // 0x38
	private Int32 alphaWidth; // 0x3c
	private Int32 alphaHeight; // 0x40
	private Boolean useUserShader; // 0x44
	private CodecType codecType; // 0x48
	private const TextureFormat format; // 0x0
	private const TextureFormat formatUV; // 0x0
	private Vector4 movieTextureST; // 0x4c
	private Vector4 movieChromaTextureST; // 0x5c
	private Vector4 movieAlphaTextureST; // 0x6c
	private Texture2D[] textures; // 0x80
	private Int32 numImages; // 0x88
	private Int32 numImagesForYUV; // 0x8c
	private IntPtr[] nativePtrs; // 0x90
	private RenderTexture[] renderTextures; // 0x98
	private Int32 playerID; // 0xa0
	private Boolean areTexturesUpdated; // 0xa4
	private Boolean isFrameUpdated; // 0xa5
	private Boolean isStoppingForSeek; // 0xa6
	private Boolean isStartTriggered; // 0xa7


	// RVA: 0x415e648 VA: 0x7596776648
	public Void .ctor(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4160b54 VA: 0x7596778b54
	protected override Void OnDisposeManaged() { }
	// RVA: 0x4160b58 VA: 0x7596778b58
	protected override Void OnDisposeUnmanaged() { }
	// RVA: 0x4160ba0 VA: 0x7596778ba0
	public override Boolean IsPrepared() { }
	// RVA: 0x4160bc0 VA: 0x7596778bc0
	public override Boolean ContinuePreparing() { }
	// RVA: 0x4160bc8 VA: 0x7596778bc8
	public override Boolean IsSuitable(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4160ce8 VA: 0x7596778ce8
	public override Boolean OnPlayerStopForSeek() { }
	// RVA: 0x4161094 VA: 0x7596779094
	public override Void OnPlayerStart() { }
	// RVA: 0x4160f24 VA: 0x7596778f24
	private Void forceUpdateMaterialTextures(Texture[] newTextures) { }
	// RVA: 0x41610a0 VA: 0x75967790a0
	public override Void AttachToPlayer(Int32 playerId) { }
	// RVA: 0x41610bc VA: 0x75967790bc
	public override Boolean UpdateFrame(Int32 playerId, FrameInfo frameInfo, ref Boolean frameDrop) { }
	// RVA: 0x416114c VA: 0x759677914c
	public override Boolean UpdateMaterial(Material material) { }
	// RVA: 0x4160a20 VA: 0x7596778a20
	private Void UpdateMovieTextureST(UInt32 dispWidth, UInt32 dispHeight) { }
	// RVA: 0x4161474 VA: 0x7596779474
	public override Void UpdateTextures() { }
	// RVA: 0x4160904 VA: 0x7596778904
	private static Void CalculateTextureSize(ref Int32 w, ref Int32 h, Int32 videoWidth, Int32 videoHeight, CodecType type, Boolean isChroma) { }
}
```