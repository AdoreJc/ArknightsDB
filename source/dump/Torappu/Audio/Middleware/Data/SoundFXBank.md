# SoundFXBank

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `Single m_totalWeight`

- `MixerDesc <mixerDesc>k__BackingField`

- `Int32 maxSoundAllowed`

- `Boolean popOldest`

- `String customMixerGroup`

- `Boolean loop`


## Properties

- `MixerDesc mixerDesc`


## Methods

- `MixerDesc get_mixerDesc()`

- `Void set_mixerDesc(MixerDesc)`

- `SoundFX _GenerateWeightedRandomSound()`

- `Void <>xLuaBaseProxy_Preload(String)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class SoundFXBank : Bank
{
	private Single m_totalWeight; // 0x30
	private MixerDesc <mixerDesc>k__BackingField; // 0x38
	public SoundFX[] sounds; // 0x50
	public Int32 maxSoundAllowed; // 0x58
	public Boolean popOldest; // 0x5c
	public String customMixerGroup; // 0x60
	public Boolean loop; // 0x68
	private static DelegateBridge __Hotfix0_get_mixerDesc; // 0x0
	private static DelegateBridge __Hotfix0_set_mixerDesc; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10
	private static DelegateBridge __Hotfix0_Preload; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_ParseMixer; // 0x28
	private static DelegateBridge __Hotfix0__GenerateWeightedRandomSound; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public MixerDesc mixerDesc { get; set; }

	// RVA: 0x3ee1578 VA: 0x75964f9578
	public MixerDesc get_mixerDesc() { }
	// RVA: 0x3ee1608 VA: 0x75964f9608
	private Void set_mixerDesc(MixerDesc value) { }
	// RVA: 0x3ee16b8 VA: 0x75964f96b8
	public override AudioAtom Play(Vector3 position) { }
	// RVA: 0x3ee1d4c VA: 0x75964f9d4c
	public override Void Preload(String persistTag) { }
	// RVA: 0x3ee1f0c VA: 0x75964f9f0c
	protected override Void OnInit() { }
	// RVA: 0x3ee2014 VA: 0x75964fa014
	public static MixerDesc ParseMixer(String bankName, String customMixerGroup) { }
	// RVA: 0x3ee1958 VA: 0x75964f9958
	private SoundFX _GenerateWeightedRandomSound() { }
	// RVA: 0x3ee2158 VA: 0x75964fa158
	public Void .ctor() { }
	// RVA: 0x3ee21c4 VA: 0x75964fa1c4
	private Void <>xLuaBaseProxy_Preload(String P0) { }
	// RVA: 0x3ee21c8 VA: 0x75964fa1c8
	private Void <>xLuaBaseProxy_OnInit() { }
}
```