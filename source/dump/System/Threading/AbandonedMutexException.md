# AbandonedMutexException

**Namespace:** `System.Threading`


## Fields

- `Int32 _mutexIndex`

- `Mutex _mutex`


## Methods

- `Void SetupException(Int32, WaitHandle)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
public class AbandonedMutexException : SystemException
{
	private Int32 _mutexIndex; // 0x8c
	private Mutex _mutex; // 0x90


	// RVA: 0x6118090 VA: 0x7598730090
	public Void .ctor() { }
	// RVA: 0x61180f4 VA: 0x75987300f4
	public Void .ctor(Int32 location, WaitHandle handle) { }
	// RVA: 0x6118200 VA: 0x7598730200
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6118174 VA: 0x7598730174
	private Void SetupException(Int32 location, WaitHandle handle) { }
}
```