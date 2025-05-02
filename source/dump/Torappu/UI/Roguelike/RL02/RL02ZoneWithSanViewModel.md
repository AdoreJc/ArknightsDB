# RL02ZoneWithSanViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String topicId`

- `String currZoneId`

- `String currZoneName`

- `Int32 sanValue`

- `String sanDesc`

- `SanEffectRank sanEffectRank`


## Methods

- `Boolean HasVariation()`

- `Boolean IsSanSystemValid()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ZoneWithSanViewModel : RoguelikeMenuCompViewModel
{
	public String topicId; // 0x18
	public String currZoneId; // 0x20
	public String currZoneName; // 0x28
	public List`1 variations; // 0x30
	public Int32 sanValue; // 0x38
	public String sanDesc; // 0x40
	public SanEffectRank sanEffectRank; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_HasVariation; // 0x8
	private static DelegateBridge __Hotfix0_IsSanSystemValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b7153c VA: 0x759518953c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b6e064 VA: 0x7595186064
	public Boolean HasVariation() { }
	// RVA: 0x2b6e77c VA: 0x759518677c
	public Boolean IsSanSystemValid() { }
	// RVA: 0x2b71ad4 VA: 0x7595189ad4
	public Void .ctor() { }
	// RVA: 0x2b71b98 VA: 0x7595189b98
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```