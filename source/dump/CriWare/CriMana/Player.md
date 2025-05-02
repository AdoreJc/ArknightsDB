# Player

**Namespace:** `CriWare.CriMana`


## Fields

- `Int32 playerId`

- `Boolean isDisposed`

- `Status internalrequiredStatus`

- `Status _nativeStatus`

- `Boolean wasStopping`

- `Boolean isPreparingForRendering`

- `Boolean isNativeStartInvoked`

- `Boolean isNativeInitialized`

- `RendererResource rendererResource`

- `MovieInfo _movieInfo`

- `FrameInfo _frameInfo`

- `Boolean isMovieInfoAvailable`

- `Boolean isFrameInfoAvailable`

- `ShaderDispatchCallback _shaderDispatchCallback`

- `Boolean enableSubtitle`

- `Int32 subtitleBufferSize`

- `UInt32 droppedFrameCount`

- `CriAtomExPlayer _atomExPlayer`

- `CriAtomExPlayer _subAtomExPlayer`

- `CriAtomExPlayer _extraAtomExPlayer`

- `CriAtomEx3dSource _atomEx3Dsource`

- `TimerType _timerType`

- `Boolean isStoppingForSeek`

- `CuePointCallback cuePointCallback`

- `StatusChangeCallback statusChangeCallback`

- `SubtitleChangeCallback OnSubtitleChanged`

- `Boolean <additiveMode>k__BackingField`

- `Int32 <maxFrameDrop>k__BackingField`

- `Boolean <applyTargetAlpha>k__BackingField`

- `Boolean <uiRenderMode>k__BackingField`

- `IntPtr <subtitleBuffer>k__BackingField`

- `Int32 <subtitleSize>k__BackingField`

- `CriManaMoviePlayerHolder <playerHolder>k__BackingField`


## Properties

- `Status requiredStatus`

- `Boolean additiveMode`

- `Int32 maxFrameDrop`

- `Boolean applyTargetAlpha`

- `Boolean uiRenderMode`

- `Boolean isFrameAvailable`

- `MovieInfo movieInfo`

- `FrameInfo frameInfo`

- `Status status`

- `Status nativeStatus`

- `Int32 numberOfEntries`

- `IntPtr subtitleBuffer`

- `Int32 subtitleSize`

- `CriAtomExPlayer atomExPlayer`

- `CriAtomExPlayer subAtomExPlayer`

- `CriAtomExPlayer extraAtomExPlayer`

- `CriAtomEx3dSource atomEx3DsourceForAmbisonics`

- `TimerType timerType`

- `CriManaMoviePlayerHolder playerHolder`

- `Boolean isAlive`


## Methods

- `Status get_requiredStatus()`

- `Void set_requiredStatus(Status)`

- `Void add_OnSubtitleChanged(SubtitleChangeCallback)`

- `Void remove_OnSubtitleChanged(SubtitleChangeCallback)`

- `Boolean get_additiveMode()`

- `Void set_additiveMode(Boolean)`

- `Int32 get_maxFrameDrop()`

- `Void set_maxFrameDrop(Int32)`

- `Boolean get_applyTargetAlpha()`

- `Void set_applyTargetAlpha(Boolean)`

- `Boolean get_uiRenderMode()`

- `Void set_uiRenderMode(Boolean)`

- `Boolean get_isFrameAvailable()`

- `MovieInfo get_movieInfo()`

- `FrameInfo get_frameInfo()`

- `Status get_status()`

- `Status get_nativeStatus()`

- `Int32 get_numberOfEntries()`

- `IntPtr get_subtitleBuffer()`

- `Void set_subtitleBuffer(IntPtr)`

- `Int32 get_subtitleSize()`

- `Void set_subtitleSize(Int32)`

- `CriAtomExPlayer get_atomExPlayer()`

- `CriAtomExPlayer get_subAtomExPlayer()`

- `CriAtomExPlayer get_extraAtomExPlayer()`

- `CriAtomEx3dSource get_atomEx3DsourceForAmbisonics()`

- `TimerType get_timerType()`

- `CriManaMoviePlayerHolder get_playerHolder()`

- `Void set_playerHolder(CriManaMoviePlayerHolder)`

- `Void CreateRendererResource(Int32, Int32, Boolean)`

- `Void DisposeRendererResource()`

- `Void Prepare()`

- `Void PrepareForRendering()`

- `Void Start()`

- `Void Stop()`

- `Void StopForSeek()`

- `Void Pause(Boolean)`

- `Boolean IsPaused()`

- `Boolean SetFile(CriFsBinder, String, SetMode)`

- `Boolean SetData(IntPtr, Int64, SetMode)`

- `Boolean SetData(Byte[], Int64, SetMode)`

- `Boolean SetContentId(CriFsBinder, Int32, SetMode)`

- `Boolean SetFileRange(String, UInt64, Int64, SetMode)`

- `Void Loop(Boolean)`

- `Void SetAudioBaseConcatenation(Boolean)`

- `Void SetMasterTimerType(TimerType)`

- `Void SetSeekPosition(Int32)`

- `Void SetMovieEventSyncMode(MovieEventSyncMode)`

- `Void SetSpeed(Single)`

- `Void SetMaxPictureDataSize(UInt32)`

- `Void SetBufferingTime(Single)`

- `Void SetMinBufferSize(Int32)`

- `Void SetAudioTrack(Int32)`

