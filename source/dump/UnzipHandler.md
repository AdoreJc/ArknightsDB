# UnzipHandler

**Namespace:** ` `


## Fields

- `HGDownloadInterface m_closure`

- `UnzipError m_error`


## Methods

- `UnzipError GetErrorInfo()`

- `Single GetProgress()`

- `Boolean IsWorking()`

- `Void ClosureOnly_SetErrorMsg(UnzipError)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnzipHandler : IUnzipInterface
{
	private HGDownloadInterface m_closure; // 0x10
	private UnzipError m_error; // 0x18


	// RVA: 0x37390a8 VA: 0x7595d510a8
	public Void .ctor(HGDownloadInterface closure) { }
	// RVA: 0x37395ac VA: 0x7595d515ac
	public UnzipError GetErrorInfo() { }
	// RVA: 0x37395c0 VA: 0x7595d515c0
	public Single GetProgress() { }
	// RVA: 0x37395ec VA: 0x7595d515ec
	public Boolean IsWorking() { }
	// RVA: 0x3739630 VA: 0x7595d51630
	public Void ClosureOnly_SetErrorMsg(UnzipError error) { }
}
```