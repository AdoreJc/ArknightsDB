# PlayerAvatarSelectStateBean

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `PlayerAvatarItemViewModel m_selectedViewModel`

- `String levelStr`


## Properties

- `PlayerAvatarItemViewModel selectedItemViewModel`


## Methods

- `PlayerAvatarItemViewModel get_selectedItemViewModel()`

- `Void InitData()`

- `Void SetSelected(PlayerAvatarItemViewModel)`

- `Boolean _CheckIsSelectedViewModel(PlayerAvatarItemViewModel)`

- `Boolean _CheckPlayerAvatarAvailable(PlayerAvatarItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarSelectStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	private List`1 m_groupViewModelList; // 0x18
	private PlayerAvatarItemViewModel m_selectedViewModel; // 0x20
	public String levelStr; // 0x28
	private static DelegateBridge __Hotfix0_get_groupViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedItemViewModel; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_SetSelected; // 0x18
	private static DelegateBridge __Hotfix0__CheckIsSelectedViewModel; // 0x20
	private static DelegateBridge __Hotfix0__CheckPlayerAvatarAvailable; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 groupViewModels { get; }
	public PlayerAvatarItemViewModel selectedItemViewModel { get; }

	// RVA: 0x27247ac VA: 0x7594d3c7ac
	public List`1 get_groupViewModels() { }
	// RVA: 0x2724744 VA: 0x7594d3c744
	public PlayerAvatarItemViewModel get_selectedItemViewModel() { }
	// RVA: 0x272416c VA: 0x7594d3c16c
	public Void InitData() { }
	// RVA: 0x27249b0 VA: 0x7594d3c9b0
	public Void SetSelected(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x272523c VA: 0x7594d3d23c
	private Boolean _CheckIsSelectedViewModel(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x2725138 VA: 0x7594d3d138
	private Boolean _CheckPlayerAvatarAvailable(PlayerAvatarItemViewModel viewModel) { }
	// RVA: 0x2725568 VA: 0x7594d3d568
	public Void .ctor() { }
}
```