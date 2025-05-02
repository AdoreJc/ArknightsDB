# PersistentFileStorage

**Namespace:** `Torappu`


## Fields

- `Boolean m_isDisposed`

- `String m_fileName`

- `String m_fileFolder`


## Methods

- `Void _TryDisposeSelf()`

- `Void Dispose()`

- `OptStatus ReadData(Action`1, Boolean)`

- `OptStatus WriteData(String, Boolean)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class PersistentFileStorage : IDisposable
{
	private const Int32 MAX_RETRY_COUNT; // 0x0
	private const Int32 BUFFER_SIZE; // 0x0
	private static Dictionary`2 s_workingStorages; // 0x0
	private Boolean m_isDisposed; // 0x10
	private String m_fileName; // 0x18
	private String m_fileFolder; // 0x20


	// RVA: 0x6767828 VA: 0x7598d7f828
	private static String _GetFileFolder(String fileName) { }
	// RVA: 0x6767878 VA: 0x7598d7f878
	public static PersistentFileStorage QueryStorage(String fileName) { }
	// RVA: 0x6767a14 VA: 0x7598d7fa14
	public static Boolean DeleteStorage(String fileName) { }
	// RVA: 0x676798c VA: 0x7598d7f98c
	private Void .ctor(String fileName) { }
	// RVA: 0x6767dd4 VA: 0x7598d7fdd4
	private Void _TryDisposeSelf() { }
	// RVA: 0x6767b70 VA: 0x7598d7fb70
	public Void Dispose() { }
	// RVA: 0x6767ef8 VA: 0x7598d7fef8
	public OptStatus ReadData(Action`1 dataHandler, Boolean useRetry) { }
	// RVA: 0x67684d8 VA: 0x7598d804d8
	public OptStatus WriteData(String data, Boolean useRetry) { }
	// RVA: 0x67689b4 VA: 0x7598d809b4
	private static Void .cctor() { }
}
```