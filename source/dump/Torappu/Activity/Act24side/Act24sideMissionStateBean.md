# Act24sideMissionStateBean

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionProp m_prop`

- `String clickMissionId`


## Properties

- `Act24sideMissionProp prop`


## Methods

- `Act24sideMissionProp get_prop()`

- `Void InitData(String)`

- `Void UpdateData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionStateBean : IStateBean, IHotfixable
{
	private Act24sideMissionProp m_prop; // 0x10
	public String clickMissionId; // 0x18
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge __Hotfix0_GetCanReceiveMission; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Act24sideMissionProp prop { get; }

	// RVA: 0x32bd768 VA: 0x75958d5768
	public Act24sideMissionProp get_prop() { }
	// RVA: 0x32bd6bc VA: 0x75958d56bc
	public Void InitData(String actId) { }
	// RVA: 0x32bda74 VA: 0x75958d5a74
	public Void UpdateData() { }
	// RVA: 0x32be724 VA: 0x75958d6724
	public List`1 GetCanReceiveMission() { }
	// RVA: 0x32bec48 VA: 0x75958d6c48
	public Void .ctor() { }
}
```