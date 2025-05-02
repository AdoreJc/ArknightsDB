# SandboxV2DungeonCaveNodeViewModel

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
public class SandboxV2DungeonCaveNodeViewModel : SandboxV2DungeonNodeViewModel
{
	private Boolean m_isAllDead; // 0xf8
	private SandboxV2DungeonProgressViewModel m_progressViewModel; // 0xfc
	private static DelegateBridge __Hotfix0_IsCleared; // 0x0
	private static DelegateBridge __Hotfix0_GetProgressViewModel; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25bc220 VA: 0x7594bd4220
	protected override Boolean IsCleared() { }
	// RVA: 0x25bc288 VA: 0x7594bd4288
	protected override SandboxV2DungeonProgressViewModel GetProgressViewModel() { }
	// RVA: 0x25bc2f4 VA: 0x7594bd42f4
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bb358 VA: 0x7594bd3358
	public Void .ctor() { }
	// RVA: 0x25bc3ec VA: 0x7594bd43ec
	private Boolean <>xLuaBaseProxy_IsCleared() { }
	// RVA: 0x25bc3f0 VA: 0x7594bd43f0
	private SandboxV2DungeonProgressViewModel <>xLuaBaseProxy_GetProgressViewModel() { }
	// RVA: 0x25bc404 VA: 0x7594bd4404
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
}
```