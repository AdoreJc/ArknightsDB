# UICostPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _costLabel`

- `Image _panelImage`

- `Slider _costSlider`

- `Single _tweenTime`

- `Color _tweenColor`

- `Color _maxCostTweenColor`

- `Image _maxCostIcon`

- `GameObject _maxCostBar`

- `Transform _uiAnchor`

- `Int32 m_cachedCost`

- `Color m_originColor`

- `Tween m_tween`

- `Tween m_maxCostIconTween`

- `Tween m_maxCostBackgroundTween`

- `PlayerSide m_playerSide`


## Properties

- `Transform uiAnchor`


## Methods

- `Transform get_uiAnchor()`

- `Void OnInit(PlayerSide, Boolean)`

- `Void UpdateData(BattleController)`

- `Void _UpdateCost(Int32, Boolean)`

- `Void _OnCostReached(Object)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICostPanel : MonoBehaviour
{
	private Text _costLabel; // 0x18
	private Image _panelImage; // 0x20
	private Slider _costSlider; // 0x28
	private Single _tweenTime; // 0x30
	private Color _tweenColor; // 0x34
	private Color _maxCostTweenColor; // 0x44
	private Image _maxCostIcon; // 0x58
	private GameObject _maxCostBar; // 0x60
	private Transform _uiAnchor; // 0x68
	private Int32 m_cachedCost; // 0x70
	private Color m_originColor; // 0x74
	private Tween m_tween; // 0x88
	private Tween m_maxCostIconTween; // 0x90
	private Tween m_maxCostBackgroundTween; // 0x98
	private PlayerSide m_playerSide; // 0xa0

	public Transform uiAnchor { get; }

	// RVA: 0x207c45c VA: 0x759469445c
	public Transform get_uiAnchor() { }
	// RVA: 0x207c464 VA: 0x7594694464
	public Void OnInit(PlayerSide playerSide, Boolean listenEvent) { }
	// RVA: 0x207c6c8 VA: 0x75946946c8
	public Void UpdateData(BattleController controller) { }
	// RVA: 0x207c618 VA: 0x7594694618
	private Void _UpdateCost(Int32 cost, Boolean force) { }
	// RVA: 0x207c994 VA: 0x7594694994
	private Void _OnCostReached(Object arg) { }
	// RVA: 0x207cc54 VA: 0x7594694c54
	private Void OnDestroy() { }
	// RVA: 0x207cc8c VA: 0x7594694c8c
	public Void .ctor() { }
}
```