- `Void SetAudioTrack(AudioTrack)`

- `Void SetSubAudioTrack(Int32)`

- `Void SetSubAudioTrack(AudioTrack)`

- `Void SetExtraAudioTrack(Int32)`

- `Void SetExtraAudioTrack(AudioTrack)`

- `Void SetVolume(Single)`

- `Single GetVolume()`

- `Void SetSubAudioVolume(Single)`

- `Single GetSubAudioVolume()`

- `Void SetExtraAudioVolume(Single)`

- `Single GetExtraAudioVolume()`

- `Void SetBusSendLevel(String, Single)`

- `Void SetSubAudioBusSendLevel(String, Single)`

- `Void SetExtraAudioBusSendLevel(String, Single)`

- `Void SetSubtitleChannel(Int32)`

- `Void SetShaderDispatchCallback(ShaderDispatchCallback)`

- `Int64 GetTime()`

- `Int32 GetDisplayedFrameNo()`

- `Boolean HasRenderedNewFrame()`

- `Void SetAsrRackId(Int32)`

- `Void SetTimeStretchQuality(Single)`

- `Void SetDecryptionKey(UInt64)`

- `Void UpdateWithUserTime(UInt64, UInt64)`

- `Void SetManualTimerUnit(UInt64, UInt64)`

- `Void UpdateWithManualTimeAdvanced()`

- `Void Update()`

- `Void SyncMasterTimer()`

- `Void OnWillRenderObject(CriManaMovieMaterialBase)`

- `Boolean UpdateMaterial(Material)`

- `Void PauseOnApplicationPause(Boolean)`

- `Boolean get_isAlive()`

- `Void IssuePluginEvent(CriManaUnityPlayer_RenderEventAction)`

- `Void Dispose(Boolean)`

- `Void InternalUpdate()`

- `IEnumerator IssuePluginUpdatesForFrames(Int32, MonoBehaviour, Boolean, Int32)`

- `Void DisableInfos(Boolean)`

- `Void PrepareNativePlayer()`

- `Void UpdateNativePlayer()`

- `Void InvokePlayerStatusCheck()`

- `Void AllocateSubtitleBuffer(Int32)`

