# RendererResourceSofdecPrimeYuvRawData

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

- `Int32 currentTextureSet`

- `Int32 drawTextureSet`

- `Int32 playerID`

- `Boolean hasTextureUpdated`

- `Boolean hasRenderedNewFrame`

- `Boolean isStoppingForSeek`


## Methods

- `Void UpdateMovieTextureST(UInt32, UInt32)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana.Detail
public class RendererResourceSofdecPrimeYuvRawData : RendererResource
{
	private Int32 width; // 0x2c
	private Int32 height; // 0x30
	private Int32 chromaWidth; // 0x34
	private Int32 chromaHeight; // 0x38
	private Int32 alphaWidth; // 0x3c
	private Int32 alphaHeight; // 0x40
	private Boolean useUserShader; // 0x44
	private CodecType codecType; // 0x48
	private Vector4 movieTextureST; // 0x4c
	private Vector4 movieChromaTextureST; // 0x5c
	private Vector4 movieAlphaTextureST; // 0x6c
	private Texture2D[][] textures; // 0x80
	private Int32 currentTextureSet; // 0x88
	private Int32 drawTextureSet; // 0x8c
	private IntPtr[] nativePixels; // 0x90
	private Int32 playerID; // 0x98
	private Boolean hasTextureUpdated; // 0x9c
	private Boolean hasRenderedNewFrame; // 0x9d
	private Boolean isStoppingForSeek; // 0x9e

	private static Int32 NumTextureSets { get; }

	// RVA: 0x41630d0 VA: 0x759677b0d0
	private static Int32 get_NumTextureSets() { }
	// RVA: 0x415ee5c VA: 0x7596776e5c
	public Void .ctor(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4163384 VA: 0x759677b384
	protected override Void OnDisposeManaged() { }
	// RVA: 0x4163388 VA: 0x759677b388
	protected override Void OnDisposeUnmanaged() { }
	// RVA: 0x41633d4 VA: 0x759677b3d4
	public override Boolean IsPrepared() { }
	// RVA: 0x41633dc VA: 0x759677b3dc
	public override Boolean ContinuePreparing() { }
	// RVA: 0x41633e4 VA: 0x759677b3e4
	public override Boolean IsSuitable(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x4163504 VA: 0x759677b504
	public override Boolean OnPlayerStopForSeek() { }
	// RVA: 0x4163520 VA: 0x759677b520
	public override Boolean HasRenderedNewFrame() { }
	// RVA: 0x4163528 VA: 0x759677b528
	public override Void AttachToPlayer(Int32 playerId) { }
	// RVA: 0x416358c VA: 0x759677b58c
	public override Boolean UpdateFrame(Int32 playerId, FrameInfo frameInfo, ref Boolean frameDrop) { }
	// RVA: 0x41635f8 VA: 0x759677b5f8
	public override Boolean UpdateMaterial(Material material) { }
	// RVA: 0x4163250 VA: 0x759677b250
	private Void UpdateMovieTextureST(UInt32 dispWidth, UInt32 dispHeight) { }
	// RVA: 0x41638c8 VA: 0x759677b8c8
	public override Void UpdateTextures() { }
	// RVA: 0x41630d8 VA: 0x759677b0d8
	private static Void CalculateTextureSize(ref Int32 w, ref Int32 h, Int32 videoWidth, Int32 videoHeight, CodecType type, Boolean isChroma) { }
}
```