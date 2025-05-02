# UICooperateBattlePinMarkMenu

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `CanvasGroup _leftMenu`

- `CanvasGroup _rightMenu`

- `Follower2D _follower`

- `Single _tweenDuration`

- `Tween m_tween`

- `CanvasGroup m_curMenu`

- `Tile m_curTile`


## Methods

- `Void SetToTile(Tile, Action`2)`

- `Void OnButtonClicked(Int32)`

- `Void ClearMenu()`

- `Void _ShowMenu(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattlePinMarkMenu : MonoBehaviour, IHotfixable
{
	private CanvasGroup _leftMenu; // 0x18
	private CanvasGroup _rightMenu; // 0x20
	private Follower2D _follower; // 0x28
	private Single _tweenDuration; // 0x30
	private Tween m_tween; // 0x38
	private CanvasGroup m_curMenu; // 0x40
	private Tile m_curTile; // 0x48
	private Action`2 m_pinAction; // 0x50
	private static DelegateBridge __Hotfix0_SetToTile; // 0x0
	private static DelegateBridge __Hotfix0_OnButtonClicked; // 0x8
	private static DelegateBridge __Hotfix0_ClearMenu; // 0x10
	private static DelegateBridge __Hotfix0__ShowMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20dde2c VA: 0x75946f5e2c
	public Void SetToTile(Tile tile, Action`2 action) { }
	// RVA: 0x20e470c VA: 0x75946fc70c
	public Void OnButtonClicked(Int32 type) { }
	// RVA: 0x20dd880 VA: 0x75946f5880
	public Void ClearMenu() { }
	// RVA: 0x20e44cc VA: 0x75946fc4cc
	private Void _ShowMenu(Tile tile) { }
	// RVA: 0x20e48d4 VA: 0x75946fc8d4
	public Void .ctor() { }
}
```