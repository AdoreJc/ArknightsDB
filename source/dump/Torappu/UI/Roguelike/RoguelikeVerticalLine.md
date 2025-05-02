# RoguelikeVerticalLine

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _backImg`

- `Image _upArrowImg`

- `Image _downArrowImg`

- `RectTransform m_startNode`

- `RectTransform m_endNode`

- `Color <arrowColor>k__BackingField`

- `Color <lineColor>k__BackingField`

- `Boolean <showArrowFlag>k__BackingField`

- `Vector3 m_startPos`

- `Vector3 m_endPos`


## Properties

- `Color arrowColor`

- `Color lineColor`

- `Boolean showArrowFlag`

- `RectTransform startNode`

- `RectTransform endNode`


## Methods

- `Color get_arrowColor()`

- `Void set_arrowColor(Color)`

- `Color get_lineColor()`

- `Void set_lineColor(Color)`

- `Boolean get_showArrowFlag()`

- `Void set_showArrowFlag(Boolean)`

- `RectTransform get_startNode()`

- `Void set_startNode(RectTransform)`

- `RectTransform get_endNode()`

- `Void set_endNode(RectTransform)`

- `Void Render(Config, VertType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeVerticalLine : MonoBehaviour, IHotfixable
{
	private Image _backImg; // 0x18
	private Image _upArrowImg; // 0x20
	private Image _downArrowImg; // 0x28
	private RectTransform m_startNode; // 0x30
	private RectTransform m_endNode; // 0x38
	private Color <arrowColor>k__BackingField; // 0x40
	private Color <lineColor>k__BackingField; // 0x50
	private Boolean <showArrowFlag>k__BackingField; // 0x60
	private Vector3 m_startPos; // 0x64
	private Vector3 m_endPos; // 0x70
	private static DelegateBridge __Hotfix0_get_arrowColor; // 0x0
	private static DelegateBridge __Hotfix0_set_arrowColor; // 0x8
	private static DelegateBridge __Hotfix0_get_lineColor; // 0x10
	private static DelegateBridge __Hotfix0_set_lineColor; // 0x18
	private static DelegateBridge __Hotfix0_get_showArrowFlag; // 0x20
	private static DelegateBridge __Hotfix0_set_showArrowFlag; // 0x28
	private static DelegateBridge __Hotfix0_get_startNode; // 0x30
	private static DelegateBridge __Hotfix0_set_startNode; // 0x38
	private static DelegateBridge __Hotfix0_get_endNode; // 0x40
	private static DelegateBridge __Hotfix0_set_endNode; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Color arrowColor { get; set; }
	public Color lineColor { get; set; }
	public Boolean showArrowFlag { get; set; }
	public RectTransform startNode { get; set; }
	public RectTransform endNode { get; set; }

	// RVA: 0x2a2180c VA: 0x759503980c
	public Color get_arrowColor() { }
	// RVA: 0x2a21874 VA: 0x7595039874
	public Void set_arrowColor(Color value) { }
	// RVA: 0x2a21918 VA: 0x7595039918
	public Color get_lineColor() { }
	// RVA: 0x2a21980 VA: 0x7595039980
	public Void set_lineColor(Color value) { }
	// RVA: 0x2a21a24 VA: 0x7595039a24
	public Boolean get_showArrowFlag() { }
	// RVA: 0x2a21a8c VA: 0x7595039a8c
	public Void set_showArrowFlag(Boolean value) { }
	// RVA: 0x2a21b0c VA: 0x7595039b0c
	public RectTransform get_startNode() { }
	// RVA: 0x2a21b74 VA: 0x7595039b74
	public Void set_startNode(RectTransform value) { }
	// RVA: 0x2a21bf8 VA: 0x7595039bf8
	public RectTransform get_endNode() { }
	// RVA: 0x2a21c60 VA: 0x7595039c60
	public Void set_endNode(RectTransform value) { }
	// RVA: 0x2a21ce4 VA: 0x7595039ce4
	public Void Render(Config colorConfig, VertType lineType) { }
	// RVA: 0x2a21e54 VA: 0x7595039e54
	public Void .ctor() { }
}
```