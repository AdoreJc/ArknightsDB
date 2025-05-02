# CriManaPlugin

**Namespace:** `CriWare`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriManaPlugin
{
	private static Int32 initializationCount; // 0x0
	private static Boolean isConfigured; // 0x4
	private static Boolean enabledMultithreadedRendering; // 0x5
	public static Int32 renderingEventOffset; // 0x8
	private static Action OnBeforeInitialize; // 0x10
	private static Action OnInitialized; // 0x18
	private static Action OnBeforeFinalize; // 0x20
	private static Action OnFinalized; // 0x28

	public static Boolean isInitialized { get; }
	public static Boolean isMultithreadedRenderingEnabled { get; }

	// RVA: 0x4143d70 VA: 0x759675bd70
	public static Boolean get_isInitialized() { }
	// RVA: 0x4143dd0 VA: 0x759675bdd0
	public static Boolean get_isMultithreadedRenderingEnabled() { }
	// RVA: 0x4143e28 VA: 0x759675be28
	public static Void add_OnBeforeInitialize(Action value) { }
	// RVA: 0x4143f04 VA: 0x759675bf04
	public static Void remove_OnBeforeInitialize(Action value) { }
	// RVA: 0x4143fe0 VA: 0x759675bfe0
	public static Void add_OnInitialized(Action value) { }
	// RVA: 0x41440bc VA: 0x759675c0bc
	public static Void remove_OnInitialized(Action value) { }
	// RVA: 0x4144198 VA: 0x759675c198
	public static Void add_OnBeforeFinalize(Action value) { }
	// RVA: 0x4144274 VA: 0x759675c274
	public static Void remove_OnBeforeFinalize(Action value) { }
	// RVA: 0x4144350 VA: 0x759675c350
	public static Void add_OnFinalized(Action value) { }
	// RVA: 0x414442c VA: 0x759675c42c
	public static Void remove_OnFinalized(Action value) { }
	// RVA: 0x4144508 VA: 0x759675c508
	public static Void SetConfigParameters(Boolean graphicsMultiThreaded, Int32 num_decoders, Int32 max_num_of_entries) { }
	// RVA: 0x41446d0 VA: 0x759675c6d0
	private static Void SetupVp9() { }
	// RVA: 0x4144acc VA: 0x759675cacc
	public static Void SetConfigAdditonalParameters_VITA(Boolean use_h264_playback, Int32 width, Int32 height) { }
	// RVA: 0x4144ad0 VA: 0x759675cad0
	public static Void SetConfigAdditonalParameters_PC(Boolean use_h264_playback) { }
	// RVA: 0x4144ad4 VA: 0x759675cad4
	public static Void UseLegacyDecoder_PC(Boolean useLegacyDecoder) { }
	// RVA: 0x4144ad8 VA: 0x759675cad8
	public static Boolean IsLegacyDecoderUsed_PC() { }
	// RVA: 0x4144ae0 VA: 0x759675cae0
	public static Void SetConfigAdditonalParameters_ANDROID(Boolean enable_buffer_output_for_h264, Boolean enable_buffer_output_for_vp9) { }
	// RVA: 0x4144d78 VA: 0x759675cd78
	public static Void SetConfigAdditonalParameters_WEBGL(String webworkerPath, UInt32 heapSize) { }
	// RVA: 0x4144d7c VA: 0x759675cd7c
	public static Void InitializeLibrary() { }
	// RVA: 0x4144f6c VA: 0x759675cf6c
	public static Boolean IsLibraryInitialized() { }
	// RVA: 0x4144fb8 VA: 0x759675cfb8
	public static Void FinalizeLibrary() { }
	// RVA: 0x41452d0 VA: 0x759675d2d0
	public static Boolean IsCodecSupported(CodecType codecType) { }
	// RVA: 0x414485c VA: 0x759675c85c
	private static Type GetVp9ExpansionClass() { }
	// RVA: 0x4144954 VA: 0x759675c954
	private static Boolean IsVp9CodecSupported() { }
	// RVA: 0x4145450 VA: 0x759675d450
	private static Boolean IsH264CodecSupported() { }
	// RVA: 0x414547c VA: 0x759675d47c
	public static Void SetDecodeThreadPriorityAndroidExperimental(Int32 prio) { }
	// RVA: 0x414554c VA: 0x759675d54c
	public static Boolean ShouldSampleRed(GraphicsDeviceType type, IntPtr tex_ptr) { }
	// RVA: 0x4145640 VA: 0x759675d640
	public static Void UseStreamerManager(Boolean flag) { }
	// RVA: 0x4145710 VA: 0x759675d710
	public static Boolean IsStreamerManagerUsed() { }
	// RVA: 0x41457cc VA: 0x759675d7cc
	public static Void Lock() { }
	// RVA: 0x414587c VA: 0x759675d87c
	public static Void Unlock() { }
	// RVA: 0x414592c VA: 0x759675d92c
	public static UInt32 GetPrimeBufferAlignmentSize() { }
	// RVA: 0x41459e0 VA: 0x759675d9e0
	public static Boolean AnalyzeMovieHeader(IntPtr data, out MovieInfo movieInfo) { }
	// RVA: 0x4144634 VA: 0x759675c634
	private static extern Void CRIWAREB4DB183E(Int32 graphics_api, Boolean graphics_multi_threaded, Int32 num_decoders, Int32 num_of_max_entries) { }
	// RVA: 0x4145198 VA: 0x759675d198
	private static extern Void CRIWAREB59D2482() { }
	// RVA: 0x41451fc VA: 0x759675d1fc
	public static extern Boolean CRIWARE9F76DF16() { }
	// RVA: 0x414526c VA: 0x759675d26c
	private static extern Void CRIWAREAB5F01A1() { }
	// RVA: 0x4145b5c VA: 0x759675db5c
	public static extern Void CRIWAREEE8E1F80(Boolean flag) { }
	// RVA: 0x4145818 VA: 0x759675d818
	public static extern Void CRIWAREB26B8FE7() { }
	// RVA: 0x41458c8 VA: 0x759675d8c8
	public static extern Void CRIWAREE16AC202() { }
	// RVA: 0x4145978 VA: 0x759675d978
	private static extern UInt32 CRIWARE69FBC135() { }
	// RVA: 0x4145694 VA: 0x759675d694
	public static extern Void criMana_UseStreamerManager(Boolean flag) { }
	// RVA: 0x414575c VA: 0x759675d75c
	public static extern Boolean criMana_IsStreamerManagerUsed() { }
	// RVA: 0x4145a88 VA: 0x759675da88
	public static extern Boolean CRIWAREF717A195(IntPtr movie_header_ptr, [Out] MovieInfo mvinf) { }
	// RVA: 0x4145bd8 VA: 0x759675dbd8
	public static extern UInt32 CRIWAREC729E61C() { }
	// RVA: 0x41454d0 VA: 0x759675d4d0
	public static extern Void criManaUnity_SetDecodeThreadPriority_ANDROID(Int32 prio) { }
	// RVA: 0x4144cf4 VA: 0x759675ccf4
	private static extern Void criManaUnity_SetConfigAdditionalParameters_ANDROID(Boolean buffer_h264, Boolean buffer_vp9) { }
	// RVA: 0x4145c40 VA: 0x759675dc40
	public static extern Boolean criManaUnity_IsBufferOutputForH264Enabled_ANDROID() { }
	// RVA: 0x4145cb0 VA: 0x759675dcb0
	public static extern Void criManaUnity_EnableSwitchTextureSampleColorGLES30_ANDROID() { }
	// RVA: 0x41455bc VA: 0x759675d5bc
	private static extern Boolean criManaUnity_ShouldSwitchTextureSampleColorToRedGLES30_ANDROID(IntPtr tex_ptr) { }
	// RVA: 0x4145d14 VA: 0x759675dd14
	public Void .ctor() { }
	// RVA: 0x4145d1c VA: 0x759675dd1c
	private static Void .cctor() { }
}
```