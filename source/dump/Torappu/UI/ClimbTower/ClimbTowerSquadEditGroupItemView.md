# ClimbTowerSquadEditGroupItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgProfession`

- `SimpleLayoutContent _charList`

- `GridLayoutGroup _gridLayout`

- `Boolean m_hasInited`

- `SpriteHub m_professionHub`

- `Adapter m_adapter`

- `Int32 m_viewIndex`

- `Int64 m_cachedGameStartTs`


## Properties

- `GridLayoutGroup gridLayout`


## Methods

- `GridLayoutGroup get_gridLayout()`

- `Void set_onCharClick(Action`1)`

- `Void Render(ProfessionCategory, List`1, SpriteHub, Int64)`

- `Void SetViewIndex(Int32)`

- `Int32 GetViewIndex()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadEditGroupItemView : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private SimpleLayoutContent _charList; // 0x20
	private GridLayoutGroup _gridLayout; // 0x28
	private Boolean m_hasInited; // 0x30
	private List`1 m_characterList; // 0x38
	private SpriteHub m_professionHub; // 0x40
	private Adapter m_adapter; // 0x48
	private Int32 m_viewIndex; // 0x50
	private Int64 m_cachedGameStartTs; // 0x58
	private Action`1 <onCharClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_gridLayout; // 0x0
	private static DelegateBridge __Hotfix0_get_onCharClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onCharClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_SetViewIndex; // 0x20
	private static DelegateBridge __Hotfix0_GetViewIndex; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public GridLayoutGroup gridLayout { get; }
	private Action`1 onCharClick { get; set; }

	// RVA: 0x2cb8b88 VA: 0x75952d0b88
	public GridLayoutGroup get_gridLayout() { }
	// RVA: 0x2cb8bf0 VA: 0x75952d0bf0
	private Action`1 get_onCharClick() { }
	// RVA: 0x2cb8c58 VA: 0x75952d0c58
	public Void set_onCharClick(Action`1 value) { }
	// RVA: 0x2cb8cdc VA: 0x75952d0cdc
	public Void Render(ProfessionCategory profession, List`1 characterList, SpriteHub professionSpriteHub, Int64 gameStartTs) { }
	// RVA: 0x2cb8ec8 VA: 0x75952d0ec8
	public Void SetViewIndex(Int32 viewIndex) { }
	// RVA: 0x2cb8f44 VA: 0x75952d0f44
	public Int32 GetViewIndex() { }
	// RVA: 0x2cb8df8 VA: 0x75952d0df8
	private Void _InitIfNot() { }
	// RVA: 0x2cb9040 VA: 0x75952d1040
	public Void .ctor() { }
}
```