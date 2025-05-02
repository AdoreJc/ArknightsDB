# SandboxV2AdminMainInventoryItemDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _cardCanvas`

- `RectTransform _cardRt`

- `Button _preBtn`

- `Button _nextBtn`

- `Text _nameLabel`

- `GameObject _countNode`

- `Text _countLabel`

- `Text _usageLabel`

- `Text _descLabel`

- `Text _approachLabel`

- `GameObject _foodStatusBar`

- `Text _foodTime`

- `GameObject _trapTagBar`

- `Image _trapTagBg`

- `Text _trapTagName`

- `Transform _itemCardContainer`

- `SandboxV2ItemCard _itemCardPrefab`

- `SandboxV2ItemCard m_itemCard`

- `Int32 m_currShowIdx`

- `Coroutine m_switchCoroutine`

- `Int32 m_targetOffset`

- `UIPageFinder m_pageFinder`

- `String <topicId>k__BackingField`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Void Render(SandboxV2AdminMainInventoryItemDetailStateBean)`

- `Void _InitIfNot()`

- `Void _FlushCard(SandboxV2AdminMainInventoryItemModel)`

- `Void _FlushFood(SandboxV2FoodVariantInfo)`

- `Void _FlushTag(SandboxPermItemData)`

- `Void _UpdateBtnState()`

- `IEnumerator _SwitchToItem(Int32)`

- `Void _ClearSwitchCoroutine()`

- `Void _TryStartSwitch()`

- `Void EventPreItem()`

- `Void EventNextItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryItemDetailView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _cardCanvas; // 0x18
	private RectTransform _cardRt; // 0x20
	private Button _preBtn; // 0x28
	private Button _nextBtn; // 0x30
	private Text _nameLabel; // 0x38
	private GameObject _countNode; // 0x40
	private Text _countLabel; // 0x48
	private Text _usageLabel; // 0x50
	private Text _descLabel; // 0x58
	private Text _approachLabel; // 0x60
	private GameObject _foodStatusBar; // 0x68
	private Text _foodTime; // 0x70
	private Image[] _attribIconList; // 0x78
	private GameObject _trapTagBar; // 0x80
	private Image _trapTagBg; // 0x88
	private Text _trapTagName; // 0x90
	private Transform _itemCardContainer; // 0x98
	private SandboxV2ItemCard _itemCardPrefab; // 0xa0
	private SandboxV2ItemCard m_itemCard; // 0xa8
	private Int32 m_currShowIdx; // 0xb0
	private List`1 m_itemList; // 0xb8
	private Coroutine m_switchCoroutine; // 0xc0
	private Int32 m_targetOffset; // 0xc8
	private UIPageFinder m_pageFinder; // 0xd0
	private const Single POSX_OFFSET; // 0x0
	private const Single FADE_DUR; // 0x0
	private String <topicId>k__BackingField; // 0xe0
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__FlushCard; // 0x20
	private static DelegateBridge __Hotfix0__FlushFood; // 0x28
	private static DelegateBridge __Hotfix0__FlushTag; // 0x30
	private static DelegateBridge __Hotfix0__UpdateBtnState; // 0x38
	private static DelegateBridge __Hotfix0__SwitchToItem; // 0x40
	private static DelegateBridge __Hotfix0__ClearSwitchCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__TryStartSwitch; // 0x50
	private static DelegateBridge __Hotfix0_EventPreItem; // 0x58
	private static DelegateBridge __Hotfix0_EventNextItem; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String topicId { get; set; }

	// RVA: 0x24d2d44 VA: 0x7594aead44
	public String get_topicId() { }
	// RVA: 0x24d2dac VA: 0x7594aeadac
	private Void set_topicId(String value) { }
	// RVA: 0x24d2738 VA: 0x7594aea738
	public Void Render(SandboxV2AdminMainInventoryItemDetailStateBean stateBean) { }
	// RVA: 0x24d2e30 VA: 0x7594aeae30
	private Void _InitIfNot() { }
	// RVA: 0x24d30dc VA: 0x7594aeb0dc
	private Void _FlushCard(SandboxV2AdminMainInventoryItemModel itemModel) { }
	// RVA: 0x24d33f8 VA: 0x7594aeb3f8
	private Void _FlushFood(SandboxV2FoodVariantInfo foodVarInfo) { }
	// RVA: 0x24d37d0 VA: 0x7594aeb7d0
	private Void _FlushTag(SandboxPermItemData itemData) { }
	// RVA: 0x24d3340 VA: 0x7594aeb340
	private Void _UpdateBtnState() { }
	// RVA: 0x24d3ab4 VA: 0x7594aebab4
	private IEnumerator _SwitchToItem(Int32 idxOffset) { }
	// RVA: 0x24d2fd0 VA: 0x7594aeafd0
	private Void _ClearSwitchCoroutine() { }
	// RVA: 0x24d3ba0 VA: 0x7594aebba0
	private Void _TryStartSwitch() { }
	// RVA: 0x24d3c44 VA: 0x7594aebc44
	public Void EventPreItem() { }
	// RVA: 0x24d3cb8 VA: 0x7594aebcb8
	public Void EventNextItem() { }
	// RVA: 0x24d3d2c VA: 0x7594aebd2c
	public Void .ctor() { }
}
```