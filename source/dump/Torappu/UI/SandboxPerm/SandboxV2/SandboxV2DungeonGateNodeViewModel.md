# SandboxV2DungeonGateNodeViewModel

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
public class SandboxV2DungeonGateNodeViewModel : SandboxV2DungeonNodeViewModel
{
	private Boolean m_isAllDead; // 0xf8
	private SandboxV2DungeonProgressViewModel m_progressViewModel; // 0xfc
	private static DelegateBridge __Hotfix0_IsCleared; // 0x0
	private static DelegateBridge __Hotfix0_GetProgressViewModel; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25bc430 VA: 0x7594bd4430
	protected override Boolean IsCleared() { }
	// RVA: 0x25bc498 VA: 0x7594bd4498
	protected override SandboxV2DungeonProgressViewModel GetProgressViewModel() { }
	// RVA: 0x25bc504 VA: 0x7594bd4504
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bb3c4 VA: 0x7594bd33c4
	public Void .ctor() { }
	// RVA: 0x25bc5fc VA: 0x7594bd45fc
	private Boolean <>xLuaBaseProxy_IsCleared() { }
	// RVA: 0x25bc600 VA: 0x7594bd4600
	private SandboxV2DungeonProgressViewModel <>xLuaBaseProxy_GetProgressViewModel() { }
	// RVA: 0x25bc614 VA: 0x7594bd4614
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
}
```