# ParamDict

**Namespace:** ` `


## Fields

- `EffectChannelRelatedParam m_wholeChannelParam`

- `AudioChannelEffect m_closure`


## Properties

- `Boolean isWholeChannels`


## Methods

- `Boolean IsEmpty()`

- `Boolean get_isWholeChannels()`

- `Void SetEffectInputParam(EffectInputParam)`

- `Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty)`

- `Void ReverseAllPropertyEffect()`

- `AudioEffectBaseValueParam GetEffectValueParam(String, AudioChannelEffectProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ParamDict : IHotfixable
{
	private Dictionary`2 m_effectChannelParamDict; // 0x10
	private EffectChannelRelatedParam m_wholeChannelParam; // 0x18
	private AudioChannelEffect m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x8
	private static DelegateBridge __Hotfix0_get_isWholeChannels; // 0x10
	private static DelegateBridge __Hotfix0_SetEffectInputParam; // 0x18
	private static DelegateBridge __Hotfix0_ReverseEffectWithTargetProperty; // 0x20
	private static DelegateBridge __Hotfix0_ReverseAllPropertyEffect; // 0x28
	private static DelegateBridge __Hotfix0_GetEffectValueParam; // 0x30

	public Boolean isWholeChannels { get; }

	// RVA: 0x3eb532c VA: 0x75964cd32c
	public Void .ctor(AudioChannelEffect closure) { }
	// RVA: 0x3eb4fe8 VA: 0x75964ccfe8
	public Boolean IsEmpty() { }
	// RVA: 0x3eb52bc VA: 0x75964cd2bc
	public Boolean get_isWholeChannels() { }
	// RVA: 0x3eb5414 VA: 0x75964cd414
	public Void SetEffectInputParam(EffectInputParam effectInputParam) { }
	// RVA: 0x3eb5864 VA: 0x75964cd864
	public Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty effectProperty) { }
	// RVA: 0x3eb5ab8 VA: 0x75964cdab8
	public Void ReverseAllPropertyEffect() { }
	// RVA: 0x3eb5d84 VA: 0x75964cdd84
	public AudioEffectBaseValueParam GetEffectValueParam(String channelName, AudioChannelEffectProperty effectProperty) { }
}
```