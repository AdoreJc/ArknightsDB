# FtpControlStream

**Namespace:** `System.Net`


## Fields

- `Socket _dataSocket`

- `IPEndPoint _passiveEndPoint`

- `TlsStream _tlsStream`

- `StringBuilder _bannerMessage`

- `StringBuilder _welcomeMessage`

- `StringBuilder _exitMessage`

- `WeakReference _credentials`

- `String _currentTypeSetting`

- `Int64 _contentLength`

- `DateTime _lastModified`

- `Boolean _dataHandshakeStarted`

- `String _loginDirectory`

- `String _establishedServerDirectory`

- `String _requestedServerDirectory`

- `Uri _responseUri`

- `FtpLoginState _loginState`


## Methods

- `PipelineInstruction QueueOrCreateFtpDataStream(ref)`

- `PipelineInstruction QueueOrCreateDataConection(PipelineEntry, ResponseDescription, Boolean, ref, out)`

- `String FormatAddress(IPAddress, Int32)`

- `String FormatAddressV6(IPAddress, Int32)`

- `Int64 GetContentLengthFrom213Response(String)`

- `DateTime GetLastModifiedFrom213Response(String)`

- `Void TryUpdateResponseUri(String, FtpWebRequest)`

- `Void TryUpdateContentLength(String)`

- `String GetLoginDirectory(String)`

- `Int32 GetPortV4(String)`

- `Int32 GetPortV6(String)`

- `Void CreateFtpListenerSocket(FtpWebRequest)`

- `String GetPortCommandLine(FtpWebRequest)`

- `String FormatFtpCommand(String, String)`

- `Socket CreateFtpDataSocket(FtpWebRequest, Socket)`

