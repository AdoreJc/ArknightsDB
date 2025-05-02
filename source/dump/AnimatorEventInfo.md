# AnimatorEventInfo

**Namespace:** ` `


## Fields

- `String _stateName`

- `AnimatorStateEvent _stateEvent`

- `Boolean _emitSignal`


## Properties

- `AnimatorStateEvent stateEvent`

- `String stateName`

- `Boolean emitSignal`


## Methods

- `AnimatorStateEvent get_stateEvent()`

- `String get_stateName()`

- `Boolean get_emitSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AnimatorEventInfo
{
	private String _stateName; // 0x10
	private AnimatorStateEvent _stateEvent; // 0x18
	private Boolean _emitSignal; // 0x1c

	public AnimatorStateEvent stateEvent { get; }
	public String stateName { get; }
	public Boolean emitSignal { get; }

	// RVA: 0x3d0872c VA: 0x759632072c
	public AnimatorStateEvent get_stateEvent() { }
	// RVA: 0x3d08734 VA: 0x7596320734
	public String get_stateName() { }
	// RVA: 0x3d0873c VA: 0x759632073c
	public Boolean get_emitSignal() { }
	// RVA: 0x3d08744 VA: 0x7596320744
	public Void .ctor() { }
}
```