# Tween

**Namespace:** ` `


## Fields

- `Action m_onKill`

- `FP m_startValue`

- `FP m_endValue`

- `FP m_duration`

- `EasingFunction m_easeFunc`

- `FP m_delayTime`

- `FP m_accumTime`

- `State m_state`

- `Vector2Bundle m_vec2Bundle`


## Properties

- `Boolean isPlaying`

- `Boolean isStopped`

- `State state`


## Methods

- `Boolean get_isPlaying()`

- `Boolean get_isStopped()`

- `State get_state()`

- `Void set_state(State)`

- `Void Init(FP, Action`1, FP, FP)`

- `Void Init(Vector2, Action`1, Vector2, FP)`

- `Void Tick(FP)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Boolean IsActive()`

- `Void Kill(Boolean)`

- `Tween Play()`

- `Tween SetDelay(FP)`

- `Tween SetEase(EaseType)`

- `Tween OnStop(Action)`

- `Void _OnComplete()`

- `Void <Init>b__20_0(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Tween : ITweenHandler, IReusable
{
	private Action`1 m_onUpdate; // 0x10
	private Action m_onKill; // 0x18
	private FP m_startValue; // 0x20
	private FP m_endValue; // 0x28
	private FP m_duration; // 0x30
	private EasingFunction m_easeFunc; // 0x38
	private FP m_delayTime; // 0x40
	private FP m_accumTime; // 0x48
	private State m_state; // 0x50
	private Vector2Bundle m_vec2Bundle; // 0x58

	public Boolean isPlaying { get; }
	public Boolean isStopped { get; }
	private State state { get; set; }

	// RVA: 0x2d03dc0 VA: 0x759531bdc0
	public Boolean get_isPlaying() { }
	// RVA: 0x2d04080 VA: 0x759531c080
	public Boolean get_isStopped() { }
	// RVA: 0x2d041a0 VA: 0x759531c1a0
	private State get_state() { }
	// RVA: 0x2d041a8 VA: 0x759531c1a8
	private Void set_state(State value) { }
	// RVA: 0x2d03930 VA: 0x759531b930
	public Void Init(FP startValue, Action`1 func, FP endValue, FP duration) { }
	// RVA: 0x2d03b18 VA: 0x759531bb18
	public Void Init(Vector2 startPos, Action`1 func, Vector2 endPos, FP duration) { }
	// RVA: 0x2d03dd0 VA: 0x759531bdd0
	public Void Tick(FP deltaTime) { }
	// RVA: 0x2d04248 VA: 0x759531c248
	public Void OnAllocate() { }
	// RVA: 0x2d04284 VA: 0x759531c284
	public Void OnRecycle() { }
	// RVA: 0x2d0428c VA: 0x759531c28c
	public Boolean IsActive() { }
	// RVA: 0x2d0429c VA: 0x759531c29c
	public Void Kill(Boolean complete) { }
	// RVA: 0x2d042cc VA: 0x759531c2cc
	public Tween Play() { }
	// RVA: 0x2d04370 VA: 0x759531c370
	public Tween SetDelay(FP delay) { }
	// RVA: 0x2d04378 VA: 0x759531c378
	public Tween SetEase(EaseType easeType) { }
	// RVA: 0x2d043c0 VA: 0x759531c3c0
	public Tween OnStop(Action onKill) { }
	// RVA: 0x2d04208 VA: 0x759531c208
	private Void _OnComplete() { }
	// RVA: 0x2d043dc VA: 0x759531c3dc
	public Void .ctor() { }
	// RVA: 0x2d043e4 VA: 0x759531c3e4
	private Void <Init>b__20_0(FP t) { }
}
```