# NameCardV2EquipmentCollectionModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Image _bgImg`

- `UIAnimationLocation _switchIconAnim`

- `SimpleLayoutContent _collectionInfosContent`

- `UIColorGraphic _itemTextColorGraphic`

- `Boolean m_hasInited`

- `Tween m_switchIconTween`

- `NameCardV2EquipmentCollectionModuleModel m_cachedModel`

- `CollectionInfoAdapter m_adapter`


## Methods

- `Void SwitchModuleStyle()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2EquipmentCollectionModuleView : NameCardV2BaseRemovableModuleView`1
{
	private const Int32 COLLECTION_INFO_SLOT; // 0x0
	private Image _bgImg; // 0xb8
	private Image[] _coloredIcons; // 0xc0
	private Text[] _coloredTexts; // 0xc8
	private UIAnimationLocation _switchIconAnim; // 0xd0
	private GameObject[] _switchIconGos; // 0xe0
	private SimpleLayoutContent _collectionInfosContent; // 0xe8
	private UIColorGraphic _itemTextColorGraphic; // 0xf0
	private Boolean m_hasInited; // 0xf8
	private Tween m_switchIconTween; // 0x100
	private NameCardV2EquipmentCollectionModuleModel m_cachedModel; // 0x108
	private CollectionInfoAdapter m_adapter; // 0x110
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x0
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x8
	private static DelegateBridge __Hotfix0_SwitchModuleStyle; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28e4250 VA: 0x7594efc250
	public override Void OnModuleViewRendered(NameCardV2EquipmentCollectionModuleModel model) { }
	// RVA: 0x28e4434 VA: 0x7594efc434
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x28e4608 VA: 0x7594efc608
	public Void SwitchModuleStyle() { }
	// RVA: 0x28e4360 VA: 0x7594efc360
	private Void _InitIfNot() { }
	// RVA: 0x28e490c VA: 0x7594efc90c
	public Void .ctor() { }
	// RVA: 0x28e499c VA: 0x7594efc99c
	private Void <>xLuaBaseProxy_OnApplyStyle(NameCardV2SkinStyle P0) { }
}
```