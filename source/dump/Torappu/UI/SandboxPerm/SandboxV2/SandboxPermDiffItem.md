# SandboxPermDiffItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _title`

- `Text _detailText`

- `Text _descText`

- `Text _titleUnSelected`

- `Text _detailTextUnSelected`

- `Text _descTextUnselected`

- `GameObject _isSelected`

- `GameObject _notSelected`

- `Image _modeIcon`

- `UIStateFinder m_stateFinder`

- `SandboxPermDiffViewModel m_viewModel`


## Methods

- `Void Render(SandboxPermDiffViewModel)`

- `Void OnSelectDiff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxPermDiffItem : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private Text _detailText; // 0x20
	private Text _descText; // 0x28
	private Text _titleUnSelected; // 0x30
	private Text _detailTextUnSelected; // 0x38
	private Text _descTextUnselected; // 0x40
	private GameObject _isSelected; // 0x48
	private GameObject _notSelected; // 0x50
	private Image _modeIcon; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private SandboxPermDiffViewModel m_viewModel; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectDiff; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2480a68 VA: 0x7594a98a68
	public Void Render(SandboxPermDiffViewModel viewModel) { }
	// RVA: 0x2480c78 VA: 0x7594a98c78
	public Void OnSelectDiff() { }
	// RVA: 0x2480d80 VA: 0x7594a98d80
	public Void .ctor() { }
}
```