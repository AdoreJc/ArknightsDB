# UIDirectionArrow

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Color _normalColor`

- `Color _highlightColor`

- `Image _fillBack`

- `Image m_image`

- `Direction m_direction`

- `UIDirectionSelector m_selector`

- `Boolean m_isHover`


## Properties

- `Boolean isHover`


## Methods

- `Boolean get_isHover()`

- `Void set_isHover(Boolean)`

- `Void SetData(Direction, UIDirectionSelector)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIDirectionArrow : MonoBehaviour
{
	private Color _normalColor; // 0x18
	private Color _highlightColor; // 0x28
	private Image _fillBack; // 0x38
	private Image m_image; // 0x40
	private Direction m_direction; // 0x48
	private UIDirectionSelector m_selector; // 0x50
	private Boolean m_isHover; // 0x58

	public Boolean isHover { get; set; }

	// RVA: 0x207d0a4 VA: 0x75946950a4
	public Boolean get_isHover() { }
	// RVA: 0x207d0ac VA: 0x75946950ac
	public Void set_isHover(Boolean value) { }
	// RVA: 0x207d1a0 VA: 0x75946951a0
	public Void SetData(Direction direction, UIDirectionSelector selector) { }
	// RVA: 0x207d1fc VA: 0x75946951fc
	private Void Awake() { }
	// RVA: 0x207d254 VA: 0x7594695254
	public Void .ctor() { }
}
```