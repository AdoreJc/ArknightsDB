# NameCardShareTeamObjectModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareTeamObjectStartLayoutElement m_closure`

- `CrossAppShareImageModel <teamIconModel>k__BackingField`


## Properties

- `CrossAppShareImageModel teamIconModel`


## Methods

- `CrossAppShareImageModel get_teamIconModel()`

- `Void set_teamIconModel(CrossAppShareImageModel)`

- `Void InitCollector(NameCardV2ShareTeamObjectStartLayoutElement)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardShareTeamObjectModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareTeamObjectStartLayoutElement m_closure; // 0x28
	private CrossAppShareImageModel <teamIconModel>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_teamIconModel; // 0x0
	private static DelegateBridge __Hotfix0_set_teamIconModel; // 0x8
	private static DelegateBridge __Hotfix0_InitCollector; // 0x10
	private static DelegateBridge __Hotfix0_CollectModel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CrossAppShareImageModel teamIconModel { get; set; }

	// RVA: 0x28da350 VA: 0x7594ef2350
	public CrossAppShareImageModel get_teamIconModel() { }
	// RVA: 0x28da63c VA: 0x7594ef263c
	private Void set_teamIconModel(CrossAppShareImageModel value) { }
	// RVA: 0x28da548 VA: 0x7594ef2548
	public Void InitCollector(NameCardV2ShareTeamObjectStartLayoutElement shareTeamObject) { }
	// RVA: 0x28da6c0 VA: 0x7594ef26c0
	public override Void CollectModel() { }
	// RVA: 0x28da4d8 VA: 0x7594ef24d8
	public Void .ctor() { }
}
```