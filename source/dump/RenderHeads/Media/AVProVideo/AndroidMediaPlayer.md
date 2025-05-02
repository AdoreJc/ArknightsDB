# AndroidMediaPlayer

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `AndroidJavaObject m_Video`

- `Texture2D m_Texture`

- `Int32 m_TextureHandle`

- `Boolean m_UseFastOesPath`

- `Single m_DurationMs`

- `Int32 m_Width`

- `Int32 m_Height`

- `Int32 m_iPlayerIndex`

- `VideoApi m_API`

- `Boolean m_HeadRotationEnabled`

- `Boolean m_FocusEnabled`

- `IntPtr m_Method_Update`

- `IntPtr m_Method_SetHeadRotation`

- `IntPtr m_Method_GetCurrentTimeMs`

- `IntPtr m_Method_GetSourceVideoFrameRate`

- `IntPtr m_Method_IsPlaying`

- `IntPtr m_Method_IsPaused`

- `IntPtr m_Method_IsFinished`

- `IntPtr m_Method_IsSeeking`

- `IntPtr m_Method_IsBuffering`

- `IntPtr m_Method_IsLooping`

- `IntPtr m_Method_HasVideo`

- `IntPtr m_Method_HasAudio`

- `IntPtr m_Method_SetFocusProps`

- `IntPtr m_Method_SetFocusEnabled`

- `IntPtr m_Method_SetFocusRotation`

- `Int32 _textureQuality`


## Methods

- `IntPtr GetMethod(String, String)`

- `Void SetOptions(Boolean, Boolean)`

