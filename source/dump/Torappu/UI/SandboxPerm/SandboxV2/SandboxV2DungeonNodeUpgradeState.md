# SandboxV2DungeonNodeUpgradeState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonNodeUpgradeView _nodeUpgradeView`

- `SandboxV2DungeonNodeUpgradeStateBean m_stateBean`

- `SandboxV2DungeonNodeUpgradeProperty m_prop`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _DismissIfCan()`

- `Void _OpenWorkbench()`

- `Void _RaiseAVGSignal()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeUpgradeState : PopupFloatState
{
	private SandboxV2DungeonNodeUpgradeView _nodeUpgradeView; // 0x70
	private SandboxV2DungeonNodeUpgradeStateBean m_stateBean; // 0x78
	private SandboxV2DungeonNodeUpgradeProperty m_prop; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__DismissIfCan; // 0x20
	private static DelegateBridge __Hotfix0__OpenWorkbench; // 0x28
	private static DelegateBridge __Hotfix0__RaiseAVGSignal; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x254822c VA: 0x7594b6022c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2548294 VA: 0x7594b60294
	protected override Void OnEnter() { }
	// RVA: 0x25484f8 VA: 0x7594b604f8
	protected override Void OnResume() { }
	// RVA: 0x2548370 VA: 0x7594b60370
	private Void _InitIfNot() { }
	// RVA: 0x25486f8 VA: 0x7594b606f8
	private Void _DismissIfCan() { }
	// RVA: 0x254880c VA: 0x7594b6080c
	private Void _OpenWorkbench() { }
	// RVA: 0x25485d4 VA: 0x7594b605d4
	private Void _RaiseAVGSignal() { }
	// RVA: 0x2548aa8 VA: 0x7594b60aa8
	public Void .ctor() { }
	// RVA: 0x2548c00 VA: 0x7594b60c00
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2548c08 VA: 0x7594b60c08
	private Void <>xLuaBaseProxy_OnResume() { }
}
```