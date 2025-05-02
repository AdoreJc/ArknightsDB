# SquadHomePlugin

**Namespace:** `Torappu.UI.Squad`


## Fields

- `PluginInputParams m_param`

- `SquadHomePluginView m_view`


## Methods

- `Void BindGroupController(GroupControllerBindings)`

- `Void OnSquadHomeStateEnter()`

- `Void OnSquadHomeStateResume()`

- `Void OnPluginLoad()`

- `SquadHomeStartBattleServicePluginBase GetStartBattleServicePlugin()`

- `SquadHomeFinishBattleServicePluginBase GetFinishBattleServicePlugin()`

- `BattleActivityMeta GetOverrideActMeta(String)`

- `Void Dispose()`

- `Boolean _CheckIfDisposed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadHomePlugin : IHotfixable, IDisposable
{
	private PluginInputParams m_param; // 0x10
	private SquadHomePluginView m_view; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_BindGroupController; // 0x8
	private static DelegateBridge __Hotfix0_OnSquadHomeStateEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnSquadHomeStateResume; // 0x18
	private static DelegateBridge __Hotfix0_OnPluginLoad; // 0x20
	private static DelegateBridge __Hotfix0_GetStartBattleServicePlugin; // 0x28
	private static DelegateBridge __Hotfix0_GetFinishBattleServicePlugin; // 0x30
	private static DelegateBridge __Hotfix0_GetOverrideActMeta; // 0x38
	private static DelegateBridge __Hotfix0_Dispose; // 0x40
	private static DelegateBridge __Hotfix0__CheckIfDisposed; // 0x48


	// RVA: 0x23cbc60 VA: 0x75949e3c60
	public Void .ctor(PluginInputParams param, SquadHomePluginView view) { }
	// RVA: 0x23cae20 VA: 0x75949e2e20
	public Void BindGroupController(GroupControllerBindings bindings) { }
	// RVA: 0x23cbe6c VA: 0x75949e3e6c
	public Void OnSquadHomeStateEnter() { }
	// RVA: 0x23cbf00 VA: 0x75949e3f00
	public Void OnSquadHomeStateResume() { }
	// RVA: 0x23cbf94 VA: 0x75949e3f94
	public Void OnPluginLoad() { }
	// RVA: 0x23cbff8 VA: 0x75949e3ff8
	public SquadHomeStartBattleServicePluginBase GetStartBattleServicePlugin() { }
	// RVA: 0x23cc08c VA: 0x75949e408c
	public SquadHomeFinishBattleServicePluginBase GetFinishBattleServicePlugin() { }
	// RVA: 0x23cc120 VA: 0x75949e4120
	public BattleActivityMeta GetOverrideActMeta(String activityId) { }
	// RVA: 0x23cc1e4 VA: 0x75949e41e4
	public Void Dispose() { }
	// RVA: 0x23cbd24 VA: 0x75949e3d24
	private Boolean _CheckIfDisposed() { }
}
```