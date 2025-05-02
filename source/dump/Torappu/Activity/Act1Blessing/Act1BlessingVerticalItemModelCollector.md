# Act1BlessingVerticalItemModelCollector

**Namespace:** `Torappu.Activity.Act1Blessing`


## Fields

- `CollectParam m_param`

- `CrossAppShareTextModel <charNameTextModel>k__BackingField`

- `CrossAppShareUIAtlasImageModel <blessingGroupImgModel>k__BackingField`

- `CrossAppShareTextModel <charNameShadowModel>k__BackingField`

- `CrossAppShareDynAssetBaseModel <illustModel>k__BackingField`


## Properties

- `CrossAppShareTextModel charNameTextModel`

- `CrossAppShareUIAtlasImageModel blessingGroupImgModel`

- `CrossAppShareTextModel charNameShadowModel`

- `CrossAppShareDynAssetBaseModel illustModel`


## Methods

- `CrossAppShareTextModel get_charNameTextModel()`

- `Void set_charNameTextModel(CrossAppShareTextModel)`

- `CrossAppShareUIAtlasImageModel get_blessingGroupImgModel()`

- `Void set_blessingGroupImgModel(CrossAppShareUIAtlasImageModel)`

- `CrossAppShareTextModel get_charNameShadowModel()`

- `Void set_charNameShadowModel(CrossAppShareTextModel)`

- `CrossAppShareDynAssetBaseModel get_illustModel()`

- `Void set_illustModel(CrossAppShareDynAssetBaseModel)`

- `Void InitCollector(CollectParam)`

- `Void CollectModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Blessing
public class Act1BlessingVerticalItemModelCollector : ICrossAppShareModelCollector, IHotfixable
{
	private CollectParam m_param; // 0x10
	private CrossAppShareTextModel <charNameTextModel>k__BackingField; // 0x18
	private CrossAppShareUIAtlasImageModel <blessingGroupImgModel>k__BackingField; // 0x20
	private CrossAppShareTextModel <charNameShadowModel>k__BackingField; // 0x28
	private CrossAppShareDynAssetBaseModel <illustModel>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_charNameTextModel; // 0x0
	private static DelegateBridge __Hotfix0_set_charNameTextModel; // 0x8
	private static DelegateBridge __Hotfix0_get_blessingGroupImgModel; // 0x10
	private static DelegateBridge __Hotfix0_set_blessingGroupImgModel; // 0x18
	private static DelegateBridge __Hotfix0_get_charNameShadowModel; // 0x20
	private static DelegateBridge __Hotfix0_set_charNameShadowModel; // 0x28
	private static DelegateBridge __Hotfix0_get_illustModel; // 0x30
	private static DelegateBridge __Hotfix0_set_illustModel; // 0x38
	private static DelegateBridge __Hotfix0_InitCollector; // 0x40
	private static DelegateBridge __Hotfix0_CollectModel; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CrossAppShareTextModel charNameTextModel { get; set; }
	public CrossAppShareUIAtlasImageModel blessingGroupImgModel { get; set; }
	public CrossAppShareTextModel charNameShadowModel { get; set; }
	public CrossAppShareDynAssetBaseModel illustModel { get; set; }

	// RVA: 0x33e45a4 VA: 0x75959fc5a4
	public CrossAppShareTextModel get_charNameTextModel() { }
	// RVA: 0x33e47b4 VA: 0x75959fc7b4
	private Void set_charNameTextModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e4674 VA: 0x75959fc674
	public CrossAppShareUIAtlasImageModel get_blessingGroupImgModel() { }
	// RVA: 0x33e4838 VA: 0x75959fc838
	private Void set_blessingGroupImgModel(CrossAppShareUIAtlasImageModel value) { }
	// RVA: 0x33e460c VA: 0x75959fc60c
	public CrossAppShareTextModel get_charNameShadowModel() { }
	// RVA: 0x33e48bc VA: 0x75959fc8bc
	private Void set_charNameShadowModel(CrossAppShareTextModel value) { }
	// RVA: 0x33e46dc VA: 0x75959fc6dc
	public CrossAppShareDynAssetBaseModel get_illustModel() { }
	// RVA: 0x33e4940 VA: 0x75959fc940
	private Void set_illustModel(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x33e49c4 VA: 0x75959fc9c4
	public Void InitCollector(CollectParam param) { }
	// RVA: 0x33e4a48 VA: 0x75959fca48
	public Void CollectModel() { }
	// RVA: 0x33e4bfc VA: 0x75959fcbfc
	public Void .ctor() { }
}
```