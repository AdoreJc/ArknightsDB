# HomeDiamondChangeView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _diamondShCount`

- `Text _changeText`

- `Text _exchangeCount`

- `Text _maxCount`

- `Text _exchangeResultCount`

- `GameObject _minus`

- `GameObject _minusGray`

- `GameObject _add`

- `GameObject _addGray`

- `UIAnimationLocation _showAnimation`

- `UIItemCard _itemPrefab`

- `Transform _containerFirst`

- `Transform _containerSecond`

- `Single _itemScale`

- `GameObject _pageContainer`

- `UnityEvent _eventBuyBuyFinish`

- `Int32 m_count`

- `Int32 m_changeRate`

- `Int32 m_maxCount`

- `Int64 m_shCount`

- `Tween m_showTweener`

- `Boolean m_isShowing`

- `UIItemCard m_costItem`

- `UIItemCard m_targetItem`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_targetModel`

- `Boolean m_initFlag`


## Methods

- `Void _Init()`

- `Void _RefreshView()`

- `Void Show()`

- `Void Dismiss()`

- `Void SendDiamondExchangeService()`

- `Void _OnExchangeResponseSuccess(ExchangeDiamondShardResponse)`

- `Void Add()`

- `Void AddToMax()`

- `Void Minus()`

- `Void MinusToOne()`

- `Void <Show>b__30_0()`

- `Void <Dismiss>b__31_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeDiamondChangeView : MonoBehaviour
{
	private Text _diamondShCount; // 0x18
	private Text _changeText; // 0x20
	private Text _exchangeCount; // 0x28
	private Text _maxCount; // 0x30
	private Text _exchangeResultCount; // 0x38
	private GameObject _minus; // 0x40
	private GameObject _minusGray; // 0x48
	private GameObject _add; // 0x50
	private GameObject _addGray; // 0x58
	private UIAnimationLocation _showAnimation; // 0x60
	private UIItemCard _itemPrefab; // 0x70
	private Transform _containerFirst; // 0x78
	private Transform _containerSecond; // 0x80
	private Single _itemScale; // 0x88
	private GameObject _pageContainer; // 0x90
	private UnityEvent _eventBuyBuyFinish; // 0x98
	private Int32 m_count; // 0xa0
	private Int32 m_changeRate; // 0xa4
	private Int32 m_maxCount; // 0xa8
	private Int64 m_shCount; // 0xb0
	private Tween m_showTweener; // 0xb8
	private Boolean m_isShowing; // 0xc0
	private UIItemCard m_costItem; // 0xc8
	private UIItemCard m_targetItem; // 0xd0
	private UIItemViewModel m_costModel; // 0xd8
	private UIItemViewModel m_targetModel; // 0xe0
	private Boolean m_initFlag; // 0xe8


	// RVA: 0x2837044 VA: 0x7594e4f044
	protected virtual Void Start() { }
	// RVA: 0x2837168 VA: 0x7594e4f168
	private Void _Init() { }
	// RVA: 0x2837404 VA: 0x7594e4f404
	private Void _RefreshView() { }
	// RVA: 0x28377ac VA: 0x7594e4f7ac
	public Void Show() { }
	// RVA: 0x28379bc VA: 0x7594e4f9bc
	public Void Dismiss() { }
	// RVA: 0x2837b48 VA: 0x7594e4fb48
	public Void SendDiamondExchangeService() { }
	// RVA: 0x2837d50 VA: 0x7594e4fd50
	private Void _OnExchangeResponseSuccess(ExchangeDiamondShardResponse response) { }
	// RVA: 0x2837dd4 VA: 0x7594e4fdd4
	public Void Add() { }
	// RVA: 0x2837de4 VA: 0x7594e4fde4
	public Void AddToMax() { }
	// RVA: 0x2837df0 VA: 0x7594e4fdf0
	public Void Minus() { }
	// RVA: 0x2837e00 VA: 0x7594e4fe00
	public Void MinusToOne() { }
	// RVA: 0x2837e0c VA: 0x7594e4fe0c
	public Void .ctor() { }
	// RVA: 0x2837eb0 VA: 0x7594e4feb0
	private Void <Show>b__30_0() { }
	// RVA: 0x2837edc VA: 0x7594e4fedc
	private Void <Dismiss>b__31_0() { }
}
```