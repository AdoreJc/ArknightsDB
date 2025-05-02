# HttpUpload

**Namespace:** `Torappu.Multiplayer`


## Fields

- `Int32 m_using`

- `String m_toPath`

- `Boolean m_raw`

- `UnityWebRequestAsyncOperation m_uploading`


## Properties

- `Single progress`

- `Boolean isDone`

- `String error`


## Methods

- `Void Upload(String, String, Action`1)`

- `Void _DoUpload()`

- `Void _handleUploadComplete(AsyncOperation)`

- `Single get_progress()`

- `Boolean get_isDone()`

- `String get_error()`

- `UnityWebRequestAsyncOperation _PostFileTo(String)`

- `Void _Done(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class HttpUpload
{
	private String[] m_urls; // 0x10
	private Int32 m_using; // 0x18
	private Byte[] m_data; // 0x20
	private String m_toPath; // 0x28
	private Boolean m_raw; // 0x30
	private Action`1 m_complete; // 0x38
	private UnityWebRequestAsyncOperation m_uploading; // 0x40

	public Single progress { get; }
	public Boolean isDone { get; }
	public String error { get; }

	// RVA: 0x359145c VA: 0x7595ba945c
	public Void .ctor(String[] svrUrls) { }
	// RVA: 0x35914f8 VA: 0x7595ba94f8
	public Void Upload(String localPath, String remotePath, Action`1 complete) { }
	// RVA: 0x3591880 VA: 0x7595ba9880
	private Void _DoUpload() { }
	// RVA: 0x3591be0 VA: 0x7595ba9be0
	private Void _handleUploadComplete(AsyncOperation obj) { }
	// RVA: 0x3591c70 VA: 0x7595ba9c70
	public Single get_progress() { }
	// RVA: 0x3591c88 VA: 0x7595ba9c88
	public Boolean get_isDone() { }
	// RVA: 0x3591ca0 VA: 0x7595ba9ca0
	public String get_error() { }
	// RVA: 0x359198c VA: 0x7595ba998c
	private UnityWebRequestAsyncOperation _PostFileTo(String url) { }
	// RVA: 0x359194c VA: 0x7595ba994c
	private Void _Done(Boolean suc) { }
}
```