# SandboxV2DungeonNodeDropDetailState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonNodeDropDetailView _view`

- `SandboxV2DungeonNodeDropDetailStateBean m_stateBean`

- `SandboxV2DungeonNodeDropDetailProperty m_prop`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _DismissIfCan()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeDropDetailState : PopupFloatState
{
	private SandboxV2DungeonNodeDropDetailView _view; // 0x70
	private SandboxV2DungeonNodeDropDetailStateBean m_stateBean; // 0x78
	private SandboxV2DungeonNodeDropDetailProperty m_prop; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__DismissIfCan; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25477a0 VA: 0x7594b5f7a0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2547808 VA: 0x7594b5f808
	protected override Void OnEnter() { }
	// RVA: 0x2547920 VA: 0x7594b5f920
	private Void _InitIfNot() { }
	// RVA: 0x2547a28 VA: 0x7594b5fa28
	private Void _DismissIfCan() { }
	// RVA: 0x2547b3c VA: 0x7594b5fb3c
	public Void .ctor() { }
	// RVA: 0x2547d44 VA: 0x7594b5fd44
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```