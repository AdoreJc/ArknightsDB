# Act13sideMissionPoolItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _emptyPartGo`

- `GameObject _normalPartGo`

- `GameObject _selectedBgGo`

- `GameObject _normalBgGo`

- `Text _textOrgName`

- `Text _textPrincipalName`

- `Image _imgAvatar`

- `RectTransform _itemParent`

- `Single _itemCardScale`

- `UIAnimationLocation _acceptAnim`

- `Act13sideDailyMissionItemViewModel m_poolItemModel`

- `Int32 m_index`

- `UIItemCard m_rewardItemView`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(String, Act13sideDailyMissionItemViewModel, Int32, Boolean)`

- `Void PlayAcceptAnim()`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionPoolItemView : MonoBehaviour, IHotfixable
{
	private GameObject _emptyPartGo; // 0x18
	private GameObject _normalPartGo; // 0x20
	private GameObject _selectedBgGo; // 0x28
	private GameObject _normalBgGo; // 0x30
	private Text _textOrgName; // 0x38
	private Text _textPrincipalName; // 0x40
	private Image _imgAvatar; // 0x48
	private RectTransform _itemParent; // 0x50
	private Single _itemCardScale; // 0x58
	private UIAnimationLocation _acceptAnim; // 0x60
	private Action`1 <onItemClick>k__BackingField; // 0x70
	private Act13sideDailyMissionItemViewModel m_poolItemModel; // 0x78
	private Int32 m_index; // 0x80
	private UIItemCard m_rewardItemView; // 0x88
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_PlayAcceptAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClick { get; set; }

	// RVA: 0x3442b64 VA: 0x7595a5ab64
	private Action`1 get_onItemClick() { }
	// RVA: 0x343cc04 VA: 0x7595a54c04
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x343cc88 VA: 0x7595a54c88
	public Void Render(String actId, Act13sideDailyMissionItemViewModel poolItemModel, Int32 index, Boolean isSelected) { }
	// RVA: 0x343ddb8 VA: 0x7595a55db8
	public Void PlayAcceptAnim() { }
	// RVA: 0x3442bcc VA: 0x7595a5abcc
	public Void OnItemClick() { }
	// RVA: 0x3442c6c VA: 0x7595a5ac6c
	public Void .ctor() { }
}
```