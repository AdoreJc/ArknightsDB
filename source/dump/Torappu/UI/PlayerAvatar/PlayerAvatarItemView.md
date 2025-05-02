# PlayerAvatarItemView

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `RectTransform _selectTransform`

- `Image _avatarImage`

- `GameObject _hotspot`

- `UIPlayerAvatarEvent clickEvent`

- `PlayerAvatarItemViewModel m_viewModel`


## Methods

- `Void Render(PlayerAvatarItemViewModel, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _selectTransform; // 0x18
	private Image _avatarImage; // 0x20
	private GameObject _hotspot; // 0x28
	public UIPlayerAvatarEvent clickEvent; // 0x30
	private PlayerAvatarItemViewModel m_viewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2726594 VA: 0x7594d3e594
	public Void Render(PlayerAvatarItemViewModel viewModel, String pageName) { }
	// RVA: 0x2726784 VA: 0x7594d3e784
	public Void OnClick() { }
	// RVA: 0x272681c VA: 0x7594d3e81c
	public Void .ctor() { }
}
```