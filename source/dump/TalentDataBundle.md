# TalentDataBundle

**Namespace:** ` `


## Methods

- `Boolean TryGetTalent(Int32, EvolvePhase, Int32, out)`

- `Boolean TryGetInitTalent(out)`

- `Boolean TryGetNextTalent(Int32, EvolvePhase, Int32, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TalentDataBundle
{
	public TalentData[] candidates; // 0x10


	// RVA: 0x33c8d38 VA: 0x75959e0d38
	public Boolean TryGetTalent(Int32 level, EvolvePhase phase, Int32 potential, out TalentData talent) { }
	// RVA: 0x33c8d40 VA: 0x75959e0d40
	protected static Boolean DoGetTalent(TalentData[] candidates, Int32 level, EvolvePhase phase, Int32 potential, out TalentData talent) { }
	// RVA: 0x33c8f9c VA: 0x75959e0f9c
	public Boolean TryGetInitTalent(out TalentData talentData) { }
	// RVA: 0x33c9164 VA: 0x75959e1164
	public Boolean TryGetNextTalent(Int32 level, EvolvePhase phase, Int32 potential, out TalentData talent) { }
	// RVA: 0x33c93b4 VA: 0x75959e13b4
	public Void .ctor() { }
}
```