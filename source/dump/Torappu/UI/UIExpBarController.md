# UIExpBarController

**Namespace:** `Torappu.UI`


## Fields

- `Tween m_tweener`

- `Single m_tweenProc`

- `Int32 m_targetLevel`

- `Int32 m_targetExp`

- `ControlModel m_controlModel`

- `UIExpBar m_expBar`

- `LevelModel m_levelModelCache`


## Properties

- `Boolean isTweening`


## Methods

- `Boolean get_isTweening()`

- `Void SetToStart()`

- `Int32 TweenAddExpTo(Int32, Int32)`

- `IEnumerator TweenTo(Int32)`

- `Void Render(Single)`

- `Single _ConvertToProc(Int32, Int32)`

- `Void _SetToMaxLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIExpBarController
{
	private const Single TWEEN_DURATION_PER_LEVEL; // 0x0
	private const Single TWEEN_DURATION_MIN; // 0x0
	private Tween m_tweener; // 0x10
	private Single m_tweenProc; // 0x18
	private Int32 m_targetLevel; // 0x1c
	private Int32 m_targetExp; // 0x20
	private ControlModel m_controlModel; // 0x28
	private UIExpBar m_expBar; // 0x30
	private LevelModel m_levelModelCache; // 0x38
	private const Int32 PROGRESS; // 0x0

	public Boolean isTweening { get; }

	// RVA: 0x2246d8c VA: 0x759485ed8c
	public Void .ctor(UIExpBar expBar, ControlModel controlModel) { }
	// RVA: 0x2246f24 VA: 0x759485ef24
	public Boolean get_isTweening() { }
	// RVA: 0x2246f38 VA: 0x759485ef38
	public Void SetToStart() { }
	// RVA: 0x2247304 VA: 0x759485f304
	public Int32 TweenAddExpTo(Int32 level, Int32 exp) { }
	// RVA: 0x2247428 VA: 0x759485f428
	private IEnumerator TweenTo(Int32 lvlAdditive) { }
	// RVA: 0x2247008 VA: 0x759485f008
	public Void Render(Single levelProc) { }
	// RVA: 0x2246f60 VA: 0x759485ef60
	private Single _ConvertToProc(Int32 level, Int32 exp) { }
	// RVA: 0x22474d4 VA: 0x759485f4d4
	private Void _SetToMaxLevel() { }
}
```