# TorappuAudioData

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `BattleVoiceData battleVoice`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class TorappuAudioData
{
	public BGMBank[] bgmBanks; // 0x10
	public SoundFXBank[] soundFXBanks; // 0x18
	public SoundFXCtrlBank[] soundFXCtrlBanks; // 0x20
	public SnapshotBank[] snapshotBanks; // 0x28
	public BattleVoiceData battleVoice; // 0x30
	public MusicData[] musics; // 0x38
	public DuckingData[] duckings; // 0x40
	public FadeStyleData[] fadeStyles; // 0x48
	public Dictionary`2 soundFxVoiceLang; // 0x50
	public Dictionary`2 bankAlias; // 0x58


	// RVA: 0x3ee4188 VA: 0x75964fc188
	public Void .ctor() { }
}
```