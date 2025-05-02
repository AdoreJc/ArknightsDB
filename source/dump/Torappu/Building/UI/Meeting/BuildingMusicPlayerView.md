# BuildingMusicPlayerView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _panelDefault`

- `GameObject _panelVisit`

- `BuildingMusicPlayerListAdapter _adapter`

- `GameObject _ascending`

- `GameObject _descending`

- `Text _name`

- `Text _unlockDesc`

- `GameObject _bottomLockIcon`

- `GameObject _btnCanSet`

- `GameObject _btnCanNotSet`

- `Text _visitName`

- `Text _visitDesc`

- `UIAutoSlideRect _visitNameSlideRect`

- `Action onChangeSortOrder`

- `Action onBkgClicked`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnSetMusicBtnClicked()`

- `Void OnChangeSortOrderClicked()`

- `Void OnBkgClicked()`

- `IEnumerator _TryEnableAutoSlide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerView : DataBinder`1, IHotfixable
{
	private GameObject _panelDefault; // 0x20
	private GameObject _panelVisit; // 0x28
	private BuildingMusicPlayerListAdapter _adapter; // 0x30
	private GameObject _ascending; // 0x38
	private GameObject _descending; // 0x40
	private Text _name; // 0x48
	private Text _unlockDesc; // 0x50
	private GameObject _bottomLockIcon; // 0x58
	private GameObject _btnCanSet; // 0x60
	private GameObject _btnCanNotSet; // 0x68
	private Text _visitName; // 0x70
	private Text _visitDesc; // 0x78
	private UIAutoSlideRect _visitNameSlideRect; // 0x80
	public Action onChangeSortOrder; // 0x88
	public Action onBkgClicked; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnSetMusicBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnChangeSortOrderClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnBkgClicked; // 0x18
	private static DelegateBridge __Hotfix0__TryEnableAutoSlide; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3ded98c VA: 0x759640598c
	public override Void OnValueChanged(MusicPlayerProperty property) { }
	// RVA: 0x3dedc14 VA: 0x7596405c14
	public Void OnSetMusicBtnClicked() { }
	// RVA: 0x3dedcb8 VA: 0x7596405cb8
	public Void OnChangeSortOrderClicked() { }
	// RVA: 0x3dedd3c VA: 0x7596405d3c
	public Void OnBkgClicked() { }
	// RVA: 0x3dedb68 VA: 0x7596405b68
	private IEnumerator _TryEnableAutoSlide() { }
	// RVA: 0x3dedde8 VA: 0x7596405de8
	public Void .ctor() { }
}
```