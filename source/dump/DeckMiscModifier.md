# DeckMiscModifier

**Namespace:** ` `


## Fields

- `Card m_sourceCard`

- `Options m_options`

- `Boolean m_isTriggered`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckMiscModifier : MiscSettingModifier
{
	private Card m_sourceCard; // 0x30
	private Options m_options; // 0x38
	private Boolean m_isTriggered; // 0x40


	// RVA: 0x1b794e0 VA: 0x75941914e0
	public override Boolean IsTriggered(Card card) { }
	// RVA: 0x1b793f8 VA: 0x75941913f8
	public Void .ctor(Card sourceCard, Boolean dontOccupyDeployCnt, Options options, AdditionalBuildCondition additionalBuildCondition, Boolean ignoreRespawningState) { }
	// RVA: 0x1b79518 VA: 0x7594191518
	public override Void Preprocess(Deck deck) { }
}
```