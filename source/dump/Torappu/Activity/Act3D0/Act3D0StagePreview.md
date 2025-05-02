# Act3D0StagePreview

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
public class Act3D0StagePreview : ActivityStageSingleComponent, IPlayerDataListener, IHotfixable
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


	// RVA: 0x322b800 VA: 0x7595843800
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x322b918 VA: 0x7595843918
	public Void OnPlayerDataChanged() { }
	// RVA: 0x322b9ec VA: 0x75958439ec
	protected override Void OnLoaded() { }
	// RVA: 0x322ba78 VA: 0x7595843a78
	protected override Void BeforeUnload() { }
	// RVA: 0x322baf0 VA: 0x7595843af0
	private Void OnDestroy() { }
	// RVA: 0x322bb5c VA: 0x7595843b5c
	public Void .ctor() { }
	// RVA: 0x322bbcc VA: 0x7595843bcc
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x322bbd4 VA: 0x7595843bd4
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```