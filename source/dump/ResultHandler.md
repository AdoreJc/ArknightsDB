# ResultHandler

**Namespace:** ` `


## Fields

- `Action <onFinal>k__BackingField`

- `LoadMaskType loadMaskType`

- `ConcurrentType concurrentType`

- `MetaFlags metaFlags`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ResultHandler`1
{
	private Action`1 <onProceed>k__BackingField; // 0x0
	private Func`2 <onBlock>k__BackingField; // 0x0
	private Action <onFinal>k__BackingField; // 0x0
	public LoadMaskType loadMaskType; // 0x0
	public ConcurrentType concurrentType; // 0x0
	private Action`1 <beforeServiceFinish>k__BackingField; // 0x0
	public MetaFlags metaFlags; // 0x0

	public virtual Action`1 onProceed { get; set; }
	public virtual Func`2 onBlock { get; set; }
	public virtual Action onFinal { get; set; }
	public virtual Action`1 beforeServiceFinish { get; set; }

	// RVA: 0x VA: 0x0
	public virtual Action`1 get_onProceed() { }
	// RVA: 0x VA: 0x0
	public virtual Void set_onProceed(Action`1 value) { }
	// RVA: 0x VA: 0x0
	public virtual Func`2 get_onBlock() { }
	// RVA: 0x VA: 0x0
	public virtual Void set_onBlock(Func`2 value) { }
	// RVA: 0x VA: 0x0
	public virtual Action get_onFinal() { }
	// RVA: 0x VA: 0x0
	public virtual Void set_onFinal(Action value) { }
	// RVA: 0x VA: 0x0
	public virtual Action SystemCancelHandler() { }
	// RVA: 0x VA: 0x0
	public virtual Action`1 get_beforeServiceFinish() { }
	// RVA: 0x VA: 0x0
	public virtual Void set_beforeServiceFinish(Action`1 value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```