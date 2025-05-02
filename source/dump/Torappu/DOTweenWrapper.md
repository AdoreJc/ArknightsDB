# DOTweenWrapper

**Namespace:** `Torappu`


## Fields

- `Tween m_internalTween`


## Methods

- `Boolean IsActive()`

- `Void Kill(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DOTweenWrapper : ITweenHandler
{
	private Tween m_internalTween; // 0x10


	// RVA: 0x2d035c8 VA: 0x759531b5c8
	private Void .ctor(Tween tween) { }
	// RVA: 0x2d035f8 VA: 0x759531b5f8
	public Boolean IsActive() { }
	// RVA: 0x2d03604 VA: 0x759531b604
	public Void Kill(Boolean complete) { }
	// RVA: 0x2d03614 VA: 0x759531b614
	public static ITweenHandler Wrap(Tween tween) { }
}
```