# UIDirectionSelector

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollower _follower`

- `TwoStateFadeSwitcher _cancelHintPanel`

- `Character m_dummy`

- `Direction m_currentDirection`

- `Boolean m_canShowCancelHint`


## Properties

- `Boolean isActive`


## Methods

- `Boolean get_isActive()`

- `Void Show(Tile, Character, Action`2)`

- `Void OnCancelled()`

- `Void OnDirectionClicked()`

- `Void OnDirectionHover(Direction)`

- `Void OnJoystickMove(Vector2)`

- `Void OnJoystickUp()`

- `Void _EndInternal(Boolean, Direction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIDirectionSelector : MonoBehaviour
{
	private const Single JOYSTICK_MOVE_THRESHOLD; // 0x0
	private UIFollower _follower; // 0x18
	private UIDirectionArrow[] _arrows; // 0x20
	private TwoStateFadeSwitcher _cancelHintPanel; // 0x28
	private Character m_dummy; // 0x30
	private Action`2 m_callback; // 0x38
	private Direction m_currentDirection; // 0x40
	private Boolean m_canShowCancelHint; // 0x44

	public Boolean isActive { get; }

	// RVA: 0x204ad38 VA: 0x7594662d38
	public Boolean get_isActive() { }
	// RVA: 0x204ad98 VA: 0x7594662d98
	public Void Show(Tile tile, Character dummy, Action`2 cb) { }
	// RVA: 0x204b298 VA: 0x7594663298
	public Void OnCancelled() { }
	// RVA: 0x204b4ec VA: 0x75946634ec
	public Void OnDirectionClicked() { }
	// RVA: 0x204af4c VA: 0x7594662f4c
	public Void OnDirectionHover(Direction direction) { }
	// RVA: 0x204b568 VA: 0x7594663568
	public Void OnJoystickMove(Vector2 offset) { }
	// RVA: 0x204b5b8 VA: 0x75946635b8
	public Void OnJoystickUp() { }
	// RVA: 0x204b418 VA: 0x7594663418
	private Void _EndInternal(Boolean selected, Direction direction) { }
	// RVA: 0x204b62c VA: 0x759466362c
	public Void .ctor() { }
}
```