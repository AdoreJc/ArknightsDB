# BattleTweenMgr

**Namespace:** `Torappu`


## Methods

- `Tween To(FP, Action`1, FP, FP)`

- `Tween To(Vector2, Action`1, Vector2, FP)`

- `Void Tick(FP)`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BattleTweenMgr
{
	private ObjectPool`1 m_tweenPool; // 0x10
	private List`1 m_tweenList; // 0x18


	// RVA: 0x2d03684 VA: 0x759531b684
	public Void .ctor(Int32 preloadSize) { }
	// RVA: 0x2d03820 VA: 0x759531b820
	public Tween To(FP startValue, Action`1 func, FP endValue, FP duration) { }
	// RVA: 0x2d039f0 VA: 0x759531b9f0
	public Tween To(Vector2 startPos, Action`1 func, Vector2 endPos, FP duration) { }
	// RVA: 0x2d03c8c VA: 0x759531bc8c
	public Void Tick(FP deltaTime) { }
	// RVA: 0x2d04090 VA: 0x759531c090
	public Void Reset() { }
}
```