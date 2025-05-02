# MediaPlayer

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `FileLocation m_VideoLocation`

- `String m_VideoPath`

- `Boolean m_AutoOpen`

- `Boolean m_AutoStart`

- `Boolean m_Loop`

- `Single m_Volume`

- `Single m_Balance`

- `Boolean m_Muted`

- `Single m_PlaybackRate`

- `Boolean m_Resample`

- `ResampleMode m_ResampleMode`

- `Int32 m_ResampleBufferSize`

- `Resampler m_Resampler`

- `Boolean m_Persistent`

- `VideoMapping m_videoMapping`

- `StereoPacking m_StereoPacking`

- `AlphaPacking m_AlphaPacking`

- `Boolean m_DisplayDebugStereoColorTint`

- `FilterMode m_FilterMode`

- `TextureWrapMode m_WrapMode`

- `Int32 m_AnisoLevel`

- `Boolean m_LoadSubtitles`

- `FileLocation m_SubtitleLocation`

- `FileLocation m_queueSubtitleLocation`

- `String m_SubtitlePath`

- `String m_queueSubtitlePath`

- `Coroutine m_loadSubtitlesRoutine`

- `Transform m_AudioHeadTransform`

- `Boolean m_AudioFocusEnabled`

- `Transform m_AudioFocusTransform`

- `Single m_AudioFocusWidthDegrees`

- `Single m_AudioFocusOffLevelDB`

- `MediaPlayerEvent m_events`

- `Int32 m_eventMask`

- `FileFormat m_forceFileFormat`

- `Boolean _pauseMediaOnAppPause`

- `Boolean _playMediaOnAppUnpause`

- `IMediaControl m_Control`

- `IMediaProducer m_Texture`

- `IMediaInfo m_Info`

- `IMediaPlayer m_Player`

- `IMediaSubtitles m_Subtitles`

- `IDisposable m_Dispose`

- `Boolean m_VideoOpened`

- `Boolean m_AutoStartTriggered`

- `Boolean m_WasPlayingOnPause`

- `Coroutine _renderingCoroutine`

- `Boolean m_EventFired_ReadyToPlay`

- `Boolean m_EventFired_Started`

- `Boolean m_EventFired_FirstFrameReady`

- `Boolean m_EventFired_FinishedPlaying`

- `Boolean m_EventFired_MetaDataReady`

- `Boolean m_EventState_PlaybackStalled`

- `Boolean m_EventState_PlaybackBuffering`

- `Boolean m_EventState_PlaybackSeeking`

- `Int32 m_EventState_PreviousWidth`

- `Int32 m_EventState_PreviousHeight`

- `Int32 m_previousSubtitleIndex`

- `Boolean m_FinishedFrameOpenCheck`

- `UInt32 m_sourceSampleRate`

- `UInt32 m_sourceChannels`

- `Boolean m_manuallySetAudioSourceProperties`

- `OptionsWindows _optionsWindows`

- `OptionsMacOSX _optionsMacOSX`

- `OptionsIOS _optionsIOS`

- `OptionsTVOS _optionsTVOS`

- `OptionsAndroid _optionsAndroid`

- `OptionsWindowsPhone _optionsWindowsPhone`

- `OptionsWindowsUWP _optionsWindowsUWP`

- `OptionsWebGL _optionsWebGL`

- `OptionsPS4 _optionsPS4`


## Properties

- `Resampler FrameResampler`

- `Boolean Persistent`

- `VideoMapping VideoLayoutMapping`

- `MediaPlayerEvent Events`

- `Boolean VideoOpened`

- `Boolean PauseMediaOnAppPause`

- `Boolean PlayMediaOnAppUnpause`

- `FileFormat ForceFileFormat`

- `Transform AudioHeadTransform`

- `Boolean AudioFocusEnabled`

- `Single AudioFocusOffLevelDB`

- `Single AudioFocusWidthDegrees`

- `Transform AudioFocusTransform`

- `OptionsWindows PlatformOptionsWindows`

- `OptionsMacOSX PlatformOptionsMacOSX`

