# RL04ShopLineupRecycleAddonPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _emptyRecyclePanel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ShopLineupRecycleAddonPlugin : RoguelikeShopLineupAddonPlugin
{
	private GameObject _emptyRecyclePanel; // 0x18
	private static DelegateBridge __Hotfix0_get_layer; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override LineupLayer layer { get; }

	// RVA: 0x2b54f64 VA: 0x759516cf64
	public override LineupLayer get_layer() { }
	// RVA: 0x2b54fcc VA: 0x759516cfcc
	public override Void Render(RoguelikeGameShopViewModel shopViewModel) { }
	// RVA: 0x2b550e4 VA: 0x759516d0e4
	public Void .ctor() { }
}
```