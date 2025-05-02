# Act3D0StageMapDecor

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Text _coinCount`

- `Text _mileStoneCount`

- `String m_actId`


## Methods

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0StageMapDecor : ActivityStageSingleComponent, IPlayerDataListener, IHotfixable
{
	private Text _coinCount; // 0x20
	private Text _mileStoneCount; // 0x28
	private String m_actId; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x322b424 VA: 0x7595843424
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x322b53c VA: 0x759584353c
	public Void OnPlayerDataChanged() { }
	// RVA: 0x322b610 VA: 0x7595843610
	protected override Void OnLoaded() { }
	// RVA: 0x322b69c VA: 0x759584369c
	protected override Void BeforeUnload() { }
	// RVA: 0x322b714 VA: 0x7595843714
	private Void OnDestroy() { }
	// RVA: 0x322b780 VA: 0x7595843780
	public Void .ctor() { }
	// RVA: 0x322b7f0 VA: 0x75958437f0
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x322b7f8 VA: 0x75958437f8
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```