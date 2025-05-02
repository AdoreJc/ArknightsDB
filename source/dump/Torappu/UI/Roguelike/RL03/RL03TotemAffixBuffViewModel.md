# RL03TotemAffixBuffViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String affixId`

- `String affixName`

- `String affixDesc`

- `String affixCombinedDesc`


## Methods

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemAffixBuffViewModel : IHotfixable
{
	public String affixId; // 0x10
	public String affixName; // 0x18
	public String affixDesc; // 0x20
	public String affixCombinedDesc; // 0x28
	private static DelegateBridge __Hotfix0_Create; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b96610 VA: 0x75951ae610
	public static RL03TotemAffixBuffViewModel Create(String topicId, String id) { }
	// RVA: 0x2b96838 VA: 0x75951ae838
	public Void LoadData(String topicId, String id) { }
	// RVA: 0x2b967c8 VA: 0x75951ae7c8
	public Void .ctor() { }
}
```