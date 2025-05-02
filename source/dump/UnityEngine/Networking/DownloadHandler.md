# DownloadHandler

**Namespace:** `UnityEngine.Networking`


## Properties

- `Boolean isDone`

- `String text`


## Methods

- `Void Release()`

- `Boolean get_isDone()`

- `Boolean IsDone()`

- `String get_text()`

- `Encoding GetTextEncoder()`

- `String GetContentType()`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine.Networking
public class DownloadHandler : IDisposable
{
	internal IntPtr m_Ptr; // 0x10

	public Boolean isDone { get; }
	public Byte[] data { get; }
	public String text { get; }

	// RVA: 0x6a87b18 VA: 0x759909fb18
	private Void Release() { }
	// RVA: 0x6a87b54 VA: 0x759909fb54
	internal Void .ctor() { }
	// RVA: 0x6a87b5c VA: 0x759909fb5c
	protected override Void Finalize() { }
	// RVA: 0x6a87bf8 VA: 0x759909fbf8
	public virtual Void Dispose() { }
	// RVA: 0x6a87c8c VA: 0x759909fc8c
	public Boolean get_isDone() { }
	// RVA: 0x6a87cc8 VA: 0x759909fcc8
	private Boolean IsDone() { }
	// RVA: 0x6a87d04 VA: 0x759909fd04
	public Byte[] get_data() { }
	// RVA: 0x6a87d10 VA: 0x759909fd10
	public String get_text() { }
	// RVA: 0x6a87d1c VA: 0x759909fd1c
	protected virtual NativeArray`1 GetNativeData() { }
	// RVA: 0x6a87d28 VA: 0x759909fd28
	protected virtual Byte[] GetData() { }
	// RVA: 0x6a87db0 VA: 0x759909fdb0
	protected virtual String GetText() { }
	// RVA: 0x6a87e70 VA: 0x759909fe70
	private Encoding GetTextEncoder() { }
	// RVA: 0x6a880e0 VA: 0x75990a00e0
	private String GetContentType() { }
	// RVA: 0x6a8811c VA: 0x75990a011c
	protected virtual Boolean ReceiveData(Byte[] data, Int32 dataLength) { }
	// RVA: 0x6a88124 VA: 0x75990a0124
	protected virtual Void ReceiveContentLengthHeader(UInt64 contentLength) { }
	// RVA: 0x6a88130 VA: 0x75990a0130
	protected virtual Void ReceiveContentLength(Int32 contentLength) { }
	// RVA: 0x6a88134 VA: 0x75990a0134
	protected virtual Void CompleteContent() { }
	// RVA: 0x6a88138 VA: 0x75990a0138
	protected virtual Single GetProgress() { }
	// RVA: 0x6a88140 VA: 0x75990a0140
	internal static Byte* InternalGetByteArray(DownloadHandler dh, out Int32 length) { }
	// RVA: 0x6a87d2c VA: 0x759909fd2c
	internal static Byte[] InternalGetByteArray(DownloadHandler dh) { }
	// RVA: 0x6a88184 VA: 0x75990a0184
	internal static NativeArray`1 InternalGetNativeArray(DownloadHandler dh, ref NativeArray`1 nativeArray) { }
	// RVA: 0x6a8825c VA: 0x75990a025c
	internal static Void DisposeNativeArray(ref NativeArray`1 data) { }
	// RVA: 0x6a882a0 VA: 0x75990a02a0
	internal static Void CreateNativeArrayForNativeData(ref NativeArray`1 data, Byte* bytes, Int32 length) { }
}
```