# CharViewModel

**Namespace:** ` `


## Fields

- `Int32 tier`

- `EvolvePhase normalEvolvePhase`

- `Int32 normalLevel`

- `EvolvePhase goldenEvolvePhase`

- `Int32 goldenLevel`

- `Boolean isGolden`

- `String charId`

- `String skinId`

- `Boolean isAssist`

- `Boolean isBackup`

- `String skillId`

- `String equipId`

- `Int32 sortId`


## Methods

- `Int32 CompareTo(CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharViewModel : IComparable`1, IHotfixable
{
	public Int32 tier; // 0x10
	public EvolvePhase normalEvolvePhase; // 0x14
	public Int32 normalLevel; // 0x18
	public EvolvePhase goldenEvolvePhase; // 0x1c
	public Int32 goldenLevel; // 0x20
	public Boolean isGolden; // 0x24
	public String charId; // 0x28
	public String skinId; // 0x30
	public Boolean isAssist; // 0x38
	public Boolean isBackup; // 0x39
	public String skillId; // 0x40
	public String equipId; // 0x48
	public Int32 sortId; // 0x50
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33560bc VA: 0x759596e0bc
	public Int32 CompareTo(CharViewModel other) { }
	// RVA: 0x33554d0 VA: 0x759596d4d0
	public Void .ctor() { }
}
```