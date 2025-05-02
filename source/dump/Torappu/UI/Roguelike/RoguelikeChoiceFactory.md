# RoguelikeChoiceFactory

**Namespace:** `Torappu.UI.Roguelike`


## Methods

- `IRoguelikeGameChoice CreateChoice(String, RoguelikeGameChoiceData, Boolean, ChoiceAddition, RoguelikeChoiceHintFactory)`

- `IRoguelikeGameChoice _CreateBasicChoice(String, RoguelikeGameChoiceData, Boolean, ChoiceAddition, RoguelikeChoiceHintFactory)`

- `RoguelikeChoiceDisplayData _DealWithAdditionalPlayerData(ChoiceAddition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceFactory
{
	private static DelegateBridge __Hotfix0_CreateChoice; // 0x0
	private static DelegateBridge __Hotfix0__CreateBasicChoice; // 0x8
	private static DelegateBridge __Hotfix0__DealWithAdditionalPlayerData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29eacd4 VA: 0x7595002cd4
	public IRoguelikeGameChoice CreateChoice(String topicId, RoguelikeGameChoiceData data, Boolean selectable, ChoiceAddition additionData, RoguelikeChoiceHintFactory hintFactory) { }
	// RVA: 0x29ead9c VA: 0x7595002d9c
	private IRoguelikeGameChoice _CreateBasicChoice(String topicId, RoguelikeGameChoiceData data, Boolean selectable, ChoiceAddition additionData, RoguelikeChoiceHintFactory hintFactory) { }
	// RVA: 0x29eaf6c VA: 0x7595002f6c
	private RoguelikeChoiceDisplayData _DealWithAdditionalPlayerData(ChoiceAddition additionData) { }
	// RVA: 0x29eb460 VA: 0x7595003460
	public Void .ctor() { }
}
```