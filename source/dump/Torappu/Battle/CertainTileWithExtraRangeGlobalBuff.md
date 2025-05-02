# CertainTileWithExtraRangeGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `ExtraRangeID _extraRangeID`

- `Boolean _excludeCenterTile`

- `String _centerTileEffect`


## Methods

- `Boolean _CheckExtraPosValid(Int32, Int32)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CertainTileWithExtraRangeGlobalBuff : CertainTileGlobalBuff
{
	private ExtraRangeID _extraRangeID; // 0x108
	private Boolean _excludeCenterTile; // 0x10c
	private String _centerTileEffect; // 0x110
	private List`1 m_centers; // 0x118
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SelectTiles; // 0x8
	private static DelegateBridge __Hotfix0__CheckExtraPosValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x4014734 VA: 0x759662c734
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x4014984 VA: 0x759662c984
	protected override List`1 SelectTiles(Boolean excludeBorderTiles) { }
	// RVA: 0x4014e88 VA: 0x759662ce88
	private Boolean _CheckExtraPosValid(Int32 row, Int32 col) { }
	// RVA: 0x4014f70 VA: 0x759662cf70
	public Void .ctor() { }
	// RVA: 0x4015030 VA: 0x759662d030
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x4015034 VA: 0x759662d034
	private List`1 <>xLuaBaseProxy_SelectTiles(Boolean P0) { }
}
```