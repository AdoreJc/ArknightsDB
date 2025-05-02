# PlayerAvatarGroupView

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `Text _titleText`

- `SimpleLayoutContent _content`

- `UIPlayerAvatarEvent clickEvent`

- `String pageName`

- `PlayerAvatarGroupViewModel m_viewModel`

- `AvatarAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(PlayerAvatarGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarGroupView : MonoBehaviour, IHotfixable
{
	private Text _titleText; // 0x18
	private SimpleLayoutContent _content; // 0x20
	public UIPlayerAvatarEvent clickEvent; // 0x28
	public String pageName; // 0x30
	private PlayerAvatarGroupViewModel m_viewModel; // 0x38
	private AvatarAdapter m_adapter; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2726190 VA: 0x7594d3e190
	private Void _InitIfNot() { }
	// RVA: 0x2726098 VA: 0x7594d3e098
	public Void Render(PlayerAvatarGroupViewModel viewModel) { }
	// RVA: 0x27262e4 VA: 0x7594d3e2e4
	public Void .ctor() { }
}
```