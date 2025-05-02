# SandboxV2DungeonNodeStagePreviewState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonNodeStagePreviewView _view`

- `SandboxV2DungeonNodeStagePreviewStateBean m_stateBean`

- `SandboxV2DungeonNodeStagePreviewProperty m_prop`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _DismissIfCan()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeStagePreviewState : PopupFloatState
{
	private SandboxV2DungeonNodeStagePreviewView _view; // 0x70
	private SandboxV2DungeonNodeStagePreviewStateBean m_stateBean; // 0x78
	private SandboxV2DungeonNodeStagePreviewProperty m_prop; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__DismissIfCan; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2547d4c VA: 0x7594b5fd4c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2547db4 VA: 0x7594b5fdb4
	protected override Void OnEnter() { }
	// RVA: 0x2547e8c VA: 0x7594b5fe8c
	private Void _InitIfNot() { }
	// RVA: 0x2547fb8 VA: 0x7594b5ffb8
	private Void _DismissIfCan() { }
	// RVA: 0x25480cc VA: 0x7594b600cc
	public Void .ctor() { }
	// RVA: 0x2548224 VA: 0x7594b60224
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```