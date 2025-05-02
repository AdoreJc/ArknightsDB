# Act29signSpecialCheckinItem

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `UIAtlasImage _specialNormalBg`

- `Image _orderIndexIcon`

- `Text _progressText`

- `GameObject _hotSpot`

- `UIAtlasImage _toBeDeterminedIcon`

- `SimpleLayoutContent _subItemListContainer`

- `Image _alreadyGetMask`

- `Image _alreadyGetImg`

- `Image _alreadyGetLabel`

- `UIAtlasImage _specialAlreadyGetLabel`

- `Text _specialAlreadyGetText`

- `UnityEvent clickEvent`

- `Int32 m_order`

- `Boolean m_isClickable`

- `ActivityCheckinCardSubObjListTool m_activityCheckinCardSubObjListTool`


## Methods

- `Void RenderItemView(Act29signSpecialCheckinItemViewModel)`

- `Void _RenderCardSubObjList(Int32, List`1, Boolean)`

- `ItemObjConfig _GetItemObjConfig(Int32)`

- `Void OnReceive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signSpecialCheckinItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _specialNormalBg; // 0x18
	private Image _orderIndexIcon; // 0x20
	private Text _progressText; // 0x28
	private GameObject _hotSpot; // 0x30
	private ItemObjConfig[] _cardSubObjConfigs; // 0x38
	private UIAtlasImage _toBeDeterminedIcon; // 0x40
	private SimpleLayoutContent _subItemListContainer; // 0x48
	private Image _alreadyGetMask; // 0x50
	private Image _alreadyGetImg; // 0x58
	private Image _alreadyGetLabel; // 0x60
	private UIAtlasImage _specialAlreadyGetLabel; // 0x68
	private Text _specialAlreadyGetText; // 0x70
	public UnityEvent clickEvent; // 0x78
	private Int32 m_order; // 0x80
	private Boolean m_isClickable; // 0x84
	private ActivityCheckinCardSubObjListTool m_activityCheckinCardSubObjListTool; // 0x88
	private static DelegateBridge __Hotfix0_RenderItemView; // 0x0
	private static DelegateBridge __Hotfix0__RenderCardSubObjList; // 0x8
	private static DelegateBridge __Hotfix0__GetItemObjConfig; // 0x10
	private static DelegateBridge __Hotfix0_OnReceive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3260724 VA: 0x7595878724
	public Void RenderItemView(Act29signSpecialCheckinItemViewModel viewModel) { }
	// RVA: 0x3261e54 VA: 0x7595879e54
	private Void _RenderCardSubObjList(Int32 order, List`1 itemList, Boolean isClickable) { }
	// RVA: 0x326201c VA: 0x759587a01c
	private ItemObjConfig _GetItemObjConfig(Int32 count) { }
	// RVA: 0x3262144 VA: 0x759587a144
	public Void OnReceive() { }
	// RVA: 0x32621c0 VA: 0x759587a1c0
	public Void .ctor() { }
}
```