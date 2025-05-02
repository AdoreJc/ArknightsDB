# SandboxV2DungeonRareAnimalGroupViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean hpRatioValid`

- `Int32 stackCount`

- `Int32 hpRatio`


## Methods

- `Boolean IsEmpty()`

- `Void Clear()`

- `Void AddRareAnimal(SandboxV2DungeonRareAnimalViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonRareAnimalGroupViewModel : IHotfixable
{
	public List`1 rareAnimalList; // 0x10
	public List`1 rareAnimalGroupDrop; // 0x18
	public Boolean hpRatioValid; // 0x20
	public Int32 stackCount; // 0x24
	public Int32 hpRatio; // 0x28
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x8
	private static DelegateBridge __Hotfix0_AddRareAnimal; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25c06c0 VA: 0x7594bd86c0
	public Boolean IsEmpty() { }
	// RVA: 0x25c074c VA: 0x7594bd874c
	public Void Clear() { }
	// RVA: 0x25c082c VA: 0x7594bd882c
	public Void AddRareAnimal(SandboxV2DungeonRareAnimalViewModel rareAnimal) { }
	// RVA: 0x25bba60 VA: 0x7594bd3a60
	public Void .ctor() { }
}
```