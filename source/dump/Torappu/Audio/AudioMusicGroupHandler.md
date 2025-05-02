# AudioMusicGroupHandler

**Namespace:** `Torappu.Audio`


## Fields

- `String m_channelName`

- `AudioFadeParam m_cachedFadeParam`


## Properties

- `String channelName`


## Methods

- `String get_channelName()`

- `Void CollectEffect(AudioChannelEffect, EffectInputParam)`

- `String PlayMusic(GroupPlayOption)`

- `Void Stop()`

- `Void _PlayMusicWithChannelToSync(String, String)`

- `AudioFadeParam _GeneMusicFadeParam(BGMBank)`

- `Void _StopChannel(AudioFadeParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioMusicGroupHandler : IHotfixable
{
	private String m_channelName; // 0x10
	private AudioFadeParam m_cachedFadeParam; // 0x18
	private SetWhenBind`2 m_setEffect; // 0x28
	private static DelegateBridge __Hotfix0_get_channelName; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_CollectEffect; // 0x10
	private static DelegateBridge __Hotfix0_PlayMusic; // 0x18
	private static DelegateBridge __Hotfix0_Stop; // 0x20
	private static DelegateBridge __Hotfix0__PlayMusicWithChannelToSync; // 0x28
	private static DelegateBridge __Hotfix0__GeneMusicFadeParam; // 0x30
	private static DelegateBridge __Hotfix0__StopChannel; // 0x38

	public String channelName { get; }

	// RVA: 0x3eb763c VA: 0x75964cf63c
	public String get_channelName() { }
	// RVA: 0x3eb76a4 VA: 0x75964cf6a4
	private Void .ctor() { }
	// RVA: 0x3eb7854 VA: 0x75964cf854
	public Void CollectEffect(AudioChannelEffect channelEffect, EffectInputParam inputParam) { }
	// RVA: 0x3eb7ad0 VA: 0x75964cfad0
	public String PlayMusic(GroupPlayOption groupPlayOption) { }
	// RVA: 0x3eb7c34 VA: 0x75964cfc34
	public Void Stop() { }
	// RVA: 0x3eb7ca0 VA: 0x75964cfca0
	private Void _PlayMusicWithChannelToSync(String bankName, String channelNameToSync) { }
	// RVA: 0x3eb7ed8 VA: 0x75964cfed8
	private AudioFadeParam _GeneMusicFadeParam(BGMBank bgmBank) { }
	// RVA: 0x3eb7e48 VA: 0x75964cfe48
	private Void _StopChannel(AudioFadeParam fadeParam) { }
}
```