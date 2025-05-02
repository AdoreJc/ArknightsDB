# TaskCanceledException

**Namespace:** `System.Threading.Tasks`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public class TaskCanceledException : OperationCanceledException
{
	private readonly Task _canceledTask; // 0x98


	// RVA: 0x612a400 VA: 0x7598742400
	public Void .ctor() { }
	// RVA: 0x612a44c VA: 0x759874244c
	public Void .ctor(Task task) { }
	// RVA: 0x612a4f8 VA: 0x75987424f8
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
}
```