# FaceSwitcher

**Namespace:** `Torappu.Battle`


## Fields

- `Single _switchTime`

- `Direction _defaultLOrR`

- `Direction m_currentUOrD`

- `Direction m_currentLOrR`

- `Boolean m_firstTouch`

- `ITweenHandler m_lastTween`

- `UnitAnimator <animator>k__BackingField`


## Properties

- `Int32 faceSign`

- `Direction currentLOrR`

- `UnitAnimator animator`


## Methods

- `Int32 get_faceSign()`

- `Direction get_currentLOrR()`

- `UnitAnimator get_animator()`

- `Void set_animator(UnitAnimator)`

- `Void Reset()`

- `Void StartSwitch(Direction, Direction, Boolean, Boolean, Action`2)`

- `Boolean _TryUpdateDirection(Direction, Direction, Boolean, out)`

- `Void _DoSwitchFaceInternal(Boolean, Action`2)`

- `Void _KillLastTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FaceSwitcher : MonoBehaviour
{
	private Single _switchTime; // 0x18
	private Direction _defaultLOrR; // 0x1c
	private Direction m_currentUOrD; // 0x20
	private Direction m_currentLOrR; // 0x24
	private Boolean m_firstTouch; // 0x28
	private ITweenHandler m_lastTween; // 0x30
	private UnitAnimator <animator>k__BackingField; // 0x38

	public Int32 faceSign { get; }
	public Direction currentLOrR { get; }
	private UnitAnimator animator { get; set; }

	// RVA: 0x3f2bc8c VA: 0x7596543c8c
	public Int32 get_faceSign() { }
	// RVA: 0x3f2e70c VA: 0x759654670c
	public Direction get_currentLOrR() { }
	// RVA: 0x3f2e714 VA: 0x7596546714
	private UnitAnimator get_animator() { }
	// RVA: 0x3f2e71c VA: 0x759654671c
	private Void set_animator(UnitAnimator value) { }
	// RVA: 0x3f2c5fc VA: 0x75965445fc
	public Void Reset() { }
	// RVA: 0x3f2c9f8 VA: 0x75965449f8
	public Void StartSwitch(Direction lOrR, Direction fourDir, Boolean immediately, Boolean idle, Action`2 onSwitchFace) { }
	// RVA: 0x3f2e7e4 VA: 0x75965467e4
	private Boolean _TryUpdateDirection(Direction lOrR, Direction fourDir, Boolean idle, out Boolean clockwise) { }
	// RVA: 0x3f2e8ec VA: 0x75965468ec
	private Void _DoSwitchFaceInternal(Boolean clockwise, Action`2 onSwitchFace) { }
	// RVA: 0x3f2e724 VA: 0x7596546724
	private Void _KillLastTween() { }
	// RVA: 0x3f2efa8 VA: 0x7596546fa8
	public Void .ctor() { }
}
```