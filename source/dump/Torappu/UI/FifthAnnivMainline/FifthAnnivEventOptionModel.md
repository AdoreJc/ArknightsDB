# FifthAnnivEventOptionModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Single <successRate>k__BackingField`

- `Int32 <choiceIdx>k__BackingField`

- `String <successDesc>k__BackingField`

- `String <failDesc>k__BackingField`


## Properties

- `Single successRate`

- `Int32 choiceIdx`

- `String successDesc`

- `String failDesc`


## Methods

- `Single get_successRate()`

- `Void set_successRate(Single)`

- `Int32 get_choiceIdx()`

- `Void set_choiceIdx(Int32)`

- `String get_successDesc()`

- `Void set_successDesc(String)`

- `String get_failDesc()`

- `Void set_failDesc(String)`

- `Void LoadData(Int32, PlayerExploreGameContextNodeEventChoice)`

- `Void _InitAbilities(Dictionary`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivEventOptionModel : FifthAnnivExploreOptionModel
{
	private Dictionary`2 m_abilitiesCond; // 0x28
	private Dictionary`2 m_abilitiesDelta; // 0x30
	private Single <successRate>k__BackingField; // 0x38
	private Int32 <choiceIdx>k__BackingField; // 0x3c
	private String <successDesc>k__BackingField; // 0x40
	private String <failDesc>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_successRate; // 0x0
	private static DelegateBridge __Hotfix0_set_successRate; // 0x8
	private static DelegateBridge __Hotfix0_get_choiceIdx; // 0x10
	private static DelegateBridge __Hotfix0_set_choiceIdx; // 0x18
	private static DelegateBridge __Hotfix0_get_successDesc; // 0x20
	private static DelegateBridge __Hotfix0_set_successDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_failDesc; // 0x30
	private static DelegateBridge __Hotfix0_set_failDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_abilitiesCond; // 0x40
	private static DelegateBridge __Hotfix0_get_abilitiesDelta; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0__InitAbilities; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Single successRate { get; set; }
	public Int32 choiceIdx { get; set; }
	public String successDesc { get; set; }
	public String failDesc { get; set; }
	public Dictionary`2 abilitiesCond { get; }
	public Dictionary`2 abilitiesDelta { get; }

	// RVA: 0x290fd00 VA: 0x7594f27d00
	public Single get_successRate() { }
	// RVA: 0x290fd68 VA: 0x7594f27d68
	private Void set_successRate(Single value) { }
	// RVA: 0x290fde4 VA: 0x7594f27de4
	public Int32 get_choiceIdx() { }
	// RVA: 0x290fe4c VA: 0x7594f27e4c
	private Void set_choiceIdx(Int32 value) { }
	// RVA: 0x290d000 VA: 0x7594f25000
	public String get_successDesc() { }
	// RVA: 0x290fec8 VA: 0x7594f27ec8
	private Void set_successDesc(String value) { }
	// RVA: 0x290cf98 VA: 0x7594f24f98
	public String get_failDesc() { }
	// RVA: 0x290ff4c VA: 0x7594f27f4c
	private Void set_failDesc(String value) { }
	// RVA: 0x290ffd0 VA: 0x7594f27fd0
	public Dictionary`2 get_abilitiesCond() { }
	// RVA: 0x2910038 VA: 0x7594f28038
	public Dictionary`2 get_abilitiesDelta() { }
	// RVA: 0x290f7ac VA: 0x7594f277ac
	public Void LoadData(Int32 index, PlayerExploreGameContextNodeEventChoice playerChoice) { }
	// RVA: 0x29100a0 VA: 0x7594f280a0
	private Void _InitAbilities(Dictionary`2 playerDict, Dictionary`2 memDict) { }
	// RVA: 0x290f6b8 VA: 0x7594f276b8
	public Void .ctor() { }
}
```