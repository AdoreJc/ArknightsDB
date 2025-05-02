# Act12sideMissionItemView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `UIScaler _scaler`

- `Image _imgBg`

- `Image _imgNote`

- `Image _imgCross`

- `Text _textSpecialDesc`

- `Text _textMissionDesc`

- `Text _textCount`

- `Text _textProgressCount`

- `Slider _sliderProgress`

- `RectTransform _itemRoot`

- `Single _rewardScale`

- `Selectable _colorHandler`

- `GameObject _completedGo`

- `TwoStateToggle _detailStateToggle`

- `Text _textUnlockCaption`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_rewardViewModel`


## Methods

- `Void Render(Act12sideMissionItemViewModel, Single)`

- `Void _UpdateCompleteStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMissionItemView : MonoBehaviour, IHotfixable
{
	private MissionStyleOption[] _styleOptions; // 0x18
	private UIScaler _scaler; // 0x20
	private Image _imgBg; // 0x28
	private Image _imgNote; // 0x30
	private Image _imgCross; // 0x38
	private Text _textSpecialDesc; // 0x40
	private Text _textMissionDesc; // 0x48
	private Text _textCount; // 0x50
	private Text _textProgressCount; // 0x58
	private Slider _sliderProgress; // 0x60
	private RectTransform _itemRoot; // 0x68
	private Single _rewardScale; // 0x70
	private Selectable _colorHandler; // 0x78
	private GameObject _completedGo; // 0x80
	private TwoStateToggle _detailStateToggle; // 0x88
	private Text _textUnlockCaption; // 0x90
	private UIItemCard m_itemCard; // 0x98
	private UIItemViewModel m_rewardViewModel; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__UpdateCompleteStatus; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3466944 VA: 0x7595a7e944
	public Void Render(Act12sideMissionItemViewModel itemViewModel, Single itemScale) { }
	// RVA: 0x3466fd4 VA: 0x7595a7efd4
	private Void _UpdateCompleteStatus(Boolean isCompleted) { }
	// RVA: 0x3467134 VA: 0x7595a7f134
	public Void .ctor() { }
}
```