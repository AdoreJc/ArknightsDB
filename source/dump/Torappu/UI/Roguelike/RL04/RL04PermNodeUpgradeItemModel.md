# RL04PermNodeUpgradeItemModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 <nodeLevel>k__BackingField`

- `String <nodeName>k__BackingField`


## Properties

- `Int32 nodeLevel`

- `String nodeName`


## Methods

- `Int32 get_nodeLevel()`

- `Void set_nodeLevel(Int32)`

- `String get_nodeName()`

- `Void set_nodeName(String)`

- `Void LoadData(RoguelikePermNodeUpgradeItemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04PermNodeUpgradeItemModel : RL04NodeUpgradeItemModel
{
	private Int32 <nodeLevel>k__BackingField; // 0x34
	private String <nodeName>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_nodeLevel; // 0x0
	private static DelegateBridge __Hotfix0_set_nodeLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_nodeName; // 0x10
	private static DelegateBridge __Hotfix0_set_nodeName; // 0x18
	private static DelegateBridge __Hotfix0_get_isTemp; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 nodeLevel { get; set; }
	public String nodeName { get; set; }
	public override Boolean isTemp { get; }

	// RVA: 0x2b3361c VA: 0x759514b61c
	public Int32 get_nodeLevel() { }
	// RVA: 0x2b33d08 VA: 0x759514bd08
	private Void set_nodeLevel(Int32 value) { }
	// RVA: 0x2b33d84 VA: 0x759514bd84
	public String get_nodeName() { }
	// RVA: 0x2b33dec VA: 0x759514bdec
	private Void set_nodeName(String value) { }
	// RVA: 0x2b33e70 VA: 0x759514be70
	public override Boolean get_isTemp() { }
	// RVA: 0x2b33058 VA: 0x759514b058
	public Void LoadData(RoguelikePermNodeUpgradeItemData permItemData) { }
	// RVA: 0x2b32fec VA: 0x759514afec
	public Void .ctor() { }
}
```