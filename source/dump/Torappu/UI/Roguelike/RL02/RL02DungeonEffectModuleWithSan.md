# RL02DungeonEffectModuleWithSan

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RL02DungeonSanEffect _effect`

- `RL02DungeonSanEffect m_effect`


## Methods

- `Void _RefreshEffect()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnReloadDungeon()`

- `Void <>xLuaBaseProxy_OnStateChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02DungeonEffectModuleWithSan : RoguelikeDungeonModule
{
	private RL02DungeonSanEffect _effect; // 0x28
	private RL02DungeonSanEffect m_effect; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnReloadDungeon; // 0x8
	private static DelegateBridge __Hotfix0__RefreshEffect; // 0x10
	private static DelegateBridge __Hotfix0_OnStateChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b60afc VA: 0x7595178afc
	protected override Void OnCreate() { }
	// RVA: 0x2b60e80 VA: 0x7595178e80
	protected override Void OnReloadDungeon() { }
	// RVA: 0x2b60b64 VA: 0x7595178b64
	private Void _RefreshEffect() { }
	// RVA: 0x2b60fbc VA: 0x7595178fbc
	protected override Void OnStateChanged() { }
	// RVA: 0x2b61094 VA: 0x7595179094
	public Void .ctor() { }
	// RVA: 0x2b61104 VA: 0x7595179104
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2b6110c VA: 0x759517910c
	private Void <>xLuaBaseProxy_OnReloadDungeon() { }
	// RVA: 0x2b61114 VA: 0x7595179114
	private Void <>xLuaBaseProxy_OnStateChanged() { }
}
```