# FireworkNpcDialogModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `String <desc>k__BackingField`

- `NpcDialogType <dialogType>k__BackingField`

- `String <npcSpineName>k__BackingField`


## Properties

- `String desc`

- `NpcDialogType dialogType`

- `String npcSpineName`


## Methods

- `String get_desc()`

- `Void set_desc(String)`

- `NpcDialogType get_dialogType()`

- `Void set_dialogType(NpcDialogType)`

- `String get_npcSpineName()`

- `Void set_npcSpineName(String)`

- `Void LoadData(Act38SideNpcDialogData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkNpcDialogModel : IHotfixable
{
	private String <desc>k__BackingField; // 0x10
	private NpcDialogType <dialogType>k__BackingField; // 0x18
	private String <npcSpineName>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_desc; // 0x0
	private static DelegateBridge __Hotfix0_set_desc; // 0x8
	private static DelegateBridge __Hotfix0_get_dialogType; // 0x10
	private static DelegateBridge __Hotfix0_set_dialogType; // 0x18
	private static DelegateBridge __Hotfix0_get_npcSpineName; // 0x20
	private static DelegateBridge __Hotfix0_set_npcSpineName; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String desc { get; set; }
	public NpcDialogType dialogType { get; set; }
	public String npcSpineName { get; set; }

	// RVA: 0x28f89d4 VA: 0x7594f109d4
	public String get_desc() { }
	// RVA: 0x28f8a3c VA: 0x7594f10a3c
	private Void set_desc(String value) { }
	// RVA: 0x28f8ac0 VA: 0x7594f10ac0
	public NpcDialogType get_dialogType() { }
	// RVA: 0x28f8b28 VA: 0x7594f10b28
	private Void set_dialogType(NpcDialogType value) { }
	// RVA: 0x28f8ba4 VA: 0x7594f10ba4
	public String get_npcSpineName() { }
	// RVA: 0x28f8c0c VA: 0x7594f10c0c
	private Void set_npcSpineName(String value) { }
	// RVA: 0x28f8c90 VA: 0x7594f10c90
	public Void LoadData(Act38SideNpcDialogData dialogData) { }
	// RVA: 0x28f8d30 VA: 0x7594f10d30
	public Void .ctor() { }
}
```