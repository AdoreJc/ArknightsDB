# RandomTileWithExtraRangeGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `ExtraRangeID _extraRangeID`

- `String _centerTileEffect`

- `GridPosition m_Center`


## Methods

- `Boolean _CheckExtraPosValid(Int32, Int32)`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RandomTileWithExtraRangeGlobalBuff : RandomTileGlobalBuff
{
	private ExtraRangeID _extraRangeID; // 0x108
	private String _centerTileEffect; // 0x110
	private GridPosition m_Center; // 0x118
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SelectTiles; // 0x8
	private static DelegateBridge __Hotfix0__CheckExtraPosValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x401a904 VA: 0x7596632904
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x401aa14 VA: 0x7596632a14
	protected override List`1 SelectTiles(Boolean excludeBorderTiles) { }
	// RVA: 0x401acb4 VA: 0x7596632cb4
	private Boolean _CheckExtraPosValid(Int32 row, Int32 col) { }
	// RVA: 0x401ad9c VA: 0x7596632d9c
	public Void .ctor() { }
	// RVA: 0x401ae08 VA: 0x7596632e08
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x401ae0c VA: 0x7596632e0c
	private List`1 <>xLuaBaseProxy_SelectTiles(Boolean P0) { }
}
```