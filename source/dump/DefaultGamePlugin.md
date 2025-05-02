# DefaultGamePlugin

**Namespace:** ` `


## Fields

- `VoicePlayer <voicePlayer>k__BackingField`


## Properties

- `VoicePlayer voicePlayer`


## Methods

- `VoicePlayer get_voicePlayer()`

- `Void set_voicePlayer(VoicePlayer)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DefaultGamePlugin : IHotfixable
{
	private VoicePlayer <voicePlayer>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_voicePlayer; // 0x0
	private static DelegateBridge __Hotfix0_set_voicePlayer; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_HookPlayVoice; // 0x18
	private static DelegateBridge __Hotfix0_PlayVoice; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected VoicePlayer voicePlayer { get; set; }

	// RVA: 0x208b718 VA: 0x75946a3718
	protected VoicePlayer get_voicePlayer() { }
	// RVA: 0x208b780 VA: 0x75946a3780
	private Void set_voicePlayer(VoicePlayer value) { }
	// RVA: 0x208b804 VA: 0x75946a3804
	public virtual Void Init(VoicePlayer voicePlayer) { }
	// RVA: 0x208b884 VA: 0x75946a3884
	public virtual Boolean HookPlayVoice(ref BattleVoiceType voiceType, ref VoiceQuery vq, ref MapLayer mapLayer, out PlayResult result) { }
	// RVA: 0x208b964 VA: 0x75946a3964
	protected virtual PlayResult PlayVoice(BattleVoiceType voiceType, VoiceQuery vq, MapLayer mapLayer) { }
	// RVA: 0x208ba30 VA: 0x75946a3a30
	public Void .ctor() { }
}
```