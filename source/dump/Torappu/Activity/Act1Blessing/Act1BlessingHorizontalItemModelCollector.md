# Act1BlessingHorizontalItemModelCollector

**Namespace:** `Torappu.Activity.Act1Blessing`


## Fields

- `CollectParam m_param`

- `CrossAppShareTextModel <charNameTextModel>k__BackingField`

- `CrossAppShareUIAtlasImageModel <blessingGroupImgModel>k__BackingField`

- `CrossAppShareTextModel <charBlessingTextModel>k__BackingField`

- `CrossAppShareTextModel <charBlessingShadowModel>k__BackingField`

- `CrossAppShareTextModel <playerIdTextModel>k__BackingField`

- `CrossAppShareTextModel <playerNameTextModel>k__BackingField`

- `CrossAppShareTextModel <playerLvTextModel>k__BackingField`

- `CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField`

- `CrossAppShareDynAssetBaseModel <illustModel>k__BackingField`


## Properties

- `CrossAppShareTextModel charNameTextModel`

- `CrossAppShareUIAtlasImageModel blessingGroupImgModel`

- `CrossAppShareTextModel charBlessingTextModel`

- `CrossAppShareTextModel charBlessingShadowModel`

- `CrossAppShareTextModel playerIdTextModel`

- `CrossAppShareTextModel playerNameTextModel`

- `CrossAppShareTextModel playerLvTextModel`

- `CrossAppShareDynAssetBaseModel avatarModel`

- `CrossAppShareDynAssetBaseModel illustModel`


## Methods

- `CrossAppShareTextModel get_charNameTextModel()`

- `Void set_charNameTextModel(CrossAppShareTextModel)`

- `CrossAppShareUIAtlasImageModel get_blessingGroupImgModel()`

- `Void set_blessingGroupImgModel(CrossAppShareUIAtlasImageModel)`

- `CrossAppShareTextModel get_charBlessingTextModel()`

- `Void set_charBlessingTextModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_charBlessingShadowModel()`

- `Void set_charBlessingShadowModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_playerIdTextModel()`

- `Void set_playerIdTextModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_playerNameTextModel()`

- `Void set_playerNameTextModel(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_playerLvTextModel()`

- `Void set_playerLvTextModel(CrossAppShareTextModel)`

- `CrossAppShareDynAssetBaseModel get_avatarModel()`

- `Void set_avatarModel(CrossAppShareDynAssetBaseModel)`

- `CrossAppShareDynAssetBaseModel get_illustModel()`

- `Void set_illustModel(CrossAppShareDynAssetBaseModel)`

- `Void InitCollector(CollectParam)`

