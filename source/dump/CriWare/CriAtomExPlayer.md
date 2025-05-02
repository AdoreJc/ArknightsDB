# CriAtomExPlayer

**Namespace:** `CriWare`


## Fields

- `CbFunc _onBeatSyncCallback`

- `EventCallback _onSequenceCallback`

- `Boolean hasExistingNativeHandle`

- `IntPtr entryPoolHandle`

- `Int32 _entryPoolCapacity`

- `Int32 max_path`

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`

- `Boolean isAvailable`

- `Int32 entryPoolCapacity`


## Methods

- `IntPtr get_nativeHandle()`

- `Boolean get_isAvailable()`

- `Void add__onBeatSyncCallback(CbFunc)`

- `Void remove__onBeatSyncCallback(CbFunc)`

- `Void add_OnBeatSyncCallback(CbFunc)`

- `Void remove_OnBeatSyncCallback(CbFunc)`

- `Void add__onSequenceCallback(EventCallback)`

- `Void remove__onSequenceCallback(EventCallback)`

- `Void add_OnSequenceCallback(EventCallback)`

- `Void remove_OnSequenceCallback(EventCallback)`

- `Void SetCue(CriAtomExAcb, String)`

- `Void SetCue(CriAtomExAcb, Int32)`

- `Void SetCueIndex(CriAtomExAcb, Int32)`

- `Void SetContentId(CriFsBinder, Int32)`

- `Void SetFile(CriFsBinder, String)`

- `Void SetData(Byte[], Int32)`

- `Void SetData(IntPtr, Int32)`

- `Void SetFormat(Format)`

- `Void SetNumChannels(Int32)`

- `Void SetSamplingRate(Int32)`

- `Void PrepareEntryPool(Int32, Boolean)`

- `Int32 GetNumEntries()`

- `Int32 GetNumConsumedEntries()`

- `Int32 get_entryPoolCapacity()`

- `Boolean EntryFile(CriFsBinder, String, Boolean)`

- `Boolean EntryContentId(CriFsBinder, Int32, Boolean)`

- `Boolean EntryData(Byte[], Int32, Boolean)`

- `Boolean EntryData(IntPtr, Int32, Boolean)`

- `Boolean EntryCue(CriAtomExAcb, String, Boolean)`

- `CriAtomExPlayback Start()`

- `CriAtomExPlayback Prepare()`

- `Boolean StartAsync(IntPtr)`

- `Boolean IsReadyToStartAsync()`

- `Void StopAsync()`

- `CriAtomExPlayback GetLastPlaybackId()`

- `Void Stop(Boolean)`

- `Void Pause()`

- `Void Resume(ResumeMode)`

- `Boolean IsPaused()`

- `Void SetVolume(Single)`

- `Void SetPitch(Single)`

- `Void SetPlaybackRatio(Single)`

- `Void SetPan3dAngle(Single)`

- `Void SetPan3dInteriorDistance(Single)`

- `Void SetPan3dVolume(Single)`

- `Void SetPanType(PanType)`

- `Void SetSendLevel(Int32, Speaker, Single)`

- `Void SetBiquadFilterParameters(BiquadFilterType, Single, Single, Single)`

- `Void SetBandpassFilterParameters(Single, Single)`

- `Void SetBusSendLevel(String, Single)`

- `Boolean GetBusSendLevel(String, out)`

- `Void SetBusSendLevel(Int32, Single)`

- `Void SetBusSendLevelOffset(String, Single)`

- `Boolean GetBusSendLevelOffset(String, out)`

- `Void SetBusSendLevelOffset(Int32, Single)`

- `Void AttachAisac(String)`

- `Void DetachAisac(String)`

- `Void SetAisacControl(String, Single)`

- `Void SetAisac(String, Single)`

- `Void SetAisacControl(UInt32, Single)`

- `Void SetAisac(UInt32, Single)`

- `Boolean GetAttachedAisacInfo(Int32, out)`

- `Void Set3dSource(CriAtomEx3dSource)`

- `Void Set3dListener(CriAtomEx3dListener)`

- `Void SetStartTime(Int64)`

- `Void SetStartTimeMicro(Int64)`

- `Void SetFirstBlockIndex(Int32)`

- `Void SetSelectorLabel(String, String)`

- `Void UnsetSelectorLabel(String)`

- `Void ClearSelectorLabels()`

- `Void SetCategory(Int32)`

- `Void SetCategory(String)`

- `Void UnsetCategory()`

- `Void SetCuePriority(Int32)`

- `Void SetVoicePriority(Int32)`

- `Void SetVoiceControlMethod(VoiceControlMethod)`

- `Void SetPreDelayTime(Single)`

- `Void SetEnvelopeAttackTime(Single)`

- `Void SetEnvelopeHoldTime(Single)`

- `Void SetEnvelopeDecayTime(Single)`

- `Void SetEnvelopeReleaseTime(Single)`

- `Void SetEnvelopeSustainLevel(Single)`

- `Void AttachFader()`

- `Void DetachFader()`

- `Void SetFadeOutTime(Int32)`

- `Void SetFadeInTime(Int32)`

- `Void SetFadeInStartOffset(Int32)`

- `Void SetFadeOutEndDelay(Int32)`

- `Boolean IsFading()`

- `Void ResetFaderParameters()`

- `Void SetGroupNumber(Int32)`

- `Void Update(CriAtomExPlayback)`

- `Void UpdateAll()`

- `Void ResetParameters()`

- `Int64 GetTime()`

- `Status GetStatus()`

- `Single GetParameterFloat32(Parameter)`

- `UInt32 GetParameterUint32(Parameter)`

- `Int32 GetParameterSint32(Parameter)`

- `Void SetSoundRendererType(SoundRendererType)`

- `Void SetRandomSeed(UInt32)`

- `Void Loop(Boolean)`

- `Void SetAsrRackId(Int32)`

- `Void SetVoicePoolIdentifier(UInt32)`

- `Void SetDspTimeStretchRatio(Single)`

- `Void SetDspPitchShifterPitch(Single)`

- `Void SetDspParameter(Int32, Single)`

- `Void SetSequencePrepareTime(UInt32)`

- `Void AttachTween(CriAtomExTween)`

- `Void DetachTween(CriAtomExTween)`

- `Void DetachTweenAll()`

- `Void SetEnvelopeAttackCurve(CurveType, Single)`

- `Void SetEnvelopeDecayCurve(CurveType, Single)`

- `Void SetEnvelopeReleaseCurve(CurveType, Single)`

- `Void AddOutputPort(CriAtomExOutputPort)`

- `Void RemoveOutputPort(CriAtomExOutputPort)`

- `Void ClearOutputPorts()`

- `Void AddPreferredOutputPort(CriAtomExOutputPort)`

- `Void RemovePreferredOutputPort(CriAtomExOutputPort)`

- `Void RemovePreferredOutputPort(String)`

- `Void ClearPreferredOutputPorts()`

- `Void SetScheduleTime(Int64)`

- `Void Stop()`

- `Void StopWithoutReleaseTime()`

- `Void Pause(Boolean)`

- `Void OnBeatSyncCallbackChainInternal(ref)`

- `Void OnSequenceCallbackChainInternal(ref)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExPlayer : CriDisposable
{
	private CbFunc _onBeatSyncCallback; // 0x20
	private EventCallback _onSequenceCallback; // 0x28
	private Boolean hasExistingNativeHandle; // 0x30
	private IntPtr entryPoolHandle; // 0x38
	private Int32 _entryPoolCapacity; // 0x40
	private Int32 max_path; // 0x44
	public static readonly UInt32 MaxOutputPorts; // 0x0
	private IntPtr handle; // 0x48

	public IntPtr nativeHandle { get; }
	public Boolean isAvailable { get; }
	public Int32 entryPoolCapacity { get; }

	// RVA: 0x4130bd4 VA: 0x7596748bd4
	public IntPtr get_nativeHandle() { }
	// RVA: 0x412e850 VA: 0x7596746850
	public Boolean get_isAvailable() { }
	// RVA: 0x4130bdc VA: 0x7596748bdc
	private Void add__onBeatSyncCallback(CbFunc value) { }
	// RVA: 0x4130c78 VA: 0x7596748c78
	private Void remove__onBeatSyncCallback(CbFunc value) { }
	// RVA: 0x4130d14 VA: 0x7596748d14
	public Void add_OnBeatSyncCallback(CbFunc value) { }
	// RVA: 0x4130dac VA: 0x7596748dac
	public Void remove_OnBeatSyncCallback(CbFunc value) { }
	// RVA: 0x4130e50 VA: 0x7596748e50
	private Void add__onSequenceCallback(EventCallback value) { }
	// RVA: 0x4130eec VA: 0x7596748eec
	private Void remove__onSequenceCallback(EventCallback value) { }
	// RVA: 0x4130f88 VA: 0x7596748f88
	public Void add_OnSequenceCallback(EventCallback value) { }
	// RVA: 0x4131020 VA: 0x7596749020
	public Void remove_OnSequenceCallback(EventCallback value) { }
	// RVA: 0x41310c4 VA: 0x75967490c4
	public Void .ctor() { }
	// RVA: 0x4131304 VA: 0x7596749304
	public Void .ctor(Int32 maxPath, Int32 maxPathStrings) { }
	// RVA: 0x4131370 VA: 0x7596749370
	public Void .ctor(Boolean enableAudioSyncedTimer) { }
	// RVA: 0x41313d8 VA: 0x75967493d8
	public Void .ctor(Int32 maxPath, Int32 maxPathStrings, Boolean enableAudioSyncedTimer) { }
	// RVA: 0x4131450 VA: 0x7596749450
	public Void .ctor(IntPtr existingNativeHandle) { }
	// RVA: 0x4131120 VA: 0x7596749120
	public Void .ctor(Int32 maxPath, Int32 maxPathStrings, Boolean enableAudioSyncedTimer, IntPtr existingNativeHandle) { }
	// RVA: 0x4131550 VA: 0x7596749550
	public override Void Dispose() { }
	// RVA: 0x4131878 VA: 0x7596749878
	public Void SetCue(CriAtomExAcb acb, String name) { }
	// RVA: 0x41319bc VA: 0x75967499bc
	public Void SetCue(CriAtomExAcb acb, Int32 id) { }
	// RVA: 0x4131aec VA: 0x7596749aec
	public Void SetCueIndex(CriAtomExAcb acb, Int32 index) { }
	// RVA: 0x4131c1c VA: 0x7596749c1c
	public Void SetContentId(CriFsBinder binder, Int32 contentId) { }
	// RVA: 0x4131d4c VA: 0x7596749d4c
	public Void SetFile(CriFsBinder binder, String path) { }
	// RVA: 0x4131e90 VA: 0x7596749e90
	public Void SetData(Byte[] buffer, Int32 size) { }
	// RVA: 0x4131f9c VA: 0x7596749f9c
	public Void SetData(IntPtr buffer, Int32 size) { }
	// RVA: 0x41320a0 VA: 0x759674a0a0
	public Void SetFormat(Format format) { }
	// RVA: 0x413218c VA: 0x759674a18c
	public Void SetNumChannels(Int32 numChannels) { }
	// RVA: 0x4132278 VA: 0x759674a278
	public Void SetSamplingRate(Int32 samplingRate) { }
	// RVA: 0x4132364 VA: 0x759674a364
	public Void PrepareEntryPool(Int32 capacity, Boolean stopOnEmpty) { }
	// RVA: 0x413250c VA: 0x759674a50c
	public Int32 GetNumEntries() { }
	// RVA: 0x4132620 VA: 0x759674a620
	public Int32 GetNumConsumedEntries() { }
	// RVA: 0x4132734 VA: 0x759674a734
	public Int32 get_entryPoolCapacity() { }
	// RVA: 0x413273c VA: 0x759674a73c
	public Boolean EntryFile(CriFsBinder binder, String path, Boolean repeat) { }
	// RVA: 0x41328f0 VA: 0x759674a8f0
	public Boolean EntryContentId(CriFsBinder binder, Int32 contentId, Boolean repeat) { }
	// RVA: 0x4132a74 VA: 0x759674aa74
	public Boolean EntryData(Byte[] buffer, Int32 size, Boolean repeat) { }
	// RVA: 0x4132be8 VA: 0x759674abe8
	public Boolean EntryData(IntPtr buffer, Int32 size, Boolean repeat) { }
	// RVA: 0x4132d54 VA: 0x759674ad54
	public Boolean EntryCue(CriAtomExAcb acb, String name, Boolean repeat) { }
	// RVA: 0x4132ef0 VA: 0x759674aef0
	public CriAtomExPlayback Start() { }
	// RVA: 0x4133094 VA: 0x759674b094
	public CriAtomExPlayback Prepare() { }
	// RVA: 0x4133170 VA: 0x759674b170
	public Boolean StartAsync(IntPtr playbackId) { }
	// RVA: 0x4133268 VA: 0x759674b268
	public Boolean IsReadyToStartAsync() { }
	// RVA: 0x4133348 VA: 0x759674b348
	public Void StopAsync() { }
	// RVA: 0x413341c VA: 0x759674b41c
	public CriAtomExPlayback GetLastPlaybackId() { }
	// RVA: 0x41334f8 VA: 0x759674b4f8
	public Void Stop(Boolean ignoresReleaseTime) { }
	// RVA: 0x4133744 VA: 0x759674b744
	public Void Pause() { }
	// RVA: 0x4133824 VA: 0x759674b824
	public Void Resume(ResumeMode mode) { }
	// RVA: 0x4133910 VA: 0x759674b910
	public Boolean IsPaused() { }
	// RVA: 0x41339ec VA: 0x759674b9ec
	public Void SetVolume(Single volume) { }
	// RVA: 0x4133ae0 VA: 0x759674bae0
	public Void SetPitch(Single pitch) { }
	// RVA: 0x4133bd4 VA: 0x759674bbd4
	public Void SetPlaybackRatio(Single ratio) { }
	// RVA: 0x4133cc8 VA: 0x759674bcc8
	public Void SetPan3dAngle(Single angle) { }
	// RVA: 0x4133dbc VA: 0x759674bdbc
	public Void SetPan3dInteriorDistance(Single distance) { }
	// RVA: 0x4133eb0 VA: 0x759674beb0
	public Void SetPan3dVolume(Single volume) { }
	// RVA: 0x4133fa4 VA: 0x759674bfa4
	public Void SetPanType(PanType panType) { }
	// RVA: 0x4134090 VA: 0x759674c090
	public Void SetSendLevel(Int32 channel, Speaker id, Single level) { }
	// RVA: 0x41341b4 VA: 0x759674c1b4
	public Void SetBiquadFilterParameters(BiquadFilterType type, Single frequency, Single gain, Single q) { }
	// RVA: 0x41342f0 VA: 0x759674c2f0
	public Void SetBandpassFilterParameters(Single cofLow, Single cofHigh) { }
	// RVA: 0x41343f4 VA: 0x759674c3f4
	public Void SetBusSendLevel(String busName, Single level) { }
	// RVA: 0x4134514 VA: 0x759674c514
	public Boolean GetBusSendLevel(String busName, out Single level) { }
	// RVA: 0x4134638 VA: 0x759674c638
	public Void SetBusSendLevel(Int32 busId, Single level) { }
	// RVA: 0x4134744 VA: 0x759674c744
	public Void SetBusSendLevelOffset(String busName, Single levelOffset) { }
	// RVA: 0x4134864 VA: 0x759674c864
	public Boolean GetBusSendLevelOffset(String busName, out Single level) { }
	// RVA: 0x4134988 VA: 0x759674c988
	public Void SetBusSendLevelOffset(Int32 busId, Single levelOffset) { }
	// RVA: 0x4134a94 VA: 0x759674ca94
	public Void AttachAisac(String globalAisacName) { }
	// RVA: 0x4134b94 VA: 0x759674cb94
	public Void DetachAisac(String globalAisacName) { }
	// RVA: 0x4134c94 VA: 0x759674cc94
	public Void SetAisacControl(String controlName, Single value) { }
	// RVA: 0x4134db4 VA: 0x759674cdb4
	public Void SetAisac(String controlName, Single value) { }
	// RVA: 0x4134db8 VA: 0x759674cdb8
	public Void SetAisacControl(UInt32 controlId, Single value) { }
	// RVA: 0x4134ec4 VA: 0x759674cec4
	public Void SetAisac(UInt32 controlId, Single value) { }
	// RVA: 0x4134f3c VA: 0x759674cf3c
	public Boolean GetAttachedAisacInfo(Int32 aisacAttachedIndex, out AisacInfo aisacInfo) { }
	// RVA: 0x4135244 VA: 0x759674d244
	public Void Set3dSource(CriAtomEx3dSource source) { }
	// RVA: 0x4135354 VA: 0x759674d354
	public Void Set3dListener(CriAtomEx3dListener listener) { }
	// RVA: 0x4135464 VA: 0x759674d464
	public Void SetStartTime(Int64 startTimeMs) { }
	// RVA: 0x4135550 VA: 0x759674d550
	public Void SetStartTimeMicro(Int64 startTimeUs) { }
	// RVA: 0x413563c VA: 0x759674d63c
	public Void SetFirstBlockIndex(Int32 index) { }
	// RVA: 0x4135728 VA: 0x759674d728
	public Void SetSelectorLabel(String selector, String label) { }
	// RVA: 0x4135854 VA: 0x759674d854
	public Void UnsetSelectorLabel(String selector) { }
	// RVA: 0x4135954 VA: 0x759674d954
	public Void ClearSelectorLabels() { }
	// RVA: 0x4135a28 VA: 0x759674da28
	public Void SetCategory(Int32 categoryId) { }
	// RVA: 0x4135b14 VA: 0x759674db14
	public Void SetCategory(String categoryName) { }
	// RVA: 0x4135c14 VA: 0x759674dc14
	public Void UnsetCategory() { }
	// RVA: 0x4135ce8 VA: 0x759674dce8
	public Void SetCuePriority(Int32 priority) { }
	// RVA: 0x4135dd4 VA: 0x759674ddd4
	public Void SetVoicePriority(Int32 priority) { }
	// RVA: 0x4135ec0 VA: 0x759674dec0
	public Void SetVoiceControlMethod(VoiceControlMethod method) { }
	// RVA: 0x4135fac VA: 0x759674dfac
	public Void SetPreDelayTime(Single time) { }
	// RVA: 0x41360a0 VA: 0x759674e0a0
	public Void SetEnvelopeAttackTime(Single time) { }
	// RVA: 0x4136194 VA: 0x759674e194
	public Void SetEnvelopeHoldTime(Single time) { }
	// RVA: 0x4136288 VA: 0x759674e288
	public Void SetEnvelopeDecayTime(Single time) { }
	// RVA: 0x413637c VA: 0x759674e37c
	public Void SetEnvelopeReleaseTime(Single time) { }
	// RVA: 0x4136470 VA: 0x759674e470
	public Void SetEnvelopeSustainLevel(Single level) { }
	// RVA: 0x4136564 VA: 0x759674e564
	public Void AttachFader() { }
	// RVA: 0x413668c VA: 0x759674e68c
	public Void DetachFader() { }
	// RVA: 0x4136760 VA: 0x759674e760
	public Void SetFadeOutTime(Int32 ms) { }
	// RVA: 0x413684c VA: 0x759674e84c
	public Void SetFadeInTime(Int32 ms) { }
	// RVA: 0x4136938 VA: 0x759674e938
	public Void SetFadeInStartOffset(Int32 ms) { }
	// RVA: 0x4136a24 VA: 0x759674ea24
	public Void SetFadeOutEndDelay(Int32 ms) { }
	// RVA: 0x4136b10 VA: 0x759674eb10
	public Boolean IsFading() { }
	// RVA: 0x4136bec VA: 0x759674ebec
	public Void ResetFaderParameters() { }
	// RVA: 0x4136cc0 VA: 0x759674ecc0
	public Void SetGroupNumber(Int32 group_no) { }
	// RVA: 0x4136dac VA: 0x759674edac
	public Void Update(CriAtomExPlayback playback) { }
	// RVA: 0x4136e98 VA: 0x759674ee98
	public Void UpdateAll() { }
	// RVA: 0x4136f6c VA: 0x759674ef6c
	public Void ResetParameters() { }
	// RVA: 0x4137040 VA: 0x759674f040
	public Int64 GetTime() { }
	// RVA: 0x412ec7c VA: 0x7596746c7c
	public Status GetStatus() { }
	// RVA: 0x4137190 VA: 0x759674f190
	public Single GetParameterFloat32(Parameter id) { }
	// RVA: 0x413727c VA: 0x759674f27c
	public UInt32 GetParameterUint32(Parameter id) { }
	// RVA: 0x4137368 VA: 0x759674f368
	public Int32 GetParameterSint32(Parameter id) { }
	// RVA: 0x4137454 VA: 0x759674f454
	public Void SetSoundRendererType(SoundRendererType type) { }
	// RVA: 0x4137540 VA: 0x759674f540
	public Void SetRandomSeed(UInt32 seed) { }
	// RVA: 0x413762c VA: 0x759674f62c
	public Void Loop(Boolean sw) { }
	// RVA: 0x4137874 VA: 0x759674f874
	public Void SetAsrRackId(Int32 asr_rack_id) { }
	// RVA: 0x4137960 VA: 0x759674f960
	public Void SetVoicePoolIdentifier(UInt32 identifier) { }
	// RVA: 0x4137a4c VA: 0x759674fa4c
	public Void SetDspTimeStretchRatio(Single ratio) { }
	// RVA: 0x4137acc VA: 0x759674facc
	public Void SetDspPitchShifterPitch(Single pitch) { }
	// RVA: 0x4137a54 VA: 0x759674fa54
	public Void SetDspParameter(Int32 id, Single value) { }
	// RVA: 0x4137b7c VA: 0x759674fb7c
	public Void SetSequencePrepareTime(UInt32 ms) { }
	// RVA: 0x4137c68 VA: 0x759674fc68
	public Void AttachTween(CriAtomExTween tween) { }
	// RVA: 0x4137d58 VA: 0x759674fd58
	public Void DetachTween(CriAtomExTween tween) { }
	// RVA: 0x4137e48 VA: 0x759674fe48
	public Void DetachTweenAll() { }
	// RVA: 0x4137f1c VA: 0x759674ff1c
	public Void SetEnvelopeAttackCurve(CurveType curveType, Single strength) { }
	// RVA: 0x4138028 VA: 0x7596750028
	public Void SetEnvelopeDecayCurve(CurveType curveType, Single strength) { }
	// RVA: 0x4138134 VA: 0x7596750134
	public Void SetEnvelopeReleaseCurve(CurveType curveType, Single strength) { }
	// RVA: 0x4138240 VA: 0x7596750240
	public Void AddOutputPort(CriAtomExOutputPort outputPort) { }
	// RVA: 0x4138330 VA: 0x7596750330
	public Void RemoveOutputPort(CriAtomExOutputPort outputPort) { }
	// RVA: 0x4138420 VA: 0x7596750420
	public Void ClearOutputPorts() { }
	// RVA: 0x41384f4 VA: 0x75967504f4
	public Void AddPreferredOutputPort(CriAtomExOutputPort outputPort) { }
	// RVA: 0x41385e4 VA: 0x75967505e4
	public Void RemovePreferredOutputPort(CriAtomExOutputPort outputPort) { }
	// RVA: 0x41386d4 VA: 0x75967506d4
	public Void RemovePreferredOutputPort(String name) { }
	// RVA: 0x41387d4 VA: 0x75967507d4
	public Void ClearPreferredOutputPorts() { }
	// RVA: 0x41388a8 VA: 0x75967508a8
	public Void SetScheduleTime(Int64 scheduleTime) { }
	// RVA: 0x4138994 VA: 0x7596750994
	public Void Stop() { }
	// RVA: 0x4131708 VA: 0x7596749708
	public Void StopWithoutReleaseTime() { }
	// RVA: 0x4138a0c VA: 0x7596750a0c
	public Void Pause(Boolean sw) { }
	// RVA: 0x4138a74 VA: 0x7596750a74
	protected override Void Finalize() { }
	// RVA: 0x4138b10 VA: 0x7596750b10
	private Void OnBeatSyncCallbackChainInternal(ref Info info) { }
	// RVA: 0x4138b68 VA: 0x7596750b68
	private Void OnSequenceCallbackChainInternal(ref CriAtomExSequenceEventInfo info) { }
	// RVA: 0x413147c VA: 0x759674947c
	private static extern IntPtr criAtomExPlayer_Create(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x41317fc VA: 0x75967497fc
	private static extern Void criAtomExPlayer_Destroy(IntPtr player) { }
	// RVA: 0x4131a58 VA: 0x7596749a58
	private static extern Void criAtomExPlayer_SetCueId(IntPtr player, IntPtr acb_hn, Int32 id) { }
	// RVA: 0x4131914 VA: 0x7596749914
	private static extern Void criAtomExPlayer_SetCueName(IntPtr player, IntPtr acb_hn, String cue_name) { }
	// RVA: 0x4131b88 VA: 0x7596749b88
	private static extern Void criAtomExPlayer_SetCueIndex(IntPtr player, IntPtr acb_hn, Int32 index) { }
	// RVA: 0x4131de8 VA: 0x7596749de8
	private static extern Void criAtomExPlayer_SetFile(IntPtr player, IntPtr binder, String path) { }
	// RVA: 0x4131f00 VA: 0x7596749f00
	private static extern Void criAtomExPlayer_SetData(IntPtr player, Byte[] buffer, Int32 size) { }
	// RVA: 0x413200c VA: 0x759674a00c
	private static extern Void criAtomExPlayer_SetData(IntPtr player, IntPtr buffer, Int32 size) { }
	// RVA: 0x4131cb8 VA: 0x7596749cb8
	private static extern Void criAtomExPlayer_SetContentId(IntPtr player, IntPtr binder, Int32 id) { }
	// RVA: 0x41379c8 VA: 0x759674f9c8
	private static extern Void criAtomExPlayer_SetVoicePoolIdentifier(IntPtr player, UInt32 identifier) { }
	// RVA: 0x4133018 VA: 0x759674b018
	private static extern UInt32 criAtomExPlayer_Start(IntPtr player) { }
	// RVA: 0x41330f4 VA: 0x759674b0f4
	private static extern UInt32 criAtomExPlayer_Prepare(IntPtr player) { }
	// RVA: 0x41331e4 VA: 0x759674b1e4
	private static extern Int32 criAtomExPlayer_StartAsync(IntPtr player, IntPtr playback_id) { }
	// RVA: 0x41333a0 VA: 0x759674b3a0
	private static extern Void criAtomExPlayer_StopAsync(IntPtr player) { }
	// RVA: 0x41332cc VA: 0x759674b2cc
	private static extern Int32 criAtomExPlayer_IsReadyToStartAsync(IntPtr player) { }
	// RVA: 0x413347c VA: 0x759674b47c
	private static extern UInt32 criAtomExPlayer_GetLastPlaybackId(IntPtr player) { }
	// RVA: 0x41335d0 VA: 0x759674b5d0
	private static extern Void criAtomExPlayer_Stop(IntPtr player) { }
	// RVA: 0x413364c VA: 0x759674b64c
	private static extern Void criAtomExPlayer_StopWithoutReleaseTime(IntPtr player) { }
	// RVA: 0x41337a0 VA: 0x759674b7a0
	private static extern Void criAtomExPlayer_Pause(IntPtr player, Boolean sw) { }
	// RVA: 0x413388c VA: 0x759674b88c
	private static extern Void criAtomExPlayer_Resume(IntPtr player, ResumeMode mode) { }
	// RVA: 0x4133968 VA: 0x759674b968
	private static extern Boolean criAtomExPlayer_IsPaused(IntPtr player) { }
	// RVA: 0x4137114 VA: 0x759674f114
	private static extern Status criAtomExPlayer_GetStatus(IntPtr player) { }
	// RVA: 0x4137098 VA: 0x759674f098
	private static extern Int64 criAtomExPlayer_GetTime(IntPtr player) { }
	// RVA: 0x4132108 VA: 0x759674a108
	private static extern Void criAtomExPlayer_SetFormat(IntPtr player, Format format) { }
	// RVA: 0x41321f4 VA: 0x759674a1f4
	private static extern Void criAtomExPlayer_SetNumChannels(IntPtr player, Int32 num_channels) { }
	// RVA: 0x41322e0 VA: 0x759674a2e0
	private static extern Void criAtomExPlayer_SetSamplingRate(IntPtr player, Int32 sampling_rate) { }
	// RVA: 0x4132470 VA: 0x759674a470
	private static extern IntPtr CRIWARECBB23C9C(IntPtr player, Int32 capacity, Int32 max_path, Boolean stopOnEmpty) { }
	// RVA: 0x4131780 VA: 0x7596749780
	private static extern Void CRIWARE2CE3FE0F(IntPtr pool) { }
	// RVA: 0x41325a4 VA: 0x759674a5a4
	private static extern Int32 CRIWARE59FD08E5(IntPtr pool) { }
	// RVA: 0x41326b8 VA: 0x759674a6b8
	private static extern Int32 CRIWARE5C6495C3(IntPtr pool) { }
	// RVA: 0x4132f9c VA: 0x759674af9c
	private static extern Void CRIWARE6E273C27(IntPtr pool) { }
	// RVA: 0x4132824 VA: 0x759674a824
	private static extern Boolean CRIWARE3B001F33(IntPtr pool, IntPtr binder, String path, Boolean repeat, Int32 max_path) { }
	// RVA: 0x41329d0 VA: 0x759674a9d0
	private static extern Boolean CRIWARE610C9213(IntPtr pool, IntPtr binder, Int32 id, Boolean repeat) { }
	// RVA: 0x4132b3c VA: 0x759674ab3c
	private static extern Boolean CRIWARE522C0BBB(IntPtr pool, Byte[] buffer, Int32 size, Boolean repeat) { }
	// RVA: 0x4132cb0 VA: 0x759674acb0
	private static extern Boolean CRIWARE522C0BBB(IntPtr pool, IntPtr buffer, Int32 size, Boolean repeat) { }
	// RVA: 0x4132e34 VA: 0x759674ae34
	private static extern Boolean CRIWARE623F7A16(IntPtr pool, IntPtr acbhn, String name, Boolean repeat) { }
	// RVA: 0x41336c8 VA: 0x759674b6c8
	private static extern Void CRIWARE06E6D8B0(IntPtr pool) { }
	// RVA: 0x41354cc VA: 0x759674d4cc
	private static extern Void criAtomExPlayer_SetStartTime(IntPtr player, Int64 start_time_ms) { }
	// RVA: 0x41355b8 VA: 0x759674d5b8
	private static extern Void criAtomExPlayer_SetStartTimeMicro(IntPtr player, Int64 startTimeUs) { }
	// RVA: 0x4137be4 VA: 0x759674fbe4
	private static extern Void criAtomExPlayer_SetSequencePrepareTime(IntPtr player, UInt32 seq_prep_time_ms) { }
	// RVA: 0x41376f0 VA: 0x759674f6f0
	private static extern Void criAtomExPlayer_LimitLoopCount(IntPtr player, Int32 count) { }
	// RVA: 0x4136e14 VA: 0x759674ee14
	private static extern Void criAtomExPlayer_Update(IntPtr player, UInt32 id) { }
	// RVA: 0x4136ef0 VA: 0x759674eef0
	private static extern Void criAtomExPlayer_UpdateAll(IntPtr player) { }
	// RVA: 0x4136fc4 VA: 0x759674efc4
	private static extern Void criAtomExPlayer_ResetParameters(IntPtr player) { }
	// RVA: 0x41371f8 VA: 0x759674f1f8
	private static extern Single criAtomExPlayer_GetParameterFloat32(IntPtr player, Parameter id) { }
	// RVA: 0x41372e4 VA: 0x759674f2e4
	private static extern UInt32 criAtomExPlayer_GetParameterUint32(IntPtr player, Parameter id) { }
	// RVA: 0x41373d0 VA: 0x759674f3d0
	private static extern Int32 criAtomExPlayer_GetParameterSint32(IntPtr player, Parameter id) { }
	// RVA: 0x4137774 VA: 0x759674f774
	private static extern IntPtr criAtomExPlayer_GetPlayerParameter(IntPtr player) { }
	// RVA: 0x41377f0 VA: 0x759674f7f0
	private static extern Void criAtomExPlayerParameter_RemoveParameter(IntPtr player_parameter, UInt32 id) { }
	// RVA: 0x4133a54 VA: 0x759674ba54
	private static extern Void criAtomExPlayer_SetVolume(IntPtr player, Single volume) { }
	// RVA: 0x4133b48 VA: 0x759674bb48
	private static extern Void criAtomExPlayer_SetPitch(IntPtr player, Single pitch) { }
	// RVA: 0x4133c3c VA: 0x759674bc3c
	private static extern Void criAtomExPlayer_SetPlaybackRatio(IntPtr player, Single playback_ratio) { }
	// RVA: 0x4133d30 VA: 0x759674bd30
	private static extern Void criAtomExPlayer_SetPan3dAngle(IntPtr player, Single pan3d_angle) { }
	// RVA: 0x4133e24 VA: 0x759674be24
	private static extern Void criAtomExPlayer_SetPan3dInteriorDistance(IntPtr player, Single pan3d_interior_distance) { }
	// RVA: 0x4133f18 VA: 0x759674bf18
	private static extern Void criAtomExPlayer_SetPan3dVolume(IntPtr player, Single pan3d_volume) { }
	// RVA: 0x413400c VA: 0x759674c00c
	private static extern Void criAtomExPlayer_SetPanType(IntPtr player, PanType panType) { }
	// RVA: 0x4134110 VA: 0x759674c110
	private static extern Void criAtomExPlayer_SetSendLevel(IntPtr player, Int32 channel, Speaker id, Single level) { }
	// RVA: 0x41346b0 VA: 0x759674c6b0
	private static extern Void criAtomExPlayer_SetBusSendLevel(IntPtr player, Int32 bus_id, Single level) { }
	// RVA: 0x413446c VA: 0x759674c46c
	private static extern Void criAtomExPlayer_SetBusSendLevelByName(IntPtr player, String bus_name, Single level) { }
	// RVA: 0x4134584 VA: 0x759674c584
	private static extern Boolean criAtomExPlayer_GetBusSendLevelByName(IntPtr player, String bus_name, out Single level) { }
	// RVA: 0x4134a00 VA: 0x759674ca00
	private static extern Void criAtomExPlayer_SetBusSendLevelOffset(IntPtr player, Int32 bus_id, Single level_offset) { }
	// RVA: 0x41347bc VA: 0x759674c7bc
	private static extern Void criAtomExPlayer_SetBusSendLevelOffsetByName(IntPtr player, String bus_name, Single level_offset) { }
	// RVA: 0x41348d4 VA: 0x759674c8d4
	private static extern Boolean criAtomExPlayer_GetBusSendLevelOffsetByName(IntPtr player, String bus_name, out Single level_offset) { }
	// RVA: 0x4134360 VA: 0x759674c360
	private static extern Void criAtomExPlayer_SetBandpassFilterParameters(IntPtr player, Single cof_low, Single cof_high) { }
	// RVA: 0x4134244 VA: 0x759674c244
	private static extern Void criAtomExPlayer_SetBiquadFilterParameters(IntPtr player, BiquadFilterType type, Single frequency, Single gain, Single q) { }
	// RVA: 0x4135e3c VA: 0x759674de3c
	private static extern Void criAtomExPlayer_SetVoicePriority(IntPtr player, Int32 priority) { }
	// RVA: 0x4135f28 VA: 0x759674df28
	private static extern Void criAtomExPlayer_SetVoiceControlMethod(IntPtr player, VoiceControlMethod method) { }
	// RVA: 0x4134e30 VA: 0x759674ce30
	private static extern Void criAtomExPlayer_SetAisacControlById(IntPtr player, UInt16 control_id, Single control_value) { }
	// RVA: 0x4134d0c VA: 0x759674cd0c
	private static extern Void criAtomExPlayer_SetAisacControlByName(IntPtr player, String control_name, Single control_value) { }
	// RVA: 0x41352d0 VA: 0x759674d2d0
	private static extern Void criAtomExPlayer_Set3dSourceHn(IntPtr player, IntPtr source) { }
	// RVA: 0x41353e0 VA: 0x759674d3e0
	private static extern Void criAtomExPlayer_Set3dListenerHn(IntPtr player, IntPtr listener) { }
	// RVA: 0x4135a90 VA: 0x759674da90
	private static extern Void criAtomExPlayer_SetCategoryById(IntPtr player, UInt32 category_id) { }
	// RVA: 0x4135b7c VA: 0x759674db7c
	private static extern Void criAtomExPlayer_SetCategoryByName(IntPtr player, String category_name) { }
	// RVA: 0x4135c6c VA: 0x759674dc6c
	private static extern Void criAtomExPlayer_UnsetCategory(IntPtr player) { }
	// RVA: 0x4135d50 VA: 0x759674dd50
	private static extern Void criAtomExPlayer_SetCuePriority(IntPtr player, Int32 cue_priority) { }
	// RVA: 0x4136014 VA: 0x759674e014
	private static extern Void criAtomExPlayer_SetPreDelayTime(IntPtr player, Single predelay_time_ms) { }
	// RVA: 0x4136108 VA: 0x759674e108
	private static extern Void criAtomExPlayer_SetEnvelopeAttackTime(IntPtr player, Single attack_time_ms) { }
	// RVA: 0x41361fc VA: 0x759674e1fc
	private static extern Void criAtomExPlayer_SetEnvelopeHoldTime(IntPtr player, Single hold_time_ms) { }
	// RVA: 0x41362f0 VA: 0x759674e2f0
	private static extern Void criAtomExPlayer_SetEnvelopeDecayTime(IntPtr player, Single decay_time_ms) { }
	// RVA: 0x41363e4 VA: 0x759674e3e4
	private static extern Void criAtomExPlayer_SetEnvelopeReleaseTime(IntPtr player, Single release_time_ms) { }
	// RVA: 0x41364d8 VA: 0x759674e4d8
	private static extern Void criAtomExPlayer_SetEnvelopeSustainLevel(IntPtr player, Single susutain_level) { }
	// RVA: 0x41365f0 VA: 0x759674e5f0
	private static extern Void criAtomExPlayer_AttachFader(IntPtr player, IntPtr config, IntPtr work, Int32 work_size) { }
	// RVA: 0x4134afc VA: 0x759674cafc
	private static extern Void criAtomExPlayer_AttachAisac(IntPtr player, String globalAisacName) { }
	// RVA: 0x4134bfc VA: 0x759674cbfc
	private static extern Void criAtomExPlayer_DetachAisac(IntPtr player, String globalAisacName) { }
	// RVA: 0x41366e4 VA: 0x759674e6e4
	private static extern Void criAtomExPlayer_DetachFader(IntPtr player) { }
	// RVA: 0x41367c8 VA: 0x759674e7c8
	private static extern Void criAtomExPlayer_SetFadeOutTime(IntPtr player, Int32 ms) { }
	// RVA: 0x41368b4 VA: 0x759674e8b4
	private static extern Void criAtomExPlayer_SetFadeInTime(IntPtr player, Int32 ms) { }
	// RVA: 0x41369a0 VA: 0x759674e9a0
	private static extern Void criAtomExPlayer_SetFadeInStartOffset(IntPtr player, Int32 ms) { }
	// RVA: 0x4136a8c VA: 0x759674ea8c
	private static extern Void criAtomExPlayer_SetFadeOutEndDelay(IntPtr player, Int32 ms) { }
	// RVA: 0x4136b68 VA: 0x759674eb68
	private static extern Boolean criAtomExPlayer_IsFading(IntPtr player) { }
	// RVA: 0x4136c44 VA: 0x759674ec44
	private static extern Void criAtomExPlayer_ResetFaderParameters(IntPtr player) { }
	// RVA: 0x4136d28 VA: 0x759674ed28
	private static extern Void criAtomExPlayer_SetGroupNumber(IntPtr player, Int32 group_no) { }
	// RVA: 0x41351a8 VA: 0x759674d1a8
	private static extern Boolean criAtomExPlayer_GetAttachedAisacInfo(IntPtr player, Int32 aisac_attached_index, IntPtr aisac_info) { }
	// RVA: 0x41356a4 VA: 0x759674d6a4
	private static extern Void criAtomExPlayer_SetFirstBlockIndex(IntPtr player, Int32 index) { }
	// RVA: 0x4135798 VA: 0x759674d798
	private static extern Void criAtomExPlayer_SetSelectorLabel(IntPtr player, String selector, String label) { }
	// RVA: 0x41358bc VA: 0x759674d8bc
	private static extern Void criAtomExPlayer_UnsetSelectorLabel(IntPtr player, String selector) { }
	// RVA: 0x41359ac VA: 0x759674d9ac
	private static extern Void criAtomExPlayer_ClearSelectorLabels(IntPtr player) { }
	// RVA: 0x41374bc VA: 0x759674f4bc
	private static extern Void criAtomExPlayer_SetSoundRendererType(IntPtr player, SoundRendererType type) { }
	// RVA: 0x41375a8 VA: 0x759674f5a8
	private static extern Void criAtomExPlayer_SetRandomSeed(IntPtr player, UInt32 seed) { }
	// RVA: 0x4138bc0 VA: 0x7596750bc0
	private static extern Void CRIWAREF5F90443(IntPtr player, Boolean sw) { }
	// RVA: 0x41378dc VA: 0x759674f8dc
	private static extern Void criAtomExPlayer_SetAsrRackId(IntPtr player, Int32 asr_rack_id) { }
	// RVA: 0x4137ae8 VA: 0x759674fae8
	private static extern Void criAtomExPlayer_SetDspParameter(IntPtr player, Int32 id, Single value) { }
	// RVA: 0x4137cd4 VA: 0x759674fcd4
	private static extern Void criAtomExPlayer_AttachTween(IntPtr player, IntPtr tween) { }
	// RVA: 0x4137dc4 VA: 0x759674fdc4
	private static extern Void criAtomExPlayer_DetachTween(IntPtr player, IntPtr tween) { }
	// RVA: 0x4137ea0 VA: 0x759674fea0
	private static extern Void criAtomExPlayer_DetachTweenAll(IntPtr player) { }
	// RVA: 0x4137f94 VA: 0x759674ff94
	private static extern Void criAtomExPlayer_SetEnvelopeAttackCurve(IntPtr player, CurveType curve_type, Single strength) { }
	// RVA: 0x41380a0 VA: 0x75967500a0
	private static extern Void criAtomExPlayer_SetEnvelopeDecayCurve(IntPtr player, CurveType curve_type, Single strength) { }
	// RVA: 0x41381ac VA: 0x75967501ac
	private static extern Void criAtomExPlayer_SetEnvelopeReleaseCurve(IntPtr player, CurveType curve_type, Single strength) { }
	// RVA: 0x41382ac VA: 0x75967502ac
	private static extern Void criAtomExPlayer_AddOutputPort(IntPtr player, IntPtr outputPort) { }
	// RVA: 0x413839c VA: 0x759675039c
	private static extern Void criAtomExPlayer_RemoveOutputPort(IntPtr player, IntPtr outputPort) { }
	// RVA: 0x4138478 VA: 0x7596750478
	private static extern Void criAtomExPlayer_ClearOutputPorts(IntPtr player) { }
	// RVA: 0x4138560 VA: 0x7596750560
	private static extern Void criAtomExPlayer_AddPreferredOutputPort(IntPtr player, IntPtr outputPort) { }
	// RVA: 0x4138650 VA: 0x7596750650
	private static extern Void criAtomExPlayer_RemovePreferredOutputPort(IntPtr player, IntPtr outputPort) { }
	// RVA: 0x413873c VA: 0x759675073c
	private static extern Void criAtomExPlayer_RemovePreferredOutputPortByName(IntPtr player, String name) { }
	// RVA: 0x413882c VA: 0x759675082c
	private static extern Void criAtomExPlayer_ClearPreferredOutputPorts(IntPtr player) { }
	// RVA: 0x4138910 VA: 0x7596750910
	private static extern Void criAtomExPlayer_SetScheduleTime(IntPtr player, Int64 schedule_time) { }
	// RVA: 0x4138c44 VA: 0x7596750c44
	private static Void .cctor() { }
}
```