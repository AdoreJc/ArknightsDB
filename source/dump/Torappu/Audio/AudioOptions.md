# AudioOptions

**Namespace:** `Torappu.Audio`


## Fields

- `Int32 channelPreloadSize`

- `AudioMixerHolder _staticLinkHolder`

- `Action onOptionsChanged`


## Properties

- `AudioMixerHolder activeMixerHolder`

- `AudioMixer mainMixer`

- `AudioMixerGroup musicGroup`

- `AudioMixerGroup voiceGroup`

- `AudioMixerGroup fxGroup`

- `AudioMixerGroup uiFxGroup`

- `AudioMixerGroup importantUIFxGroup`

- `AudioMixerGroup battleFxGroup`

- `AudioMixerGroup importantBattleFxGroup`


## Methods

- `Void add_onOptionsChanged(Action)`

- `Void remove_onOptionsChanged(Action)`

- `AudioMixerHolder get_activeMixerHolder()`

- `AudioMixer get_mainMixer()`

- `AudioMixerGroup get_musicGroup()`

- `AudioMixerGroup get_voiceGroup()`

- `AudioMixerGroup get_fxGroup()`

- `AudioMixerGroup get_uiFxGroup()`

- `AudioMixerGroup get_importantUIFxGroup()`

- `AudioMixerGroup get_battleFxGroup()`

- `AudioMixerGroup get_importantBattleFxGroup()`

- `AudioMixerGroup SelectMixerGroup(Category, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioOptions : SingletonScriptableObject`1, IHotfixable
{
	private const String CONFIG_RES_PATH; // 0x0
	public String[] musicVolumeParams; // 0x18
	public String[] voiceVolumeParams; // 0x20
	public String[] fxVolumeParams; // 0x28
	public Int32 channelPreloadSize; // 0x30
	private AudioMixerHolder _staticLinkHolder; // 0x38
	private Action onOptionsChanged; // 0x40
	private static DelegateBridge __Hotfix0_add_onOptionsChanged; // 0x0
	private static DelegateBridge __Hotfix0_remove_onOptionsChanged; // 0x8
	private static DelegateBridge __Hotfix0_get_activeMixerHolder; // 0x10
	private static DelegateBridge __Hotfix0_get_mainMixer; // 0x18
	private static DelegateBridge __Hotfix0_get_musicGroup; // 0x20
	private static DelegateBridge __Hotfix0_get_voiceGroup; // 0x28
	private static DelegateBridge __Hotfix0_get_fxGroup; // 0x30
	private static DelegateBridge __Hotfix0_get_uiFxGroup; // 0x38
	private static DelegateBridge __Hotfix0_get_importantUIFxGroup; // 0x40
	private static DelegateBridge __Hotfix0_get_battleFxGroup; // 0x48
	private static DelegateBridge __Hotfix0_get_importantBattleFxGroup; // 0x50
	private static DelegateBridge __Hotfix0_SelectMixerGroup; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected AudioMixerHolder activeMixerHolder { get; }
	public AudioMixer mainMixer { get; }
	public AudioMixerGroup musicGroup { get; }
	public AudioMixerGroup voiceGroup { get; }
	public AudioMixerGroup fxGroup { get; }
	public AudioMixerGroup uiFxGroup { get; }
	public AudioMixerGroup importantUIFxGroup { get; }
	public AudioMixerGroup battleFxGroup { get; }
	public AudioMixerGroup importantBattleFxGroup { get; }

	// RVA: 0x3eb824c VA: 0x75964d024c
	public Void add_onOptionsChanged(Action value) { }
	// RVA: 0x3eb8328 VA: 0x75964d0328
	public Void remove_onOptionsChanged(Action value) { }
	// RVA: 0x3eb8404 VA: 0x75964d0404
	protected AudioMixerHolder get_activeMixerHolder() { }
	// RVA: 0x3eb846c VA: 0x75964d046c
	public AudioMixer get_mainMixer() { }
	// RVA: 0x3eb84e4 VA: 0x75964d04e4
	public AudioMixerGroup get_musicGroup() { }
	// RVA: 0x3eb855c VA: 0x75964d055c
	public AudioMixerGroup get_voiceGroup() { }
	// RVA: 0x3eb85d4 VA: 0x75964d05d4
	public AudioMixerGroup get_fxGroup() { }
	// RVA: 0x3eb864c VA: 0x75964d064c
	public AudioMixerGroup get_uiFxGroup() { }
	// RVA: 0x3eb86c4 VA: 0x75964d06c4
	public AudioMixerGroup get_importantUIFxGroup() { }
	// RVA: 0x3eb873c VA: 0x75964d073c
	public AudioMixerGroup get_battleFxGroup() { }
	// RVA: 0x3eb87b4 VA: 0x75964d07b4
	public AudioMixerGroup get_importantBattleFxGroup() { }
	// RVA: 0x3eb882c VA: 0x75964d082c
	public AudioMixerGroup SelectMixerGroup(Category category, Boolean important) { }
	// RVA: 0x3eb8968 VA: 0x75964d0968
	public Void .ctor() { }
}
```