- `Void DeallocateSubtitleBuffer()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana
public class Player : CriDisposable
{
	private const Int32 InvalidPlayerId; // 0x0
	private static Player updatingPlayer; // 0x0
	private Int32 playerId; // 0x20
	private Boolean isDisposed; // 0x24
	private Status internalrequiredStatus; // 0x28
	private Status _nativeStatus; // 0x2c
	private Nullable`1 lastNativeStatus; // 0x30
	private Nullable`1 lastPlayerStatus; // 0x38
	private Boolean wasStopping; // 0x40
	private Boolean isPreparingForRendering; // 0x41
	private Boolean isNativeStartInvoked; // 0x42
	private Boolean isNativeInitialized; // 0x43
	private RendererResource rendererResource; // 0x48
	private MovieInfo _movieInfo; // 0x50
	private FrameInfo _frameInfo; // 0x58
	private Boolean isMovieInfoAvailable; // 0x60
	private Boolean isFrameInfoAvailable; // 0x61
	private ShaderDispatchCallback _shaderDispatchCallback; // 0x68
	private Boolean enableSubtitle; // 0x70
	private Int32 subtitleBufferSize; // 0x74
	private UInt32 droppedFrameCount; // 0x78
	private CriAtomExPlayer _atomExPlayer; // 0x80
	private CriAtomExPlayer _subAtomExPlayer; // 0x88
	private CriAtomExPlayer _extraAtomExPlayer; // 0x90
	private CriAtomEx3dSource _atomEx3Dsource; // 0x98
	private TimerType _timerType; // 0xa0
	private Boolean isStoppingForSeek; // 0xa4
	public CuePointCallback cuePointCallback; // 0xa8
	public StatusChangeCallback statusChangeCallback; // 0xb0
	private SubtitleChangeCallback OnSubtitleChanged; // 0xb8
	private Boolean <additiveMode>k__BackingField; // 0xc0
	private Int32 <maxFrameDrop>k__BackingField; // 0xc4
	private Boolean <applyTargetAlpha>k__BackingField; // 0xc8
	private Boolean <uiRenderMode>k__BackingField; // 0xc9
	private IntPtr <subtitleBuffer>k__BackingField; // 0xd0
	private Int32 <subtitleSize>k__BackingField; // 0xd8
	private CriManaMoviePlayerHolder <playerHolder>k__BackingField; // 0xe0

	private Status requiredStatus { get; set; }
	public Boolean additiveMode { get; set; }
	public Int32 maxFrameDrop { get; set; }
	public Boolean applyTargetAlpha { get; set; }
	public Boolean uiRenderMode { get; set; }
	public Boolean isFrameAvailable { get; }
	public MovieInfo movieInfo { get; }
	public FrameInfo frameInfo { get; }
	public Status status { get; }
	public Status nativeStatus { get; }
	public Int32 numberOfEntries { get; }
	public IntPtr subtitleBuffer { get; set; }
	public Int32 subtitleSize { get; set; }
	public CriAtomExPlayer atomExPlayer { get; }
	public CriAtomExPlayer subAtomExPlayer { get; }
	public CriAtomExPlayer extraAtomExPlayer { get; }
	public CriAtomEx3dSource atomEx3DsourceForAmbisonics { get; }
	public TimerType timerType { get; }
	public CriManaMoviePlayerHolder playerHolder { get; set; }
	public Boolean isAlive { get; }

	// RVA: 0x4155f90 VA: 0x759676df90
	private Status get_requiredStatus() { }
	// RVA: 0x4155f98 VA: 0x759676df98
	private Void set_requiredStatus(Status value) { }
	// RVA: 0x4156094 VA: 0x759676e094
	public Void add_OnSubtitleChanged(SubtitleChangeCallback value) { }
	// RVA: 0x4156130 VA: 0x759676e130
	public Void remove_OnSubtitleChanged(SubtitleChangeCallback value) { }
	// RVA: 0x41561cc VA: 0x759676e1cc
	public Boolean get_additiveMode() { }
	// RVA: 0x41561d4 VA: 0x759676e1d4
	public Void set_additiveMode(Boolean value) { }
	// RVA: 0x41561e0 VA: 0x759676e1e0
	public Int32 get_maxFrameDrop() { }
	// RVA: 0x41561e8 VA: 0x759676e1e8
	public Void set_maxFrameDrop(Int32 value) { }
	// RVA: 0x41561f0 VA: 0x759676e1f0
	public Boolean get_applyTargetAlpha() { }
	// RVA: 0x41561f8 VA: 0x759676e1f8
	public Void set_applyTargetAlpha(Boolean value) { }
	// RVA: 0x4156204 VA: 0x759676e204
	public Boolean get_uiRenderMode() { }
	// RVA: 0x415620c VA: 0x759676e20c
	public Void set_uiRenderMode(Boolean value) { }
	// RVA: 0x4156218 VA: 0x759676e218
	public Boolean get_isFrameAvailable() { }
	// RVA: 0x41504d0 VA: 0x75967684d0
	public MovieInfo get_movieInfo() { }
	// RVA: 0x4156220 VA: 0x759676e220
	public FrameInfo get_frameInfo() { }
	// RVA: 0x414f01c VA: 0x759676701c
	public Status get_status() { }
	// RVA: 0x4156238 VA: 0x759676e238
	public Status get_nativeStatus() { }
	// RVA: 0x4156240 VA: 0x759676e240
	public Int32 get_numberOfEntries() { }
	// RVA: 0x4156324 VA: 0x759676e324
	public IntPtr get_subtitleBuffer() { }
	// RVA: 0x415632c VA: 0x759676e32c
	private Void set_subtitleBuffer(IntPtr value) { }
	// RVA: 0x4156334 VA: 0x759676e334
	public Int32 get_subtitleSize() { }
	// RVA: 0x415633c VA: 0x759676e33c
	private Void set_subtitleSize(Int32 value) { }
	// RVA: 0x4156344 VA: 0x759676e344
	public CriAtomExPlayer get_atomExPlayer() { }
	// RVA: 0x415634c VA: 0x759676e34c
	public CriAtomExPlayer get_subAtomExPlayer() { }
	// RVA: 0x4156354 VA: 0x759676e354
	public CriAtomExPlayer get_extraAtomExPlayer() { }
	// RVA: 0x415635c VA: 0x759676e35c
	public CriAtomEx3dSource get_atomEx3DsourceForAmbisonics() { }
	// RVA: 0x4156364 VA: 0x759676e364
	public TimerType get_timerType() { }
	// RVA: 0x415636c VA: 0x759676e36c
	public CriManaMoviePlayerHolder get_playerHolder() { }
	// RVA: 0x4156374 VA: 0x759676e374
	public Void set_playerHolder(CriManaMoviePlayerHolder value) { }
	// RVA: 0x415637c VA: 0x759676e37c
	public Void .ctor() { }
	// RVA: 0x41566ac VA: 0x759676e6ac
	public Void .ctor(Boolean advanced_audio_mode, Boolean ambisonics_mode, UInt32 max_path_length) { }
	// RVA: 0x4156b98 VA: 0x759676eb98
	protected override Void Finalize() { }
	// RVA: 0x4156ed8 VA: 0x759676eed8
	public override Void Dispose() { }
	// RVA: 0x4156f3c VA: 0x759676ef3c
	public Void CreateRendererResource(Int32 width, Int32 height, Boolean alpha) { }
	// RVA: 0x41574c4 VA: 0x759676f4c4
	public Void DisposeRendererResource() { }
	// RVA: 0x41574f4 VA: 0x759676f4f4
	public Void Prepare() { }
	// RVA: 0x414f458 VA: 0x7596767458
	public Void PrepareForRendering() { }
	// RVA: 0x414f198 VA: 0x7596767198
	public Void Start() { }
	// RVA: 0x414f6e4 VA: 0x75967676e4
	public Void Stop() { }
	// RVA: 0x414f610 VA: 0x7596767610
	public Void StopForSeek() { }
	// RVA: 0x41506a4 VA: 0x75967686a4
	public Void Pause(Boolean sw) { }
	// RVA: 0x415069c VA: 0x759676869c
	public Boolean IsPaused() { }
	// RVA: 0x414f0d4 VA: 0x75967670d4
	public Boolean SetFile(CriFsBinder binder, String moviePath, SetMode setMode) { }
	// RVA: 0x414f0a8 VA: 0x75967670a8
	public Boolean SetData(IntPtr data, Int64 dataSize, SetMode setMode) { }
	// RVA: 0x4157d90 VA: 0x759676fd90
	public Boolean SetData(Byte[] data, Int64 datasize, SetMode setMode) { }
	// RVA: 0x4157fa4 VA: 0x759676ffa4
	public Boolean SetContentId(CriFsBinder binder, Int32 contentId, SetMode setMode) { }
	// RVA: 0x4158250 VA: 0x7596770250
	public Boolean SetFileRange(String filePath, UInt64 offset, Int64 range, SetMode setMode) { }
	// RVA: 0x414f170 VA: 0x7596767170
	public Void Loop(Boolean sw) { }
	// RVA: 0x4158558 VA: 0x7596770558
	public Void SetAudioBaseConcatenation(Boolean enabled) { }
	// RVA: 0x4158640 VA: 0x7596770640
	public Void SetMasterTimerType(TimerType timerType) { }
	// RVA: 0x414f190 VA: 0x7596767190
	public Void SetSeekPosition(Int32 frameNumber) { }
	// RVA: 0x4158808 VA: 0x7596770808
	public Void SetMovieEventSyncMode(MovieEventSyncMode mode) { }
	// RVA: 0x41588ec VA: 0x75967708ec
	public Void SetSpeed(Single speed) { }
	// RVA: 0x41589d0 VA: 0x75967709d0
	public Void SetMaxPictureDataSize(UInt32 maxDataSize) { }
	// RVA: 0x4158ab4 VA: 0x7596770ab4
	public Void SetBufferingTime(Single sec) { }
	// RVA: 0x4158b98 VA: 0x7596770b98
	public Void SetMinBufferSize(Int32 min_buffer_size) { }
	// RVA: 0x4158c7c VA: 0x7596770c7c
	public Void SetAudioTrack(Int32 track) { }
	// RVA: 0x4158d60 VA: 0x7596770d60
	public Void SetAudioTrack(AudioTrack track) { }
	// RVA: 0x4158d84 VA: 0x7596770d84
	public Void SetSubAudioTrack(Int32 track) { }
	// RVA: 0x4158e68 VA: 0x7596770e68
	public Void SetSubAudioTrack(AudioTrack track) { }
	// RVA: 0x4158e8c VA: 0x7596770e8c
	public Void SetExtraAudioTrack(Int32 track) { }
	// RVA: 0x4158f70 VA: 0x7596770f70
	public Void SetExtraAudioTrack(AudioTrack track) { }
	// RVA: 0x414f744 VA: 0x7596767744
	public Void SetVolume(Single volume) { }
	// RVA: 0x414ec8c VA: 0x7596766c8c
	public Single GetVolume() { }
	// RVA: 0x414f74c VA: 0x759676774c
	public Void SetSubAudioVolume(Single volume) { }
	// RVA: 0x414ec94 VA: 0x7596766c94
	public Single GetSubAudioVolume() { }
	// RVA: 0x414f754 VA: 0x7596767754
	public Void SetExtraAudioVolume(Single volume) { }
	// RVA: 0x414ec9c VA: 0x7596766c9c
	public Single GetExtraAudioVolume() { }
	// RVA: 0x41594c8 VA: 0x75967714c8
	public Void SetBusSendLevel(String bus_name, Single level) { }
	// RVA: 0x41595c4 VA: 0x75967715c4
	public Void SetSubAudioBusSendLevel(String bus_name, Single volume) { }
	// RVA: 0x41596c0 VA: 0x75967716c0
	public Void SetExtraAudioBusSendLevel(String bus_name, Single volume) { }
	// RVA: 0x41597bc VA: 0x75967717bc
	public Void SetSubtitleChannel(Int32 channel) { }
	// RVA: 0x4159c9c VA: 0x7596771c9c
	public Void SetShaderDispatchCallback(ShaderDispatchCallback shaderDispatchCallback) { }
	// RVA: 0x4159ca4 VA: 0x7596771ca4
	public Int64 GetTime() { }
	// RVA: 0x4159d8c VA: 0x7596771d8c
	public Int32 GetDisplayedFrameNo() { }
	// RVA: 0x4151534 VA: 0x7596769534
	public Boolean HasRenderedNewFrame() { }
	// RVA: 0x4159ea0 VA: 0x7596771ea0
	public Void SetAsrRackId(Int32 asrRackId) { }
	// RVA: 0x4159f84 VA: 0x7596771f84
	public Void SetTimeStretchQuality(Single quality) { }
	// RVA: 0x415a068 VA: 0x7596772068
	public Void SetDecryptionKey(UInt64 key) { }
	// RVA: 0x41504e8 VA: 0x75967684e8
	public Void UpdateWithUserTime(UInt64 timeCount, UInt64 timeUnit) { }
	// RVA: 0x415a5ec VA: 0x75967725ec
	public Void SetManualTimerUnit(UInt64 timeUnitN, UInt64 timeUnitD) { }
	// RVA: 0x415a770 VA: 0x7596772770
	public Void UpdateWithManualTimeAdvanced() { }
	// RVA: 0x415a8cc VA: 0x75967728cc
	public Void Update() { }
	// RVA: 0x415a8e4 VA: 0x75967728e4
	public Void SyncMasterTimer() { }
	// RVA: 0x41505e8 VA: 0x75967685e8
	public Void OnWillRenderObject(CriManaMovieMaterialBase sender) { }
	// RVA: 0x415aa40 VA: 0x7596772a40
	public Boolean UpdateMaterial(Material material) { }
	// RVA: 0x415aa88 VA: 0x7596772a88
	public Void PauseOnApplicationPause(Boolean sw) { }
	// RVA: 0x415aae4 VA: 0x7596772ae4
	public Boolean get_isAlive() { }
	// RVA: 0x415a9c0 VA: 0x75967729c0
	public Void IssuePluginEvent(CriManaUnityPlayer_RenderEventAction renderEventAction) { }
	// RVA: 0x4156c30 VA: 0x759676ec30
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x415a238 VA: 0x7596772238
	private Void InternalUpdate() { }
	// RVA: 0x415acb0 VA: 0x7596772cb0
	private IEnumerator IssuePluginUpdatesForFrames(Int32 frameCount, MonoBehaviour playerHolder, Boolean destroy, Int32 playerId) { }
	// RVA: 0x41577f4 VA: 0x759676f7f4
	private Void DisableInfos(Boolean keepFrameInfo) { }
	// RVA: 0x415753c VA: 0x759676f53c
	private Void PrepareNativePlayer() { }
	// RVA: 0x41575cc VA: 0x759676f5cc
	private Void UpdateNativePlayer() { }
	// RVA: 0x4155fc0 VA: 0x759676dfc0
	private Void InvokePlayerStatusCheck() { }
	// RVA: 0x4159a48 VA: 0x7596771a48
	private Void AllocateSubtitleBuffer(Int32 size) { }
	// RVA: 0x4159b18 VA: 0x7596771b18
	private Void DeallocateSubtitleBuffer() { }
	// RVA: 0x41565d0 VA: 0x759676e5d0
	internal Void SetupPlayerHolder() { }
	// RVA: 0x4155e78 VA: 0x759676de78
	private static Void CuePointCallbackFromNative(IntPtr ptr1, IntPtr ptr2, in EventPoint eventPoint) { }
	// RVA: 0x4155ef0 VA: 0x759676def0
	private static Void SubtitleCallbackFromNative(IntPtr ptr1, IntPtr ptr2) { }
	// RVA: 0x4156248 VA: 0x759676e248
	internal static Int32 NativeMethods_GetNumberOfEntry(Int32 playerId) { }
	// RVA: 0x4156504 VA: 0x759676e504
	internal static Int32 NativeMethods_Create() { }
	// RVA: 0x41569cc VA: 0x759676e9cc
	internal static Int32 NativeMethods_CreateWithParameters(Boolean useAtomExPlayer, UInt32 maxPathLength) { }
	// RVA: 0x4156ab0 VA: 0x759676eab0
	internal static IntPtr NativeMethods_GetAtomExPlayerByTrackId(Int32 player_id, UInt32 track_id) { }
	// RVA: 0x4157720 VA: 0x759676f720
	internal Void NativeMethods_Stop(Int32 player_id) { }
	// RVA: 0x4157808 VA: 0x759676f808
	internal Void NativeMethods_Pause(Int32 player_id, Int32 sw) { }
	// RVA: 0x41578e4 VA: 0x759676f8e4
	internal static Boolean NativeMethods_IsPaused(Int32 player_id) { }
	// RVA: 0x41579c0 VA: 0x759676f9c0
	internal static Void NativeMethods_SetFile(Int32 player_id, IntPtr binder, String path) { }
	// RVA: 0x4157aac VA: 0x759676faac
	internal static Boolean NativeMethods_EntryFile(Int32 player_id, IntPtr binder, String path, Boolean repeat) { }
	// RVA: 0x4157ba8 VA: 0x759676fba8
	internal static Void NativeMethods_SetData(Int32 player_id, IntPtr data, Int64 datasize) { }
	// RVA: 0x4157dbc VA: 0x759676fdbc
	internal static Void NativeMethods_SetData(Int32 player_id, Byte[] data, Int64 datasize) { }
	// RVA: 0x4157c94 VA: 0x759676fc94
	internal static Boolean NativeMethods_EntryData(Int32 player_id, IntPtr data, Int64 datasize, Boolean repeat) { }
	// RVA: 0x4157ea8 VA: 0x759676fea8
	internal static Boolean NativeMethods_EntryData(Int32 player_id, Byte[] data, Int64 datasize, Boolean repeat) { }
	// RVA: 0x4158068 VA: 0x7596770068
	internal static Void NativeMethods_SetContentId(Int32 player_id, IntPtr binder, Int32 content_id) { }
	// RVA: 0x4158154 VA: 0x7596770154
	internal static Boolean NativeMethods_EntryContentId(Int32 player_id, IntPtr binder, Int32 content_id, Boolean repeat) { }
	// RVA: 0x415827c VA: 0x759677027c
	internal static Void NativeMethods_SetFileRange(Int32 player_id, String path, UInt64 offset, Int64 range) { }
	// RVA: 0x4158370 VA: 0x7596770370
	internal static Boolean NativeMethods_EntryFileRange(Int32 player_id, String path, UInt64 offset, Int64 range, Boolean repeat) { }
	// RVA: 0x415847c VA: 0x759677047c
	internal Void NativeMethods_Loop(Int32 player_id, Int32 sw) { }
	// RVA: 0x4158564 VA: 0x7596770564
	internal static Void NativeMethods_SetAudioBaseConcatenation(Int32 player_id, Boolean flag) { }
	// RVA: 0x4158650 VA: 0x7596770650
	internal static Void NativeMethods_SetMasterTimerType(Int32 player_id, TimerType timer_type) { }
	// RVA: 0x415872c VA: 0x759677072c
	internal static Void NativeMethods_SetSeekPosition(Int32 player_id, Int32 seek_frame_no) { }
	// RVA: 0x4158810 VA: 0x7596770810
	internal static Void NativeMethods_SetMovieEventSyncMode(Int32 player_id, MovieEventSyncMode mode) { }
	// RVA: 0x41588f4 VA: 0x75967708f4
	internal static Void NativeMethods_SetSpeed(Int32 player_id, Single speed) { }
	// RVA: 0x41589d8 VA: 0x75967709d8
	internal static Void NativeMethods_SetMaxPictureDataSize(Int32 player_id, UInt32 max_data_size) { }
	// RVA: 0x4158abc VA: 0x7596770abc
	internal static Void NativeMethods_SetBufferingTime(Int32 player_id, Single sec) { }
	// RVA: 0x4158ba0 VA: 0x7596770ba0
	internal static Void NativeMethods_SetMinBufferSize(Int32 player_id, Int32 min_buffer_size) { }
	// RVA: 0x4158c84 VA: 0x7596770c84
	internal static Void NativeMethods_SetAudioTrack(Int32 player_id, Int32 track) { }
	// RVA: 0x4158d8c VA: 0x7596770d8c
	internal static Void NativeMethods_SetSubAudioTrack(Int32 player_id, Int32 track) { }
	// RVA: 0x4158e94 VA: 0x7596770e94
	internal static Void NativeMethods_SetExtraAudioTrack(Int32 player_id, Int32 track) { }
	// RVA: 0x4158f94 VA: 0x7596770f94
	internal static Void NativeMethods_SetVolume(Int32 player_id, Single vol) { }
	// RVA: 0x4159070 VA: 0x7596771070
	internal static Single NativeMethods_GetVolume(Int32 player_id) { }
	// RVA: 0x4159150 VA: 0x7596771150
	internal static Void NativeMethods_SetSubAudioVolume(Int32 player_id, Single vol) { }
	// RVA: 0x415922c VA: 0x759677122c
	internal static Single NativeMethods_GetSubAudioVolume(Int32 player_id) { }
	// RVA: 0x415930c VA: 0x759677130c
	internal static Void NativeMethods_SetExtraAudioVolume(Int32 player_id, Single vol) { }
	// RVA: 0x41593e8 VA: 0x75967713e8
	internal static Single NativeMethods_GetExtraAudioVolume(Int32 player_id) { }
	// RVA: 0x41594d0 VA: 0x75967714d0
	internal static Void NativeMethods_SetBusSendLevelByName(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x41595cc VA: 0x75967715cc
	internal static Void NativeMethods_SetSubAudioBusSendLevelByName(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x41596c8 VA: 0x75967716c8
	internal static Void NativeMethods_SetExtraAudioBusSendLevelByName(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x415996c VA: 0x759677196c
	internal static Void NativeMethods_SetSubtitleCallback(Int32 player_id, SubtitleCallbackFromNativeDelegate cbfunc) { }
	// RVA: 0x4159bc0 VA: 0x7596771bc0
	internal static Void NativeMethods_SetSubtitleChannel(Int32 player_id, Int32 channel) { }
	// RVA: 0x4159cac VA: 0x7596771cac
	internal static Int64 NativeMethods_GetTime(Int32 player_id) { }
	// RVA: 0x4159dc4 VA: 0x7596771dc4
	internal static Int32 NativeMethods_GetDisplayedFrameNo(Int32 player_id) { }
	// RVA: 0x4159ea8 VA: 0x7596771ea8
	internal static Void NativeMethods_SetAsrRackId(Int32 player_id, Int32 asr_rack_id) { }
	// RVA: 0x4159f8c VA: 0x7596771f8c
	internal static Void NativeMethods_SetTimeStretchQuality(Int32 player_id, Single quality) { }
	// RVA: 0x415a14c VA: 0x759677214c
	internal static Void NativeMethods_SetUserTime(Int32 player_id, UInt64 user_count, UInt64 user_unit) { }
	// RVA: 0x415a684 VA: 0x7596772684
	internal static Void NativeMethods_SetManualTimerUnit(Int32 player_id, UInt64 timer_unit_n, UInt64 timer_unit_d) { }
	// RVA: 0x415a7f8 VA: 0x75967727f8
	internal static Void NativeMethods_AdvanceManualTimer(Int32 player_id) { }
	// RVA: 0x415a8ec VA: 0x75967728ec
	internal static Void NativeMethods_SyncMasterTimer(Int32 player_id) { }
	// RVA: 0x415aaf4 VA: 0x7596772af4
	internal static IntPtr NativeMethods_GetRenderEventFunc() { }
	// RVA: 0x415abdc VA: 0x7596772bdc
	internal static Void NativeMethods_Destroy(Int32 player_id) { }
	// RVA: 0x415ad64 VA: 0x7596772d64
	internal static Void NativeMethods_SyncUpdate(Int32 player_id) { }
	// RVA: 0x415ae38 VA: 0x7596772e38
	internal static Void NativeMethods_GetMovieInfo(Int32 player_id, [Out] MovieInfo movie_info) { }
	// RVA: 0x415af14 VA: 0x7596772f14
	internal Void NativeMethods_Start(Int32 player_id) { }
	// RVA: 0x415b1c0 VA: 0x75967731c0
	internal Void NativeMethods_Prepare(Int32 player_id) { }
	// RVA: 0x415b294 VA: 0x7596773294
	internal static Int32 NativeMethods_Update(Int32 player_id) { }
	// RVA: 0x415b0e4 VA: 0x75967730e4
	internal static Void NativeMethods_SetCuePointCallback(Int32 player_id, CuePointCallbackFromNativeDelegate cbfunc) { }
	// RVA: 0x415b370 VA: 0x7596773370
	internal static Int32 NativeMethods_GetSubtitleOnTime(Int32 player_id, IntPtr subtitle_buffer, Int32 subtitle_buffer_size) { }
	// RVA: 0x415a070 VA: 0x7596772070
	internal static Void NativeMethods_SetDecryptionKey(Int32 player_id, UInt64 key) { }
	// RVA: 0x415b4e0 VA: 0x75967734e0
	internal static extern Int32 CRIWAREE9FC813E() { }
	// RVA: 0x415d42c VA: 0x759677542c
	internal static extern Int32 CRIWARE3A6E2552() { }
	// RVA: 0x415b548 VA: 0x7596773548
	internal static extern Int32 CRIWARE94E9893B(Boolean useAtomExPlayer, UInt32 maxPathLength) { }
	// RVA: 0x415cf5c VA: 0x7596774f5c
	internal static extern Void CRIWARE99111FE9(Int32 player_id) { }
	// RVA: 0x415b7d4 VA: 0x75967737d4
	internal static extern Void CRIWARE3FF6C123(Int32 player_id, IntPtr binder, String path) { }
	// RVA: 0x415bbb8 VA: 0x7596773bb8
	internal static extern Void CRIWARE74F9373A(Int32 player_id, IntPtr binder, Int32 content_id) { }
	// RVA: 0x415bcf0 VA: 0x7596773cf0
	internal static extern Void CRIWAREAC81C8CF(Int32 player_id, String path, UInt64 offset, Int64 range) { }
	// RVA: 0x415b938 VA: 0x7596773938
	internal static extern Void CRIWAREBD7E64E1(Int32 player_id, IntPtr data, Int64 datasize) { }
	// RVA: 0x415b9cc VA: 0x75967739cc
	internal static extern Void CRIWAREBD7E64E1(Int32 player_id, Byte[] data, Int64 datasize) { }
	// RVA: 0x415b87c VA: 0x759677387c
	internal static extern Boolean CRIWARE340855B4(Int32 player_id, IntPtr binder, String path, Boolean repeat) { }
	// RVA: 0x415bc4c VA: 0x7596773c4c
	internal static extern Boolean CRIWARE89F5F4E8(Int32 player_id, IntPtr binder, Int32 content_id, Boolean repeat) { }
	// RVA: 0x415bda0 VA: 0x7596773da0
	internal static extern Boolean CRIWARE2B9092A9(Int32 player_id, String path, UInt64 offset, Int64 range, Boolean repeat) { }
	// RVA: 0x415ba68 VA: 0x7596773a68
	internal static extern Boolean CRIWARE6587A256(Int32 player_id, IntPtr data, Int64 datasize, Boolean repeat) { }
	// RVA: 0x415bb0c VA: 0x7596773b0c
	internal static extern Boolean CRIWARE6587A256(Int32 player_id, Byte[] data, Int64 datasize, Boolean repeat) { }
	// RVA: 0x415d494 VA: 0x7596775494
	internal static extern Void CRIWARE35201A91(Int32 player_id) { }
	// RVA: 0x415b464 VA: 0x7596773464
	internal static extern Int32 CRIWARE1354FEA7(Int32 player_id) { }
	// RVA: 0x415d288 VA: 0x7596775288
	internal static extern Void CRIWARE62E9D3D4(Int32 player_id, CuePointCallbackFromNativeDelegate cbfunc) { }
	// RVA: 0x415c9bc VA: 0x75967749bc
	internal static extern Void CRIWARE11EC40C0(Int32 player_id, SubtitleCallbackFromNativeDelegate cbfunc) { }
	// RVA: 0x415d054 VA: 0x7596775054
	internal static extern Void CRIWARE9A8AC346(Int32 player_id, [Out] MovieInfo movie_info) { }
	// RVA: 0x415d20c VA: 0x759677520c
	internal static extern Int32 CRIWAREC2475753(Int32 player_id) { }
	// RVA: 0x415d190 VA: 0x7596775190
	internal static extern Void CRIWARE7652287A(Int32 player_id) { }
	// RVA: 0x415d114 VA: 0x7596775114
	internal static extern Void CRIWARE439340B3(Int32 player_id) { }
	// RVA: 0x415b650 VA: 0x7596773650
	internal static extern Void CRIWAREFC4BD812(Int32 player_id) { }
	// RVA: 0x415bff8 VA: 0x7596773ff8
	internal static extern Void CRIWAREAA815027(Int32 player_id, Int32 seek_frame_no) { }
	// RVA: 0x415c07c VA: 0x759677407c
	internal static extern Void CRIWARED3E36645(Int32 player_id, MovieEventSyncMode mode) { }
	// RVA: 0x415b6cc VA: 0x75967736cc
	internal static extern Void CRIWARE2AC4CA7E(Int32 player_id, Int32 sw) { }
	// RVA: 0x415b750 VA: 0x7596773750
	internal static extern Boolean CRIWARE88ED0C7C(Int32 player_id) { }
	// RVA: 0x415be6c VA: 0x7596773e6c
	internal static extern Void CRIWARE284D752E(Int32 player_id, Int32 sw) { }
	// RVA: 0x415bef0 VA: 0x7596773ef0
	internal static extern Void CRIWAREE054EF2C(Int32 player_id, Boolean flag) { }
	// RVA: 0x415cacc VA: 0x7596774acc
	internal static extern Int64 CRIWARE626DF59A(Int32 player_id) { }
	// RVA: 0x415d510 VA: 0x7596775510
	internal static extern Int32 CRIWARE015F102F(Int32 player_id) { }
	// RVA: 0x415b5cc VA: 0x75967735cc
	internal static extern IntPtr CRIWARE4E36FD70(Int32 player_id, UInt32 track_id) { }
	// RVA: 0x415cb48 VA: 0x7596774b48
	internal static extern Int32 CRIWAREFD3EF64A(Int32 player_id) { }
	// RVA: 0x415c320 VA: 0x7596774320
	internal static extern Void CRIWARE0CA1216B(Int32 player_id, Int32 track) { }
	// RVA: 0x415c4ac VA: 0x75967744ac
	internal static extern Void CRIWARE4F06C1D4(Int32 player_id, Single vol) { }
	// RVA: 0x415c538 VA: 0x7596774538
	internal static extern Single CRIWARE086C6A97(Int32 player_id) { }
	// RVA: 0x415c3a4 VA: 0x75967743a4
	internal static extern Void CRIWARE9EC619B6(Int32 player_id, Int32 track) { }
	// RVA: 0x415c5b4 VA: 0x75967745b4
	internal static extern Void CRIWARE9B69D97C(Int32 player_id, Single vol) { }
	// RVA: 0x415c640 VA: 0x7596774640
	internal static extern Single CRIWAREE218A3A4(Int32 player_id) { }
	// RVA: 0x415c428 VA: 0x7596774428
	internal static extern Void CRIWARE894B55A2(Int32 player_id, Int32 track) { }
	// RVA: 0x415c6bc VA: 0x75967746bc
	internal static extern Void CRIWARE27EEE694(Int32 player_id, Single vol) { }
	// RVA: 0x415c748 VA: 0x7596774748
	internal static extern Single CRIWAREF299792C(Int32 player_id) { }
	// RVA: 0x415c7c4 VA: 0x75967747c4
	internal static extern Void CRIWARED5BBE158(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x415c86c VA: 0x759677486c
	internal static extern Void CRIWARE068E5808(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x415c914 VA: 0x7596774914
	internal static extern Void CRIWARE5604C40B(Int32 player_id, String bus_name, Single level) { }
	// RVA: 0x415ca48 VA: 0x7596774a48
	internal static extern Void CRIWARE6F6D87FE(Int32 player_id, Int32 channel) { }
	// RVA: 0x415d314 VA: 0x7596775314
	internal static extern Int32 CRIWARE65D61A6A(Int32 player_id, IntPtr subtitle_buffer, Int32 subtitle_buffer_size) { }
	// RVA: 0x415c100 VA: 0x7596774100
	internal static extern Void CRIWARE61B8FA6A(Int32 player_id, Single speed) { }
	// RVA: 0x415c18c VA: 0x759677418c
	internal static extern Void CRIWAREECCF5E62(Int32 player_id, UInt32 max_data_size) { }
	// RVA: 0x415c210 VA: 0x7596774210
	internal static extern Void CRIWAREB73990A9(Int32 player_id, Single sec) { }
	// RVA: 0x415c29c VA: 0x759677429c
	internal static extern Void CRIWAREC4A02CCE(Int32 player_id, Int32 min_buffer_size) { }
	// RVA: 0x415cbc4 VA: 0x7596774bc4
	internal static extern Void CRIWARE35F190C7(Int32 player_id, Int32 asr_rack_id) { }
	// RVA: 0x415cc48 VA: 0x7596774c48
	internal static extern Void CRIWAREF0F20CEB(Int32 player_id, Single quality) { }
	// RVA: 0x415cfd8 VA: 0x7596774fd8
	internal static extern Void CRIWARE74BAE3A5(Int32 player_id) { }
	// RVA: 0x415bf74 VA: 0x7596773f74
	internal static extern Void CRIWARE8FCF2B74(Int32 player_id, TimerType timer_type) { }
	// RVA: 0x415ccd4 VA: 0x7596774cd4
	internal static extern Void CRIWARE77CA0811(Int32 player_id, UInt64 user_count, UInt64 user_unit) { }
	// RVA: 0x415cd68 VA: 0x7596774d68
	internal static extern Void CRIWARE903CEF6A(Int32 player_id, UInt64 timer_unit_n, UInt64 timer_unit_d) { }
	// RVA: 0x415cdfc VA: 0x7596774dfc
	internal static extern Void CRIWARE4973B306(Int32 player_id) { }
	// RVA: 0x415ce78 VA: 0x7596774e78
	internal static extern Void CRIWARE041A49E0(Int32 player_id) { }
	// RVA: 0x415d3a8 VA: 0x75967753a8
	internal static extern Void CRIWAREBDD4960C(Int32 player_id, UInt64 key) { }
	// RVA: 0x415cef4 VA: 0x7596774ef4
	internal static extern IntPtr criWareUnity_GetRenderEventFunc() { }
}
```