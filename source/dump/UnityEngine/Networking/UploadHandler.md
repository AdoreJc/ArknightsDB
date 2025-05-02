# UploadHandler

**Namespace:** `UnityEngine.Networking`


## Properties

- `String contentType`


## Methods

- `Void Release()`

- `Void set_contentType(String)`

- `Void InternalSetContentType(String)`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine.Networking
public class UploadHandler : IDisposable
{
	internal IntPtr m_Ptr; // 0x10

	public String contentType { set; }

	// RVA: 0x6a8851c VA: 0x75990a051c
	private Void Release() { }
	// RVA: 0x6a88558 VA: 0x75990a0558
	internal Void .ctor() { }
	// RVA: 0x6a88560 VA: 0x75990a0560
	protected override Void Finalize() { }
	// RVA: 0x6a885fc VA: 0x75990a05fc
	public virtual Void Dispose() { }
	// RVA: 0x6a8764c VA: 0x759909f64c
	public Void set_contentType(String value) { }
	// RVA: 0x6a88690 VA: 0x75990a0690
	internal virtual Void SetContentType(String newContentType) { }
	// RVA: 0x6a886d4 VA: 0x75990a06d4
	private Void InternalSetContentType(String newContentType) { }
}
```