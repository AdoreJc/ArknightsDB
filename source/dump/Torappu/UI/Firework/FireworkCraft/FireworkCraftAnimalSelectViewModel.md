# FireworkCraftAnimalSelectViewModel

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `String selectedAnimalId`

- `String equipedAnimalId`

- `Int32 loadSeqNum`


## Methods

- `Void LoadData()`

- `Void RefreshEquipedAnimalId()`

- `Boolean SetSelectedAnimalId(String)`

- `AnimalStatus GetAnimalStatus(FireworkCraftAnimalViewModel)`

- `FireworkCraftAnimalViewModel GetAnimalViewModel(String)`

- `FireworkCraftAnimalViewModel GetSelectedAnimalViewModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAnimalSelectViewModel : IHotfixable
{
	public ListDict`2 animalViewModels; // 0x10
	public String selectedAnimalId; // 0x18
	public String equipedAnimalId; // 0x20
	public Int32 loadSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshEquipedAnimalId; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedAnimalId; // 0x10
	private static DelegateBridge __Hotfix0_GetAnimalStatus; // 0x18
	private static DelegateBridge __Hotfix0_GetAnimalViewModel; // 0x20
	private static DelegateBridge __Hotfix0_GetSelectedAnimalViewModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x29010c4 VA: 0x7594f190c4
	public Void LoadData() { }
	// RVA: 0x29021c4 VA: 0x7594f1a1c4
	public Void RefreshEquipedAnimalId() { }
	// RVA: 0x2901ec8 VA: 0x7594f19ec8
	public Boolean SetSelectedAnimalId(String animalId) { }
	// RVA: 0x2900b2c VA: 0x7594f18b2c
	public AnimalStatus GetAnimalStatus(FireworkCraftAnimalViewModel viewModel) { }
	// RVA: 0x2902280 VA: 0x7594f1a280
	public FireworkCraftAnimalViewModel GetAnimalViewModel(String animalId) { }
	// RVA: 0x290200c VA: 0x7594f1a00c
	public FireworkCraftAnimalViewModel GetSelectedAnimalViewModel() { }
	// RVA: 0x29030c8 VA: 0x7594f1b0c8
	public Void .ctor() { }
}
```