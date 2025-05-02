# Act29sideAudioController

**Namespace:** ` `


## Fields

- `String m_normalBankName`

- `String m_depressedBankName`

- `String m_enthuBankName`

- `Boolean m_playExtraMusic`

- `UIMusicDuckingHelper m_musicDuckingHelper`

- `AudioMusicGroupHandler m_depressedMusicGroupHandler`

- `AudioMusicGroupHandler m_enthuMusicGroupHandler`


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void set_isValid(Boolean)`

- `Void Init(Blackboard)`

- `Void PlayAudio(AudioType)`

- `Void MuteAllExtraAudio()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class Act29sideAudioController
{
	private const Int32 EXPECTED_BANK_NUM; // 0x0
	private const Int32 NORMAL_BANK_ID; // 0x0
	private const Int32 DEPRESSED_BANK_ID; // 0x0
	private const Int32 ENTHU_BANK_ID; // 0x0
	private String m_normalBankName; // 0x10
	private String m_depressedBankName; // 0x18
	private String m_enthuBankName; // 0x20
	private Boolean m_playExtraMusic; // 0x28
	private UIMusicDuckingHelper m_musicDuckingHelper; // 0x30
	private AudioMusicGroupHandler m_depressedMusicGroupHandler; // 0x38
	private AudioMusicGroupHandler m_enthuMusicGroupHandler; // 0x40

	public Boolean isValid { get; set; }

	// RVA: 0x4030f28 VA: 0x7596648f28
	public Boolean get_isValid() { }
	// RVA: 0x4030f30 VA: 0x7596648f30
	public Void set_isValid(Boolean value) { }
	// RVA: 0x402f610 VA: 0x7596647610
	public Void Init(Blackboard blackboard) { }
	// RVA: 0x4030050 VA: 0x7596648050
	public Void PlayAudio(AudioType type) { }
	// RVA: 0x4030a70 VA: 0x7596648a70
	public Void MuteAllExtraAudio() { }
	// RVA: 0x402f0b8 VA: 0x75966470b8
	public Void .ctor() { }
}
```