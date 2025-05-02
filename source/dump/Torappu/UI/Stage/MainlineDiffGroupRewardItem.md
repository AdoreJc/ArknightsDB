# MainlineDiffGroupRewardItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _itemContainer`

- `Image _icon`

- `Text _apCost`

- `GameObject _isPassed`

- `GameObject _isComplete`

- `GameObject _unPassed`

- `GameObject _selectedObj`

- `Text _diffName`

- `StageRewardPreviewItem _itemRewardCard`

- `UIStringEvent onRewardClick`

- `Boolean m_detail`

- `StageInfo m_cacheViewModel`

- `StageRewardPreviewItem m_itemRewardCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(StageInfo, Boolean)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainlineDiffGroupRewardItem : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Image _icon; // 0x20
	private Text _apCost; // 0x28
	private GameObject _isPassed; // 0x30
	private GameObject _isComplete; // 0x38
	private GameObject _unPassed; // 0x40
	private GameObject _selectedObj; // 0x48
	private Text _diffName; // 0x50
	private StageRewardPreviewItem _itemRewardCard; // 0x58
	public UIStringEvent onRewardClick; // 0x60
	private Boolean m_detail; // 0x68
	private StageInfo m_cacheViewModel; // 0x70
	private StageRewardPreviewItem m_itemRewardCard; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ef484c VA: 0x759550c84c
	private Void _InitIfNot() { }
	// RVA: 0x2ef4938 VA: 0x759550c938
	public Void Render(StageInfo stageViewModel, Boolean isSelectStage) { }
	// RVA: 0x2ef4bac VA: 0x759550cbac
	public Void OnItemClick() { }
	// RVA: 0x2ef4c48 VA: 0x759550cc48
	public Void .ctor() { }
}
```