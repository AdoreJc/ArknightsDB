# CharAdvancedStats

**Namespace:** ` `


## Fields

- `Vector2 outputDamageRange`

- `Vector2 inputDamageRange`

- `Single outputDamageTotal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharAdvancedStats : IHotfixable
{
	public Vector2 outputDamageRange; // 0x10
	public Vector2 inputDamageRange; // 0x18
	public Single outputDamageTotal; // 0x20
	public List`1 outputElementDamageTotal; // 0x28
	public List`1 outputEpBreakCnt; // 0x30
	public List`1 snapshots; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ToList; // 0x8
	private static DelegateBridge __Hotfix0_ToListFinal; // 0x10
	private static DelegateBridge __Hotfix0_ToListEpBreakCnt; // 0x18


	// RVA: 0x3fe0bf8 VA: 0x75965f8bf8
	public Void .ctor() { }
	// RVA: 0x3fe2218 VA: 0x75965fa218
	public List`1 ToList() { }
	// RVA: 0x3fe2590 VA: 0x75965fa590
	public List`1 ToListFinal() { }
	// RVA: 0x3fe27c8 VA: 0x75965fa7c8
	public List`1 ToListEpBreakCnt() { }
}
```