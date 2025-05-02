# ClimbTowerSquadSingleEditCharItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `RectTransform _charCardRoot`

- `Single _charCardScale`

- `GameObject _selectGo`

- `GameObject _trackNewGo`

- `UICharacterCardPanel m_charCard`

- `Boolean m_hasInited`

- `ClimbTowerSquadItemModel m_squadItemModel`

- `Boolean m_isSelect`


## Methods

- `Void set_onCharSelect(Action`1)`

- `Void UpdateViewData(ClimbTowerSquadItemModel, Int32)`

- `Void _InitIfNot()`

- `Void _OnCharClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditCharItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _charCardRoot; // 0x18
	private Single _charCardScale; // 0x20
	private GameObject _selectGo; // 0x28
	private GameObject _trackNewGo; // 0x30
	private UICharacterCardPanel m_charCard; // 0x38
	private Boolean m_hasInited; // 0x40
	private ClimbTowerSquadItemModel m_squadItemModel; // 0x48
	private Boolean m_isSelect; // 0x50
	private Action`1 <onCharSelect>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onCharSelect; // 0x8
	private static DelegateBridge __Hotfix0_UpdateViewData; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnCharClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onCharSelect { get; set; }

	// RVA: 0x2cc90f0 VA: 0x75952e10f0
	private Action`1 get_onCharSelect() { }
	// RVA: 0x2cc9158 VA: 0x75952e1158
	public Void set_onCharSelect(Action`1 value) { }
	// RVA: 0x2cc91dc VA: 0x75952e11dc
	public Void UpdateViewData(ClimbTowerSquadItemModel squadItemModel, Int32 selectCardId) { }
	// RVA: 0x2cc9344 VA: 0x75952e1344
	private Void _InitIfNot() { }
	// RVA: 0x2cc956c VA: 0x75952e156c
	private Void _OnCharClick(Int32 _) { }
	// RVA: 0x2cc9648 VA: 0x75952e1648
	public Void .ctor() { }
}
```