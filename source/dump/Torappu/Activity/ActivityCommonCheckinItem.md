# ActivityCommonCheckinItem

**Namespace:** `Torappu.Activity`


## Fields

- `Transform _itemContainer`

- `GameObject _canReceiveBack`

- `GameObject _normalBack`

- `GameObject _canNotReceiveBtn`

- `GameObject _alreadyReceiveBtn`

- `GameObject _acceptReceiveBack`

- `CanvasGroup _canvasGroup`

- `Text _orderIndex`

- `ActivityCommonCheckinItemObj _itemObj`

- `UIIntEvent clickEvent`

- `Animator _animator`

- `Int32 m_order`

- `Boolean m_isReceived`


## Methods

- `Void OnEnable()`

- `Void _RenderItem(Int32, List`1, Boolean)`

- `Void RenderItemView(Int32, Int32, List`1, Boolean, Boolean)`

- `Void OnReceive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinItem : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private GameObject _canReceiveBack; // 0x20
	private GameObject _normalBack; // 0x28
	private GameObject _canNotReceiveBtn; // 0x30
	private GameObject _alreadyReceiveBtn; // 0x38
	private GameObject _acceptReceiveBack; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Text _orderIndex; // 0x50
	private ActivityCommonCheckinItemObj _itemObj; // 0x58
	public UIIntEvent clickEvent; // 0x60
	private Animator _animator; // 0x68
	private Int32 m_order; // 0x70
	private Boolean m_isReceived; // 0x74
	private const String ANIMATOR_PARAM; // 0x0
	private List`1 m_itemCardList; // 0x78
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0__RenderItem; // 0x8
	private static DelegateBridge __Hotfix0_RenderItemView; // 0x10
	private static DelegateBridge __Hotfix0_OnReceive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30cfb74 VA: 0x75956e7b74
	private Void OnEnable() { }
	// RVA: 0x30cfc04 VA: 0x75956e7c04
	private Void _RenderItem(Int32 order, List`1 itemList, Boolean isReceived) { }
	// RVA: 0x30d0164 VA: 0x75956e8164
	public Void RenderItemView(Int32 order, Int32 dayInfo, List`1 itemList, Boolean hasInfoFlag, Boolean canReceiveFlag) { }
	// RVA: 0x30d02f0 VA: 0x75956e82f0
	public Void OnReceive() { }
	// RVA: 0x30d0384 VA: 0x75956e8384
	public Void .ctor() { }
}
```