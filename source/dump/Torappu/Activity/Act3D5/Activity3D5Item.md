# Activity3D5Item

**Namespace:** `Torappu.Activity.Act3D5`


## Fields

- `Sprite _normalBG`

- `Sprite _normalCompleteBG`

- `Sprite _bigCompleteBG`

- `Image _bg`

- `GameObject _bigMark`

- `UITweenFade _bright`

- `Text _rewardCnt`

- `Text _rewardName`

- `Transform _rewardIconRoot`

- `Button _getMarkBtn`

- `Button _getBtn`

- `Text _needDesc`

- `Text _needCount`

- `UIChildrenColorGraphic _colorAlter`

- `String m_activityId`

- `CollectionInfo m_data`

- `Boolean m_hasGot`

- `UIItemCard m_itemCell`


## Properties

- `Boolean hasGot`


## Methods

- `Void Refresh(String, CollectionInfo, Boolean, Boolean)`

- `Boolean get_hasGot()`

- `Void OnEnable()`

- `Void Flash()`

- `Void OnGetReward()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <OnGetReward>b__23_0(ActivityGetCollectionRewardResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D5
public class Activity3D5Item : MonoBehaviour, IHotfixable
{
	private Sprite _normalBG; // 0x18
	private Sprite _normalCompleteBG; // 0x20
	private Sprite _bigCompleteBG; // 0x28
	private Image _bg; // 0x30
	private GameObject _bigMark; // 0x38
	private UITweenFade _bright; // 0x40
	private Text _rewardCnt; // 0x48
	private Text _rewardName; // 0x50
	private Transform _rewardIconRoot; // 0x58
	private Button _getMarkBtn; // 0x60
	private Button _getBtn; // 0x68
	private Text _needDesc; // 0x70
	private Text _needCount; // 0x78
	private UIChildrenColorGraphic _colorAlter; // 0x80
	private String m_activityId; // 0x88
	private CollectionInfo m_data; // 0x90
	private Boolean m_hasGot; // 0x98
	private UIItemCard m_itemCell; // 0xa0
	private static DelegateBridge __Hotfix0_Refresh; // 0x0
	private static DelegateBridge __Hotfix0_get_hasGot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_Flash; // 0x18
	private static DelegateBridge __Hotfix0_OnGetReward; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean hasGot { get; }

	// RVA: 0x322734c VA: 0x759583f34c
	public Void Refresh(String activityId, CollectionInfo data, Boolean reached, Boolean geted) { }
	// RVA: 0x3227c28 VA: 0x759583fc28
	public Boolean get_hasGot() { }
	// RVA: 0x3227c90 VA: 0x759583fc90
	private Void OnEnable() { }
	// RVA: 0x3227d68 VA: 0x759583fd68
	public Void Flash() { }
	// RVA: 0x3227e5c VA: 0x759583fe5c
	public Void OnGetReward() { }
	// RVA: 0x3228078 VA: 0x7595840078
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x3228160 VA: 0x7595840160
	public Void .ctor() { }
	// RVA: 0x32281d0 VA: 0x75958401d0
	private Void <OnGetReward>b__23_0(ActivityGetCollectionRewardResponse response) { }
}
```