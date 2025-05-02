# AsyncLoadRequest

**Namespace:** ` `


## Fields

- `IConverter m_converter`

- `Type m_dbType`


## Methods

- `String GetName()`

- `Object Deserialize(ConverterInput)`

- `Boolean Finish(AsyncLoadResult)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AsyncLoadRequest`1 : IAsyncLoadRequest
{
	private Action`1 m_dataCb; // 0x0
	private IConverter m_converter; // 0x0
	private Type m_dbType; // 0x0


	// RVA: 0x VA: 0x0
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Action`1 dataCallback, IConverter converter, Type dbType) { }
	// RVA: 0x VA: 0x0
	public String GetName() { }
	// RVA: 0x VA: 0x0
	public Object Deserialize(ConverterInput input) { }
	// RVA: 0x VA: 0x0
	public Boolean Finish(AsyncLoadResult result) { }
}
```