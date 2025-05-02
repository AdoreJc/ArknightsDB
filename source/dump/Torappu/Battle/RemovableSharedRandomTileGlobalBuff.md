# RemovableSharedRandomTileGlobalBuff

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean TryRemoveBindingTiles(List`1)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Boolean <>xLuaBaseProxy_TryAddBindingTiles(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Boolean <>xLuaBaseProxy_FilterTile(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RemovableSharedRandomTileGlobalBuff : SharedRandomTileGlobalBuff
{
	private static Dictionary`2 createCnt; // 0x0
	private static Dictionary`2 effectHolder; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_ClearAllStaticVariables; // 0x18
	private static DelegateBridge __Hotfix0_TryAddBindingTiles; // 0x20
	private static DelegateBridge __Hotfix0_TryRemoveBindingTiles; // 0x28
	private static DelegateBridge __Hotfix0_OnTick; // 0x30
	private static DelegateBridge __Hotfix0_FilterTile; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x401ae14 VA: 0x7596632e14
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x401b058 VA: 0x7596633058
	public static Void ClearAllStaticVariables() { }
	// RVA: 0x401b178 VA: 0x7596633178
	public override Boolean TryAddBindingTiles(List`1 tiles) { }
	// RVA: 0x401b83c VA: 0x759663383c
	public Boolean TryRemoveBindingTiles(List`1 tiles) { }
	// RVA: 0x401bd48 VA: 0x7596633d48
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x401c304 VA: 0x7596634304
	protected override Boolean FilterTile(Tile tile) { }
	// RVA: 0x401c390 VA: 0x7596634390
	public Void .ctor() { }
	// RVA: 0x401c4f8 VA: 0x75966344f8
	private static Void .cctor() { }
	// RVA: 0x401c5e4 VA: 0x75966345e4
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x401c5e8 VA: 0x75966345e8
	private Boolean <>xLuaBaseProxy_TryAddBindingTiles(List`1 P0) { }
	// RVA: 0x401ca84 VA: 0x7596634a84
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x401ca88 VA: 0x7596634a88
	private Boolean <>xLuaBaseProxy_FilterTile(Tile P0) { }
}
```