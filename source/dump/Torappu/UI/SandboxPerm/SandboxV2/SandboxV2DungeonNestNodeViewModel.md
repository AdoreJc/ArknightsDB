# SandboxV2DungeonNestNodeViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean m_isAllDead`

- `SandboxV2DungeonProgressViewModel m_progressViewModel`


## Methods

- `Boolean <>xLuaBaseProxy_IsCleared()`

- `SandboxV2DungeonProgressViewModel <>xLuaBaseProxy_GetProgressViewModel()`

- `Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNestNodeViewModel : SandboxV2DungeonNodeViewModel
{
	private Boolean m_isAllDead; // 0xf8
	private SandboxV2DungeonProgressViewModel m_progressViewModel; // 0xfc
	private static DelegateBridge __Hotfix0_IsCleared; // 0x0
	private static DelegateBridge __Hotfix0_GetProgressViewModel; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25bc014 VA: 0x7594bd4014
	protected override Boolean IsCleared() { }
	// RVA: 0x25bc07c VA: 0x7594bd407c
	protected override SandboxV2DungeonProgressViewModel GetProgressViewModel() { }
	// RVA: 0x25bc0e8 VA: 0x7594bd40e8
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bb2ec VA: 0x7594bd32ec
	public Void .ctor() { }
	// RVA: 0x25bc1dc VA: 0x7594bd41dc
	private Boolean <>xLuaBaseProxy_IsCleared() { }
	// RVA: 0x25bc1e0 VA: 0x7594bd41e0
	private SandboxV2DungeonProgressViewModel <>xLuaBaseProxy_GetProgressViewModel() { }
	// RVA: 0x25bc1f4 VA: 0x7594bd41f4
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
}
```