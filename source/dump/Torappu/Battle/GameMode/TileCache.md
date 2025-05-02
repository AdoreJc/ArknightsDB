# TileCache

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `LevelData data`


## Methods

- `Void LoadData(LevelData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class TileCache : TileCacheBase
{
	private Dictionary`2 m_tileMap; // 0x10
	private LevelData data; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_CollectTile; // 0x8
	private static DelegateBridge __Hotfix0_GetTiles; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1d14560 VA: 0x759432c560
	public Void LoadData(LevelData levelData) { }
	// RVA: 0x1d0d210 VA: 0x7594325210
	public List`1 CollectTile(String key, Func`2 isValid, Boolean readOnly) { }
	// RVA: 0x1d1460c VA: 0x759432c60c
	public IEnumerable`1 GetTiles(String key, Func`2 isValid) { }
	// RVA: 0x1d14738 VA: 0x759432c738
	public Void .ctor() { }
}
```