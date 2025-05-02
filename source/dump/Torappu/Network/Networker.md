# Networker

**Namespace:** `Torappu.Network`


## Fields

- `Boolean _enableProfile`

- `LoginInfo m_loginInfo`

- `UInt32 m_loginInfoHash`

- `String <overrideRouterUrl>k__BackingField`

- `Int32 m_serviceCount`

- `Boolean m_lastSeqNumFailed`

- `Int32 m_seqNum`

- `Int32 m_latestSucceedSeqNum`


## Properties

- `Configuration networkConfig`

- `String overrideRouterUrl`

- `JsonSerializerSettings serializeSetting`

- `String annouceUrl`

- `String preAnnouceUrl`

- `String preAnnouceConfigUrl`

- `String serviceLicenseUrl`

- `Boolean isBusy`

- `String uid`

- `LoginInfo loginInfo`

- `UInt32 loginInfoHash`

- `Int32 serviceLicenseVersion`


## Methods

- `Configuration get_networkConfig()`

- `Configuration GetOverrideNetworkConfig()`

- `Void OverrideNetworkOptions(Nullable`1, NetworkConfigPriority)`

- `String get_overrideRouterUrl()`

- `Void set_overrideRouterUrl(String)`

- `Void OverrideNetworkRouterUrl(String)`

- `JsonSerializerSettings get_serializeSetting()`

- `String get_annouceUrl()`

- `String get_preAnnouceUrl()`

- `String get_preAnnouceConfigUrl()`

- `String get_serviceLicenseUrl()`

- `Boolean get_isBusy()`

- `Void InitLoginInfo(LoginInfo)`

- `String get_uid()`

- `LoginInfo get_loginInfo()`

- `UInt32 get_loginInfoHash()`

- `Int32 get_serviceLicenseVersion()`

- `WebHttpResult SendGet(String, String)`

- `WebHttpInstruction YieldSendGet(String, String)`

- `WebHttpResult SendPost(String, String, String)`

- `WebHttpResult SendPost(String, String, String, Dictionary`2)`

- `WebHttpInstruction YieldSendPost(String, String, String, Dictionary`2)`

- `String _ParseServiceUrl(String, String)`

- `IEnumerator _SendGetCoroutine(String, String, WebHttpResult)`

- `IEnumerator _SendPostCoroutine(String, String, String, Dictionary`2, WebHttpResult)`

- `IEnumerator _RequestOnNextFrame(Request, RequestResult`1)`

- `IEnumerator _HttpGet(String, String, Dictionary`2, WebHttpResult)`

- `IEnumerator _HttpPost(String, String, Dictionary`2, WebHttpResult)`

- `IEnumerator _HttpRequest(String, String, Dictionary`2, WebHttpResponse)`

- `IEnumerator _PostImpl(String, String, Dictionary`2, WebHttpResponse, Func`1)`

- `IEnumerator _PostWithProperNetworkUtil(String, String, Dictionary`2, WebHttpResponse, Func`1)`

- `IEnumerator _PostExtraLargeReqeust(String, String, Dictionary`2, WebHttpResponse, Func`1)`

- `IEnumerator _PostWithUnityWebRequest(String, String, Dictionary`2, WebHttpResponse, Func`1)`

- `Void _ProcessHttpWebResponse(UnityWebRequest, WebHttpResponse, HttpMethod)`

- `IEnumerator _PostWithBestHttp(String, String, Dictionary`2, WebHttpResponse, Func`1)`

- `Void _ProcessHttpWebResponse(HTTPRequest, HTTPResponse, WebHttpResponse)`

- `Void _HandleRequestCanceled(RequestResult`1)`

- `Void _HandleResponse(RespMsgBundle`1, RequestResult`1)`

- `Void _HandleResponseError(Int64, String, RequestResult`1)`

- `Void _HandleTimeoutError(RequestResult`1)`

- `Void _HandleClientInternalError(RequestResult`1, Exception)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Network
public class Networker : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	public const String CONTENT_TYPE_JSON; // 0x0
	public const String CONTENT_ENCODING_GZIP; // 0x0
	private static readonly Byte[] GZIP_MAGIC_BYTES; // 0x0
	public const Int64 CUSTOM_ERROR_CODE_TIMEOUT; // 0x0
	public const Int64 CUSTOM_ERROR_CODE_CONCLOSED; // 0x0
	private const Int64 CUSTOM_ERROR_CODE_TLS_ERROR; // 0x0
	public const Int32 CUSTOM_ERROR_CODE_SECURE_BASE; // 0x0
	public const Int64 CUSTOM_ERROR_CODE_CLIENT_ERROR; // 0x0
	private const Int32 GENERAL_TIMEOUT; // 0x0
	private const Int32 LARGE_REQUEST_THRESHOLD; // 0x0
	private const String PRE_ANNOUNCE_CONFIG_JSON; // 0x0
	private const String PRE_ANNOUNCE_INFO_JSON; // 0x0
	private Boolean _enableProfile; // 0x18
	private LoginInfo m_loginInfo; // 0x20
	private UInt32 m_loginInfoHash; // 0x40
	private ListDict`2 m_overrideNetworkConfigs; // 0x48
	private String <overrideRouterUrl>k__BackingField; // 0x50
	private Int32 m_serviceCount; // 0x58
	private Boolean m_lastSeqNumFailed; // 0x5c
	private Int32 m_seqNum; // 0x60
	private Int32 m_latestSucceedSeqNum; // 0x64
	private static IRequestHandler s_requestHanlder; // 0x8
	private static __XLua_Gen_Delegate154 __Hotfix0_get_networkConfig; // 0x10
	private static __XLua_Gen_Delegate154 __Hotfix0_GetOverrideNetworkConfig; // 0x18
	private static __XLua_Gen_Delegate155 __Hotfix0_OverrideNetworkOptions; // 0x20
	private static __XLua_Gen_Delegate89 __Hotfix0_get_overrideRouterUrl; // 0x28
	private static __XLua_Gen_Delegate0 __Hotfix0_set_overrideRouterUrl; // 0x30
	private static __XLua_Gen_Delegate0 __Hotfix0_OverrideNetworkRouterUrl; // 0x38
	private static __XLua_Gen_Delegate156 __Hotfix0_get_serializeSetting; // 0x40
	private static __XLua_Gen_Delegate89 __Hotfix0_get_annouceUrl; // 0x48
	private static __XLua_Gen_Delegate89 __Hotfix0_get_preAnnouceUrl; // 0x50
	private static __XLua_Gen_Delegate89 __Hotfix0_get_preAnnouceConfigUrl; // 0x58
	private static __XLua_Gen_Delegate89 __Hotfix0_get_serviceLicenseUrl; // 0x60
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isBusy; // 0x68
	private static __XLua_Gen_Delegate1 __Hotfix0_OnDuplicated; // 0x70
	private static __XLua_Gen_Delegate1 __Hotfix0_OnInit; // 0x78
	private static __XLua_Gen_Delegate157 __Hotfix0_InitLoginInfo; // 0x80
	private static __XLua_Gen_Delegate89 __Hotfix0_get_uid; // 0x88
	private static __XLua_Gen_Delegate158 __Hotfix0_get_loginInfo; // 0x90
	private static __XLua_Gen_Delegate159 __Hotfix0_get_loginInfoHash; // 0x98
	private static __XLua_Gen_Delegate10 __Hotfix0_get_serviceLicenseVersion; // 0xa0
	private static __XLua_Gen_Delegate160 __Hotfix0_SendGet; // 0xa8
	private static __XLua_Gen_Delegate161 __Hotfix0_YieldSendGet; // 0xb0
	private static __XLua_Gen_Delegate162 __Hotfix0_SendPost; // 0xb8
	private static __XLua_Gen_Delegate163 __Hotfix1_SendPost; // 0xc0
	private static __XLua_Gen_Delegate164 __Hotfix0_YieldSendPost; // 0xc8
	private static __XLua_Gen_Delegate165 __Hotfix0_IsServerBusinessError; // 0xd0
	private static __XLua_Gen_Delegate165 __Hotfix0_IsServerAuthTimeout; // 0xd8
	private static __XLua_Gen_Delegate1 __Hotfix0_SetGlobalRequestHandler; // 0xe0
	private static __XLua_Gen_Delegate166 __Hotfix0__ParseServiceUrl; // 0xe8
	private static __XLua_Gen_Delegate167 __Hotfix0__SendGetCoroutine; // 0xf0
	private static __XLua_Gen_Delegate168 __Hotfix0__SendPostCoroutine; // 0xf8
	private static __XLua_Gen_Delegate169 __Hotfix0__HttpGet; // 0x100
	private static __XLua_Gen_Delegate169 __Hotfix0__HttpPost; // 0x108
	private static __XLua_Gen_Delegate169 __Hotfix0__HttpRequest; // 0x110
	private static __XLua_Gen_Delegate168 __Hotfix0__PostImpl; // 0x118
	private static __XLua_Gen_Delegate168 __Hotfix0__PostWithProperNetworkUtil; // 0x120
	private static __XLua_Gen_Delegate8 __Hotfix0__CheckNetworkShouldRetry; // 0x128
	private static __XLua_Gen_Delegate8 __Hotfix0_CheckIfUseBestHttp; // 0x130
	private static __XLua_Gen_Delegate1 __Hotfix0__ResetWebResponse; // 0x138
	private static __XLua_Gen_Delegate168 __Hotfix0__PostExtraLargeReqeust; // 0x140
	private static __XLua_Gen_Delegate170 __Hotfix0__CheckIfUseExtraLargeRequest; // 0x148
	private static __XLua_Gen_Delegate168 __Hotfix0__PostWithUnityWebRequest; // 0x150
	private static __XLua_Gen_Delegate171 __Hotfix0__ReadWebRequestResponse; // 0x158
	private static __XLua_Gen_Delegate170 __Hotfix0__CheckIfGZip; // 0x160
	private static __XLua_Gen_Delegate168 __Hotfix0__PostWithBestHttp; // 0x168
	private static __XLua_Gen_Delegate8 __Hotfix0__CheckIfRequestDone; // 0x170
	private static __XLua_Gen_Delegate12 __Hotfix0__ProcessHttpWebResponse; // 0x178
	private static __XLua_Gen_Delegate21 __Hotfix0__GetErrorCodeFromBestHttp; // 0x180
	private static __XLua_Gen_Delegate172 __Hotfix0__GenerateRequestHeader; // 0x188
	private static __XLua_Gen_Delegate173 __Hotfix0__SecureUrl; // 0x190
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x198

	protected Configuration networkConfig { get; }
	public String overrideRouterUrl { get; set; }
	public JsonSerializerSettings serializeSetting { get; }
	public String annouceUrl { get; }
	public String preAnnouceUrl { get; }
	public String preAnnouceConfigUrl { get; }
	public String serviceLicenseUrl { get; }
	public Boolean isBusy { get; }
	public String uid { get; }
	public LoginInfo loginInfo { get; }
	public UInt32 loginInfoHash { get; }
	public Int32 serviceLicenseVersion { get; }

	// RVA: 0x67add44 VA: 0x7598dc5d44
	protected Configuration get_networkConfig() { }
	// RVA: 0x67adfac VA: 0x7598dc5fac
	public Configuration GetOverrideNetworkConfig() { }
	// RVA: 0x67ae210 VA: 0x7598dc6210
	public Void OverrideNetworkOptions(Nullable`1 overrideConfig, NetworkConfigPriority priorityEnum) { }
	// RVA: 0x67ae3a0 VA: 0x7598dc63a0
	public String get_overrideRouterUrl() { }
	// RVA: 0x67ae420 VA: 0x7598dc6420
	private Void set_overrideRouterUrl(String value) { }
	// RVA: 0x67ae4bc VA: 0x7598dc64bc
	public Void OverrideNetworkRouterUrl(String routerUrl) { }
	// RVA: 0x67ae554 VA: 0x7598dc6554
	public JsonSerializerSettings get_serializeSetting() { }
	// RVA: 0x67ae658 VA: 0x7598dc6658
	public String get_annouceUrl() { }
	// RVA: 0x67ae6f0 VA: 0x7598dc66f0
	public String get_preAnnouceUrl() { }
	// RVA: 0x67ae820 VA: 0x7598dc6820
	public String get_preAnnouceConfigUrl() { }
	// RVA: 0x67ae964 VA: 0x7598dc6964
	public String get_serviceLicenseUrl() { }
	// RVA: 0x67ae9fc VA: 0x7598dc69fc
	public Boolean get_isBusy() { }
	// RVA: 0x67aea84 VA: 0x7598dc6a84
	protected override Void OnDuplicated() { }
	// RVA: 0x67aeb40 VA: 0x7598dc6b40
	protected override Void OnInit() { }
	// RVA: 0x67aec08 VA: 0x7598dc6c08
	public Void InitLoginInfo(LoginInfo loginInfo) { }
	// RVA: 0x67aecd0 VA: 0x7598dc6cd0
	public String get_uid() { }
	// RVA: 0x67aed50 VA: 0x7598dc6d50
	public LoginInfo get_loginInfo() { }
	// RVA: 0x67aedf0 VA: 0x7598dc6df0
	public UInt32 get_loginInfoHash() { }
	// RVA: 0x67aee70 VA: 0x7598dc6e70
	public Int32 get_serviceLicenseVersion() { }
	// RVA: 0x VA: 0x0
	public RequestResult`1 SendRequest(Request request) { }
	// RVA: 0x67aeef0 VA: 0x7598dc6ef0
	public WebHttpResult SendGet(String url, String param) { }
	// RVA: 0x67af10c VA: 0x7598dc710c
	public WebHttpInstruction YieldSendGet(String url, String param) { }
	// RVA: 0x67af2dc VA: 0x7598dc72dc
	public WebHttpResult SendPost(String url, String param, String contentType) { }
	// RVA: 0x67af548 VA: 0x7598dc7548
	public WebHttpResult SendPost(String url, String param, String contentType, Dictionary`2 header) { }
	// RVA: 0x67af65c VA: 0x7598dc765c
	public WebHttpInstruction YieldSendPost(String url, String param, String contentType, Dictionary`2 header) { }
	// RVA: 0x67af77c VA: 0x7598dc777c
	public static Boolean IsServerBusinessError(Int64 responseCode) { }
	// RVA: 0x67af804 VA: 0x7598dc7804
	public static Boolean IsServerAuthTimeout(Int64 responseCode) { }
	// RVA: 0x67af888 VA: 0x7598dc7888
	public static Void SetGlobalRequestHandler(IRequestHandler handler) { }
	// RVA: 0x67af924 VA: 0x7598dc7924
	private String _ParseServiceUrl(String entry, String serviceCode) { }
	// RVA: 0x67aefe8 VA: 0x7598dc6fe8
	private IEnumerator _SendGetCoroutine(String url, String param, WebHttpResult result) { }
	// RVA: 0x67af3e8 VA: 0x7598dc73e8
	private IEnumerator _SendPostCoroutine(String url, String param, String contentType, Dictionary`2 addHeader, WebHttpResult result) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _RequestOnNextFrame(Request request, RequestResult`1 resultHandler) { }
	// RVA: 0x67afaa0 VA: 0x7598dc7aa0
	private IEnumerator _HttpGet(String url, String param, Dictionary`2 header, WebHttpResult result) { }
	// RVA: 0x67afc04 VA: 0x7598dc7c04
	private IEnumerator _HttpPost(String url, String param, Dictionary`2 header, WebHttpResult result) { }
	// RVA: 0x67afd68 VA: 0x7598dc7d68
	private IEnumerator _HttpRequest(String url, String text, Dictionary`2 header, WebHttpResponse outResponse) { }
	// RVA: 0x67afecc VA: 0x7598dc7ecc
	private IEnumerator _PostImpl(String url, String text, Dictionary`2 header, WebHttpResponse outResponse, Func`1 checkIfCancelled) { }
	// RVA: 0x67b0054 VA: 0x7598dc8054
	private IEnumerator _PostWithProperNetworkUtil(String url, String text, Dictionary`2 header, WebHttpResponse outResponse, Func`1 checkIfCancelled) { }
	// RVA: 0x67b01dc VA: 0x7598dc81dc
	private static Boolean _CheckNetworkShouldRetry(WebHttpResponse httpRes) { }
	// RVA: 0x67b0290 VA: 0x7598dc8290
	public static Boolean CheckIfUseBestHttp(String url) { }
	// RVA: 0x67b0404 VA: 0x7598dc8404
	private static Void _ResetWebResponse(WebHttpResponse outResponse) { }
	// RVA: 0x67b05b4 VA: 0x7598dc85b4
	private IEnumerator _PostExtraLargeReqeust(String url, String text, Dictionary`2 header, WebHttpResponse outResponse, Func`1 checkIfCancelled) { }
	// RVA: 0x67b073c VA: 0x7598dc873c
	private static Boolean _CheckIfUseExtraLargeRequest(String url, String text) { }
	// RVA: 0x67b07d0 VA: 0x7598dc87d0
	private IEnumerator _PostWithUnityWebRequest(String url, String text, Dictionary`2 header, WebHttpResponse outResponse, Func`1 checkIfCancelled) { }
	// RVA: 0x67b0958 VA: 0x7598dc8958
	private Void _ProcessHttpWebResponse(UnityWebRequest webRequest, WebHttpResponse outResponse, HttpMethod method) { }
	// RVA: 0x67b0b58 VA: 0x7598dc8b58
	private static Boolean _ReadWebRequestResponse(UnityWebRequest request, Boolean enableGZip, out String outText, out Byte[] outBytes) { }
	// RVA: 0x67b0ea8 VA: 0x7598dc8ea8
	private static Boolean _CheckIfGZip(UnityWebRequest request, DownloadHandler downloadHandler) { }
	// RVA: 0x67b10b8 VA: 0x7598dc90b8
	private IEnumerator _PostWithBestHttp(String url, String text, Dictionary`2 header, WebHttpResponse outResponse, Func`1 checkIfCancelled) { }
	// RVA: 0x67b1240 VA: 0x7598dc9240
	private static Boolean _CheckIfRequestDone(HTTPRequest request) { }
	// RVA: 0x67b12d4 VA: 0x7598dc92d4
	private Void _ProcessHttpWebResponse(HTTPRequest request, HTTPResponse response, WebHttpResponse outResponse) { }
	// RVA: 0x67b1594 VA: 0x7598dc9594
	private static Int64 _GetErrorCodeFromBestHttp(HTTPRequest request) { }
	// RVA: 0x67b16ac VA: 0x7598dc96ac
	private Dictionary`2 _GenerateRequestHeader(Request request) { }
	// RVA: 0x VA: 0x0
	private Void _HandleRequestCanceled(RequestResult`1 result) { }
	// RVA: 0x VA: 0x0
	private Void _HandleResponse(RespMsgBundle`1 body, RequestResult`1 result) { }
	// RVA: 0x VA: 0x0
	private Void _HandleResponseError(Int64 responseCode, String responseText, RequestResult`1 result) { }
	// RVA: 0x VA: 0x0
	private Void _HandleTimeoutError(RequestResult`1 result) { }
	// RVA: 0x VA: 0x0
	private Void _HandleClientInternalError(RequestResult`1 result, Exception e) { }
	// RVA: 0x VA: 0x0
	private static Void _HandleSecureSysError(RequestResult`1 result, Int32 errorCode) { }
	// RVA: 0x67b19a4 VA: 0x7598dc99a4
	private static Boolean _SecureUrl(String url, out String secureUrl, out Int32 errorCode) { }
	// RVA: 0x67b1a54 VA: 0x7598dc9a54
	private static Void _Condition_TEST_ProfileHttpResponse(String url, HttpMethod method, WebHttpResponse response) { }
	// RVA: 0x67b1c8c VA: 0x7598dc9c8c
	public Void .ctor() { }
	// RVA: 0x67b1d88 VA: 0x7598dc9d88
	private static Void .cctor() { }
}
```