# UIAnimationPerform

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Animation _animation`

- `Boolean _useWrapper`

- `AnimationWrapper _animationWrapper`

- `String _wrapperAnimKey`

- `Boolean _setFixedUpdateMode`


## Properties

- `Boolean useWrapper`


## Methods

- `Boolean get_useWrapper()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIAnimationPerform : UIPerform
{
	private Animation _animation; // 0x38
	private Boolean _useWrapper; // 0x40
	private AnimationWrapper _animationWrapper; // 0x48
	private String _wrapperAnimKey; // 0x50
	private Boolean _setFixedUpdateMode; // 0x58

	private Boolean useWrapper { get; }

	// RVA: 0x2051f44 VA: 0x7594669f44
	private Boolean get_useWrapper() { }
	// RVA: 0x2051f4c VA: 0x7594669f4c
	protected override Void DoPlay() { }
	// RVA: 0x20520b0 VA: 0x759466a0b0
	protected override Void DoComplete() { }
	// RVA: 0x20520d4 VA: 0x759466a0d4
	protected override Void DoKill() { }
	// RVA: 0x20520f8 VA: 0x759466a0f8
	public override Void OnUpdate(Single deltaTime) { }
	// RVA: 0x2052138 VA: 0x759466a138
	public Void .ctor() { }
}
```