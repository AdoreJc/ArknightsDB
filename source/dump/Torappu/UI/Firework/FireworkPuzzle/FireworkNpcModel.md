# FireworkNpcModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `String <idleSpineName>k__BackingField`


## Properties

- `String idleSpineName`


## Methods

- `String get_idleSpineName()`

- `Void set_idleSpineName(String)`

- `Void LoadData(String)`

- `FireworkNpcDialogModel RandomDialogByType(NpcDialogType, FireworkNpcDialogModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkNpcModel : IHotfixable
{
	private Dictionary`2 m_dialogDict; // 0x10
	private String <idleSpineName>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_idleSpineName; // 0x0
	private static DelegateBridge __Hotfix0_set_idleSpineName; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_RandomDialogByType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String idleSpineName { get; set; }

	// RVA: 0x28f8da0 VA: 0x7594f10da0
	public String get_idleSpineName() { }
	// RVA: 0x28f8e08 VA: 0x7594f10e08
	private Void set_idleSpineName(String value) { }
	// RVA: 0x28f8e8c VA: 0x7594f10e8c
	public Void LoadData(String actId) { }
	// RVA: 0x28f9234 VA: 0x7594f11234
	public FireworkNpcDialogModel RandomDialogByType(NpcDialogType dialogType, FireworkNpcDialogModel lastDialog) { }
	// RVA: 0x28f934c VA: 0x7594f1134c
	public Void .ctor() { }
}
```