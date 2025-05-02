# UIBattleUnderframePanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Transform _root`

- `Image _btnImage`

- `Image _btnShadowImage`

- `Follower2D _follower`

- `GameObject _blocker`

- `Button _withdrawButton`

- `Action onButtonClick`

- `Sprite m_defaultIcon`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Param)`

- `Void Hide()`

- `Void OnButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleUnderframePanel : MonoBehaviour, IHotfixable
{
	private Transform _root; // 0x18
	private Image _btnImage; // 0x20
	private Image _btnShadowImage; // 0x28
	private Follower2D _follower; // 0x30
	private GameObject _blocker; // 0x38
	private Button _withdrawButton; // 0x40
	private Action onButtonClick; // 0x48
	private Sprite m_defaultIcon; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0_OnButtonClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2048a24 VA: 0x7594660a24
	private Void _InitIfNot() { }
	// RVA: 0x2048ab4 VA: 0x7594660ab4
	public Void Render(Param param) { }
	// RVA: 0x2048ca0 VA: 0x7594660ca0
	public Void Hide() { }
	// RVA: 0x2048d60 VA: 0x7594660d60
	public Void OnButtonClick() { }
	// RVA: 0x2048dcc VA: 0x7594660dcc
	public Void .ctor() { }
}
```