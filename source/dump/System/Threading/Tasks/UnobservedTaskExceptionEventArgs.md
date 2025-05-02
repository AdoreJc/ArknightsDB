# UnobservedTaskExceptionEventArgs

**Namespace:** `System.Threading.Tasks`


## Fields

- `AggregateException m_exception`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public class UnobservedTaskExceptionEventArgs : EventArgs
{
	private AggregateException m_exception; // 0x10
	internal Boolean m_observed; // 0x18


	// RVA: 0x61356ac VA: 0x759874d6ac
	public Void .ctor(AggregateException exception) { }
}
```