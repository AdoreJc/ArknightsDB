# MedalGroupListItem

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _backImage`

- `Text _groupName`

- `Text _groupDesc`

- `GameObject _templateContainer`

- `GameObject _getFlag`

- `Text _getTime`

- `UIStringEvent onClickEvent`

- `MedalGroupViewModel m_cacheViewModel`

- `UIMedalGroupView m_groupView`


## Methods

- `Void Render(MedalGroupViewModel, UIPage)`

- `Void _UpdateGroupView(MedalGroupViewModel, UIPage)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupListItem : MonoBehaviour, IHotfixable
{
	private Image _backImage; // 0x18
	private Text _groupName; // 0x20
	private Text _groupDesc; // 0x28
	private GameObject _templateContainer; // 0x30
	private GameObject _getFlag; // 0x38
	private Text _getTime; // 0x40
	public UIStringEvent onClickEvent; // 0x48
	private MedalGroupViewModel m_cacheViewModel; // 0x50
	private UIMedalGroupView m_groupView; // 0x58
	private static readonly Color BACK_COLOR; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateGroupView; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x279d558 VA: 0x7594db5558
	public Void Render(MedalGroupViewModel viewModel, UIPage page) { }
	// RVA: 0x279d9ac VA: 0x7594db59ac
	private Void _UpdateGroupView(MedalGroupViewModel viewModel, UIPage page) { }
	// RVA: 0x279dbd0 VA: 0x7594db5bd0
	public Void OnClick() { }
	// RVA: 0x279dc88 VA: 0x7594db5c88
	public Void .ctor() { }
	// RVA: 0x279dd08 VA: 0x7594db5d08
	private static Void .cctor() { }
}
```