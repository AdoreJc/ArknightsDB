# SandboxV2DungeonMineNodeViewModel

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
public class SandboxV2DungeonMineNodeViewModel : SandboxV2DungeonNodeViewModel
{
	private Boolean m_isAllDead; // 0xf8
	private SandboxV2DungeonProgressViewModel m_progressViewModel; // 0xfc
	private static DelegateBridge __Hotfix0_IsCleared; // 0x0
	private static DelegateBridge __Hotfix0_GetProgressViewModel; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCustomData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25bc640 VA: 0x7594bd4640
	protected override Boolean IsCleared() { }
	// RVA: 0x25bc6a8 VA: 0x7594bd46a8
	protected override SandboxV2DungeonProgressViewModel GetProgressViewModel() { }
	// RVA: 0x25bc714 VA: 0x7594bd4714
	protected override Void UpdateCustomData(UpdateParam updateParam) { }
	// RVA: 0x25bb430 VA: 0x7594bd3430
	public Void .ctor() { }
	// RVA: 0x25bc80c VA: 0x7594bd480c
	private Boolean <>xLuaBaseProxy_IsCleared() { }
	// RVA: 0x25bc810 VA: 0x7594bd4810
	private SandboxV2DungeonProgressViewModel <>xLuaBaseProxy_GetProgressViewModel() { }
	// RVA: 0x25bc824 VA: 0x7594bd4824
	private Void <>xLuaBaseProxy_UpdateCustomData(UpdateParam P0) { }
}
```