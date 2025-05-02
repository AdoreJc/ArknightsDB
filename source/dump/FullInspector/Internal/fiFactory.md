# fiFactory

**Namespace:** `FullInspector.Internal`


## Methods

- `T GetInstance()`

- `Void ReuseInstance(T)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiFactory`1
{
	private Stack`1 _reusable; // 0x0
	private Action`1 _reset; // 0x0
	private Object[] _constructArgs; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor(Action`1 reset, Object[] constructArgs) { }
	// RVA: 0x VA: 0x0
	public T GetInstance() { }
	// RVA: 0x VA: 0x0
	public Void ReuseInstance(T instance) { }
}
```