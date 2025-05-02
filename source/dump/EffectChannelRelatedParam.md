# EffectChannelRelatedParam

**Namespace:** ` `


## Methods

- `Void SetEffectInputParam(AudioEffectBaseValueParam, AudioChannelEffectProperty)`

- `Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty, Int32)`

- `Void ReverseAllPropertyEffect(Int32)`

- `AudioEffectBaseValueParam GetEffectValueParam(AudioChannelEffectProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class EffectChannelRelatedParam : IHotfixable
{
	public EnumIntStructDictionary`2 propertyParamMap; // 0x10
	private static DelegateBridge __Hotfix0_SetEffectInputParam; // 0x0
	private static DelegateBridge __Hotfix0_ReverseEffectWithTargetProperty; // 0x8
	private static DelegateBridge __Hotfix0_ReverseAllPropertyEffect; // 0x10
	private static DelegateBridge __Hotfix0_GetEffectValueParam; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3eb6490 VA: 0x75964ce490
	public Void SetEffectInputParam(AudioEffectBaseValueParam newEffectBaseParam, AudioChannelEffectProperty property) { }
	// RVA: 0x3eb6608 VA: 0x75964ce608
	public Void ReverseEffectWithTargetProperty(AudioChannelEffectProperty effectProperty, Int32 sequenceNum) { }
	// RVA: 0x3eb6804 VA: 0x75964ce804
	public Void ReverseAllPropertyEffect(Int32 sequenceNum) { }
	// RVA: 0x3eb6cb8 VA: 0x75964cecb8
	public AudioEffectBaseValueParam GetEffectValueParam(AudioChannelEffectProperty effectProperty) { }
	// RVA: 0x3eb6e00 VA: 0x75964cee00
	public Void .ctor() { }
}
```