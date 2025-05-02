# RecordStream

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Fields

- `TlsProtocol mHandler`

- `Stream mInput`

- `Stream mOutput`

- `TlsCompression mPendingCompression`

- `TlsCompression mReadCompression`

- `TlsCompression mWriteCompression`

- `TlsCipher mPendingCipher`

- `TlsCipher mReadCipher`

- `TlsCipher mWriteCipher`

- `Int64 mReadSeqNo`

- `Int64 mWriteSeqNo`

- `MemoryStream mBuffer`

- `TlsHandshakeHash mHandshakeHash`

- `ProtocolVersion mReadVersion`

- `ProtocolVersion mWriteVersion`

- `Boolean mRestrictReadVersion`

- `Int32 mPlaintextLimit`

- `Int32 mCompressedLimit`

- `Int32 mCiphertextLimit`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
internal class RecordStream
{
	private const Int32 DEFAULT_PLAINTEXT_LIMIT; // 0x0
	internal const Int32 TLS_HEADER_SIZE; // 0x0
	internal const Int32 TLS_HEADER_TYPE_OFFSET; // 0x0
	internal const Int32 TLS_HEADER_VERSION_OFFSET; // 0x0
	internal const Int32 TLS_HEADER_LENGTH_OFFSET; // 0x0
	private TlsProtocol mHandler; // 0x10
	private Stream mInput; // 0x18
	private Stream mOutput; // 0x20
	private TlsCompression mPendingCompression; // 0x28
	private TlsCompression mReadCompression; // 0x30
	private TlsCompression mWriteCompression; // 0x38
	private TlsCipher mPendingCipher; // 0x40
	private TlsCipher mReadCipher; // 0x48
	private TlsCipher mWriteCipher; // 0x50
	private Int64 mReadSeqNo; // 0x58
	private Int64 mWriteSeqNo; // 0x60
	private MemoryStream mBuffer; // 0x68
	private TlsHandshakeHash mHandshakeHash; // 0x70
	private ProtocolVersion mReadVersion; // 0x78
	private ProtocolVersion mWriteVersion; // 0x80
	private Boolean mRestrictReadVersion; // 0x88
	private Int32 mPlaintextLimit; // 0x8c
	private Int32 mCompressedLimit; // 0x90
	private Int32 mCiphertextLimit; // 0x94

	internal virtual ProtocolVersion ReadVersion { get; set; }
	internal virtual TlsHandshakeHash HandshakeHash { get; }

	// RVA: 0x64e63f8 VA: 0x7598afe3f8
	internal Void .ctor(TlsProtocol handler, Stream input, Stream output) { }
	// RVA: 0x64e6510 VA: 0x7598afe510
	internal virtual Void Init(TlsContext context) { }
	// RVA: 0x64e66b0 VA: 0x7598afe6b0
	internal virtual Int32 GetPlaintextLimit() { }
	// RVA: 0x64e66b8 VA: 0x7598afe6b8
	internal virtual Void SetPlaintextLimit(Int32 plaintextLimit) { }
	// RVA: 0x64e66d4 VA: 0x7598afe6d4
	internal virtual ProtocolVersion get_ReadVersion() { }
	// RVA: 0x64e66dc VA: 0x7598afe6dc
	internal virtual Void set_ReadVersion(ProtocolVersion value) { }
	// RVA: 0x64e66e4 VA: 0x7598afe6e4
	internal virtual Void SetWriteVersion(ProtocolVersion writeVersion) { }
	// RVA: 0x64e66ec VA: 0x7598afe6ec
	internal virtual Void SetRestrictReadVersion(Boolean enabled) { }
	// RVA: 0x64e66f8 VA: 0x7598afe6f8
	internal virtual Void SetPendingConnectionState(TlsCompression tlsCompression, TlsCipher tlsCipher) { }
	// RVA: 0x64e6728 VA: 0x7598afe728
	internal virtual Void SentWriteCipherSpec() { }
	// RVA: 0x64e67a4 VA: 0x7598afe7a4
	internal virtual Void ReceivedReadCipherSpec() { }
	// RVA: 0x64e6820 VA: 0x7598afe820
	internal virtual Void FinaliseHandshake() { }
	// RVA: 0x64e68c0 VA: 0x7598afe8c0
	internal virtual Boolean ReadRecord() { }
	// RVA: 0x64e6c14 VA: 0x7598afec14
	internal virtual Byte[] DecodeAndVerify(Byte type, Stream input, Int32 len) { }
	// RVA: 0x64e6f48 VA: 0x7598afef48
	internal virtual Void WriteRecord(Byte type, Byte[] plaintext, Int32 plaintextOffset, Int32 plaintextLength) { }
	// RVA: 0x64e7354 VA: 0x7598aff354
	internal virtual Void NotifyHelloComplete() { }
	// RVA: 0x64e7408 VA: 0x7598aff408
	internal virtual TlsHandshakeHash get_HandshakeHash() { }
	// RVA: 0x64e7410 VA: 0x7598aff410
	internal virtual TlsHandshakeHash PrepareToFinish() { }
	// RVA: 0x64e74cc VA: 0x7598aff4cc
	internal virtual Void UpdateHandshakeData(Byte[] message, Int32 offset, Int32 len) { }
	// RVA: 0x64e7590 VA: 0x7598aff590
	internal virtual Void SafeClose() { }
	// RVA: 0x64e76f0 VA: 0x7598aff6f0
	internal virtual Void Flush() { }
	// RVA: 0x64e6ef4 VA: 0x7598afeef4
	private Byte[] GetBufferContents() { }
	// RVA: 0x64e6a70 VA: 0x7598afea70
	private static Void CheckType(Byte type, Byte alertDescription) { }
	// RVA: 0x64e6ea0 VA: 0x7598afeea0
	private static Void CheckLength(Int32 length, Int32 limit, Byte alertDescription) { }
}
```