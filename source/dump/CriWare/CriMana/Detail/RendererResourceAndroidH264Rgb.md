# RendererResourceAndroidH264Rgb

**Namespace:** `CriWare.CriMana.Detail`


## Fields

- `Int32 playerId`

- `Int32 width`

- `Int32 height`

- `Int32 dispWidth`

- `Int32 dispHeight`

- `Int32 alphaWidth`

- `Int32 alphaHeight`

- `Boolean useUserShader`

- `Vector4 movieTextureST`

- `Vector4 alphaTextureST`

- `Boolean needsUpdateTexture`

- `Boolean needsToDetachInitTexture`

- `Boolean areTexturesUpdated`

- `Boolean isStoppingForSeek`

- `Boolean isStartTriggered`

- `UInt32 nativeTextureId`


## Methods

- `Void forceUpdateMaterialTextures(Texture[])`

- `Void UpdateMovieTextureST(Single[], Single, Single)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana.Detail
public class RendererResourceAndroidH264Rgb : RendererResource
{
	private const Int32 RenderEventAction_ATTACH; // 0x0
	private Int32 playerId; // 0x2c
	private Int32 width; // 0x30
	private Int32 height; // 0x34
	private Int32 dispWidth; // 0x38
	private Int32 dispHeight; // 0x3c
	private Int32 alphaWidth; // 0x40
	private Int32 alphaHeight; // 0x44
	private Boolean useUserShader; // 0x48
	private Vector4 movieTextureST; // 0x4c
	private Vector4 alphaTextureST; // 0x5c
	private Texture2D[] textures; // 0x70
	private IntPtr[] nativePtrs; // 0x78
	private Boolean needsUpdateTexture; // 0x80
	private Boolean needsToDetachInitTexture; // 0x81
	private Boolean areTexturesUpdated; // 0x82
	private Boolean isStoppingForSeek; // 0x83
	private Boolean isStartTriggered; // 0x84
	private UInt32 nativeTextureId; // 0x88


	// RVA: 0x415e3a8 VA: 0x75967763a8
	public Void .ctor(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x415f480 VA: 0x7596777480
	protected override Void OnDisposeManaged() { }
	// RVA: 0x415f484 VA: 0x7596777484
	protected override Void OnDisposeUnmanaged() { }
	// RVA: 0x415f59c VA: 0x759677759c
	public override Boolean IsPrepared() { }
	// RVA: 0x415f5a4 VA: 0x75967775a4
	public override Boolean ContinuePreparing() { }
	// RVA: 0x415f5ac VA: 0x75967775ac
	public override Boolean IsSuitable(Int32 playerId, MovieInfo movieInfo, Boolean additive, Shader userShader) { }
	// RVA: 0x415f6c8 VA: 0x75967776c8
	public override Boolean OnPlayerStopForSeek() { }
	// RVA: 0x415f6e0 VA: 0x75967776e0
	public override Void OnPlayerStart() { }
	// RVA: 0x415f6ec VA: 0x75967776ec
	public override Boolean ShouldSkipDestroyOnStopForSeek() { }
	// RVA: 0x415f6f4 VA: 0x75967776f4
	private Void forceUpdateMaterialTextures(Texture[] newTextures) { }
	// RVA: 0x415f810 VA: 0x7596777810
	public override Void AttachToPlayer(Int32 playerId) { }
	// RVA: 0x415f8d4 VA: 0x75967778d4
	public override Boolean UpdateFrame(Int32 playerId, FrameInfo frameInfo, ref Boolean frameDrop) { }
	// RVA: 0x415faac VA: 0x7596777aac
	public override Boolean UpdateMaterial(Material material) { }
	// RVA: 0x415fef4 VA: 0x7596777ef4
	private Void UpdateMovieTextureST(Single[] texCoords, Single dispWidth, Single dispHeight) { }
	// RVA: 0x415ff98 VA: 0x7596777f98
	public override Void UpdateTextures() { }
	// RVA: 0x4160470 VA: 0x7596778470
	public static Boolean IsSupported() { }
	// RVA: 0x416079c VA: 0x759677879c
	private static extern Boolean criManaUnity_IsMediaCodecSupported_ANDROID(Int32 device_type) { }
	// RVA: 0x4160820 VA: 0x7596778820
	private static extern UInt32 criManaUnity_MediaCodecCreateTexture_ANDROID() { }
	// RVA: 0x4160888 VA: 0x7596778888
	private static extern Void criManaUnity_MediaCodecDeleteTexture_ANDROID(UInt32 oes_texture) { }
	// RVA: 0x415f848 VA: 0x7596777848
	private static extern Boolean criManaUnityPlayer_MediaCodecAttachTexture_ANDROID(Int32 player_id, UInt32 oes_texture) { }
	// RVA: 0x415f94c VA: 0x759677794c
	private static extern Void criManaUnityPlayer_MediaCodecDetachTexture_ANDROID(Int32 player_id, UInt32 oes_texture) { }
}
```