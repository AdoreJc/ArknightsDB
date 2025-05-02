# FireworkCraftAnimalViewModel

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `String animalId`

- `Int32 sortId`

- `String animalDesc`

- `String animalNameId`

- `Boolean isUnlocked`

- `String unlockStageId`

- `String unlockStageCode`

- `String changedToast`


## Methods

- `Void LoadData(AnimalData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAnimalViewModel : IHotfixable
{
	public String animalId; // 0x10
	public Int32 sortId; // 0x18
	public String animalDesc; // 0x20
	public String animalNameId; // 0x28
	public Boolean isUnlocked; // 0x30
	public String unlockStageId; // 0x38
	public String unlockStageCode; // 0x40
	public String changedToast; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2902ea4 VA: 0x7594f1aea4
	public Void LoadData(AnimalData animalData, Boolean unlocked) { }
	// RVA: 0x2903058 VA: 0x7594f1b058
	public Void .ctor() { }
}
```