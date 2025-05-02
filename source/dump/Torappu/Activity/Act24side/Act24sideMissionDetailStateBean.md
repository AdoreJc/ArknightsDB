# Act24sideMissionDetailStateBean

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionDetailProp m_prop`

- `String clickMissionId`


## Properties

- `Act24sideMissionDetailProp prop`


## Methods

- `Act24sideMissionDetailProp get_prop()`

- `Void InitData(String)`

- `Void UpdateData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionDetailStateBean : IStateBean, IHotfixable
{
	private Act24sideMissionDetailProp m_prop; // 0x10
	public String clickMissionId; // 0x18
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Act24sideMissionDetailProp prop { get; }

	// RVA: 0x32b5444 VA: 0x75958cd444
	public Act24sideMissionDetailProp get_prop() { }
	// RVA: 0x32b5398 VA: 0x75958cd398
	public Void InitData(String actId) { }
	// RVA: 0x32b5964 VA: 0x75958cd964
	public Void UpdateData() { }
	// RVA: 0x32b61a8 VA: 0x75958ce1a8
	public Void .ctor() { }
}
```