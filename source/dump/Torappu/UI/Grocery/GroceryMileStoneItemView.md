# GroceryMileStoneItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `TwoStateToggle _bkgAndPrizeTextToggle`

- `Text _needPointNumText`

- `Transform _itemCardHolder`

- `Single _itemCardScaleInfo`

- `GameObject _finishMask`

- `UIColorGraphic _btnRaycast`

- `RectTransform _replicateItemContainer`

- `UIAnimationLocation _repAnim`

- `UIItemCard m_itemCard`

- `UIItemCard m_repItemCard`

- `String m_cacheId`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `Tween m_loopTween`


## Methods

- `Void Render(GroceryMileStoneItemViewModel)`

- `Void OnClick()`

- `Void _UpdateReplicateInfo(GroceryMileStoneItemViewModel)`

- `Void _InitIfNot()`

- `UIItemCard _EnsureRepItemCard()`

- `Void _OnItemCardClicked(Int32)`

- `Void _OnRepItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryMileStoneItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _bkgAndPrizeTextToggle; // 0x18
	private Text _needPointNumText; // 0x20
	private Transform _itemCardHolder; // 0x28
	private Single _itemCardScaleInfo; // 0x30
	private GameObject _finishMask; // 0x38
	private UIColorGraphic _btnRaycast; // 0x40
	private GameObject[] _panelReplicateItem; // 0x48
	private RectTransform _replicateItemContainer; // 0x50
	private UIAnimationLocation _repAnim; // 0x58
	private UIItemCard m_itemCard; // 0x68
	private UIItemCard m_repItemCard; // 0x70
	private String m_cacheId; // 0x78
	private Boolean m_hasInited; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private Tween m_loopTween; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__UpdateReplicateInfo; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__EnsureRepItemCard; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnRepItemCardClicked; // 0x30
	private static DelegateBridge __Hotfix1__OnItemCardClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x28a82b8 VA: 0x7594ec02b8
	public Void Render(GroceryMileStoneItemViewModel model) { }
	// RVA: 0x28a88ac VA: 0x7594ec08ac
	public Void OnClick() { }
	// RVA: 0x28a8680 VA: 0x7594ec0680
	private Void _UpdateReplicateInfo(GroceryMileStoneItemViewModel model) { }
	// RVA: 0x28a8494 VA: 0x7594ec0494
	private Void _InitIfNot() { }
	// RVA: 0x28a899c VA: 0x7594ec099c
	private UIItemCard _EnsureRepItemCard() { }
	// RVA: 0x28a8b98 VA: 0x7594ec0b98
	private Void _OnItemCardClicked(Int32 index) { }
	// RVA: 0x28a8cf8 VA: 0x7594ec0cf8
	private Void _OnRepItemCardClicked(Int32 index) { }
	// RVA: 0x28a8c14 VA: 0x7594ec0c14
	private static Void _OnItemCardClicked(UIItemCard itemCard) { }
	// RVA: 0x28a8d74 VA: 0x7594ec0d74
	public Void .ctor() { }
}
```