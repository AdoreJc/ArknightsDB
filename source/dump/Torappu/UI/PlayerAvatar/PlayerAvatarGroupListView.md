# PlayerAvatarGroupListView

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `SimpleLayoutContent _content`

- `UIPlayerAvatarEvent _clickAvatarEvent`

- `String pageName`

- `PlayerAvatarGroupListAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarGroupListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private UIPlayerAvatarEvent _clickAvatarEvent; // 0x20
	public String pageName; // 0x28
	private PlayerAvatarGroupListAdapter m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2725b80 VA: 0x7594d3db80
	private Void _InitIfNot() { }
	// RVA: 0x2724814 VA: 0x7594d3c814
	public Void Render(List`1 viewModelList) { }
	// RVA: 0x2725d6c VA: 0x7594d3dd6c
	public Void .ctor() { }
}
```