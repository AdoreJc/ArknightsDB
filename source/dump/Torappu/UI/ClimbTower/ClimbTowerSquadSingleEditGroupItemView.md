# ClimbTowerSquadSingleEditGroupItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgProfession`

- `SimpleLayoutContent _charList`

- `GridLayoutGroup _gridLayout`

- `Boolean m_hasInited`

- `SpriteHub m_professionHub`

- `Int32 m_selectCardId`

- `Adapter m_adapter`

- `Int64 m_cachedGameStartTs`


## Properties

- `GridLayoutGroup gridLayout`


## Methods

- `Void set_onCharSelect(Action`1)`

- `GridLayoutGroup get_gridLayout()`

- `Void InitView(ProfessionCategory, List`1, SpriteHub, Int64)`

- `Void Refresh(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditGroupItemView : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private SimpleLayoutContent _charList; // 0x20
	private GridLayoutGroup _gridLayout; // 0x28
	private Action`1 <onCharSelect>k__BackingField; // 0x30
	private Boolean m_hasInited; // 0x38
	private List`1 m_characterList; // 0x40
	private SpriteHub m_professionHub; // 0x48
	private Int32 m_selectCardId; // 0x50
	private Adapter m_adapter; // 0x58
	private Int64 m_cachedGameStartTs; // 0x60
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_gridLayout; // 0x10
	private static DelegateBridge __Hotfix0_InitView; // 0x18
	private static DelegateBridge __Hotfix0_Refresh; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onCharSelect { get; set; }
	public GridLayoutGroup gridLayout { get; }

	// RVA: 0x2cc96c4 VA: 0x75952e16c4
	private Action`1 get_onCharSelect() { }
	// RVA: 0x2cc8e70 VA: 0x75952e0e70
	public Void set_onCharSelect(Action`1 value) { }
	// RVA: 0x2cc8d40 VA: 0x75952e0d40
	public GridLayoutGroup get_gridLayout() { }
	// RVA: 0x2cc8ef4 VA: 0x75952e0ef4
	public Void InitView(ProfessionCategory profession, List`1 charList, SpriteHub professionSpriteHub, Int64 gameStartTs) { }
	// RVA: 0x2cc8ffc VA: 0x75952e0ffc
	public Void Refresh(Int32 selectCardId) { }
	// RVA: 0x2cc972c VA: 0x75952e172c
	private Void _InitIfNot() { }
	// RVA: 0x2cc9890 VA: 0x75952e1890
	public Void .ctor() { }
}
```