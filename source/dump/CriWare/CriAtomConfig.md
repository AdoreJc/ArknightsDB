# CriAtomConfig

**Namespace:** `CriWare`


## Fields

- `String acfFileName`

- `Int32 maxVirtualVoices`

- `Int32 maxVoiceLimitGroups`

- `Int32 maxCategories`

- `Int32 maxAisacs`

- `Int32 maxBusSends`

- `Int32 maxSequenceEventsPerFrame`

- `Int32 maxBeatSyncCallbacksPerFrame`

- `Int32 maxCueLinkCallbacksPerFrame`

- `StandardVoicePoolConfig standardVoicePoolConfig`

- `HcaMxVoicePoolConfig hcaMxVoicePoolConfig`

- `Int32 outputSamplingRate`

- `Boolean usesInGamePreview`

- `InGamePreviewSwitchMode inGamePreviewMode`

- `Boolean switchInitializeSocket`

- `InGamePreviewConfig inGamePreviewConfig`

- `Single serverFrequency`

- `SpeakerMapping speakerMapping`

- `Int32 asrOutputChannels`

- `Boolean useRandomSeedWithTime`

- `Int32 categoriesPerPlayback`

- `Int32 maxFaders`

- `Int32 maxBuses`

- `Single maxPitch`

- `Int32 maxParameterBlocks`

- `SoundRendererType soundRendererType`

- `Boolean keepPlayingSoundOnPause`

- `Boolean enableSonicSync`

- `Boolean enableAtomSoundDisabledMode`

- `Boolean enableAtomSoundDisabledModeLinux`

- `EditorPcmOutputConfig editorPcmOutputConfig`

- `Int32 pcBufferingTime`

- `Boolean useMicrosoftSpatialSound`

- `LinuxOutput linuxOutput`

- `Int32 linuxPulseLatencyUsec`

- `Boolean iosEnableSonicSync`

- `Int32 iosBufferingTime`

- `Boolean iosOverrideIPodMusic`

- `Boolean iosEnableOSNotificationHandling`

- `Boolean androidEnableSonicSync`

- `Int32 androidBufferingTime`

- `Int32 androidStartBufferingTime`

- `AndroidLowLatencyStandardVoicePoolConfig androidLowLatencyStandardVoicePoolConfig`

- `Boolean androidUsesAndroidFastMixer`

- `Boolean androidForceToUseAsrForDefaultPlayback`

- `Boolean androidUsesAAudio`

- `Int32 androidStreamType`

- `VitaManaVoicePoolConfig vitaManaVoicePoolConfig`

- `VitaAtrac9VoicePoolConfig vitaAtrac9VoicePoolConfig`

- `Ps4Atrac9VoicePoolConfig ps4Atrac9VoicePoolConfig`

- `Ps5PortConfig ps5PortConfig`

- `Int32 ps5Mp3StreamingVoices`

- `Boolean switchEnableSonicSync`

- `SwitchOpusVoicePoolConfig switchOpusVoicePoolConfig`

- `Ps4Audio3dConfig ps4Audio3dConfig`

- `Int32 ps4Mp3StreamingVoices`

- `WebGLWebAudioVoicePoolConfig webglWebAudioVoicePoolConfig`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomConfig
{
	public String acfFileName; // 0x10
	public Int32 maxVirtualVoices; // 0x18
	public Int32 maxVoiceLimitGroups; // 0x1c
	public Int32 maxCategories; // 0x20
	public Int32 maxAisacs; // 0x24
	public Int32 maxBusSends; // 0x28
	public Int32 maxSequenceEventsPerFrame; // 0x2c
	public Int32 maxBeatSyncCallbacksPerFrame; // 0x30
	public Int32 maxCueLinkCallbacksPerFrame; // 0x34
	public StandardVoicePoolConfig standardVoicePoolConfig; // 0x38
	public HcaMxVoicePoolConfig hcaMxVoicePoolConfig; // 0x40
	public Int32 outputSamplingRate; // 0x48
	public Boolean usesInGamePreview; // 0x4c
	public InGamePreviewSwitchMode inGamePreviewMode; // 0x50
	public Boolean switchInitializeSocket; // 0x54
	public InGamePreviewConfig inGamePreviewConfig; // 0x58
	public Single serverFrequency; // 0x60
	public SpeakerMapping speakerMapping; // 0x64
	public Int32 asrOutputChannels; // 0x68
	public Boolean useRandomSeedWithTime; // 0x6c
	public Int32 categoriesPerPlayback; // 0x70
	public Int32 maxFaders; // 0x74
	public Int32 maxBuses; // 0x78
	public Single maxPitch; // 0x7c
	public Int32 maxParameterBlocks; // 0x80
	public SoundRendererType soundRendererType; // 0x84
	public Boolean keepPlayingSoundOnPause; // 0x88
	public Boolean enableSonicSync; // 0x89
	public Boolean enableAtomSoundDisabledMode; // 0x8a
	public Boolean enableAtomSoundDisabledModeLinux; // 0x8b
	public EditorPcmOutputConfig editorPcmOutputConfig; // 0x90
	public Int32 pcBufferingTime; // 0x98
	public Boolean useMicrosoftSpatialSound; // 0x9c
	public LinuxOutput linuxOutput; // 0xa0
	public Int32 linuxPulseLatencyUsec; // 0xa4
	public Boolean iosEnableSonicSync; // 0xa8
	public Int32 iosBufferingTime; // 0xac
	public Boolean iosOverrideIPodMusic; // 0xb0
	public Boolean iosEnableOSNotificationHandling; // 0xb1
	public Boolean androidEnableSonicSync; // 0xb2
	public Int32 androidBufferingTime; // 0xb4
	public Int32 androidStartBufferingTime; // 0xb8
	public AndroidLowLatencyStandardVoicePoolConfig androidLowLatencyStandardVoicePoolConfig; // 0xc0
	public Boolean androidUsesAndroidFastMixer; // 0xc8
	public Boolean androidForceToUseAsrForDefaultPlayback; // 0xc9
	public Boolean androidUsesAAudio; // 0xca
	public Int32 androidStreamType; // 0xcc
	public VitaManaVoicePoolConfig vitaManaVoicePoolConfig; // 0xd0
	public VitaAtrac9VoicePoolConfig vitaAtrac9VoicePoolConfig; // 0xd8
	public Ps4Atrac9VoicePoolConfig ps4Atrac9VoicePoolConfig; // 0xe0
	public Ps5PortConfig ps5PortConfig; // 0xe8
	public Int32 ps5Mp3StreamingVoices; // 0xf0
	public Boolean switchEnableSonicSync; // 0xf4
	public SwitchOpusVoicePoolConfig switchOpusVoicePoolConfig; // 0xf8
	public Ps4Audio3dConfig ps4Audio3dConfig; // 0x100
	public Int32 ps4Mp3StreamingVoices; // 0x108
	public WebGLWebAudioVoicePoolConfig webglWebAudioVoicePoolConfig; // 0x110


	// RVA: 0x414a830 VA: 0x7596762830
	public Void .ctor() { }
}
```