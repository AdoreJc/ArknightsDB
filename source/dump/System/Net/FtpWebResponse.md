# FtpWebResponse

**Namespace:** `System.Net`


## Fields

- `Int64 _contentLength`

- `Uri _responseUri`

- `FtpStatusCode _statusCode`

- `String _statusLine`

- `WebHeaderCollection _ftpRequestHeaders`

- `DateTime _lastModified`

- `String _bannerMessage`

- `String _welcomeMessage`

- `String _exitMessage`


## Properties

- `FtpStatusCode StatusCode`


## Methods

- `FtpStatusCode get_StatusCode()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class FtpWebResponse : WebResponse, IDisposable
{
	internal Stream _responseStream; // 0x20
	private Int64 _contentLength; // 0x28
	private Uri _responseUri; // 0x30
	private FtpStatusCode _statusCode; // 0x38
	private String _statusLine; // 0x40
	private WebHeaderCollection _ftpRequestHeaders; // 0x48
	private DateTime _lastModified; // 0x50
	private String _bannerMessage; // 0x58
	private String _welcomeMessage; // 0x60
	private String _exitMessage; // 0x68

	public override Int64 ContentLength { get; }
	public override WebHeaderCollection Headers { get; }
	public override Uri ResponseUri { get; }
	public FtpStatusCode StatusCode { get; }

	// RVA: 0x642682c VA: 0x7598a3e82c
	internal Void .ctor(Stream responseStream, Int64 contentLength, Uri responseUri, FtpStatusCode statusCode, String statusLine, DateTime lastModified, String bannerMessage, String welcomeMessage, String exitMessage) { }
	// RVA: 0x6425230 VA: 0x7598a3d230
	internal Void UpdateStatus(FtpStatusCode statusCode, String statusLine, String exitMessage) { }
	// RVA: 0x6426ff0 VA: 0x7598a3eff0
	public override Stream GetResponseStream() { }
	// RVA: 0x6426784 VA: 0x7598a3e784
	internal Void SetResponseStream(Stream stream) { }
	// RVA: 0x64270f0 VA: 0x7598a3f0f0
	public override Void Close() { }
	// RVA: 0x64271d4 VA: 0x7598a3f1d4
	public override Int64 get_ContentLength() { }
	// RVA: 0x64271dc VA: 0x7598a3f1dc
	public override WebHeaderCollection get_Headers() { }
	// RVA: 0x6427304 VA: 0x7598a3f304
	public override Uri get_ResponseUri() { }
	// RVA: 0x642730c VA: 0x7598a3f30c
	public FtpStatusCode get_StatusCode() { }
}
```