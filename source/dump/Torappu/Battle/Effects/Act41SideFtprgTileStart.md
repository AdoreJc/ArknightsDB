# Act41SideFtprgTileStart

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Int32 _modeToFinish`

- `Tile m_tile`


## Methods

- `Void Update()`

- `Void OnLocatedCharacterUpdate(Character)`

- `Void OnEntityEnter(Entity)`

- `Void OnEntityLeave(Entity)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class Act41SideFtprgTileStart : Behaviour, ITileListener
{
	private List`1 _enemyKeyToBind; // 0x20
	private Int32 _modeToFinish; // 0x28
	private Tile m_tile; // 0x30
	private ObjectPtr`1 m_bindedEnemy; // 0x38
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x18
	private static DelegateBridge __Hotfix0_OnEntityEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnEntityLeave; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x20092dc VA: 0x75946212dc
	public override Void OnPlay() { }
	// RVA: 0x20093e8 VA: 0x75946213e8
	public override Void OnFinish() { }
	// RVA: 0x2009510 VA: 0x7594621510
	private Void Update() { }
	// RVA: 0x2009610 VA: 0x7594621610
	public Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x2009688 VA: 0x7594621688
	public Void OnEntityEnter(Entity entity) { }
	// RVA: 0x2009858 VA: 0x7594621858
	public Void OnEntityLeave(Entity entity) { }
	// RVA: 0x20098d0 VA: 0x75946218d0
	public Void .ctor() { }
	// RVA: 0x2009948 VA: 0x7594621948
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2009950 VA: 0x7594621950
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```