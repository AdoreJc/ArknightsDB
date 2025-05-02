# Socket

**Namespace:** `System.Net.Sockets`


## Fields

- `CachedEventArgs _cachedTaskEventArgs`

- `Boolean is_closed`

- `Boolean is_listening`

- `Boolean useOverlappedIO`

- `Int32 linger_timeout`

- `AddressFamily addressFamily`

- `SocketType socketType`

- `ProtocolType protocolType`

- `Int32 m_IntCleanedUp`


## Properties

- `IntPtr Handle`

- `AddressFamily AddressFamily`

- `SocketType SocketType`

- `ProtocolType ProtocolType`

- `Boolean ExclusiveAddressUse`

- `Int32 ReceiveBufferSize`

- `Int32 SendBufferSize`

- `Int32 ReceiveTimeout`

- `Int32 SendTimeout`

- `Int16 Ttl`

- `Boolean DontFragment`

- `Boolean DualMode`

- `Boolean IsDualMode`

- `Int32 Available`

- `Boolean EnableBroadcast`

- `Boolean IsBound`

- `EndPoint LocalEndPoint`

- `Boolean Blocking`

- `Boolean Connected`

- `Boolean NoDelay`

- `EndPoint RemoteEndPoint`


## Methods

- `Void ReturnSocketAsyncEventArgs(Int32TaskSocketAsyncEventArgs, Boolean)`

