# AudioChannelEffect

**Namespace:** `Torappu.Audio`


## Fields

- `Int32 m_sequenceNum`

- `ParamDict m_paramDict`


## Methods

- `Boolean IsEmpty()`

- `Void SetEffectInputParam(EffectInputParam)`

- `Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty)`

- `Void ReverseAllPropertyEffect()`

- `AudioEffectBaseValueParam GetEffectValueParam(String, AudioChannelEffectProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioChannelEffect : IHotfixable
{
	private Int32 m_sequenceNum; // 0x10
	private ParamDict m_paramDict; // 0x18
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_SetEffectInputParam; // 0x8
	private static DelegateBridge __Hotfix0_ReverseEffectWithTargetProperty; // 0x10
	private static DelegateBridge __Hotfix0_ReverseAllPropertyEffect; // 0x18
	private static DelegateBridge __Hotfix0_GetEffectValueParam; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3eb4f6c VA: 0x75964ccf6c
	public Boolean IsEmpty() { }
	// RVA: 0x3eb5080 VA: 0x75964cd080
	public Void SetEffectInputParam(EffectInputParam effectInputParam) { }
	// RVA: 0x3eb57c4 VA: 0x75964cd7c4
	public Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty effectProperty) { }
	// RVA: 0x3eb5a34 VA: 0x75964cda34
	public Void ReverseAllPropertyEffect() { }
	// RVA: 0x3eb5c78 VA: 0x75964cdc78
	public AudioEffectBaseValueParam GetEffectValueParam(String channelName, AudioChannelEffectProperty effectProperty) { }
	// RVA: 0x3eb5ecc VA: 0x75964cdecc
	public Void .ctor() { }
}
```