# RoguelikeCharSelectBranchView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIColorGraphic _brachIconColor`

- `Image _brachIcon`

- `Color _selectedIconColor`

- `Color _unselectedIconColor`

- `GameObject _panelselectedBg`

- `GameObject _panelunselectedBg`

- `GameObject _panelLockBg`

- `GameObject _panelIcon`

- `GameObject _panelLock`

- `GameObject _panelLevel`

- `GameObject _panelSingleBranch`

- `GameObject _panelMultiBranch`

- `Text _singleBranchName`

- `Text _multiBranchName`

- `Image _multiExtraBranchIcon`

- `Text _equipLvl`

- `String m_equipId`


## Methods

- `Void set_onBranchClicked(Action`1)`

- `Void Render(RoguelikeCharSelectBranchItemViewModel, Boolean)`

- `Void OnBranchClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectBranchView : MonoBehaviour, IHotfixable
{
	private UIColorGraphic _brachIconColor; // 0x18
	private Image _brachIcon; // 0x20
	private Color _selectedIconColor; // 0x28
	private Color _unselectedIconColor; // 0x38
	private GameObject _panelselectedBg; // 0x48
	private GameObject _panelunselectedBg; // 0x50
	private GameObject _panelLockBg; // 0x58
	private GameObject _panelIcon; // 0x60
	private GameObject _panelLock; // 0x68
	private GameObject _panelLevel; // 0x70
	private GameObject _panelSingleBranch; // 0x78
	private GameObject _panelMultiBranch; // 0x80
	private Text _singleBranchName; // 0x88
	private Text _multiBranchName; // 0x90
	private Image _multiExtraBranchIcon; // 0x98
	private Text _equipLvl; // 0xa0
	private Action`1 m_onBranchClicked; // 0xa8
	private String m_equipId; // 0xb0
	private static DelegateBridge __Hotfix0_set_onBranchClicked; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnBranchClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Action`1 onBranchClicked { set; }

	// RVA: 0x2acd7d4 VA: 0x75950e57d4
	public Void set_onBranchClicked(Action`1 value) { }
	// RVA: 0x2acd858 VA: 0x75950e5858
	public Void Render(RoguelikeCharSelectBranchItemViewModel branchModel, Boolean isSelected) { }
	// RVA: 0x2acdb0c VA: 0x75950e5b0c
	public Void OnBranchClicked() { }
	// RVA: 0x2acdb94 VA: 0x75950e5b94
	public Void .ctor() { }
}
```