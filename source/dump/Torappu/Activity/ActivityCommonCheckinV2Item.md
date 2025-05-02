# ActivityCommonCheckinV2Item

**Namespace:** `Torappu.Activity`


## Fields

- `Text _orderIndex`

- `Image _normalShadow`

- `Image _normalBg`

- `SimpleLayoutContent _subItemListContainer`

- `Image _acceptableLight`

- `Image _acceptableBg`

- `Image _logoImg`

- `Image _rewardDot`

- `Image _rewardAcceptableMask`

- `Image _decImg`

- `Image _decorImg`

- `Image _rewardAcceptableDot`

- `GameObject _hotSpot`

- `Image _arrowImg`

- `Image _alreadyGetMask`

- `Image _alreadyGetImg`

- `Image _alreadyGetLabel`

- `UIIntEvent clickEvent`

- `Int32 m_order`

- `Boolean m_isClickable`

- `ActivityCheckinCardSubObjListTool m_activityCheckinCardSubObjListTool`


## Methods

- `Void RenderItemView(ItemConfigGroup, Int32, CheckInDailyInfo, Boolean, Boolean, Boolean)`

- `Void _RenderCardSubObjList(Int32, List`1, Boolean)`

- `ItemObjConfig _GetItemObjConfig(Int32)`

- `Void OnReceive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinV2Item : MonoBehaviour, IHotfixable
{
	private const String ANIMATOR_PARAM; // 0x0
	private Text _orderIndex; // 0x18
	private Image _normalShadow; // 0x20
	private Image _normalBg; // 0x28
	private SimpleLayoutContent _subItemListContainer; // 0x30
	private Image _acceptableLight; // 0x38
	private Image _acceptableBg; // 0x40
	private Image _logoImg; // 0x48
	private Image _rewardDot; // 0x50
	private Image _rewardAcceptableMask; // 0x58
	private Image _decImg; // 0x60
	private Image _decorImg; // 0x68
	private Image _rewardAcceptableDot; // 0x70
	private GameObject _hotSpot; // 0x78
	private ItemObjConfig[] _cardSubObjConfigs; // 0x80
	private Image _arrowImg; // 0x88
	private Image _alreadyGetMask; // 0x90
	private Image _alreadyGetImg; // 0x98
	private Image _alreadyGetLabel; // 0xa0
	public UIIntEvent clickEvent; // 0xa8
	private Int32 m_order; // 0xb0
	private Boolean m_isClickable; // 0xb4
	private ActivityCheckinCardSubObjListTool m_activityCheckinCardSubObjListTool; // 0xb8
	private static DelegateBridge __Hotfix0_RenderItemView; // 0x0
	private static DelegateBridge __Hotfix0__RenderCardSubObjList; // 0x8
	private static DelegateBridge __Hotfix0__GetItemObjConfig; // 0x10
	private static DelegateBridge __Hotfix0_OnReceive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30d08d4 VA: 0x75956e88d4
	public Void RenderItemView(ItemConfigGroup configGroup, Int32 order, CheckInDailyInfo dailyInfo, Boolean hasInfoFlag, Boolean canReceiveFlag, Boolean lastTargetFlag) { }
	// RVA: 0x30d0d5c VA: 0x75956e8d5c
	private Void _RenderCardSubObjList(Int32 order, List`1 itemList, Boolean isClickable) { }
	// RVA: 0x30d0f18 VA: 0x75956e8f18
	private ItemObjConfig _GetItemObjConfig(Int32 count) { }
	// RVA: 0x30d1518 VA: 0x75956e9518
	public Void OnReceive() { }
	// RVA: 0x30d15ac VA: 0x75956e95ac
	public Void .ctor() { }
}
```