# TransitionChaosData

**Namespace:** ` `


## Fields

- `Int32 chaosIncreaseNum`

- `Int32 chaosLevelBefore`

- `Int32 chaosLevelAfter`


## Methods

- `Void LoadData(String, ChaosZoneDelta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransitionChaosData : IHotfixable
{
	public Int32 chaosIncreaseNum; // 0x10
	public Int32 chaosLevelBefore; // 0x14
	public Int32 chaosLevelAfter; // 0x18
	public List`1 chaosDelta; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb1be4 VA: 0x75951c9be4
	public Void LoadData(String topicId, ChaosZoneDelta playerDeltaChaos) { }
	// RVA: 0x2bb1e84 VA: 0x75951c9e84
	public Void .ctor() { }
}
```