- `OptionsIOS PlatformOptionsIOS`

- `OptionsTVOS PlatformOptionsTVOS`

- `OptionsAndroid PlatformOptionsAndroid`

- `OptionsWindowsPhone PlatformOptionsWindowsPhone`

- `OptionsWindowsUWP PlatformOptionsWindowsUWP`

- `OptionsWebGL PlatformOptionsWebGL`

- `OptionsPS4 PlatformOptionsPS4`

- `Boolean SubtitlesEnabled`

- `String SubtitlePath`

- `FileLocation SubtitleLocation`


## Methods

- `Resampler get_FrameResampler()`

- `Boolean get_Persistent()`

- `Void set_Persistent(Boolean)`

- `VideoMapping get_VideoLayoutMapping()`

- `Void set_VideoLayoutMapping(VideoMapping)`

- `MediaPlayerEvent get_Events()`

- `Boolean get_VideoOpened()`

- `Boolean get_PauseMediaOnAppPause()`

- `Void set_PauseMediaOnAppPause(Boolean)`

- `Boolean get_PlayMediaOnAppUnpause()`

- `Void set_PlayMediaOnAppUnpause(Boolean)`

- `FileFormat get_ForceFileFormat()`

- `Void set_ForceFileFormat(FileFormat)`

- `Void set_AudioHeadTransform(Transform)`

- `Transform get_AudioHeadTransform()`

- `Boolean get_AudioFocusEnabled()`

- `Void set_AudioFocusEnabled(Boolean)`

- `Single get_AudioFocusOffLevelDB()`

- `Void set_AudioFocusOffLevelDB(Single)`

- `Single get_AudioFocusWidthDegrees()`

- `Void set_AudioFocusWidthDegrees(Single)`

- `Transform get_AudioFocusTransform()`

- `Void set_AudioFocusTransform(Transform)`

- `OptionsWindows get_PlatformOptionsWindows()`

- `OptionsMacOSX get_PlatformOptionsMacOSX()`

- `OptionsIOS get_PlatformOptionsIOS()`

- `OptionsTVOS get_PlatformOptionsTVOS()`

- `OptionsAndroid get_PlatformOptionsAndroid()`

- `OptionsWindowsPhone get_PlatformOptionsWindowsPhone()`

- `OptionsWindowsUWP get_PlatformOptionsWindowsUWP()`

- `OptionsWebGL get_PlatformOptionsWebGL()`

- `OptionsPS4 get_PlatformOptionsPS4()`

- `Void Awake()`

- `Void Initialise()`

- `Void Start()`

- `Boolean OpenVideoFromFile(FileLocation, String, Boolean)`

- `Boolean OpenVideoFromBuffer(Byte[], Boolean)`

- `Boolean StartOpenChunkedVideoFromBuffer(UInt64, Boolean)`

- `Boolean AddChunkToVideoBuffer(Byte[], UInt64, UInt64)`

- `Boolean EndOpenChunkedVideoFromBuffer()`

- `Boolean get_SubtitlesEnabled()`

- `String get_SubtitlePath()`

- `FileLocation get_SubtitleLocation()`

- `Boolean EnableSubtitles(FileLocation, String)`

- `IEnumerator LoadSubtitlesCoroutine(String, FileLocation, String)`

- `Void DisableSubtitles()`

- `Boolean OpenVideoFromBufferInternal(Byte[])`

- `Boolean StartOpenVideoFromBufferInternal(UInt64)`

- `Boolean AddChunkToBufferInternal(Byte[], UInt64, UInt64)`

- `Boolean EndOpenVideoFromBufferInternal()`

- `Boolean OpenVideoFromFile()`

- `Void SetPlaybackOptions()`

- `Void CloseVideo()`

- `Void Play()`

- `Void Pause()`

- `Void Stop()`

- `Void Rewind(Boolean)`

- `Void LateUpdate()`

- `Void UpdateResampler()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnApplicationQuit()`

- `Void StartRenderCoroutine()`

- `Void StopRenderCoroutine()`

- `IEnumerator FinalRenderCapture()`

