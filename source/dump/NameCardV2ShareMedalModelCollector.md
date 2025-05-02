# NameCardV2ShareMedalModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareMedalStartLayoutElement m_closure`

- `CrossAppShareDynAssetBaseModel <diyMedalGroup>k__BackingField`

- `CrossAppShareDynAssetBaseModel <suitMedalGroup>k__BackingField`


## Properties

- `CrossAppShareDynAssetBaseModel diyMedalGroup`

- `CrossAppShareDynAssetBaseModel suitMedalGroup`


## Methods

- `Void InitCollector(NameCardV2ShareMedalStartLayoutElement)`

- `CrossAppShareDynAssetBaseModel get_diyMedalGroup()`

- `Void set_diyMedalGroup(CrossAppShareDynAssetBaseModel)`

- `CrossAppShareDynAssetBaseModel get_suitMedalGroup()`

- `Void set_suitMedalGroup(CrossAppShareDynAssetBaseModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareMedalModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareMedalStartLayoutElement m_closure; // 0x28
	private CrossAppShareDynAssetBaseModel <diyMedalGroup>k__BackingField; // 0x30
	private CrossAppShareDynAssetBaseModel <suitMedalGroup>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_InitCollector; // 0x0
	private static DelegateBridge __Hotfix0_get_diyMedalGroup; // 0x8
	private static DelegateBridge __Hotfix0_set_diyMedalGroup; // 0x10
	private static DelegateBridge __Hotfix0_get_suitMedalGroup; // 0x18
	private static DelegateBridge __Hotfix0_set_suitMedalGroup; // 0x20
	private static DelegateBridge __Hotfix0_CollectModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public CrossAppShareDynAssetBaseModel diyMedalGroup { get; set; }
	public CrossAppShareDynAssetBaseModel suitMedalGroup { get; set; }

	// RVA: 0x28d96d8 VA: 0x7594ef16d8
	public Void InitCollector(NameCardV2ShareMedalStartLayoutElement closure) { }
	// RVA: 0x28d9478 VA: 0x7594ef1478
	public CrossAppShareDynAssetBaseModel get_diyMedalGroup() { }
	// RVA: 0x28d97cc VA: 0x7594ef17cc
	private Void set_diyMedalGroup(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x28d94e0 VA: 0x7594ef14e0
	public CrossAppShareDynAssetBaseModel get_suitMedalGroup() { }
	// RVA: 0x28d9850 VA: 0x7594ef1850
	private Void set_suitMedalGroup(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x28d98d4 VA: 0x7594ef18d4
	public override Void CollectModel() { }
	// RVA: 0x28d9668 VA: 0x7594ef1668
	public Void .ctor() { }
}
```