# BuildingShopOutputSlot

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Text _textCount`

- `Text _textLimit`

- `SimpleLayoutContent _cardLayout`

- `CardAdapter m_adapter`

- `String m_cachedSlotId`

- `Boolean m_isInited`


## Methods

- `UIItemViewModel _FindItemViewModel(ItemType)`

- `Void _Init()`

- `Void _UpdateOutput(ShopInfoViewModel)`

- `Int32 _CountItems(List`1, ItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopOutputSlot : DataBinder`1
{
	private const String STACK_CARD_NAME; // 0x0
	private const Single ANIM_DUR; // 0x0
	private const Int32 MAX_STACK_COUNT; // 0x0
	private Text _textCount; // 0x20
	private Text _textLimit; // 0x28
	private SimpleLayoutContent _cardLayout; // 0x30
	private CardAdapter m_adapter; // 0x38
	private List`1 m_iconInfoList; // 0x40
	private List`1 m_itemModels; // 0x48
	private String m_cachedSlotId; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__FindItemViewModel; // 0x8
	private static DelegateBridge __Hotfix0__Init; // 0x10
	private static DelegateBridge __Hotfix0__UpdateOutput; // 0x18
	private static DelegateBridge __Hotfix0__CountItems; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3dbf954 VA: 0x75963d7954
	public override Void OnValueChanged(SRoomViewProperty property) { }
	// RVA: 0x3dbfef0 VA: 0x75963d7ef0
	private UIItemViewModel _FindItemViewModel(ItemType itemType) { }
	// RVA: 0x3dbfb08 VA: 0x75963d7b08
	private Void _Init() { }
	// RVA: 0x3dbfbbc VA: 0x75963d7bbc
	private Void _UpdateOutput(ShopInfoViewModel shopInfo) { }
	// RVA: 0x3dc0150 VA: 0x75963d8150
	private Int32 _CountItems(List`1 icons, ItemType itemType) { }
	// RVA: 0x3dc0248 VA: 0x75963d8248
	public Void .ctor() { }
}
```