- `PlatformOptions GetCurrentPlatformOptions()`

- `String GetPlatformVideoApiString()`

- `Int64 GetPlatformFileOffset()`

- `String GetPlatformHttpHeaderJson()`

- `String GetPlatformFilePath(Platform, ref, ref)`

- `Boolean ForceWaitForNewFrame(Int32, Single)`

- `Void UpdateAudioFocus()`

- `Void UpdateAudioHeadTransform()`

- `Void UpdateErrors()`

- `Void UpdateEvents()`

- `Boolean IsHandleEvent(EventType)`

- `Boolean FireEventIfPossible(EventType, Boolean)`

- `Boolean CanFireEvent(EventType, Boolean)`

- `Void OnApplicationFocus(Boolean)`

- `Void OnApplicationPause(Boolean)`

- `IEnumerator ExtractFrameCoroutine(Texture2D, ProcessExtractedFrame, Single, Boolean, Int32, Int32)`

- `Void ExtractFrameAsync(Texture2D, ProcessExtractedFrame, Single, Boolean, Int32, Int32)`

- `Texture2D ExtractFrame(Texture2D, Single, Boolean, Int32, Int32)`

- `Texture ExtractFrame(Single, Boolean, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class MediaPlayer : MonoBehaviour
{
	public FileLocation m_VideoLocation; // 0x18
	public String m_VideoPath; // 0x20
	public Boolean m_AutoOpen; // 0x28
	public Boolean m_AutoStart; // 0x29
	public Boolean m_Loop; // 0x2a
	public Single m_Volume; // 0x2c
	private Single m_Balance; // 0x30
	public Boolean m_Muted; // 0x34
	public Single m_PlaybackRate; // 0x38
	public Boolean m_Resample; // 0x3c
	public ResampleMode m_ResampleMode; // 0x40
	public Int32 m_ResampleBufferSize; // 0x44
	private Resampler m_Resampler; // 0x48
	private Boolean m_Persistent; // 0x50
	private VideoMapping m_videoMapping; // 0x54
	public StereoPacking m_StereoPacking; // 0x58
	public AlphaPacking m_AlphaPacking; // 0x5c
	public Boolean m_DisplayDebugStereoColorTint; // 0x60
	public FilterMode m_FilterMode; // 0x64
	public TextureWrapMode m_WrapMode; // 0x68
	public Int32 m_AnisoLevel; // 0x6c
	private Boolean m_LoadSubtitles; // 0x70
	private FileLocation m_SubtitleLocation; // 0x74
	private FileLocation m_queueSubtitleLocation; // 0x78
	private String m_SubtitlePath; // 0x80
	private String m_queueSubtitlePath; // 0x88
	private Coroutine m_loadSubtitlesRoutine; // 0x90
	private Transform m_AudioHeadTransform; // 0x98
	private Boolean m_AudioFocusEnabled; // 0xa0
	private Transform m_AudioFocusTransform; // 0xa8
	private Single m_AudioFocusWidthDegrees; // 0xb0
	private Single m_AudioFocusOffLevelDB; // 0xb4
	private MediaPlayerEvent m_events; // 0xb8
	private Int32 m_eventMask; // 0xc0
	private FileFormat m_forceFileFormat; // 0xc4
	private Boolean _pauseMediaOnAppPause; // 0xc8
	private Boolean _playMediaOnAppUnpause; // 0xc9
	private IMediaControl m_Control; // 0xd0
	private IMediaProducer m_Texture; // 0xd8
	private IMediaInfo m_Info; // 0xe0
	private IMediaPlayer m_Player; // 0xe8
	private IMediaSubtitles m_Subtitles; // 0xf0
	private IDisposable m_Dispose; // 0xf8
	private Boolean m_VideoOpened; // 0x100
	private Boolean m_AutoStartTriggered; // 0x101
	private Boolean m_WasPlayingOnPause; // 0x102
	private Coroutine _renderingCoroutine; // 0x108
	private static Boolean s_GlobalStartup; // 0x0
	private Boolean m_EventFired_ReadyToPlay; // 0x110
	private Boolean m_EventFired_Started; // 0x111
	private Boolean m_EventFired_FirstFrameReady; // 0x112
	private Boolean m_EventFired_FinishedPlaying; // 0x113
	private Boolean m_EventFired_MetaDataReady; // 0x114
	private Boolean m_EventState_PlaybackStalled; // 0x115
	private Boolean m_EventState_PlaybackBuffering; // 0x116
	private Boolean m_EventState_PlaybackSeeking; // 0x117
	private Int32 m_EventState_PreviousWidth; // 0x118
	private Int32 m_EventState_PreviousHeight; // 0x11c
	private Int32 m_previousSubtitleIndex; // 0x120
	private static Camera m_DummyCamera; // 0x8
	private Boolean m_FinishedFrameOpenCheck; // 0x124
	private UInt32 m_sourceSampleRate; // 0x128
	private UInt32 m_sourceChannels; // 0x12c
	private Boolean m_manuallySetAudioSourceProperties; // 0x130
	private OptionsWindows _optionsWindows; // 0x138
	private OptionsMacOSX _optionsMacOSX; // 0x140
	private OptionsIOS _optionsIOS; // 0x148
	private OptionsTVOS _optionsTVOS; // 0x150
	private OptionsAndroid _optionsAndroid; // 0x158
	private OptionsWindowsPhone _optionsWindowsPhone; // 0x160
	private OptionsWindowsUWP _optionsWindowsUWP; // 0x168
	private OptionsWebGL _optionsWebGL; // 0x170
	private OptionsPS4 _optionsPS4; // 0x178

	public Resampler FrameResampler { get; }
	public Boolean Persistent { get; set; }
	public VideoMapping VideoLayoutMapping { get; set; }
	public virtual IMediaInfo Info { get; }
	public virtual IMediaControl Control { get; }
	public virtual IMediaPlayer Player { get; }
	public virtual IMediaProducer TextureProducer { get; }
	public virtual IMediaSubtitles Subtitles { get; }
	public MediaPlayerEvent Events { get; }
	public Boolean VideoOpened { get; }
	public Boolean PauseMediaOnAppPause { get; set; }
	public Boolean PlayMediaOnAppUnpause { get; set; }
	public FileFormat ForceFileFormat { get; set; }
	public Transform AudioHeadTransform { get; set; }
	public Boolean AudioFocusEnabled { get; set; }
	public Single AudioFocusOffLevelDB { get; set; }
	public Single AudioFocusWidthDegrees { get; set; }
	public Transform AudioFocusTransform { get; set; }
	public OptionsWindows PlatformOptionsWindows { get; }
	public OptionsMacOSX PlatformOptionsMacOSX { get; }
	public OptionsIOS PlatformOptionsIOS { get; }
	public OptionsTVOS PlatformOptionsTVOS { get; }
	public OptionsAndroid PlatformOptionsAndroid { get; }
	public OptionsWindowsPhone PlatformOptionsWindowsPhone { get; }
	public OptionsWindowsUWP PlatformOptionsWindowsUWP { get; }
	public OptionsWebGL PlatformOptionsWebGL { get; }
	public OptionsPS4 PlatformOptionsPS4 { get; }
	public Boolean SubtitlesEnabled { get; }
	public String SubtitlePath { get; }
	public FileLocation SubtitleLocation { get; }

	// RVA: 0x667efd4 VA: 0x7598c96fd4
	public Resampler get_FrameResampler() { }
	// RVA: 0x667efdc VA: 0x7598c96fdc
	public Boolean get_Persistent() { }
	// RVA: 0x667efe4 VA: 0x7598c96fe4
	public Void set_Persistent(Boolean value) { }
	// RVA: 0x667eff0 VA: 0x7598c96ff0
	public VideoMapping get_VideoLayoutMapping() { }
	// RVA: 0x667eff8 VA: 0x7598c96ff8
	public Void set_VideoLayoutMapping(VideoMapping value) { }
	// RVA: 0x667f000 VA: 0x7598c97000
	public virtual IMediaInfo get_Info() { }
	// RVA: 0x667f008 VA: 0x7598c97008
	public virtual IMediaControl get_Control() { }
	// RVA: 0x667f010 VA: 0x7598c97010
	public virtual IMediaPlayer get_Player() { }
	// RVA: 0x667f018 VA: 0x7598c97018
	public virtual IMediaProducer get_TextureProducer() { }
	// RVA: 0x667f020 VA: 0x7598c97020
	public virtual IMediaSubtitles get_Subtitles() { }
	// RVA: 0x6676644 VA: 0x7598c8e644
	public MediaPlayerEvent get_Events() { }
	// RVA: 0x667f028 VA: 0x7598c97028
	public Boolean get_VideoOpened() { }
	// RVA: 0x667f030 VA: 0x7598c97030
	public Boolean get_PauseMediaOnAppPause() { }
	// RVA: 0x667f038 VA: 0x7598c97038
	public Void set_PauseMediaOnAppPause(Boolean value) { }
	// RVA: 0x667f044 VA: 0x7598c97044
	public Boolean get_PlayMediaOnAppUnpause() { }
	// RVA: 0x667f04c VA: 0x7598c9704c
	public Void set_PlayMediaOnAppUnpause(Boolean value) { }
	// RVA: 0x667f058 VA: 0x7598c97058
	public FileFormat get_ForceFileFormat() { }
	// RVA: 0x667f060 VA: 0x7598c97060
	public Void set_ForceFileFormat(FileFormat value) { }
	// RVA: 0x667f068 VA: 0x7598c97068
	public Void set_AudioHeadTransform(Transform value) { }
	// RVA: 0x667f070 VA: 0x7598c97070
	public Transform get_AudioHeadTransform() { }
	// RVA: 0x667f078 VA: 0x7598c97078
	public Boolean get_AudioFocusEnabled() { }
	// RVA: 0x667f080 VA: 0x7598c97080
	public Void set_AudioFocusEnabled(Boolean value) { }
	// RVA: 0x667f08c VA: 0x7598c9708c
	public Single get_AudioFocusOffLevelDB() { }
	// RVA: 0x667f094 VA: 0x7598c97094
	public Void set_AudioFocusOffLevelDB(Single value) { }
	// RVA: 0x667f09c VA: 0x7598c9709c
	public Single get_AudioFocusWidthDegrees() { }
	// RVA: 0x667f0a4 VA: 0x7598c970a4
	public Void set_AudioFocusWidthDegrees(Single value) { }
	// RVA: 0x667f0ac VA: 0x7598c970ac
	public Transform get_AudioFocusTransform() { }
	// RVA: 0x667f0b4 VA: 0x7598c970b4
	public Void set_AudioFocusTransform(Transform value) { }
	// RVA: 0x667f0bc VA: 0x7598c970bc
	public OptionsWindows get_PlatformOptionsWindows() { }
	// RVA: 0x667f0c4 VA: 0x7598c970c4
	public OptionsMacOSX get_PlatformOptionsMacOSX() { }
	// RVA: 0x667f0cc VA: 0x7598c970cc
	public OptionsIOS get_PlatformOptionsIOS() { }
	// RVA: 0x667f0d4 VA: 0x7598c970d4
	public OptionsTVOS get_PlatformOptionsTVOS() { }
	// RVA: 0x667f0dc VA: 0x7598c970dc
	public OptionsAndroid get_PlatformOptionsAndroid() { }
	// RVA: 0x667f0e4 VA: 0x7598c970e4
	public OptionsWindowsPhone get_PlatformOptionsWindowsPhone() { }
	// RVA: 0x667f0ec VA: 0x7598c970ec
	public OptionsWindowsUWP get_PlatformOptionsWindowsUWP() { }
	// RVA: 0x667f0f4 VA: 0x7598c970f4
	public OptionsWebGL get_PlatformOptionsWebGL() { }
	// RVA: 0x667f0fc VA: 0x7598c970fc
	public OptionsPS4 get_PlatformOptionsPS4() { }
	// RVA: 0x667f104 VA: 0x7598c97104
	private Void Awake() { }
	// RVA: 0x667f184 VA: 0x7598c97184
	protected Void Initialise() { }
	// RVA: 0x667f508 VA: 0x7598c97508
	private Void Start() { }
	// RVA: 0x667fc50 VA: 0x7598c97c50
	public Boolean OpenVideoFromFile(FileLocation location, String path, Boolean autoPlay) { }
	// RVA: 0x667fca0 VA: 0x7598c97ca0
	public Boolean OpenVideoFromBuffer(Byte[] buffer, Boolean autoPlay) { }
	// RVA: 0x667ff08 VA: 0x7598c97f08
	public Boolean StartOpenChunkedVideoFromBuffer(UInt64 length, Boolean autoPlay) { }
	// RVA: 0x6680164 VA: 0x7598c98164
	public Boolean AddChunkToVideoBuffer(Byte[] chunk, UInt64 offset, UInt64 chunkSize) { }
	// RVA: 0x6680260 VA: 0x7598c98260
	public Boolean EndOpenChunkedVideoFromBuffer() { }
	// RVA: 0x6680338 VA: 0x7598c98338
	public Boolean get_SubtitlesEnabled() { }
	// RVA: 0x6680340 VA: 0x7598c98340
	public String get_SubtitlePath() { }
	// RVA: 0x6680348 VA: 0x7598c98348
	public FileLocation get_SubtitleLocation() { }
	// RVA: 0x667f838 VA: 0x7598c97838
	public Boolean EnableSubtitles(FileLocation fileLocation, String filePath) { }
	// RVA: 0x66803dc VA: 0x7598c983dc
	private IEnumerator LoadSubtitlesCoroutine(String url, FileLocation fileLocation, String filePath) { }
	// RVA: 0x66804b8 VA: 0x7598c984b8
	public Void DisableSubtitles() { }
	// RVA: 0x667fd24 VA: 0x7598c97d24
	private Boolean OpenVideoFromBufferInternal(Byte[] buffer) { }
	// RVA: 0x667ff8c VA: 0x7598c97f8c
	private Boolean StartOpenVideoFromBufferInternal(UInt64 length) { }
	// RVA: 0x6680168 VA: 0x7598c98168
	private Boolean AddChunkToBufferInternal(Byte[] chunk, UInt64 offset, UInt64 chunkSize) { }
	// RVA: 0x6680264 VA: 0x7598c98264
	private Boolean EndOpenVideoFromBufferInternal() { }
	// RVA: 0x667f57c VA: 0x7598c9757c
	private Boolean OpenVideoFromFile() { }
	// RVA: 0x668071c VA: 0x7598c9871c
	private Void SetPlaybackOptions() { }
	// RVA: 0x66805cc VA: 0x7598c985cc
	public Void CloseVideo() { }
	// RVA: 0x6680ce4 VA: 0x7598c98ce4
	public Void Play() { }
	// RVA: 0x6680e0c VA: 0x7598c98e0c
	public Void Pause() { }
	// RVA: 0x6680f20 VA: 0x7598c98f20
	public Void Stop() { }
	// RVA: 0x6680fcc VA: 0x7598c98fcc
	public Void Rewind(Boolean pause) { }
	// RVA: 0x6681094 VA: 0x7598c99094
	protected virtual Void Update() { }
	// RVA: 0x6681eb0 VA: 0x7598c99eb0
	private Void LateUpdate() { }
	// RVA: 0x6681eb4 VA: 0x7598c99eb4
	private Void UpdateResampler() { }
	// RVA: 0x6681fa8 VA: 0x7598c99fa8
	private Void OnEnable() { }
	// RVA: 0x668206c VA: 0x7598c9a06c
	private Void OnDisable() { }
	// RVA: 0x6682128 VA: 0x7598c9a128
	protected virtual Void OnDestroy() { }
	// RVA: 0x668224c VA: 0x7598c9a24c
	private Void OnApplicationQuit() { }
	// RVA: 0x667fbe0 VA: 0x7598c97be0
	private Void StartRenderCoroutine() { }
	// RVA: 0x6680ca0 VA: 0x7598c98ca0
	private Void StopRenderCoroutine() { }
	// RVA: 0x6682384 VA: 0x7598c9a384
	private IEnumerator FinalRenderCapture() { }
	// RVA: 0x6680350 VA: 0x7598c98350
	public static Platform GetPlatform() { }
	// RVA: 0x6682420 VA: 0x7598c9a420
	public PlatformOptions GetCurrentPlatformOptions() { }
	// RVA: 0x6682428 VA: 0x7598c9a428
	public static String GetPath(FileLocation location) { }
	// RVA: 0x668254c VA: 0x7598c9a54c
	public static String GetFilePath(String path, FileLocation location) { }
	// RVA: 0x6680c04 VA: 0x7598c98c04
	private String GetPlatformVideoApiString() { }
	// RVA: 0x6680ba4 VA: 0x7598c98ba4
	private Int64 GetPlatformFileOffset() { }
	// RVA: 0x6680bc0 VA: 0x7598c98bc0
	private String GetPlatformHttpHeaderJson() { }
	// RVA: 0x6680358 VA: 0x7598c98358
	private String GetPlatformFilePath(Platform platform, ref String filePath, ref FileLocation fileLocation) { }
	// RVA: 0x6682814 VA: 0x7598c9a814
	public virtual BaseMediaPlayer CreatePlatformMediaPlayer() { }
	// RVA: 0x6682ad8 VA: 0x7598c9aad8
	private Boolean ForceWaitForNewFrame(Int32 lastFrameCount, Single timeoutMs) { }
	// RVA: 0x6681468 VA: 0x7598c99468
	private Void UpdateAudioFocus() { }
	// RVA: 0x66812d8 VA: 0x7598c992d8
	private Void UpdateAudioHeadTransform() { }
	// RVA: 0x66816b0 VA: 0x7598c996b0
	private Void UpdateErrors() { }
	// RVA: 0x6681898 VA: 0x7598c99898
	private Void UpdateEvents() { }
	// RVA: 0x6680c84 VA: 0x7598c98c84
	protected Boolean IsHandleEvent(EventType eventType) { }
	// RVA: 0x6682d64 VA: 0x7598c9ad64
	private Boolean FireEventIfPossible(EventType eventType, Boolean hasFired) { }
	// RVA: 0x6682df0 VA: 0x7598c9adf0
	private Boolean CanFireEvent(EventType et, Boolean hasFired) { }
	// RVA: 0x6683630 VA: 0x7598c9b630
	private Void OnApplicationFocus(Boolean focusStatus) { }
	// RVA: 0x6683714 VA: 0x7598c9b714
	private Void OnApplicationPause(Boolean pauseStatus) { }
	// RVA: 0x6683884 VA: 0x7598c9b884
	private static Camera GetDummyCamera() { }
	// RVA: 0x6683abc VA: 0x7598c9babc
	private IEnumerator ExtractFrameCoroutine(Texture2D target, ProcessExtractedFrame callback, Single timeSeconds, Boolean accurateSeek, Int32 timeoutMs, Int32 timeThresholdMs) { }
	// RVA: 0x6683bb4 VA: 0x7598c9bbb4
	public Void ExtractFrameAsync(Texture2D target, ProcessExtractedFrame callback, Single timeSeconds, Boolean accurateSeek, Int32 timeoutMs, Int32 timeThresholdMs) { }
	// RVA: 0x6683bd8 VA: 0x7598c9bbd8
	public Texture2D ExtractFrame(Texture2D target, Single timeSeconds, Boolean accurateSeek, Int32 timeoutMs, Int32 timeThresholdMs) { }
	// RVA: 0x6683dd8 VA: 0x7598c9bdd8
	private Texture ExtractFrame(Single timeSeconds, Boolean accurateSeek, Int32 timeoutMs, Int32 timeThresholdMs) { }
	// RVA: 0x6684208 VA: 0x7598c9c208
	public Void .ctor() { }
}
```