# NameCardV2ShareAvatarModelCollector

**Namespace:** ` `


## Fields

- `NameCardV2ShareAvatarStartLayoutElement m_closure`

- `CrossAppShareTextModel <doctorLevelModel>k__BackingField`

- `CrossAppShareTextModel <doctorNameModel>k__BackingField`

- `CrossAppShareTextModel <doctorUidModel>k__BackingField`

- `CrossAppShareImageModel <bgImgModel>k__BackingField`

- `CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField`

- `CrossAppShareObjectActiveModel <uidObjectModel>k__BackingField`


## Properties

- `CrossAppShareTextModel doctorLevelModel`

- `CrossAppShareTextModel doctorNameModel`

- `CrossAppShareTextModel doctorUidModel`

- `CrossAppShareImageModel bgImgModel`

- `CrossAppShareDynAssetBaseModel avatarModel`

- `CrossAppShareObjectActiveModel uidObjectModel`


## Methods

- `Void InitCollector(NameCardV2ShareAvatarStartLayoutElement)`

- `CrossAppShareTextModel get_doctorLevelModel()`

- `Void set_doctorLevelModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_doctorNameModel()`

- `Void set_doctorNameModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_doctorUidModel()`

- `Void set_doctorUidModel(CrossAppShareTextModel)`

- `CrossAppShareImageModel get_bgImgModel()`

- `Void set_bgImgModel(CrossAppShareImageModel)`

- `CrossAppShareDynAssetBaseModel get_avatarModel()`

- `Void set_avatarModel(CrossAppShareDynAssetBaseModel)`

- `CrossAppShareObjectActiveModel get_uidObjectModel()`

- `Void set_uidObjectModel(CrossAppShareObjectActiveModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NameCardV2ShareAvatarModelCollector : CrossAppShareElementModelCollector
{
	private NameCardV2ShareAvatarStartLayoutElement m_closure; // 0x28
	private CrossAppShareTextModel <doctorLevelModel>k__BackingField; // 0x30
	private CrossAppShareTextModel <doctorNameModel>k__BackingField; // 0x38
	private CrossAppShareTextModel <doctorUidModel>k__BackingField; // 0x40
	private CrossAppShareImageModel <bgImgModel>k__BackingField; // 0x48
	private CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField; // 0x50
	private CrossAppShareObjectActiveModel <uidObjectModel>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_InitCollector; // 0x0
	private static DelegateBridge __Hotfix0_get_doctorLevelModel; // 0x8
	private static DelegateBridge __Hotfix0_set_doctorLevelModel; // 0x10
	private static DelegateBridge __Hotfix0_get_doctorNameModel; // 0x18
	private static DelegateBridge __Hotfix0_set_doctorNameModel; // 0x20
	private static DelegateBridge __Hotfix0_get_doctorUidModel; // 0x28
	private static DelegateBridge __Hotfix0_set_doctorUidModel; // 0x30
	private static DelegateBridge __Hotfix0_get_bgImgModel; // 0x38
	private static DelegateBridge __Hotfix0_set_bgImgModel; // 0x40
	private static DelegateBridge __Hotfix0_get_avatarModel; // 0x48
	private static DelegateBridge __Hotfix0_set_avatarModel; // 0x50
	private static DelegateBridge __Hotfix0_get_uidObjectModel; // 0x58
	private static DelegateBridge __Hotfix0_set_uidObjectModel; // 0x60
	private static DelegateBridge __Hotfix0_CollectModel; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public CrossAppShareTextModel doctorLevelModel { get; set; }
	public CrossAppShareTextModel doctorNameModel { get; set; }
	public CrossAppShareTextModel doctorUidModel { get; set; }
	public CrossAppShareImageModel bgImgModel { get; set; }
	public CrossAppShareDynAssetBaseModel avatarModel { get; set; }
	public CrossAppShareObjectActiveModel uidObjectModel { get; set; }

	// RVA: 0x28d4118 VA: 0x7594eec118
	public Void InitCollector(NameCardV2ShareAvatarStartLayoutElement closure) { }
	// RVA: 0x28d31dc VA: 0x7594eeb1dc
	public CrossAppShareTextModel get_doctorLevelModel() { }
	// RVA: 0x28d420c VA: 0x7594eec20c
	private Void set_doctorLevelModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d3244 VA: 0x7594eeb244
	public CrossAppShareTextModel get_doctorNameModel() { }
	// RVA: 0x28d4290 VA: 0x7594eec290
	private Void set_doctorNameModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d32ac VA: 0x7594eeb2ac
	public CrossAppShareTextModel get_doctorUidModel() { }
	// RVA: 0x28d4314 VA: 0x7594eec314
	private Void set_doctorUidModel(CrossAppShareTextModel value) { }
	// RVA: 0x28d3314 VA: 0x7594eeb314
	public CrossAppShareImageModel get_bgImgModel() { }
	// RVA: 0x28d4398 VA: 0x7594eec398
	private Void set_bgImgModel(CrossAppShareImageModel value) { }
	// RVA: 0x28d337c VA: 0x7594eeb37c
	public CrossAppShareDynAssetBaseModel get_avatarModel() { }
	// RVA: 0x28d441c VA: 0x7594eec41c
	private Void set_avatarModel(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x28d33e4 VA: 0x7594eeb3e4
	public CrossAppShareObjectActiveModel get_uidObjectModel() { }
	// RVA: 0x28d44a0 VA: 0x7594eec4a0
	private Void set_uidObjectModel(CrossAppShareObjectActiveModel value) { }
	// RVA: 0x28d4524 VA: 0x7594eec524
	public override Void CollectModel() { }
	// RVA: 0x28d40a8 VA: 0x7594eec0a8
	public Void .ctor() { }
}
```