# InteractSlot

**Namespace:** ` `


## Fields

- `VCharacter m_character`

- `VFurnitureBridge <owner>k__BackingField`

- `Options <options>k__BackingField`

- `Single <weightValue>k__BackingField`


## Properties

- `VFurnitureBridge owner`

- `Options options`

- `Single weightValue`

- `Boolean isEmpty`

- `VCharacter character`

- `String displayName`


## Methods

- `VFurnitureBridge get_owner()`

- `Void set_owner(VFurnitureBridge)`

- `Options get_options()`

- `Void set_options(Options)`

- `Single get_weightValue()`

- `Void set_weightValue(Single)`

- `Boolean get_isEmpty()`

- `VCharacter get_character()`

- `String get_displayName()`

- `Boolean Verify(VCharacter)`

- `Boolean Register(VCharacter)`

- `Boolean Unregister(VCharacter)`

- `Void MakeEmpty()`

- `Boolean CheckReached(Vector2, Single)`

- `Single GetNearestDist(Vector2)`

- `Boolean CheckInteractableWith(VCharacter)`

- `Boolean IsVCharInteractable(VCharacter)`

- `Boolean _CheckSkinValid(VCharacter)`

- `Void OnVCharInteract(VCharacter)`

- `Void OnInteractableChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InteractSlot : IItemWithWeight, IVCharInteractable, IHotfixable
{
	private const Single SLOT_REACH_DISTANCE; // 0x0
	private VCharacter m_character; // 0x10
	private VFurnitureBridge <owner>k__BackingField; // 0x18
	private Options <options>k__BackingField; // 0x20
	private Single <weightValue>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_owner; // 0x0
	private static DelegateBridge __Hotfix0_set_owner; // 0x8
	private static DelegateBridge __Hotfix0_get_options; // 0x10
	private static DelegateBridge __Hotfix0_set_options; // 0x18
	private static DelegateBridge __Hotfix0_get_weightValue; // 0x20
	private static DelegateBridge __Hotfix0_set_weightValue; // 0x28
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x30
	private static DelegateBridge __Hotfix0_get_character; // 0x38
	private static DelegateBridge __Hotfix0_get_displayName; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0_Verify; // 0x50
	private static DelegateBridge __Hotfix0_Register; // 0x58
	private static DelegateBridge __Hotfix0_Unregister; // 0x60
	private static DelegateBridge __Hotfix0_MakeEmpty; // 0x68
	private static DelegateBridge __Hotfix0_CheckReached; // 0x70
	private static DelegateBridge __Hotfix0_GetNearestDist; // 0x78
	private static DelegateBridge __Hotfix0_CheckInteractableWith; // 0x80
	private static DelegateBridge __Hotfix0_IsVCharInteractable; // 0x88
	private static DelegateBridge __Hotfix0__CheckSkinValid; // 0x90
	private static DelegateBridge __Hotfix0_OnVCharInteract; // 0x98
	private static DelegateBridge __Hotfix0_OnInteractableChanged; // 0xa0

	public VFurnitureBridge owner { get; set; }
	public Options options { get; set; }
	public Single weightValue { get; set; }
	public Boolean isEmpty { get; }
	public VCharacter character { get; }
	public String displayName { get; }

	// RVA: 0x384e650 VA: 0x7595e66650
	public VFurnitureBridge get_owner() { }
	// RVA: 0x3854798 VA: 0x7595e6c798
	private Void set_owner(VFurnitureBridge value) { }
	// RVA: 0x384c7c4 VA: 0x7595e647c4
	public Options get_options() { }
	// RVA: 0x385481c VA: 0x7595e6c81c
	private Void set_options(Options value) { }
	// RVA: 0x38548dc VA: 0x7595e6c8dc
	public Single get_weightValue() { }
	// RVA: 0x3854944 VA: 0x7595e6c944
	public Void set_weightValue(Single value) { }
	// RVA: 0x384e35c VA: 0x7595e6635c
	public Boolean get_isEmpty() { }
	// RVA: 0x384e3f4 VA: 0x7595e663f4
	public VCharacter get_character() { }
	// RVA: 0x38549c0 VA: 0x7595e6c9c0
	public String get_displayName() { }
	// RVA: 0x38540a4 VA: 0x7595e6c0a4
	public Void .ctor(VFurnitureBridge owner, Options options) { }
	// RVA: 0x3848bc4 VA: 0x7595e60bc4
	public Boolean Verify(VCharacter character) { }
	// RVA: 0x384e540 VA: 0x7595e66540
	public Boolean Register(VCharacter character) { }
	// RVA: 0x384e45c VA: 0x7595e6645c
	public Boolean Unregister(VCharacter character) { }
	// RVA: 0x3853fc8 VA: 0x7595e6bfc8
	public Void MakeEmpty() { }
	// RVA: 0x384ddd4 VA: 0x7595e65dd4
	public Boolean CheckReached(Vector2 pos, Single dist) { }
	// RVA: 0x385453c VA: 0x7595e6c53c
	public Single GetNearestDist(Vector2 pos) { }
	// RVA: 0x384d800 VA: 0x7595e65800
	public Boolean CheckInteractableWith(VCharacter character) { }
	// RVA: 0x3854270 VA: 0x7595e6c270
	public Boolean IsVCharInteractable(VCharacter character) { }
	// RVA: 0x3854a5c VA: 0x7595e6ca5c
	public Boolean _CheckSkinValid(VCharacter targetChar) { }
	// RVA: 0x3854b38 VA: 0x7595e6cb38
	public Void OnVCharInteract(VCharacter character) { }
	// RVA: 0x3854bf0 VA: 0x7595e6cbf0
	public Void OnInteractableChanged(Boolean interactable) { }
}
```