# TweenParams

**Namespace:** `DG.Tweening`


## Methods

- `TweenParams Clear()`

- `TweenParams SetAutoKill(Boolean)`

- `TweenParams SetId(Object)`

- `TweenParams SetId(String)`

- `TweenParams SetId(Int32)`

- `TweenParams SetTarget(Object)`

- `TweenParams SetLoops(Int32, Nullable`1)`

- `TweenParams SetEase(Ease, Nullable`1, Nullable`1)`

- `TweenParams SetEase(AnimationCurve)`

- `TweenParams SetEase(EaseFunction)`

- `TweenParams SetRecyclable(Boolean)`

- `TweenParams SetUpdate(Boolean)`

- `TweenParams SetUpdate(UpdateType, Boolean)`

- `TweenParams OnStart(TweenCallback)`

- `TweenParams OnPlay(TweenCallback)`

- `TweenParams OnRewind(TweenCallback)`

- `TweenParams OnUpdate(TweenCallback)`

- `TweenParams OnStepComplete(TweenCallback)`

- `TweenParams OnComplete(TweenCallback)`

- `TweenParams OnKill(TweenCallback)`

- `TweenParams OnWaypointChange(TweenCallback`1)`

- `TweenParams SetDelay(Single)`

- `TweenParams SetRelative(Boolean)`

- `TweenParams SetSpeedBased(Boolean)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening
public class TweenParams
{
	public static readonly TweenParams Params; // 0x0
	internal Object id; // 0x10
	internal String stringId; // 0x18
	internal Int32 intId; // 0x20
	internal Object target; // 0x28
	internal UpdateType updateType; // 0x30
	internal Boolean isIndependentUpdate; // 0x34
	internal TweenCallback onStart; // 0x38
	internal TweenCallback onPlay; // 0x40
	internal TweenCallback onRewind; // 0x48
	internal TweenCallback onUpdate; // 0x50
	internal TweenCallback onStepComplete; // 0x58
	internal TweenCallback onComplete; // 0x60
	internal TweenCallback onKill; // 0x68
	internal TweenCallback`1 onWaypointChange; // 0x70
	internal Boolean isRecyclable; // 0x78
	internal Boolean isSpeedBased; // 0x79
	internal Boolean autoKill; // 0x7a
	internal Int32 loops; // 0x7c
	internal LoopType loopType; // 0x80
	internal Single delay; // 0x84
	internal Boolean isRelative; // 0x88
	internal Ease easeType; // 0x8c
	internal EaseFunction customEase; // 0x90
	internal Single easeOvershootOrAmplitude; // 0x98
	internal Single easePeriod; // 0x9c


	// RVA: 0x417ad7c VA: 0x7596792d7c
	public Void .ctor() { }
	// RVA: 0x417ada0 VA: 0x7596792da0
	public TweenParams Clear() { }
	// RVA: 0x417af1c VA: 0x7596792f1c
	public TweenParams SetAutoKill(Boolean autoKillOnCompletion) { }
	// RVA: 0x417af28 VA: 0x7596792f28
	public TweenParams SetId(Object objectId) { }
	// RVA: 0x417af44 VA: 0x7596792f44
	public TweenParams SetId(String stringId) { }
	// RVA: 0x417af60 VA: 0x7596792f60
	public TweenParams SetId(Int32 intId) { }
	// RVA: 0x417af68 VA: 0x7596792f68
	public TweenParams SetTarget(Object target) { }
	// RVA: 0x417af84 VA: 0x7596792f84
	public TweenParams SetLoops(Int32 loops, Nullable`1 loopType) { }
	// RVA: 0x417b014 VA: 0x7596793014
	public TweenParams SetEase(Ease ease, Nullable`1 overshootOrAmplitude, Nullable`1 period) { }
	// RVA: 0x417b118 VA: 0x7596793118
	public TweenParams SetEase(AnimationCurve animCurve) { }
	// RVA: 0x417b1e4 VA: 0x75967931e4
	public TweenParams SetEase(EaseFunction customEase) { }
	// RVA: 0x417b208 VA: 0x7596793208
	public TweenParams SetRecyclable(Boolean recyclable) { }
	// RVA: 0x417b214 VA: 0x7596793214
	public TweenParams SetUpdate(Boolean isIndependentUpdate) { }
	// RVA: 0x417b288 VA: 0x7596793288
	public TweenParams SetUpdate(UpdateType updateType, Boolean isIndependentUpdate) { }
	// RVA: 0x417b298 VA: 0x7596793298
	public TweenParams OnStart(TweenCallback action) { }
	// RVA: 0x417b2b4 VA: 0x75967932b4
	public TweenParams OnPlay(TweenCallback action) { }
	// RVA: 0x417b2d0 VA: 0x75967932d0
	public TweenParams OnRewind(TweenCallback action) { }
	// RVA: 0x417b2ec VA: 0x75967932ec
	public TweenParams OnUpdate(TweenCallback action) { }
	// RVA: 0x417b308 VA: 0x7596793308
	public TweenParams OnStepComplete(TweenCallback action) { }
	// RVA: 0x417b324 VA: 0x7596793324
	public TweenParams OnComplete(TweenCallback action) { }
	// RVA: 0x417b340 VA: 0x7596793340
	public TweenParams OnKill(TweenCallback action) { }
	// RVA: 0x417b35c VA: 0x759679335c
	public TweenParams OnWaypointChange(TweenCallback`1 action) { }
	// RVA: 0x417b378 VA: 0x7596793378
	public TweenParams SetDelay(Single delay) { }
	// RVA: 0x417b380 VA: 0x7596793380
	public TweenParams SetRelative(Boolean isRelative) { }
	// RVA: 0x417b38c VA: 0x759679338c
	public TweenParams SetSpeedBased(Boolean isSpeedBased) { }
	// RVA: 0x417b398 VA: 0x7596793398
	private static Void .cctor() { }
}
```