# RendererResourceAndroidSofdecPrimeYuvLegacyGles2

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

- `Int32 movieWidth`

- `Int32 movieHeight`

- `Vector4 movieTextureST`

- `Vector4 movieChromaTextureST`

- `Vector4 movieAlphaTextureST`

- `Int32 numImages`

- `Int32 numImagesForYUV`

- `Int32 numTextureSets`

- `Int32 currentTextureSet`

- `Int32 drawTextureSet`

- `Int32 playerID`

- `Boolean isStoppingForSeek`


## Methods

- `Void UpdateMovieTextureST(UInt32, UInt32)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana.Detail
public class RendererResourceAndroidSofdecPrimeYuvLegacyGles2 : RendererResource
{
	private Int32 width; // 0x2c
	private Int32 height; // 0x30
	private Int32 chromaWidth; // 0x34
	private Int32 chromaHeight; // 0x38
	private Int32 alphaWidth; // 0x3c
	private Int32 alphaHeight; // 0x40
	private Boolean useUserShader; // 0x44
	private CodecType codecType; // 0x48
	private Int32 movieWidth; // 0x4c
	private Int32 movieHeight; // 0x50
	private const TextureFormat format; // 0x0
	private const TextureFormat formatUV; // 0x0
	private Vector4 movieTextureST; // 0x54
	private Vector4 movieChromaTextureST; // 0x64
	private Vector4 movieAlphaTextureST; // 0x74
	private Texture2D[][] textures; // 0x88
	private RenderTexture[] renderTextures; // 0x90
	private IntPtr[][] nativeTextures; // 0x98
	private Int32 numImages; // 0xa0
	private Int32 numImagesForYUV; // 0xa4
	private Int32 numTextureSets; // 0xa8
	private Int32 currentTextureSet; // 0xac
	private Int32 drawTextureSet; // 0xb0
	private Int32 playerID; // 0xb4
	private Boolean isStoppingForSeek; // 0xb8


	// RVA: 0x415e9a0 VA: 0x75967769a0
	public Void .ctor(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4161924 VA: 0x7596779924
	protected override Void OnDisposeManaged() { }
	// RVA: 0x4161928 VA: 0x7596779928
	protected override Void OnDisposeUnmanaged() { }
	// RVA: 0x4161a5c VA: 0x7596779a5c
	public override Boolean IsPrepared() { }
	// RVA: 0x4161a64 VA: 0x7596779a64
	public override Boolean ContinuePreparing() { }
	// RVA: 0x4161a6c VA: 0x7596779a6c
	public override Boolean IsSuitable(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4161b70 VA: 0x7596779b70
	public override Boolean OnPlayerStopForSeek() { }
	// RVA: 0x4161b8c VA: 0x7596779b8c
	public override Void AttachToPlayer(Int32 playerId) { }
	// RVA: 0x4161c98 VA: 0x7596779c98
	public override Boolean UpdateFrame(Int32 playerId, FrameInfo frameInfo, ref Boolean frameDrop) { }
	// RVA: 0x41625b4 VA: 0x759677a5b4
	public override Boolean UpdateMaterial(Material material) { }
	// RVA: 0x4162480 VA: 0x759677a480
	private Void UpdateMovieTextureST(UInt32 dispWidth, UInt32 dispHeight) { }
	// RVA: 0x41628f0 VA: 0x759677a8f0
	public override Void UpdateTextures() { }
	// RVA: 0x4162350 VA: 0x759677a350
	private static Void CalculateTextureSize(ref Int32 w, ref Int32 h, Int32 videoWidth, Int32 videoHeight, CodecType type, Boolean isChroma) { }
}
```