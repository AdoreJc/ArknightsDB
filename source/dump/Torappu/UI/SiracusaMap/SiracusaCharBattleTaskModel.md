# SiracusaCharBattleTaskModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `BattleTaskData m_battleTaskData`


## Properties

- `String stageId`

- `String taskDesc`


## Methods

- `String get_stageId()`

- `String get_taskDesc()`

- `Void <>xLuaBaseProxy_LoadData(SiracusaData, TaskBasicInfoData, TaskInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharBattleTaskModel : SiracusaCharTaskModel
{
	private BattleTaskData m_battleTaskData; // 0x28
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_taskDesc; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String stageId { get; }
	public String taskDesc { get; }

	// RVA: 0x23e5278 VA: 0x75949fd278
	public String get_stageId() { }
	// RVA: 0x23e52f0 VA: 0x75949fd2f0
	public String get_taskDesc() { }
	// RVA: 0x23e5384 VA: 0x75949fd384
	public override Void LoadData(SiracusaData siracusaData, TaskBasicInfoData taskInfoData, TaskInfo playerTask) { }
	// RVA: 0x23e51a0 VA: 0x75949fd1a0
	public Void .ctor() { }
	// RVA: 0x23e548c VA: 0x75949fd48c
	private Void <>xLuaBaseProxy_LoadData(SiracusaData P0, TaskBasicInfoData P1, TaskInfo P2) { }
}
```