- `Void CollectModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Blessing
public class Act1BlessingHorizontalItemModelCollector : ICrossAppShareModelCollector, IHotfixable
{
	private CollectParam m_param; // 0x10
	private CrossAppShareTextModel <charNameTextModel>k__BackingField; // 0x18
	private CrossAppShareUIAtlasImageModel <blessingGroupImgModel>k__BackingField; // 0x20
	private CrossAppShareTextModel <charBlessingTextModel>k__BackingField; // 0x28
	private CrossAppShareTextModel <charBlessingShadowModel>k__BackingField; // 0x30
	private CrossAppShareTextModel <playerIdTextModel>k__BackingField; // 0x38
	private CrossAppShareTextModel <playerNameTextModel>k__BackingField; // 0x40
	private CrossAppShareTextModel <playerLvTextModel>k__BackingField; // 0x48
	private CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField; // 0x50
	private CrossAppShareDynAssetBaseModel <illustModel>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_charNameTextModel; // 0x0
	private static DelegateBridge __Hotfix0_set_charNameTextModel; // 0x8
	private static DelegateBridge __Hotfix0_get_blessingGroupImgModel; // 0x10
	private static DelegateBridge __Hotfix0_set_blessingGroupImgModel; // 0x18
	private static DelegateBridge __Hotfix0_get_charBlessingTextModel; // 0x20
	private static DelegateBridge __Hotfix0_set_charBlessingTextModel; // 0x28
	private static DelegateBridge __Hotfix0_get_charBlessingShadowModel; // 0x30
	private static DelegateBridge __Hotfix0_set_charBlessingShadowModel; // 0x38
	private static DelegateBridge __Hotfix0_get_playerIdTextModel; // 0x40
	private static DelegateBridge __Hotfix0_set_playerIdTextModel; // 0x48
	private static DelegateBridge __Hotfix0_get_playerNameTextModel; // 0x50
	private static DelegateBridge __Hotfix0_set_playerNameTextModel; // 0x58
	private static DelegateBridge __Hotfix0_get_playerLvTextModel; // 0x60
	private static DelegateBridge __Hotfix0_set_playerLvTextModel; // 0x68
	private static DelegateBridge __Hotfix0_get_avatarModel; // 0x70
	private static DelegateBridge __Hotfix0_set_avatarModel; // 0x78
	private static DelegateBridge __Hotfix0_get_illustModel; // 0x80
	private static DelegateBridge __Hotfix0_set_illustModel; // 0x88
	private static DelegateBridge __Hotfix0_InitCollector; // 0x90
	private static DelegateBridge __Hotfix0_CollectModel; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public CrossAppShareTextModel charNameTextModel { get; set; }
	public CrossAppShareUIAtlasImageModel blessingGroupImgModel { get; set; }
	public CrossAppShareTextModel charBlessingTextModel { get; set; }
	public CrossAppShareTextModel charBlessingShadowModel { get; set; }
	public CrossAppShareTextModel playerIdTextModel { get; set; }
	public CrossAppShareTextModel playerNameTextModel { get; set; }
	public CrossAppShareTextModel playerLvTextModel { get; set; }
	public CrossAppShareDynAssetBaseModel avatarModel { get; set; }
	public CrossAppShareDynAssetBaseModel illustModel { get; set; }

	// RVA: 0x33e3770 VA: 0x75959fb770
	public CrossAppShareTextModel get_charNameTextModel() { }
	// RVA: 0x33e3b88 VA: 0x75959fbb88
	private Void set_charNameTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e39e0 VA: 0x75959fb9e0
	public CrossAppShareUIAtlasImageModel get_blessingGroupImgModel() { }
	// RVA: 0x33e3c0c VA: 0x75959fbc0c
	private Void set_blessingGroupImgModel(CrossAppShareUIAtlasImageModel value) { }
	// RVA: 0x33e37d8 VA: 0x75959fb7d8
	public CrossAppShareTextModel get_charBlessingTextModel() { }
	// RVA: 0x33e3c90 VA: 0x75959fbc90
	private Void set_charBlessingTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e3840 VA: 0x75959fb840
	public CrossAppShareTextModel get_charBlessingShadowModel() { }
	// RVA: 0x33e3d14 VA: 0x75959fbd14
	private Void set_charBlessingShadowModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e38a8 VA: 0x75959fb8a8
	public CrossAppShareTextModel get_playerIdTextModel() { }
	// RVA: 0x33e3d98 VA: 0x75959fbd98
	private Void set_playerIdTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e3910 VA: 0x75959fb910
	public CrossAppShareTextModel get_playerNameTextModel() { }
	// RVA: 0x33e3e1c VA: 0x75959fbe1c
	private Void set_playerNameTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e3978 VA: 0x75959fb978
	public CrossAppShareTextModel get_playerLvTextModel() { }
	// RVA: 0x33e3ea0 VA: 0x75959fbea0
	private Void set_playerLvTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e3a48 VA: 0x75959fba48
	public CrossAppShareDynAssetBaseModel get_avatarModel() { }
	// RVA: 0x33e3f24 VA: 0x75959fbf24
	private Void set_avatarModel(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x33e3ab0 VA: 0x75959fbab0
	public CrossAppShareDynAssetBaseModel get_illustModel() { }
	// RVA: 0x33e3fa8 VA: 0x75959fbfa8
	private Void set_illustModel(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x33e402c VA: 0x75959fc02c
	public Void InitCollector(CollectParam param) { }
	// RVA: 0x33e40b0 VA: 0x75959fc0b0
	public Void CollectModel() { }
	// RVA: 0x33e43dc VA: 0x75959fc3dc
	public Void .ctor() { }
}
```