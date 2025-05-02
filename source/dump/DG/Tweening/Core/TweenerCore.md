# TweenerCore

**Namespace:** `DG.Tweening.Core`


## Fields

- `T2 startValue`

- `T2 endValue`

- `T2 changeValue`

- `TPlugOptions plugOptions`

- `Type _colorType`

- `Type _color32Type`


## Methods

- `Boolean ValidateChangeValueType(Type, out)`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening.Core
public class TweenerCore`3 : Tweener
{
	public T2 startValue; // 0x0
	public T2 endValue; // 0x0
	public T2 changeValue; // 0x0
	public TPlugOptions plugOptions; // 0x0
	public DOGetter`1 getter; // 0x0
	public DOSetter`1 setter; // 0x0
	internal ABSTweenPlugin`3 tweenPlugin; // 0x0
	private const String _TxtCantChangeSequencedValues; // 0x0
	private Type _colorType; // 0x0
	private Type _color32Type; // 0x0


	// RVA: 0x VA: 0x0
	internal Void .ctor() { }
	// RVA: 0x VA: 0x0
	public override Tweener ChangeStartValue(Object newStartValue, Single newDuration) { }
	// RVA: 0x VA: 0x0
	public override Tweener ChangeEndValue(Object newEndValue, Boolean snapStartValue) { }
	// RVA: 0x VA: 0x0
	public override Tweener ChangeEndValue(Object newEndValue, Single newDuration, Boolean snapStartValue) { }
	// RVA: 0x VA: 0x0
	public override Tweener ChangeValues(Object newStartValue, Object newEndValue, Single newDuration) { }
	// RVA: 0x VA: 0x0
	public TweenerCore`3 ChangeStartValue(T2 newStartValue, Single newDuration) { }
	// RVA: 0x VA: 0x0
	public TweenerCore`3 ChangeEndValue(T2 newEndValue, Boolean snapStartValue) { }
	// RVA: 0x VA: 0x0
	public TweenerCore`3 ChangeEndValue(T2 newEndValue, Single newDuration, Boolean snapStartValue) { }
	// RVA: 0x VA: 0x0
	public TweenerCore`3 ChangeValues(T2 newStartValue, T2 newEndValue, Single newDuration) { }
	// RVA: 0x VA: 0x0
	internal override Tweener SetFrom(Boolean relative) { }
	// RVA: 0x VA: 0x0
	internal Tweener SetFrom(T2 fromValue, Boolean setImmediately, Boolean relative) { }
	// RVA: 0x VA: 0x0
	internal sealed override Void Reset() { }
	// RVA: 0x VA: 0x0
	internal override Boolean Validate() { }
	// RVA: 0x VA: 0x0
	private Boolean ValidateChangeValueType(Type newType, out Boolean isColor32ToColor) { }
	// RVA: 0x VA: 0x0
	internal override Single UpdateDelay(Single elapsed) { }
	// RVA: 0x VA: 0x0
	internal override Boolean Startup() { }
	// RVA: 0x VA: 0x0
	internal override Boolean ApplyTween(Single prevPosition, Int32 prevCompletedLoops, Int32 newCompletedSteps, Boolean useInversePosition, UpdateMode updateMode, UpdateNotice updateNotice) { }
}
```