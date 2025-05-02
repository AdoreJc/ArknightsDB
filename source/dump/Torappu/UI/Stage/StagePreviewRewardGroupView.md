# StagePreviewRewardGroupView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StagePreviewRewardItemView _itemView`

- `Transform _itemContainer`

- `GameObject _longPart`

- `GameObject _littlePart`

- `StageDropType _dropType`

- `GridLayoutGroup _layOutGroup`

- `StagePreviewRewardGroupViewPlugin _plugin`


## Methods

- `Void Render(Dictionary`2, List`1, OverrideDropInfo, Boolean, Boolean)`

- `IEnumerator _UpdateLayoutCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewRewardGroupView : MonoBehaviour, IHotfixable
{
	private StagePreviewRewardItemView _itemView; // 0x18
	private Transform _itemContainer; // 0x20
	private GameObject _longPart; // 0x28
	private GameObject _littlePart; // 0x30
	private StageDropType _dropType; // 0x38
	private GridLayoutGroup _layOutGroup; // 0x40
	private StagePreviewRewardGroupViewPlugin _plugin; // 0x48
	private List`1 m_viewList; // 0x50
	private List`1 m_dropTypeList; // 0x58
	public List`1 hideTimelyDrop; // 0x60
	private static DelegateBridge __Hotfix0_get_dropTypeList; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateLayoutCoroutine; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 dropTypeList { get; }

	// RVA: 0x2f9ccf8 VA: 0x75955b4cf8
	public List`1 get_dropTypeList() { }
	// RVA: 0x2f9cea8 VA: 0x75955b4ea8
	public Void Render(Dictionary`2 viewModelDict, List`1 timelyReward, OverrideDropInfo overrideDropInfo, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x2f9d594 VA: 0x75955b5594
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x2f9d640 VA: 0x75955b5640
	public Void .ctor() { }
}
```