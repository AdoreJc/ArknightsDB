# VFurnitureManager

**Namespace:** `Torappu.Building.Vault`


## Properties

- `Boolean isEmpty`


## Methods

- `Boolean get_isEmpty()`

- `Void Init(IList`1)`

- `Void Add(VFurnitureBridge)`

- `Void ClearAll()`

- `Boolean PickRandomSlot(VCharacter, out, Func`3)`

- `Boolean PickRandomSlot(VCharacter, out, Func`3, IList`1)`

- `Boolean PickRandomSlotWithWeight(VCharacter, out, Func`3)`

- `Boolean _ValidSlot(VCharacter, InteractSlot)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VFurnitureManager : IHotfixable
{
	private static List`1 s_sharedSlotList; // 0x0
	private List`1 m_furnitures; // 0x10
	private List`1 m_slots; // 0x18
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x8
	private static DelegateBridge __Hotfix0_get_furnitures; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Add; // 0x20
	private static DelegateBridge __Hotfix0_ClearAll; // 0x28
	private static DelegateBridge __Hotfix0_PickRandomSlot; // 0x30
	private static DelegateBridge __Hotfix1_PickRandomSlot; // 0x38
	private static DelegateBridge __Hotfix0_PickRandomSlotWithWeight; // 0x40
	private static DelegateBridge __Hotfix0__ValidSlot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean isEmpty { get; }
	public List`1 furnitures { get; }

	// RVA: 0x38504c0 VA: 0x7595e684c0
	public Boolean get_isEmpty() { }
	// RVA: 0x3854e04 VA: 0x7595e6ce04
	public List`1 get_furnitures() { }
	// RVA: 0x3854e7c VA: 0x7595e6ce7c
	public Void Init(IList`1 furnitures) { }
	// RVA: 0x38550dc VA: 0x7595e6d0dc
	public Void Add(VFurnitureBridge furniture) { }
	// RVA: 0x3854fec VA: 0x7595e6cfec
	public Void ClearAll() { }
	// RVA: 0x3850558 VA: 0x7595e68558
	public Boolean PickRandomSlot(VCharacter character, out InteractSlot slot, Func`3 validator) { }
	// RVA: 0x385524c VA: 0x7595e6d24c
	public Boolean PickRandomSlot(VCharacter character, out InteractSlot slot, Func`3 validator, IList`1 slots) { }
	// RVA: 0x38556bc VA: 0x7595e6d6bc
	public Boolean PickRandomSlotWithWeight(VCharacter character, out InteractSlot slot, Func`3 weightGetter) { }
	// RVA: 0x38555c4 VA: 0x7595e6d5c4
	private Boolean _ValidSlot(VCharacter targetChar, InteractSlot slot) { }
	// RVA: 0x38559d0 VA: 0x7595e6d9d0
	public Void .ctor() { }
	// RVA: 0x3855af4 VA: 0x7595e6daf4
	private static Void .cctor() { }
}
```