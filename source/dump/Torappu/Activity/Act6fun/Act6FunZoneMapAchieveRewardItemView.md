# Act6FunZoneMapAchieveRewardItemView

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Transform _itemContainer`

- `Single _itemScale`

- `GameObject _objCanClaimDesc`

- `GameObject _objCanClaimTxtMask`

- `GameObject _objClaimedDesc`

- `Text _txtAchieveNeedCount`

- `Color _claimedCol`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `String m_cachedRewardId`

- `Act6FunAchieveRewardItemState m_cachedRewardItemState`


## Methods

- `Void set_onClaimReward(Action`1)`

- `Void Render(Act6FunZoneMapAchieveRewardItemViewModel)`

- `Void _InitIfNot()`

- `Void _OnClickItemShowDetailInfo(Int32)`

- `Void OnClaimRewardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchieveRewardItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Single _itemScale; // 0x20
	private GameObject _objCanClaimDesc; // 0x28
	private GameObject _objCanClaimTxtMask; // 0x30
	private GameObject _objClaimedDesc; // 0x38
	private Text _txtAchieveNeedCount; // 0x40
	private Color _claimedCol; // 0x48
	private Action`1 <onClaimReward>k__BackingField; // 0x58
	private Boolean m_hasInited; // 0x60
	private UIItemCard m_itemCard; // 0x68
	private UIItemViewModel m_itemModel; // 0x70
	private String m_cachedRewardId; // 0x78
	private Act6FunAchieveRewardItemState m_cachedRewardItemState; // 0x80
	private static DelegateBridge __Hotfix0_get_onClaimReward; // 0x0
	private static DelegateBridge __Hotfix0_set_onClaimReward; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnClickItemShowDetailInfo; // 0x20
	private static DelegateBridge __Hotfix0_OnClaimRewardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClaimReward { get; set; }

	// RVA: 0x31b5830 VA: 0x75957cd830
	private Action`1 get_onClaimReward() { }
	// RVA: 0x31b5898 VA: 0x75957cd898
	public Void set_onClaimReward(Action`1 value) { }
	// RVA: 0x31b591c VA: 0x75957cd91c
	public Void Render(Act6FunZoneMapAchieveRewardItemViewModel itemViewModel) { }
	// RVA: 0x31b5b40 VA: 0x75957cdb40
	private Void _InitIfNot() { }
	// RVA: 0x31b5d34 VA: 0x75957cdd34
	private Void _OnClickItemShowDetailInfo(Int32 index) { }
	// RVA: 0x31b5df0 VA: 0x75957cddf0
	public Void OnClaimRewardClick() { }
	// RVA: 0x31b5e9c VA: 0x75957cde9c
	public Void .ctor() { }
}
```