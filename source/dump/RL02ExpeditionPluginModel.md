# RL02ExpeditionPluginModel

**Namespace:** ` `


## Methods

- `Void LoadData(String)`

- `Int32 OverrideExpeditionCharListSort(RoguelikeExpeditionCharCardViewModel, RoguelikeExpeditionCharCardViewModel)`

- `RoguelikeCharBuffModel GetCharBuff(String)`

- `Boolean _HasMutationCharBuff(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RL02ExpeditionPluginModel : IHotfixable
{
	public Dictionary`2 charBuffs; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OverrideExpeditionCharListSort; // 0x8
	private static DelegateBridge __Hotfix0_GetCharBuff; // 0x10
	private static DelegateBridge __Hotfix0__HasMutationCharBuff; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b6aa0c VA: 0x7595182a0c
	public Void LoadData(String topicId) { }
	// RVA: 0x2b6b0b0 VA: 0x75951830b0
	public Int32 OverrideExpeditionCharListSort(RoguelikeExpeditionCharCardViewModel lhs, RoguelikeExpeditionCharCardViewModel rhs) { }
	// RVA: 0x2b6ae64 VA: 0x7595182e64
	public RoguelikeCharBuffModel GetCharBuff(String charInstId) { }
	// RVA: 0x2b6b238 VA: 0x7595183238
	private Boolean _HasMutationCharBuff(String charInstId) { }
	// RVA: 0x2b6afec VA: 0x7595182fec
	public Void .ctor() { }
}
```