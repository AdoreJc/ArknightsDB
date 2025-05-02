# BuildingTradingGainedOrderView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `GameObject _panelComplete`

- `GameObject _panelNotEnougth`

- `Image _completeIcon`

- `Image _uncompleteIcon`

- `SimpleLayoutContent _itemLayout`

- `Animator _animator`

- `Action onFinishClicked`

- `Action onDeleteClicked`

- `Boolean m_isTransiting`

- `UIAnimation m_pendingTransition`

- `SimpleLayoutAdapter m_itemAdapter`

- `Boolean m_isInited`

- `TradingOrderStruct m_cachedOrder`


## Properties

- `TradingOrderStruct currentOrder`


## Methods

- `TradingOrderStruct get_currentOrder()`

- `Void OnEnable()`

- `Void Render(TradingOrderStruct)`

- `Void EventOnFinishClicked()`

- `Void EventOnDeleteClicked()`

- `Void _InitIfNot()`

- `Boolean _CheckOrderBuffed(TradingOrderStruct)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingGainedOrderView : MonoBehaviour
{
	private const String ANIM_COMPLETE_KEY; // 0x0
	private GameObject _panelComplete; // 0x18
	private GameObject _panelNotEnougth; // 0x20
	private Text[] _textsTitle; // 0x28
	private Text[] _textsRewardCount; // 0x30
	private RewardIconPair[] _completeIconHub; // 0x38
	private RewardIconPair[] _uncompleteIconHub; // 0x40
	private Image _completeIcon; // 0x48
	private Image _uncompleteIcon; // 0x50
	private SimpleLayoutContent _itemLayout; // 0x58
	private Animator _animator; // 0x60
	private Image[] _orderBuffIcon; // 0x68
	private GameObject[] _panelIconGroup; // 0x70
	private GameObject[] _panelSpecialIcon; // 0x78
	private GameObject[] _panelExtraIcon; // 0x80
	public Action onFinishClicked; // 0x88
	public Action onDeleteClicked; // 0x90
	private Boolean m_isTransiting; // 0x98
	private UIAnimation m_pendingTransition; // 0xa0
	private SimpleLayoutAdapter m_itemAdapter; // 0xa8
	private Boolean m_isInited; // 0xb0
	private TradingOrderStruct m_cachedOrder; // 0xb8

	public TradingOrderStruct currentOrder { get; }

	// RVA: 0x3d837a4 VA: 0x759639b7a4
	public TradingOrderStruct get_currentOrder() { }
	// RVA: 0x3d837b4 VA: 0x759639b7b4
	private Void OnEnable() { }
	// RVA: 0x3d8380c VA: 0x759639b80c
	public Void Render(TradingOrderStruct orderStruct) { }
	// RVA: 0x3d83e68 VA: 0x759639be68
	public Void EventOnFinishClicked() { }
	// RVA: 0x3d83ea4 VA: 0x759639bea4
	public Void EventOnDeleteClicked() { }
	// RVA: 0x3d83bdc VA: 0x759639bbdc
	private Void _InitIfNot() { }
	// RVA: 0x3d83c74 VA: 0x759639bc74
	private static Void _LoadSprite(RewardIconPair[] hub, Image icon, TradingOrderReward type) { }
	// RVA: 0x3d83e10 VA: 0x759639be10
	private Boolean _CheckOrderBuffed(TradingOrderStruct orderStruct) { }
	// RVA: 0x3d83f74 VA: 0x759639bf74
	public Void .ctor() { }
}
```