# Slider

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Slider : tkControl`2
{
	private readonly Value`1 _min; // 0x0
	private readonly Value`1 _max; // 0x0
	private readonly Func`3 _getValue; // 0x0
	private readonly Action`3 _setValue; // 0x0
	private readonly Value`1 _label; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(Value`1 min, Value`1 max, Func`3 getValue, Action`3 setValue) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Value`1 label, Value`1 min, Value`1 max, Func`3 getValue, Action`3 setValue) { }
	// RVA: 0x VA: 0x0
	protected override T DoEdit(Rect rect, T obj, TContext context, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	protected override Single DoGetHeight(T obj, TContext context, fiGraphMetadata metadata) { }
}
```