- `Void DisplayLoadFailureSuggestion(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class AndroidMediaPlayer : BaseMediaPlayer
{
	protected static AndroidJavaObject s_ActivityContext; // 0x0
	protected static AndroidJavaObject s_Interface; // 0x8
	protected static Boolean s_bInitialised; // 0x10
	private static String s_Version; // 0x18
	private static IntPtr _nativeFunction_RenderEvent; // 0x20
	protected AndroidJavaObject m_Video; // 0x48
	private Texture2D m_Texture; // 0x50
	private Int32 m_TextureHandle; // 0x58
	private Boolean m_UseFastOesPath; // 0x5c
	private Single m_DurationMs; // 0x60
	private Int32 m_Width; // 0x64
	private Int32 m_Height; // 0x68
	protected Int32 m_iPlayerIndex; // 0x6c
	private VideoApi m_API; // 0x70
	private Boolean m_HeadRotationEnabled; // 0x74
	private Boolean m_FocusEnabled; // 0x75
	private IntPtr m_Method_Update; // 0x78
	private IntPtr m_Method_SetHeadRotation; // 0x80
	private IntPtr m_Method_GetCurrentTimeMs; // 0x88
	private IntPtr m_Method_GetSourceVideoFrameRate; // 0x90
	private IntPtr m_Method_IsPlaying; // 0x98
	private IntPtr m_Method_IsPaused; // 0xa0
	private IntPtr m_Method_IsFinished; // 0xa8
	private IntPtr m_Method_IsSeeking; // 0xb0
	private IntPtr m_Method_IsBuffering; // 0xb8
	private IntPtr m_Method_IsLooping; // 0xc0
	private IntPtr m_Method_HasVideo; // 0xc8
	private IntPtr m_Method_HasAudio; // 0xd0
	private IntPtr m_Method_SetFocusProps; // 0xd8
	private IntPtr m_Method_SetFocusEnabled; // 0xe0
	private IntPtr m_Method_SetFocusRotation; // 0xe8
	private jvalue[] m_Value0; // 0xf0
	private jvalue[] m_Value1; // 0xf8
	private jvalue[] m_Value2; // 0x100
	private jvalue[] m_Value4; // 0x108
	private Int32 _textureQuality; // 0x110


	// RVA: 0x668a8d8 VA: 0x7598ca28d8
	public static Boolean InitialisePlatform() { }
	// RVA: 0x668ad38 VA: 0x7598ca2d38
	public static Void DeinitPlatform() { }
	// RVA: 0x668ae94 VA: 0x7598ca2e94
	private static Void IssuePluginEvent(AVPPluginEvent type, Int32 param) { }
	// RVA: 0x668af24 VA: 0x7598ca2f24
	private IntPtr GetMethod(String methodName, String signature) { }
	// RVA: 0x668b088 VA: 0x7598ca3088
	public Void .ctor(Boolean useFastOesPath, Boolean showPosterFrame, VideoApi api, Boolean enable360Audio, Audio360ChannelMode channelMode, Boolean preferSoftware) { }
	// RVA: 0x668b9d8 VA: 0x7598ca39d8
	public Void SetOptions(Boolean useFastOesPath, Boolean showPosterFrame) { }
	// RVA: 0x668bb40 VA: 0x7598ca3b40
	public override Int64 GetEstimatedTotalBandwidthUsed() { }
	// RVA: 0x668bc44 VA: 0x7598ca3c44
	public override String GetVersion() { }
	// RVA: 0x668bc9c VA: 0x7598ca3c9c
	public override Boolean OpenVideoFromFile(String path, Int64 offset, String httpHeaderJson, UInt32 sourceSamplerate, UInt32 sourceChannels, Int32 forceFileFormat) { }
	// RVA: 0x668beec VA: 0x7598ca3eec
	private Void DisplayLoadFailureSuggestion(String path) { }
	// RVA: 0x668bfa0 VA: 0x7598ca3fa0
	public override TimeRange[] GetSeekableTimeRanges() { }
	// RVA: 0x668c0c4 VA: 0x7598ca40c4
	public override Void CloseVideo() { }
	// RVA: 0x668c208 VA: 0x7598ca4208
	public override Void SetLooping(Boolean bLooping) { }
	// RVA: 0x668c308 VA: 0x7598ca4308
	public override Boolean IsLooping() { }
	// RVA: 0x668c438 VA: 0x7598ca4438
	public override Boolean HasVideo() { }
	// RVA: 0x668c568 VA: 0x7598ca4568
	public override Boolean HasAudio() { }
	// RVA: 0x668c698 VA: 0x7598ca4698
	public override Boolean HasMetaData() { }
	// RVA: 0x668c6f0 VA: 0x7598ca46f0
	public override Boolean CanPlay() { }
	// RVA: 0x668c77c VA: 0x7598ca477c
	public override Void Play() { }
	// RVA: 0x668c830 VA: 0x7598ca4830
	public override Void Pause() { }
	// RVA: 0x668c8e4 VA: 0x7598ca48e4
	public override Void Stop() { }
	// RVA: 0x668c998 VA: 0x7598ca4998
	public override Void Seek(Single timeMs) { }
	// RVA: 0x668caf8 VA: 0x7598ca4af8
	public override Void SeekFast(Single timeMs) { }
	// RVA: 0x668cc58 VA: 0x7598ca4c58
	public override Single GetCurrentTimeMs() { }
	// RVA: 0x668cd84 VA: 0x7598ca4d84
	public override Void SetPlaybackRate(Single rate) { }
	// RVA: 0x668ce90 VA: 0x7598ca4e90
	public override Single GetPlaybackRate() { }
	// RVA: 0x668cf5c VA: 0x7598ca4f5c
	public override Void SetAudioHeadRotation(Quaternion q) { }
	// RVA: 0x668d2bc VA: 0x7598ca52bc
	public override Void ResetAudioHeadRotation() { }
	// RVA: 0x668d3c8 VA: 0x7598ca53c8
	public override Void SetAudioFocusEnabled(Boolean enabled) { }
	// RVA: 0x668d554 VA: 0x7598ca5554
	public override Void SetAudioFocusProperties(Single offFocusLevel, Single widthDegrees) { }
	// RVA: 0x668d740 VA: 0x7598ca5740
	public override Void SetAudioFocusRotation(Quaternion q) { }
	// RVA: 0x668da0c VA: 0x7598ca5a0c
	public override Void ResetAudioFocus() { }
	// RVA: 0x668dee8 VA: 0x7598ca5ee8
	public override Single GetDurationMs() { }
	// RVA: 0x668def0 VA: 0x7598ca5ef0
	public override Int32 GetVideoWidth() { }
	// RVA: 0x668def8 VA: 0x7598ca5ef8
	public override Int32 GetVideoHeight() { }
	// RVA: 0x668df00 VA: 0x7598ca5f00
	public override Single GetVideoFrameRate() { }
	// RVA: 0x668e030 VA: 0x7598ca6030
	public override Single GetBufferingProgress() { }
	// RVA: 0x668e104 VA: 0x7598ca6104
	public override Single GetVideoDisplayRate() { }
	// RVA: 0x668e188 VA: 0x7598ca6188
	public override Boolean IsSeeking() { }
	// RVA: 0x668e2b8 VA: 0x7598ca62b8
	public override Boolean IsPlaying() { }
	// RVA: 0x668e3e8 VA: 0x7598ca63e8
	public override Boolean IsPaused() { }
	// RVA: 0x668e518 VA: 0x7598ca6518
	public override Boolean IsFinished() { }
	// RVA: 0x668e648 VA: 0x7598ca6648
	public override Boolean IsBuffering() { }
	// RVA: 0x668e778 VA: 0x7598ca6778
	public override Texture GetTexture(Int32 index) { }
	// RVA: 0x668e7ac VA: 0x7598ca67ac
	public override Int32 GetTextureFrameCount() { }
	// RVA: 0x668e8a4 VA: 0x7598ca68a4
	public override Boolean RequiresVerticalFlip() { }
	// RVA: 0x668e8ac VA: 0x7598ca68ac
	public override Void MuteAudio(Boolean bMuted) { }
	// RVA: 0x668e9ac VA: 0x7598ca69ac
	public override Boolean IsMuted() { }
	// RVA: 0x668ea78 VA: 0x7598ca6a78
	public override Void SetVolume(Single volume) { }
	// RVA: 0x668eb84 VA: 0x7598ca6b84
	public override Single GetVolume() { }
	// RVA: 0x668ec50 VA: 0x7598ca6c50
	public override Void SetBalance(Single balance) { }
	// RVA: 0x668ed5c VA: 0x7598ca6d5c
	public override Single GetBalance() { }
	// RVA: 0x668ee28 VA: 0x7598ca6e28
	public override Int32 GetAudioTrackCount() { }
	// RVA: 0x668eef4 VA: 0x7598ca6ef4
	public override Int32 GetCurrentAudioTrack() { }
	// RVA: 0x668efc0 VA: 0x7598ca6fc0
	public override Void SetAudioTrack(Int32 index) { }
	// RVA: 0x668f0bc VA: 0x7598ca70bc
	public override String GetCurrentAudioTrackId() { }
	// RVA: 0x668f0e8 VA: 0x7598ca70e8
	public override Int32 GetCurrentAudioTrackBitrate() { }
	// RVA: 0x668f0f0 VA: 0x7598ca70f0
	public override Int32 GetVideoTrackCount() { }
	// RVA: 0x668f124 VA: 0x7598ca7124
	public override Int32 GetCurrentVideoTrack() { }
	// RVA: 0x668f12c VA: 0x7598ca712c
	public override Void SetVideoTrack(Int32 index) { }
	// RVA: 0x668f130 VA: 0x7598ca7130
	public override String GetCurrentVideoTrackId() { }
	// RVA: 0x668f170 VA: 0x7598ca7170
	public override Int32 GetCurrentVideoTrackBitrate() { }
	// RVA: 0x668f23c VA: 0x7598ca723c
	public override Boolean WaitForNextFrame(Camera dummyCamera, Int32 previousFrameCount) { }
	// RVA: 0x668f3f0 VA: 0x7598ca73f0
	public override Int64 GetTextureTimeStamp() { }
	// RVA: 0x668f4bc VA: 0x7598ca74bc
	public override Void Render() { }
	// RVA: 0x668fdd4 VA: 0x7598ca7dd4
	protected override Void ApplyTextureProperties(Texture texture) { }
	// RVA: 0x668fe8c VA: 0x7598ca7e8c
	public override Void OnEnable() { }
	// RVA: 0x668ff90 VA: 0x7598ca7f90
	public override Double GetCurrentDateTimeSecondsSince1970() { }
	// RVA: 0x669005c VA: 0x7598ca805c
	public override Void Update() { }
	// RVA: 0x6690304 VA: 0x7598ca8304
	public override Boolean PlayerSupportsLinearColorSpace() { }
	// RVA: 0x669030c VA: 0x7598ca830c
	public override Single[] GetTextureTransform() { }
	// RVA: 0x66903d8 VA: 0x7598ca83d8
	public override Void Dispose() { }
	// RVA: 0x6690658 VA: 0x7598ca8658
	private static Void .cctor() { }
}
```