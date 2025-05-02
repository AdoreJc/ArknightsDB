# RandomTileGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `BuildableType _buildableType`

- `RandomWeightType _weightType`


## Methods

- `Boolean _CheckValidMap()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RandomTileGlobalBuff : AbstractBindingTileGlobalBuff
{
	protected BuildableType _buildableType; // 0x100
	private RandomWeightType _weightType; // 0x104
	private static DelegateBridge __Hotfix0_SelectTiles; // 0x0
	private static DelegateBridge __Hotfix0_TryAddBindingTiles; // 0x8
	private static DelegateBridge __Hotfix0__SelectTilesByManhattanDistanceFromCenter; // 0x10
	private static DelegateBridge __Hotfix0__SelectTilesByEqualWeight; // 0x18
	private static DelegateBridge __Hotfix0__CheckValidMap; // 0x20
	private static DelegateBridge __Hotfix0_FilterTile; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x40199fc VA: 0x75966319fc
	protected override List`1 SelectTiles(Boolean excludeBorderTiles) { }
	// RVA: 0x401a36c VA: 0x759663236c
	public virtual Boolean TryAddBindingTiles(List`1 tiles) { }
	// RVA: 0x4019afc VA: 0x7596631afc
	private List`1 _SelectTilesByManhattanDistanceFromCenter(Boolean excludeBorderTiles) { }
	// RVA: 0x401a04c VA: 0x759663204c
	private List`1 _SelectTilesByEqualWeight(Boolean excludeBorderTiles) { }
	// RVA: 0x401a734 VA: 0x7596632734
	private Boolean _CheckValidMap() { }
	// RVA: 0x401a7f0 VA: 0x75966327f0
	protected virtual Boolean FilterTile(Tile tile) { }
	// RVA: 0x401a888 VA: 0x7596632888
	public Void .ctor() { }
}
```