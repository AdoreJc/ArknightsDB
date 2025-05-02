# UnzipInterface

**Namespace:** ` `


## Fields

- `BuildinDownloadInterface m_closure`


## Methods

- `Single GetProgress()`

- `Boolean IsWorking()`

- `UnzipError GetErrorInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnzipInterface : IUnzipInterface
{
	private BuildinDownloadInterface m_closure; // 0x10


	// RVA: 0x373a834 VA: 0x7595d52834
	public Void .ctor(BuildinDownloadInterface closure) { }
	// RVA: 0x373a864 VA: 0x7595d52864
	public Single GetProgress() { }
	// RVA: 0x373a9d4 VA: 0x7595d529d4
	public Boolean IsWorking() { }
	// RVA: 0x373aaf8 VA: 0x7595d52af8
	public UnzipError GetErrorInfo() { }
}
```