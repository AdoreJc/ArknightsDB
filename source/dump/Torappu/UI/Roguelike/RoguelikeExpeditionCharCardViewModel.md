# RoguelikeExpeditionCharCardViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String <charInstId>k__BackingField`

- `String <charId>k__BackingField`

- `String <charName>k__BackingField`

- `String <skinId>k__BackingField`

- `Int32 <instId>k__BackingField`

- `EvolvePhase <evolvePhase>k__BackingField`

- `EvolvePhase <maxEvolvePhase>k__BackingField`

- `Int32 <upgradePhase>k__BackingField`


## Properties

- `String charInstId`

- `String charId`

- `String charName`

- `String skinId`

- `Int32 instId`

- `EvolvePhase evolvePhase`

- `EvolvePhase maxEvolvePhase`

- `Int32 upgradePhase`


## Methods

- `String get_charInstId()`

- `Void set_charInstId(String)`

- `String get_charId()`

- `Void set_charId(String)`

- `String get_charName()`

- `Void set_charName(String)`

- `String get_skinId()`

- `Void set_skinId(String)`

- `Int32 get_instId()`

- `Void set_instId(Int32)`

- `EvolvePhase get_evolvePhase()`

- `Void set_evolvePhase(EvolvePhase)`

- `EvolvePhase get_maxEvolvePhase()`

- `Void set_maxEvolvePhase(EvolvePhase)`

- `Int32 get_upgradePhase()`

- `Void set_upgradePhase(Int32)`

- `Void FillViewModel(String, Char)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionCharCardViewModel : IHotfixable
{
	private String <charInstId>k__BackingField; // 0x10
	private String <charId>k__BackingField; // 0x18
	private String <charName>k__BackingField; // 0x20
	private String <skinId>k__BackingField; // 0x28
	private Int32 <instId>k__BackingField; // 0x30
	private EvolvePhase <evolvePhase>k__BackingField; // 0x34
	private EvolvePhase <maxEvolvePhase>k__BackingField; // 0x38
	private Int32 <upgradePhase>k__BackingField; // 0x3c
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x0
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x8
	private static DelegateBridge __Hotfix0_get_charId; // 0x10
	private static DelegateBridge __Hotfix0_set_charId; // 0x18
	private static DelegateBridge __Hotfix0_get_charName; // 0x20
	private static DelegateBridge __Hotfix0_set_charName; // 0x28
	private static DelegateBridge __Hotfix0_get_skinId; // 0x30
	private static DelegateBridge __Hotfix0_set_skinId; // 0x38
	private static DelegateBridge __Hotfix0_get_instId; // 0x40
	private static DelegateBridge __Hotfix0_set_instId; // 0x48
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x50
	private static DelegateBridge __Hotfix0_set_evolvePhase; // 0x58
	private static DelegateBridge __Hotfix0_get_maxEvolvePhase; // 0x60
	private static DelegateBridge __Hotfix0_set_maxEvolvePhase; // 0x68
	private static DelegateBridge __Hotfix0_get_upgradePhase; // 0x70
	private static DelegateBridge __Hotfix0_set_upgradePhase; // 0x78
	private static DelegateBridge __Hotfix0_FillViewModel; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String charInstId { get; set; }
	public String charId { get; set; }
	public String charName { get; set; }
	public String skinId { get; set; }
	public Int32 instId { get; set; }
	public EvolvePhase evolvePhase { get; set; }
	public EvolvePhase maxEvolvePhase { get; set; }
	public Int32 upgradePhase { get; set; }

	// RVA: 0x2a31a58 VA: 0x7595049a58
	public String get_charInstId() { }
	// RVA: 0x2a31ac0 VA: 0x7595049ac0
	private Void set_charInstId(String value) { }
	// RVA: 0x2a31b44 VA: 0x7595049b44
	public String get_charId() { }
	// RVA: 0x2a31bac VA: 0x7595049bac
	private Void set_charId(String value) { }
	// RVA: 0x2a31c30 VA: 0x7595049c30
	public String get_charName() { }
	// RVA: 0x2a31c98 VA: 0x7595049c98
	private Void set_charName(String value) { }
	// RVA: 0x2a31d1c VA: 0x7595049d1c
	public String get_skinId() { }
	// RVA: 0x2a31d84 VA: 0x7595049d84
	private Void set_skinId(String value) { }
	// RVA: 0x2a31e08 VA: 0x7595049e08
	public Int32 get_instId() { }
	// RVA: 0x2a31e70 VA: 0x7595049e70
	private Void set_instId(Int32 value) { }
	// RVA: 0x2a31eec VA: 0x7595049eec
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2a31f54 VA: 0x7595049f54
	private Void set_evolvePhase(EvolvePhase value) { }
	// RVA: 0x2a31fd0 VA: 0x7595049fd0
	public EvolvePhase get_maxEvolvePhase() { }
	// RVA: 0x2a32038 VA: 0x759504a038
	private Void set_maxEvolvePhase(EvolvePhase value) { }
	// RVA: 0x2a320b4 VA: 0x759504a0b4
	public Int32 get_upgradePhase() { }
	// RVA: 0x2a3211c VA: 0x759504a11c
	private Void set_upgradePhase(Int32 value) { }
	// RVA: 0x2a32198 VA: 0x759504a198
	public Void FillViewModel(String charInstId, Char playerChar) { }
	// RVA: 0x2a323b0 VA: 0x759504a3b0
	public Void .ctor() { }
}
```