- `TriState IsFtpDataStreamWriteable()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class FtpControlStream : CommandStream
{
	private Socket _dataSocket; // 0x88
	private IPEndPoint _passiveEndPoint; // 0x90
	private TlsStream _tlsStream; // 0x98
	private StringBuilder _bannerMessage; // 0xa0
	private StringBuilder _welcomeMessage; // 0xa8
	private StringBuilder _exitMessage; // 0xb0
	private WeakReference _credentials; // 0xb8
	private String _currentTypeSetting; // 0xc0
	private Int64 _contentLength; // 0xc8
	private DateTime _lastModified; // 0xd0
	private Boolean _dataHandshakeStarted; // 0xd8
	private String _loginDirectory; // 0xe0
	private String _establishedServerDirectory; // 0xe8
	private String _requestedServerDirectory; // 0xf0
	private Uri _responseUri; // 0xf8
	private FtpLoginState _loginState; // 0x100
	internal FtpStatusCode StatusCode; // 0x104
	internal String StatusLine; // 0x108
	private static readonly AsyncCallback s_acceptCallbackDelegate; // 0x0
	private static readonly AsyncCallback s_connectCallbackDelegate; // 0x8
	private static readonly AsyncCallback s_SSLHandshakeCallback; // 0x10

	internal NetworkCredential Credentials { get; set; }
	internal Int64 ContentLength { get; }
	internal DateTime LastModified { get; }
	internal Uri ResponseUri { get; }
	internal String BannerMessage { get; }
	internal String WelcomeMessage { get; }
	internal String ExitMessage { get; }

	// RVA: 0x641b35c VA: 0x7598a3335c
	internal NetworkCredential get_Credentials() { }
	// RVA: 0x641b404 VA: 0x7598a33404
	internal Void set_Credentials(NetworkCredential value) { }
	// RVA: 0x641b494 VA: 0x7598a33494
	internal Void .ctor(TcpClient client) { }
	// RVA: 0x641b530 VA: 0x7598a33530
	internal Void AbortConnect() { }
	// RVA: 0x641b5bc VA: 0x7598a335bc
	private static Void AcceptCallback(IAsyncResult asyncResult) { }
	// RVA: 0x641b9c8 VA: 0x7598a339c8
	private static Void ConnectCallback(IAsyncResult asyncResult) { }
	// RVA: 0x641bb78 VA: 0x7598a33b78
	private static Void SSLHandshakeCallback(IAsyncResult asyncResult) { }
	// RVA: 0x641bd3c VA: 0x7598a33d3c
	private PipelineInstruction QueueOrCreateFtpDataStream(ref Stream stream) { }
	// RVA: 0x641c330 VA: 0x7598a34330
	protected override Void ClearState() { }
	// RVA: 0x641c400 VA: 0x7598a34400
	protected override PipelineInstruction PipelineCallback(PipelineEntry entry, ResponseDescription response, Boolean timeout, ref Stream stream) { }
	// RVA: 0x641dd20 VA: 0x7598a35d20
	protected override PipelineEntry[] BuildCommandsList(WebRequest req) { }
	// RVA: 0x641cc98 VA: 0x7598a34c98
	private PipelineInstruction QueueOrCreateDataConection(PipelineEntry entry, ResponseDescription response, Boolean timeout, ref Stream stream, out Boolean isSocketReady) { }
	// RVA: 0x641ed38 VA: 0x7598a36d38
	private static Void GetPathInfo(GetPathOption pathOption, Uri uri, out String path, out String directory, out String filename) { }
	// RVA: 0x641f6ec VA: 0x7598a376ec
	private String FormatAddress(IPAddress address, Int32 Port) { }
	// RVA: 0x641f810 VA: 0x7598a37810
	private String FormatAddressV6(IPAddress address, Int32 port) { }
	// RVA: 0x641f920 VA: 0x7598a37920
	internal Int64 get_ContentLength() { }
	// RVA: 0x641f928 VA: 0x7598a37928
	internal DateTime get_LastModified() { }
	// RVA: 0x641f930 VA: 0x7598a37930
	internal Uri get_ResponseUri() { }
	// RVA: 0x641f938 VA: 0x7598a37938
	internal String get_BannerMessage() { }
	// RVA: 0x641f950 VA: 0x7598a37950
	internal String get_WelcomeMessage() { }
	// RVA: 0x641f968 VA: 0x7598a37968
	internal String get_ExitMessage() { }
	// RVA: 0x641d7ac VA: 0x7598a357ac
	private Int64 GetContentLengthFrom213Response(String responseString) { }
	// RVA: 0x641d8ec VA: 0x7598a358ec
	private DateTime GetLastModifiedFrom213Response(String str) { }
	// RVA: 0x641d430 VA: 0x7598a35430
	private Void TryUpdateResponseUri(String str, FtpWebRequest request) { }
	// RVA: 0x641d338 VA: 0x7598a35338
	private Void TryUpdateContentLength(String str) { }
	// RVA: 0x641dc70 VA: 0x7598a35c70
	private String GetLoginDirectory(String str) { }
	// RVA: 0x641f2b8 VA: 0x7598a372b8
	private Int32 GetPortV4(String responseString) { }
	// RVA: 0x641f4ac VA: 0x7598a374ac
	private Int32 GetPortV6(String responseString) { }
	// RVA: 0x641ef38 VA: 0x7598a36f38
	private Void CreateFtpListenerSocket(FtpWebRequest request) { }
	// RVA: 0x641f0c4 VA: 0x7598a370c4
	private String GetPortCommandLine(FtpWebRequest request) { }
	// RVA: 0x641ec28 VA: 0x7598a36c28
	private String FormatFtpCommand(String command, String parameter) { }
	// RVA: 0x641f66c VA: 0x7598a3766c
	protected Socket CreateFtpDataSocket(FtpWebRequest request, Socket templateSocket) { }
	// RVA: 0x641f980 VA: 0x7598a37980
	protected override Boolean CheckValid(ResponseDescription response, ref Int32 validThrough, ref Int32 completeLength) { }
	// RVA: 0x641c018 VA: 0x7598a34018
	private TriState IsFtpDataStreamWriteable() { }
	// RVA: 0x641fd70 VA: 0x7598a37d70
	private static Void .cctor() { }
}
```