- `Void ReturnSocketAsyncEventArgs(TaskSocketAsyncEventArgs`1)`

- `IntPtr get_Handle()`

- `AddressFamily get_AddressFamily()`

- `SocketType get_SocketType()`

- `ProtocolType get_ProtocolType()`

- `Boolean get_ExclusiveAddressUse()`

- `Void set_ExclusiveAddressUse(Boolean)`

- `Void set_ReceiveBufferSize(Int32)`

- `Void set_SendBufferSize(Int32)`

- `Void set_ReceiveTimeout(Int32)`

- `Void set_SendTimeout(Int32)`

- `Int16 get_Ttl()`

- `Void set_Ttl(Int16)`

- `Void set_DontFragment(Boolean)`

- `Boolean get_DualMode()`

- `Void set_DualMode(Boolean)`

- `Boolean get_IsDualMode()`

- `Int32 Send(Byte[])`

- `Int32 Send(IList`1, SocketFlags)`

- `Int32 Send(Byte[], Int32, Int32, SocketFlags)`

- `Int32 Receive(Byte[])`

- `Int32 Receive(Byte[], Int32, Int32, SocketFlags)`

- `Int32 Receive(IList`1, SocketFlags)`

- `Int32 IOControl(IOControlCode, Byte[], Byte[])`

- `Void SetIPProtectionLevel(IPProtectionLevel)`

- `IAsyncResult BeginConnect(IPAddress, Int32, AsyncCallback, Object)`

- `IAsyncResult BeginSend(Byte[], Int32, Int32, SocketFlags, AsyncCallback, Object)`

- `Int32 EndSend(IAsyncResult)`

- `IAsyncResult BeginReceive(Byte[], Int32, Int32, SocketFlags, AsyncCallback, Object)`

- `Int32 EndReceive(IAsyncResult)`

- `Void Dispose()`

- `Void SocketDefaults()`

- `Int32 get_Available()`

- `Void set_EnableBroadcast(Boolean)`

- `Boolean get_IsBound()`

- `EndPoint get_LocalEndPoint()`

- `Boolean get_Blocking()`

- `Void set_Blocking(Boolean)`

- `Boolean get_Connected()`

- `Void set_NoDelay(Boolean)`

- `EndPoint get_RemoteEndPoint()`

- `Boolean Poll(Int32, SelectMode)`

- `Socket Accept()`

- `IAsyncResult BeginAccept(AsyncCallback, Object)`

- `Socket EndAccept(IAsyncResult)`

- `Socket EndAccept(out, out, IAsyncResult)`

- `Void Bind(EndPoint)`

- `Void Listen(Int32)`

- `Void Connect(IPAddress, Int32)`

- `Void Connect(EndPoint)`

- `Boolean ConnectAsync(SocketAsyncEventArgs)`

- `IAsyncResult BeginConnect(String, Int32, AsyncCallback, Object)`

- `IAsyncResult BeginConnect(EndPoint, AsyncCallback, Object)`

- `IAsyncResult BeginConnect(IPAddress[], Int32, AsyncCallback, Object)`

- `Void EndConnect(IAsyncResult)`

- `Boolean GetCheckedIPs(SocketAsyncEventArgs, out)`

- `Void Disconnect(Boolean)`

- `Void EndDisconnect(IAsyncResult)`

- `Int32 Receive(Byte[], Int32, Int32, SocketFlags, out)`

- `Int32 Receive(Memory`1, Int32, Int32, SocketFlags, out)`

- `Int32 Receive(IList`1, SocketFlags, out)`

- `Int32 Receive(Span`1, SocketFlags, out)`

- `Int32 Send(ReadOnlySpan`1, SocketFlags, out)`

- `Boolean ReceiveAsync(SocketAsyncEventArgs)`

- `IAsyncResult BeginReceive(Byte[], Int32, Int32, SocketFlags, out, AsyncCallback, Object)`

- `Int32 EndReceive(IAsyncResult, out)`

- `Int32 ReceiveFrom(Byte[], Int32, Int32, SocketFlags, ref)`

- `Int32 ReceiveFrom(Memory`1, Int32, Int32, SocketFlags, ref, out)`

- `Int32 EndReceiveFrom_internal(SocketAsyncResult, SocketAsyncEventArgs)`

- `Int32 Send(Byte[], Int32, Int32, SocketFlags, out)`

- `Int32 Send(IList`1, SocketFlags, out)`

- `Boolean SendAsync(SocketAsyncEventArgs)`

- `IAsyncResult BeginSend(Byte[], Int32, Int32, SocketFlags, out, AsyncCallback, Object)`

- `Int32 EndSend(IAsyncResult, out)`

- `Int32 SendTo(Byte[], Int32, Int32, SocketFlags, EndPoint)`

- `Int32 EndSendTo(IAsyncResult)`

- `Object GetSocketOption(SocketOptionLevel, SocketOptionName)`

- `Void SetSocketOption(SocketOptionLevel, SocketOptionName, Object)`

- `Void SetSocketOption(SocketOptionLevel, SocketOptionName, Boolean)`

- `Void SetSocketOption(SocketOptionLevel, SocketOptionName, Int32)`

- `Int32 IOControl(Int32, Byte[], Byte[])`

- `Void Close()`

- `Void Close(Int32)`

- `Void Shutdown(SocketShutdown)`

- `Void Linger(IntPtr)`

- `Void ThrowIfDisposedAndClosed()`

- `Void ThrowIfBufferNull(Byte[])`

- `Void ThrowIfBufferOutOfRange(Byte[], Int32, Int32)`

- `Void ThrowIfUdp()`

- `SocketAsyncResult ValidateEndIAsyncResult(IAsyncResult, String, String)`

- `Void QueueIOSelectorJob(SemaphoreSlim, IntPtr, IOSelectorJob)`

- `Void InitSocketAsyncEventArgs(SocketAsyncEventArgs, AsyncCallback, Object, SocketOperation)`

- `SocketAsyncOperation SocketOperationToSocketAsyncOperation(SocketOperation)`

- `IPEndPoint RemapIPEndPoint(IPEndPoint)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class Socket : IDisposable
{
	private static readonly EventHandler`1 AcceptCompletedHandler; // 0x0
	private static readonly EventHandler`1 ReceiveCompletedHandler; // 0x8
	private static readonly EventHandler`1 SendCompletedHandler; // 0x10
	private static readonly TaskSocketAsyncEventArgs`1 s_rentedSocketSentinel; // 0x18
	private static readonly Int32TaskSocketAsyncEventArgs s_rentedInt32Sentinel; // 0x20
	private static readonly Task`1 s_zeroTask; // 0x28
	private CachedEventArgs _cachedTaskEventArgs; // 0x10
	private static Object s_InternalSyncObject; // 0x30
	internal static Boolean s_SupportsIPv4; // 0x38
	internal static Boolean s_SupportsIPv6; // 0x39
	internal static Boolean s_OSSupportsIPv6; // 0x3a
	internal static Boolean s_Initialized; // 0x3b
	private static Boolean s_LoggingEnabled; // 0x3c
	internal static Boolean s_PerfCountersEnabled; // 0x3d
	internal const Int32 DefaultCloseTimeout; // 0x0
	private const Int32 SOCKET_CLOSED_CODE; // 0x0
	private const String TIMEOUT_EXCEPTION_MSG; // 0x0
	private Boolean is_closed; // 0x18
	private Boolean is_listening; // 0x19
	private Boolean useOverlappedIO; // 0x1a
	private Int32 linger_timeout; // 0x1c
	private AddressFamily addressFamily; // 0x20
	private SocketType socketType; // 0x24
	private ProtocolType protocolType; // 0x28
	internal SafeSocketHandle m_Handle; // 0x30
	internal EndPoint seed_endpoint; // 0x38
	internal SemaphoreSlim ReadSem; // 0x40
	internal SemaphoreSlim WriteSem; // 0x48
	internal Boolean is_blocking; // 0x50
	internal Boolean is_bound; // 0x51
	internal Boolean is_connected; // 0x52
	private Int32 m_IntCleanedUp; // 0x54
	internal Boolean connect_in_progress; // 0x58
	internal readonly Int32 ID; // 0x5c
	private static AsyncCallback AcceptAsyncCallback; // 0x40
	private static IOAsyncCallback BeginAcceptCallback; // 0x48
	private static IOAsyncCallback BeginAcceptReceiveCallback; // 0x50
	private static AsyncCallback ConnectAsyncCallback; // 0x58
	private static IOAsyncCallback BeginConnectCallback; // 0x60
	private static AsyncCallback DisconnectAsyncCallback; // 0x68
	private static IOAsyncCallback BeginDisconnectCallback; // 0x70
	private static AsyncCallback ReceiveAsyncCallback; // 0x78
	private static IOAsyncCallback BeginReceiveCallback; // 0x80
	private static IOAsyncCallback BeginReceiveGenericCallback; // 0x88
	private static AsyncCallback ReceiveFromAsyncCallback; // 0x90
	private static IOAsyncCallback BeginReceiveFromCallback; // 0x98
	private static AsyncCallback SendAsyncCallback; // 0xa0
	private static IOAsyncCallback BeginSendGenericCallback; // 0xa8
	private static AsyncCallback SendToAsyncCallback; // 0xb0

	public static Boolean OSSupportsIPv4 { get; }
	public static Boolean OSSupportsIPv6 { get; }
	public IntPtr Handle { get; }
	public AddressFamily AddressFamily { get; }
	public SocketType SocketType { get; }
	public ProtocolType ProtocolType { get; }
	public Boolean ExclusiveAddressUse { get; set; }
	public Int32 ReceiveBufferSize { set; }
	public Int32 SendBufferSize { set; }
	public Int32 ReceiveTimeout { set; }
	public Int32 SendTimeout { set; }
	public Int16 Ttl { get; set; }
	public Boolean DontFragment { set; }
	public Boolean DualMode { get; set; }
	private Boolean IsDualMode { get; }
	private static Object InternalSyncObject { get; }
	internal Boolean CleanedUp { get; }
	public Int32 Available { get; }
	public Boolean EnableBroadcast { set; }
	public Boolean IsBound { get; }
	public EndPoint LocalEndPoint { get; }
	public Boolean Blocking { get; set; }
	public Boolean Connected { get; }
	public Boolean NoDelay { set; }
	public EndPoint RemoteEndPoint { get; }
	internal static Int32 FamilyHint { get; }

	// RVA: 0x634f3a4 VA: 0x75989673a4
	internal ValueTask`1 ReceiveAsync(Memory`1 buffer, SocketFlags socketFlags, Boolean fromNetworkStream, CancellationToken cancellationToken) { }
	// RVA: 0x63504f8 VA: 0x75989684f8
	private Task`1 ReceiveAsyncApm(Memory`1 buffer, SocketFlags socketFlags) { }
	// RVA: 0x634fcc4 VA: 0x7598967cc4
	internal ValueTask SendAsyncForNetworkStream(ReadOnlyMemory`1 buffer, SocketFlags socketFlags, CancellationToken cancellationToken) { }
	// RVA: 0x63508f4 VA: 0x75989688f4
	private Task`1 SendAsyncApm(ReadOnlyMemory`1 buffer, SocketFlags socketFlags) { }
	// RVA: 0x6350d48 VA: 0x7598968d48
	private static Void CompleteAccept(Socket s, TaskSocketAsyncEventArgs`1 saea) { }
	// RVA: 0x6350fe8 VA: 0x7598968fe8
	private static Void CompleteSendReceive(Socket s, Int32TaskSocketAsyncEventArgs saea, Boolean isReceive) { }
	// RVA: 0x6350efc VA: 0x7598968efc
	private static Exception GetException(SocketError error, Boolean wrapExceptionsInIOExceptions) { }
	// RVA: 0x6351168 VA: 0x7598969168
	private Void ReturnSocketAsyncEventArgs(Int32TaskSocketAsyncEventArgs saea, Boolean isReceive) { }
	// RVA: 0x6350ea0 VA: 0x7598968ea0
	private Void ReturnSocketAsyncEventArgs(TaskSocketAsyncEventArgs`1 saea) { }
	// RVA: 0x63511d0 VA: 0x75989691d0
	public Void .ctor(AddressFamily addressFamily, SocketType socketType, ProtocolType protocolType) { }
	// RVA: 0x635187c VA: 0x759896987c
	public static Boolean get_OSSupportsIPv4() { }
	// RVA: 0x63518e0 VA: 0x75989698e0
	public static Boolean get_OSSupportsIPv6() { }
	// RVA: 0x6351944 VA: 0x7598969944
	public IntPtr get_Handle() { }
	// RVA: 0x6351960 VA: 0x7598969960
	public AddressFamily get_AddressFamily() { }
	// RVA: 0x6351968 VA: 0x7598969968
	public SocketType get_SocketType() { }
	// RVA: 0x6351970 VA: 0x7598969970
	public ProtocolType get_ProtocolType() { }
	// RVA: 0x6351978 VA: 0x7598969978
	public Boolean get_ExclusiveAddressUse() { }
	// RVA: 0x63519fc VA: 0x75989699fc
	public Void set_ExclusiveAddressUse(Boolean value) { }
	// RVA: 0x6351ba8 VA: 0x7598969ba8
	public Void set_ReceiveBufferSize(Int32 value) { }
	// RVA: 0x6351c0c VA: 0x7598969c0c
	public Void set_SendBufferSize(Int32 value) { }
	// RVA: 0x6351c70 VA: 0x7598969c70
	public Void set_ReceiveTimeout(Int32 value) { }
	// RVA: 0x6351cdc VA: 0x7598969cdc
	public Void set_SendTimeout(Int32 value) { }
	// RVA: 0x6351d48 VA: 0x7598969d48
	public Int16 get_Ttl() { }
	// RVA: 0x6351e40 VA: 0x7598969e40
	public Void set_Ttl(Int16 value) { }
	// RVA: 0x6351f30 VA: 0x7598969f30
	public Void set_DontFragment(Boolean value) { }
	// RVA: 0x6351fb4 VA: 0x7598969fb4
	public Boolean get_DualMode() { }
	// RVA: 0x635209c VA: 0x759896a09c
	public Void set_DualMode(Boolean value) { }
	// RVA: 0x6352124 VA: 0x759896a124
	private Boolean get_IsDualMode() { }
	// RVA: 0x635213c VA: 0x759896a13c
	internal Boolean CanTryAddressFamily(AddressFamily family) { }
	// RVA: 0x6352174 VA: 0x759896a174
	public Int32 Send(Byte[] buffer) { }
	// RVA: 0x63521a0 VA: 0x759896a1a0
	public Int32 Send(IList`1 buffers, SocketFlags socketFlags) { }
	// RVA: 0x634dd98 VA: 0x7598965d98
	public Int32 Send(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags) { }
	// RVA: 0x63528fc VA: 0x759896a8fc
	public Int32 Receive(Byte[] buffer) { }
	// RVA: 0x634d63c VA: 0x759896563c
	public Int32 Receive(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags) { }
	// RVA: 0x6352a34 VA: 0x759896aa34
	public Int32 Receive(IList`1 buffers, SocketFlags socketFlags) { }
	// RVA: 0x6353000 VA: 0x759896b000
	public Int32 IOControl(IOControlCode ioControlCode, Byte[] optionInValue, Byte[] optionOutValue) { }
	// RVA: 0x63516b8 VA: 0x75989696b8
	public Void SetIPProtectionLevel(IPProtectionLevel level) { }
	// RVA: 0x6353194 VA: 0x759896b194
	public IAsyncResult BeginConnect(IPAddress address, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x634ecd8 VA: 0x7598966cd8
	public IAsyncResult BeginSend(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, AsyncCallback callback, Object state) { }
	// RVA: 0x634ef74 VA: 0x7598966f74
	public Int32 EndSend(IAsyncResult asyncResult) { }
	// RVA: 0x634e6b0 VA: 0x75989666b0
	public IAsyncResult BeginReceive(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, AsyncCallback callback, Object state) { }
	// RVA: 0x634e94c VA: 0x759896694c
	public Int32 EndReceive(IAsyncResult asyncResult) { }
	// RVA: 0x6353b3c VA: 0x759896bb3c
	private static Object get_InternalSyncObject() { }
	// RVA: 0x6353420 VA: 0x759896b420
	internal Boolean get_CleanedUp() { }
	// RVA: 0x6351450 VA: 0x7598969450
	internal static Void InitializeSockets() { }
	// RVA: 0x6353c64 VA: 0x759896bc64
	public Void Dispose() { }
	// RVA: 0x6353cd0 VA: 0x759896bcd0
	protected override Void Finalize() { }
	// RVA: 0x634e258 VA: 0x7598966258
	internal Void InternalShutdown(SocketShutdown how) { }
	// RVA: 0x635030c VA: 0x759896830c
	internal Void SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, Int32 optionValue, Boolean silent) { }
	// RVA: 0x6353fe0 VA: 0x759896bfe0
	internal Void .ctor(AddressFamily family, SocketType type, ProtocolType proto, SafeSocketHandle safe_handle) { }
	// RVA: 0x63517a8 VA: 0x75989697a8
	private Void SocketDefaults() { }
	// RVA: 0x63516b4 VA: 0x75989696b4
	private static IntPtr Socket_icall(AddressFamily family, SocketType type, ProtocolType proto, out Int32 error) { }
	// RVA: 0x634d134 VA: 0x7598965134
	public Int32 get_Available() { }
	// RVA: 0x63541cc VA: 0x759896c1cc
	private static Int32 Available_internal(SafeSocketHandle safeHandle, out Int32 error) { }
	// RVA: 0x63542f4 VA: 0x759896c2f4
	private static Int32 Available_icall(IntPtr socket, out Int32 error) { }
	// RVA: 0x63542f8 VA: 0x759896c2f8
	public Void set_EnableBroadcast(Boolean value) { }
	// RVA: 0x6354374 VA: 0x759896c374
	public Boolean get_IsBound() { }
	// RVA: 0x635437c VA: 0x759896c37c
	public EndPoint get_LocalEndPoint() { }
	// RVA: 0x6354470 VA: 0x759896c470
	private static SocketAddress LocalEndPoint_internal(SafeSocketHandle safeHandle, Int32 family, out Int32 error) { }
	// RVA: 0x63545a0 VA: 0x759896c5a0
	private static SocketAddress LocalEndPoint_icall(IntPtr socket, Int32 family, out Int32 error) { }
	// RVA: 0x63545a4 VA: 0x759896c5a4
	public Boolean get_Blocking() { }
	// RVA: 0x63545ac VA: 0x759896c5ac
	public Void set_Blocking(Boolean value) { }
	// RVA: 0x635467c VA: 0x759896c67c
	private static Void Blocking_internal(SafeSocketHandle safeHandle, Boolean block, out Int32 error) { }
	// RVA: 0x635479c VA: 0x759896c79c
	internal static Void Blocking_icall(IntPtr socket, Boolean block, out Int32 error) { }
	// RVA: 0x63547a4 VA: 0x759896c7a4
	public Boolean get_Connected() { }
	// RVA: 0x6354100 VA: 0x759896c100
	public Void set_NoDelay(Boolean value) { }
	// RVA: 0x6354804 VA: 0x759896c804
	public EndPoint get_RemoteEndPoint() { }
	// RVA: 0x6354900 VA: 0x759896c900
	private static SocketAddress RemoteEndPoint_internal(SafeSocketHandle safeHandle, Int32 family, out Int32 error) { }
	// RVA: 0x6354a30 VA: 0x759896ca30
	private static SocketAddress RemoteEndPoint_icall(IntPtr socket, Int32 family, out Int32 error) { }
	// RVA: 0x6354a34 VA: 0x759896ca34
	public Boolean Poll(Int32 microSeconds, SelectMode mode) { }
	// RVA: 0x6354bd4 VA: 0x759896cbd4
	private static Boolean Poll_internal(SafeSocketHandle safeHandle, SelectMode mode, Int32 timeout, out Int32 error) { }
	// RVA: 0x6354d14 VA: 0x759896cd14
	private static Boolean Poll_icall(IntPtr socket, SelectMode mode, Int32 timeout, out Int32 error) { }
	// RVA: 0x6354d18 VA: 0x759896cd18
	public Socket Accept() { }
	// RVA: 0x6354fb8 VA: 0x759896cfb8
	internal Void Accept(Socket acceptSocket) { }
	// RVA: 0x63550e8 VA: 0x759896d0e8
	public IAsyncResult BeginAccept(AsyncCallback callback, Object state) { }
	// RVA: 0x63553b8 VA: 0x759896d3b8
	public Socket EndAccept(IAsyncResult asyncResult) { }
	// RVA: 0x63553e0 VA: 0x759896d3e0
	public Socket EndAccept(out Byte[] buffer, out Int32 bytesTransferred, IAsyncResult asyncResult) { }
	// RVA: 0x6354e58 VA: 0x759896ce58
	private static SafeSocketHandle Accept_internal(SafeSocketHandle safeHandle, out Int32 error, Boolean blocking) { }
	// RVA: 0x635562c VA: 0x759896d62c
	private static IntPtr Accept_icall(IntPtr sock, out Int32 error, Boolean blocking) { }
	// RVA: 0x6355634 VA: 0x759896d634
	public Void Bind(EndPoint localEP) { }
	// RVA: 0x6355878 VA: 0x759896d878
	private static Void Bind_internal(SafeSocketHandle safeHandle, SocketAddress sa, out Int32 error) { }
	// RVA: 0x6355998 VA: 0x759896d998
	private static Void Bind_icall(IntPtr sock, SocketAddress sa, out Int32 error) { }
	// RVA: 0x635599c VA: 0x759896d99c
	public Void Listen(Int32 backlog) { }
	// RVA: 0x6355a94 VA: 0x759896da94
	private static Void Listen_internal(SafeSocketHandle safeHandle, Int32 backlog, out Int32 error) { }
	// RVA: 0x6355bb4 VA: 0x759896dbb4
	private static Void Listen_icall(IntPtr sock, Int32 backlog, out Int32 error) { }
	// RVA: 0x6355bb8 VA: 0x759896dbb8
	public Void Connect(IPAddress address, Int32 port) { }
	// RVA: 0x6355c34 VA: 0x759896dc34
	public Void Connect(EndPoint remoteEP) { }
	// RVA: 0x63560c8 VA: 0x759896e0c8
	public Boolean ConnectAsync(SocketAsyncEventArgs e) { }
	// RVA: 0x6356fc4 VA: 0x759896efc4
	public IAsyncResult BeginConnect(String host, Int32 port, AsyncCallback callback, Object state) { }
	// RVA: 0x6353430 VA: 0x759896b430
	public IAsyncResult BeginConnect(EndPoint remoteEP, AsyncCallback callback, Object state) { }
	// RVA: 0x63572b4 VA: 0x759896f2b4
	public IAsyncResult BeginConnect(IPAddress[] addresses, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x6356ce4 VA: 0x759896ece4
	private static Boolean BeginMConnect(SocketAsyncResult sockares) { }
	// RVA: 0x6356860 VA: 0x759896e860
	private static Boolean BeginSConnect(SocketAsyncResult sockares) { }
	// RVA: 0x6356f14 VA: 0x759896ef14
	public Void EndConnect(IAsyncResult asyncResult) { }
	// RVA: 0x6355fa4 VA: 0x759896dfa4
	private static Void Connect_internal(SafeSocketHandle safeHandle, SocketAddress sa, out Int32 error, Boolean blocking) { }
	// RVA: 0x63574fc VA: 0x759896f4fc
	private static Void Connect_icall(IntPtr sock, SocketAddress sa, out Int32 error, Boolean blocking) { }
	// RVA: 0x635667c VA: 0x759896e67c
	private Boolean GetCheckedIPs(SocketAsyncEventArgs e, out IPAddress[] addresses) { }
	// RVA: 0x6357504 VA: 0x759896f504
	public Void Disconnect(Boolean reuseSocket) { }
	// RVA: 0x635771c VA: 0x759896f71c
	public Void EndDisconnect(IAsyncResult asyncResult) { }
	// RVA: 0x63575fc VA: 0x759896f5fc
	private static Void Disconnect_internal(SafeSocketHandle safeHandle, Boolean reuse, out Int32 error) { }
	// RVA: 0x63577cc VA: 0x759896f7cc
	private static Void Disconnect_icall(IntPtr sock, Boolean reuse, out Int32 error) { }
	// RVA: 0x6352928 VA: 0x759896a928
	public Int32 Receive(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x6357aa4 VA: 0x759896faa4
	private Int32 Receive(Memory`1 buffer, Int32 offset, Int32 size, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x6352a9c VA: 0x759896aa9c
	public Int32 Receive(IList`1 buffers, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x634d918 VA: 0x7598965918
	public Int32 Receive(Span`1 buffer, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x634e074 VA: 0x7598966074
	public Int32 Send(ReadOnlySpan`1 buffer, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x6357e0c VA: 0x759896fe0c
	public Boolean ReceiveAsync(SocketAsyncEventArgs e) { }
	// RVA: 0x63538a8 VA: 0x759896b8a8
	public IAsyncResult BeginReceive(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, out SocketError errorCode, AsyncCallback callback, Object state) { }
	// RVA: 0x6353a4c VA: 0x759896ba4c
	public Int32 EndReceive(IAsyncResult asyncResult, out SocketError errorCode) { }
	// RVA: 0x6357cc8 VA: 0x759896fcc8
	private static Int32 Receive_internal(SafeSocketHandle safeHandle, WSABUF* bufarray, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x6358024 VA: 0x7598970024
	private static Int32 Receive_array_icall(IntPtr sock, WSABUF* bufarray, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x6357960 VA: 0x759896f960
	private static Int32 Receive_internal(SafeSocketHandle safeHandle, Byte* buffer, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x635802c VA: 0x759897002c
	private static Int32 Receive_icall(IntPtr sock, Byte* buffer, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x6358034 VA: 0x7598970034
	public Int32 ReceiveFrom(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, ref EndPoint remoteEP) { }
	// RVA: 0x635814c VA: 0x759897014c
	internal Int32 ReceiveFrom(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, ref EndPoint remoteEP, out SocketError errorCode) { }
	// RVA: 0x635842c VA: 0x759897042c
	private Int32 ReceiveFrom(Memory`1 buffer, Int32 offset, Int32 size, SocketFlags socketFlags, ref EndPoint remoteEP, out SocketError errorCode) { }
	// RVA: 0x63586d8 VA: 0x75989706d8
	private Int32 EndReceiveFrom_internal(SocketAsyncResult sockares, SocketAsyncEventArgs ares) { }
	// RVA: 0x63582d8 VA: 0x75989702d8
	private static Int32 ReceiveFrom_internal(SafeSocketHandle safeHandle, Byte* buffer, Int32 count, SocketFlags flags, ref SocketAddress sockaddr, out Int32 error, Boolean blocking) { }
	// RVA: 0x63587b0 VA: 0x75989707b0
	private static Int32 ReceiveFrom_icall(IntPtr sock, Byte* buffer, Int32 count, SocketFlags flags, ref SocketAddress sockaddr, out Int32 error, Boolean blocking) { }
	// RVA: 0x63527b8 VA: 0x759896a7b8
	public Int32 Send(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x6352208 VA: 0x759896a208
	public Int32 Send(IList`1 buffers, SocketFlags socketFlags, out SocketError errorCode) { }
	// RVA: 0x6358a40 VA: 0x7598970a40
	public Boolean SendAsync(SocketAsyncEventArgs e) { }
	// RVA: 0x6353580 VA: 0x759896b580
	public IAsyncResult BeginSend(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, out SocketError errorCode, AsyncCallback callback, Object state) { }
	// RVA: 0x6358d3c VA: 0x7598970d3c
	private static Void BeginSendCallback(SocketAsyncResult sockares, Int32 sent_so_far) { }
	// RVA: 0x63537b8 VA: 0x759896b7b8
	public Int32 EndSend(IAsyncResult asyncResult, out SocketError errorCode) { }
	// RVA: 0x63588fc VA: 0x75989708fc
	private static Int32 Send_internal(SafeSocketHandle safeHandle, WSABUF* bufarray, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x63590f4 VA: 0x75989710f4
	private static Int32 Send_array_icall(IntPtr sock, WSABUF* bufarray, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x63587b8 VA: 0x75989707b8
	private static Int32 Send_internal(SafeSocketHandle safeHandle, Byte* buffer, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x63590fc VA: 0x75989710fc
	private static Int32 Send_icall(IntPtr sock, Byte* buffer, Int32 count, SocketFlags flags, out Int32 error, Boolean blocking) { }
	// RVA: 0x6359104 VA: 0x7598971104
	public Int32 SendTo(Byte[] buffer, Int32 offset, Int32 size, SocketFlags socketFlags, EndPoint remoteEP) { }
	// RVA: 0x6359414 VA: 0x7598971414
	public Int32 EndSendTo(IAsyncResult asyncResult) { }
	// RVA: 0x63592c0 VA: 0x75989712c0
	private static Int32 SendTo_internal(SafeSocketHandle safeHandle, Byte* buffer, Int32 count, SocketFlags flags, SocketAddress sa, out Int32 error, Boolean blocking) { }
	// RVA: 0x63594cc VA: 0x75989714cc
	private static Int32 SendTo_icall(IntPtr sock, Byte* buffer, Int32 count, SocketFlags flags, SocketAddress sa, out Int32 error, Boolean blocking) { }
	// RVA: 0x634cb84 VA: 0x7598964b84
	public Object GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName) { }
	// RVA: 0x63594d4 VA: 0x75989714d4
	private static Void GetSocketOption_obj_internal(SafeSocketHandle safeHandle, SocketOptionLevel level, SocketOptionName name, out Object obj_val, out Int32 error) { }
	// RVA: 0x635960c VA: 0x759897160c
	private static Void GetSocketOption_obj_icall(IntPtr socket, SocketOptionLevel level, SocketOptionName name, out Object obj_val, out Int32 error) { }
	// RVA: 0x6359610 VA: 0x7598971610
	public Void SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, Object optionValue) { }
	// RVA: 0x6359974 VA: 0x7598971974
	public Void SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, Boolean optionValue) { }
	// RVA: 0x6351a7c VA: 0x7598969a7c
	public Void SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, Int32 optionValue) { }
	// RVA: 0x6353e90 VA: 0x759896be90
	private static Void SetSocketOption_internal(SafeSocketHandle safeHandle, SocketOptionLevel level, SocketOptionName name, Object obj_val, Byte[] byte_val, Int32 int_val, out Int32 error) { }
	// RVA: 0x635997c VA: 0x759897197c
	private static Void SetSocketOption_icall(IntPtr socket, SocketOptionLevel level, SocketOptionName name, Object obj_val, Byte[] byte_val, Int32 int_val, out Int32 error) { }
	// RVA: 0x6353004 VA: 0x759896b004
	public Int32 IOControl(Int32 ioControlCode, Byte[] optionInValue, Byte[] optionOutValue) { }
	// RVA: 0x6359980 VA: 0x7598971980
	private static Int32 IOControl_internal(SafeSocketHandle safeHandle, Int32 ioctl_code, Byte[] input, Byte[] output, out Int32 error) { }
	// RVA: 0x6359ac8 VA: 0x7598971ac8
	private static Int32 IOControl_icall(IntPtr sock, Int32 ioctl_code, Byte[] input, Byte[] output, out Int32 error) { }
	// RVA: 0x6359acc VA: 0x7598971acc
	public Void Close() { }
	// RVA: 0x634e2e0 VA: 0x75989662e0
	public Void Close(Int32 timeout) { }
	// RVA: 0x6359ad4 VA: 0x7598971ad4
	internal static Void Close_icall(IntPtr socket, out Int32 error) { }
	// RVA: 0x6359ad8 VA: 0x7598971ad8
	public Void Shutdown(SocketShutdown how) { }
	// RVA: 0x6353d70 VA: 0x759896bd70
	private static Void Shutdown_internal(SafeSocketHandle safeHandle, SocketShutdown how, out Int32 error) { }
	// RVA: 0x6359bf0 VA: 0x7598971bf0
	internal static Void Shutdown_icall(IntPtr socket, SocketShutdown how, out Int32 error) { }
	// RVA: 0x6359bf4 VA: 0x7598971bf4
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6359c54 VA: 0x7598971c54
	private Void Linger(IntPtr handle) { }
	// RVA: 0x6354140 VA: 0x759896c140
	private Void ThrowIfDisposedAndClosed() { }
	// RVA: 0x63577d4 VA: 0x759896f7d4
	private Void ThrowIfBufferNull(Byte[] buffer) { }
	// RVA: 0x635782c VA: 0x759896f82c
	private Void ThrowIfBufferOutOfRange(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x63547ac VA: 0x759896c7ac
	private Void ThrowIfUdp() { }
	// RVA: 0x63554e0 VA: 0x759896d4e0
	private SocketAsyncResult ValidateEndIAsyncResult(IAsyncResult ares, String methodName, String argName) { }
	// RVA: 0x6355258 VA: 0x759896d258
	private Void QueueIOSelectorJob(SemaphoreSlim sem, IntPtr handle, IOSelectorJob job) { }
	// RVA: 0x63565f0 VA: 0x759896e5f0
	private Void InitSocketAsyncEventArgs(SocketAsyncEventArgs e, AsyncCallback callback, Object state, SocketOperation operation) { }
	// RVA: 0x6359dc0 VA: 0x7598971dc0
	private SocketAsyncOperation SocketOperationToSocketAsyncOperation(SocketOperation op) { }
	// RVA: 0x63557bc VA: 0x759896d7bc
	private IPEndPoint RemapIPEndPoint(IPEndPoint input) { }
	// RVA: 0x6359e6c VA: 0x7598971e6c
	internal static Void cancel_blocking_socket_operation(Thread thread) { }
	// RVA: 0x6359e70 VA: 0x7598971e70
	internal static Int32 get_FamilyHint() { }
	// RVA: 0x6359ef8 VA: 0x7598971ef8
	private static Boolean IsProtocolSupported_internal(NetworkInterfaceComponent networkInterface) { }
	// RVA: 0x6353c10 VA: 0x759896bc10
	private static Boolean IsProtocolSupported(NetworkInterfaceComponent networkInterface) { }
	// RVA: 0x6359efc VA: 0x7598971efc
	private static Void .cctor() { }
}
```