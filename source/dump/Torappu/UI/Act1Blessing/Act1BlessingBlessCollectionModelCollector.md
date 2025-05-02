# Act1BlessingBlessCollectionModelCollector

**Namespace:** `Torappu.UI.Act1Blessing`


## Fields

- `CollectParam m_collectParam`

- `CrossAppShareImageModel <charAvatar1>k__BackingField`

- `CrossAppShareImageModel <charAvatar2>k__BackingField`

- `CrossAppShareImageModel <charAvatar3>k__BackingField`

- `CrossAppShareImageModel <charAvatar4>k__BackingField`

- `CrossAppShareTextModel <playerIdText>k__BackingField`

- `CrossAppShareTextModel <playerNameText>k__BackingField`

- `CrossAppShareTextModel <playerLvText>k__BackingField`

- `CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField`


## Properties

- `CrossAppShareImageModel charAvatar1`

- `CrossAppShareImageModel charAvatar2`

- `CrossAppShareImageModel charAvatar3`

- `CrossAppShareImageModel charAvatar4`

- `CrossAppShareTextModel playerIdText`

- `CrossAppShareTextModel playerNameText`

- `CrossAppShareTextModel playerLvText`

- `CrossAppShareDynAssetBaseModel avatarModel`


## Methods

- `CrossAppShareImageModel get_charAvatar1()`

- `Void set_charAvatar1(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_charAvatar2()`

- `Void set_charAvatar2(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_charAvatar3()`

- `Void set_charAvatar3(CrossAppShareImageModel)`

- `CrossAppShareImageModel get_charAvatar4()`

- `Void set_charAvatar4(CrossAppShareImageModel)`

- `CrossAppShareTextModel get_playerIdText()`

- `Void set_playerIdText(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_playerNameText()`

- `Void set_playerNameText(CrossAppShareTextModel)`

- `CrossAppShareTextModel get_playerLvText()`

- `Void set_playerLvText(CrossAppShareTextModel)`

- `CrossAppShareDynAssetBaseModel get_avatarModel()`

- `Void set_avatarModel(CrossAppShareDynAssetBaseModel)`

- `Void InitCollector(CollectParam)`

- `Void CollectModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Act1Blessing
public class Act1BlessingBlessCollectionModelCollector : ICrossAppShareModelCollector, IHotfixable
{
	private CollectParam m_collectParam; // 0x10
	private CrossAppShareImageModel <charAvatar1>k__BackingField; // 0x18
	private CrossAppShareImageModel <charAvatar2>k__BackingField; // 0x20
	private CrossAppShareImageModel <charAvatar3>k__BackingField; // 0x28
	private CrossAppShareImageModel <charAvatar4>k__BackingField; // 0x30
	private CrossAppShareTextModel <playerIdText>k__BackingField; // 0x38
	private CrossAppShareTextModel <playerNameText>k__BackingField; // 0x40
	private CrossAppShareTextModel <playerLvText>k__BackingField; // 0x48
	private CrossAppShareDynAssetBaseModel <avatarModel>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_charAvatar1; // 0x0
	private static DelegateBridge __Hotfix0_set_charAvatar1; // 0x8
	private static DelegateBridge __Hotfix0_get_charAvatar2; // 0x10
	private static DelegateBridge __Hotfix0_set_charAvatar2; // 0x18
	private static DelegateBridge __Hotfix0_get_charAvatar3; // 0x20
	private static DelegateBridge __Hotfix0_set_charAvatar3; // 0x28
	private static DelegateBridge __Hotfix0_get_charAvatar4; // 0x30
	private static DelegateBridge __Hotfix0_set_charAvatar4; // 0x38
	private static DelegateBridge __Hotfix0_get_playerIdText; // 0x40
	private static DelegateBridge __Hotfix0_set_playerIdText; // 0x48
	private static DelegateBridge __Hotfix0_get_playerNameText; // 0x50
	private static DelegateBridge __Hotfix0_set_playerNameText; // 0x58
	private static DelegateBridge __Hotfix0_get_playerLvText; // 0x60
	private static DelegateBridge __Hotfix0_set_playerLvText; // 0x68
	private static DelegateBridge __Hotfix0_get_avatarModel; // 0x70
	private static DelegateBridge __Hotfix0_set_avatarModel; // 0x78
	private static DelegateBridge __Hotfix0_InitCollector; // 0x80
	private static DelegateBridge __Hotfix0_CollectModel; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public CrossAppShareImageModel charAvatar1 { get; set; }
	public CrossAppShareImageModel charAvatar2 { get; set; }
	public CrossAppShareImageModel charAvatar3 { get; set; }
	public CrossAppShareImageModel charAvatar4 { get; set; }
	public CrossAppShareTextModel playerIdText { get; set; }
	public CrossAppShareTextModel playerNameText { get; set; }
	public CrossAppShareTextModel playerLvText { get; set; }
	public CrossAppShareDynAssetBaseModel avatarModel { get; set; }

	// RVA: 0x3002918 VA: 0x759561a918
	public CrossAppShareImageModel get_charAvatar1() { }
	// RVA: 0x3002cc8 VA: 0x759561acc8
	private Void set_charAvatar1(CrossAppShareImageModel value) { }
	// RVA: 0x3002980 VA: 0x759561a980
	public CrossAppShareImageModel get_charAvatar2() { }
	// RVA: 0x3002d4c VA: 0x759561ad4c
	private Void set_charAvatar2(CrossAppShareImageModel value) { }
	// RVA: 0x30029e8 VA: 0x759561a9e8
	public CrossAppShareImageModel get_charAvatar3() { }
	// RVA: 0x3002dd0 VA: 0x759561add0
	private Void set_charAvatar3(CrossAppShareImageModel value) { }
	// RVA: 0x3002a50 VA: 0x759561aa50
	public CrossAppShareImageModel get_charAvatar4() { }
	// RVA: 0x3002e54 VA: 0x759561ae54
	private Void set_charAvatar4(CrossAppShareImageModel value) { }
	// RVA: 0x3002ab8 VA: 0x759561aab8
	public CrossAppShareTextModel get_playerIdText() { }
	// RVA: 0x3002ed8 VA: 0x759561aed8
	private Void set_playerIdText(CrossAppShareTextModel value) { }
	// RVA: 0x3002b20 VA: 0x759561ab20
	public CrossAppShareTextModel get_playerNameText() { }
	// RVA: 0x3002f5c VA: 0x759561af5c
	private Void set_playerNameText(CrossAppShareTextModel value) { }
	// RVA: 0x3002b88 VA: 0x759561ab88
	public CrossAppShareTextModel get_playerLvText() { }
	// RVA: 0x3002fe0 VA: 0x759561afe0
	private Void set_playerLvText(CrossAppShareTextModel value) { }
	// RVA: 0x3002bf0 VA: 0x759561abf0
	public CrossAppShareDynAssetBaseModel get_avatarModel() { }
	// RVA: 0x3003064 VA: 0x759561b064
	private Void set_avatarModel(CrossAppShareDynAssetBaseModel value) { }
	// RVA: 0x30030e8 VA: 0x759561b0e8
	public Void InitCollector(CollectParam collectParam) { }
	// RVA: 0x300316c VA: 0x759561b16c
	public Void CollectModel() { }
	// RVA: 0x30033f8 VA: 0x759561b3f8
	public Void .ctor() { }
}
```