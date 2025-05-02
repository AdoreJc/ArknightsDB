# CertainTileGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `String m_tileKey`


## Methods

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CertainTileGlobalBuff : AbstractBindingTileGlobalBuff
{
	private String m_tileKey; // 0x100
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SelectTiles; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x40143ec VA: 0x759662c3ec
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x40144b4 VA: 0x759662c4b4
	protected override List`1 SelectTiles(Boolean excludeBorderTiles) { }
	// RVA: 0x40146c4 VA: 0x759662c6c4
	public Void .ctor() { }
	// RVA: 0x4014730 VA: 0x759662c730
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
}
```