# RL03DungeonEffectModuleWithChaosAndVision

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03DungeonChaosAndVisionEffect _chaosAndVisionEffect`

- `RL03DungeonChaosAndVisionEffect m_chaosAndVisionEffect`


## Methods

- `Void _RefreshEffect()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnReloadDungeon()`

- `Void <>xLuaBaseProxy_OnStateChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03DungeonEffectModuleWithChaosAndVision : RoguelikeDungeonModule
{
	private const Int32 DEFAULT_VISION_NUM; // 0x0
	private RL03DungeonChaosAndVisionEffect _chaosAndVisionEffect; // 0x28
	private RL03DungeonChaosAndVisionEffect m_chaosAndVisionEffect; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnReloadDungeon; // 0x8
	private static DelegateBridge __Hotfix0_OnStateChanged; // 0x10
	private static DelegateBridge __Hotfix0__RefreshEffect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b97920 VA: 0x75951af920
	protected override Void OnCreate() { }
	// RVA: 0x2b97dbc VA: 0x75951afdbc
	protected override Void OnReloadDungeon() { }
	// RVA: 0x2b97e24 VA: 0x75951afe24
	protected override Void OnStateChanged() { }
	// RVA: 0x2b97988 VA: 0x75951af988
	private Void _RefreshEffect() { }
	// RVA: 0x2b97f00 VA: 0x75951aff00
	public Void .ctor() { }
	// RVA: 0x2b97f70 VA: 0x75951aff70
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2b97f78 VA: 0x75951aff78
	private Void <>xLuaBaseProxy_OnReloadDungeon() { }
	// RVA: 0x2b97f80 VA: 0x75951aff80
	private Void <>xLuaBaseProxy_OnStateChanged() { }
}
```