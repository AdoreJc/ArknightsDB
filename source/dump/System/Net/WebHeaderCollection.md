# WebHeaderCollection

**Namespace:** `System.Net`


## Fields

- `Int32 m_NumCommonHeaders`

- `NameValueCollection m_InnerCollection`

- `WebHeaderCollectionType m_Type`


## Properties

- `NameValueCollection InnerCollection`

- `Boolean AllowHttpRequestHeader`


## Methods

- `Void NormalizeCommonHeaders()`

- `NameValueCollection get_InnerCollection()`

- `Boolean get_AllowHttpRequestHeader()`

- `Void Remove(HttpRequestHeader)`

- `Void Add(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class WebHeaderCollection : NameValueCollection, ISerializable
{
	private static readonly HeaderInfoTable HInfo; // 0x0
	private String[] m_CommonHeaders; // 0x60
	private Int32 m_NumCommonHeaders; // 0x68
	private static readonly String[] s_CommonHeaderNames; // 0x8
	private static readonly SByte[] s_CommonHeaderHints; // 0x10
	private NameValueCollection m_InnerCollection; // 0x70
	private WebHeaderCollectionType m_Type; // 0x78
	private static readonly Char[] HttpTrimCharacters; // 0x18
	private static RfcChar[] RfcCharMap; // 0x20

	private NameValueCollection InnerCollection { get; }
	private Boolean AllowHttpRequestHeader { get; }
	public override Int32 Count { get; }
	public override String[] AllKeys { get; }

	// RVA: 0x642bc58 VA: 0x7598a43c58
	private Void NormalizeCommonHeaders() { }
	// RVA: 0x642bd70 VA: 0x7598a43d70
	private NameValueCollection get_InnerCollection() { }
	// RVA: 0x642be20 VA: 0x7598a43e20
	internal static Boolean AllowMultiValues(String name) { }
	// RVA: 0x642bfa4 VA: 0x7598a43fa4
	private Boolean get_AllowHttpRequestHeader() { }
	// RVA: 0x642bfdc VA: 0x7598a43fdc
	public Void Remove(HttpRequestHeader header) { }
	// RVA: 0x642c14c VA: 0x7598a4414c
	internal Void AddInternal(String name, String value) { }
	// RVA: 0x642c1a0 VA: 0x7598a441a0
	internal Void ChangeInternal(String name, String value) { }
	// RVA: 0x642c1f4 VA: 0x7598a441f4
	internal Void RemoveInternal(String name) { }
	// RVA: 0x642c250 VA: 0x7598a44250
	internal Void CheckUpdate(String name, String value) { }
	// RVA: 0x642c2c8 VA: 0x7598a442c8
	internal static String CheckBadChars(String name, Boolean isHeaderValue) { }
	// RVA: 0x642c668 VA: 0x7598a44668
	internal static Boolean ContainsNonAsciiChars(String token) { }
	// RVA: 0x642c6ec VA: 0x7598a446ec
	internal Void ThrowOnRestrictedHeader(String headerName) { }
	// RVA: 0x642c854 VA: 0x7598a44854
	public override Void Add(String name, String value) { }
	// RVA: 0x642ca08 VA: 0x7598a44a08
	public Void Add(String header) { }
	// RVA: 0x642cce4 VA: 0x7598a44ce4
	public override Void Set(String name, String value) { }
	// RVA: 0x642cf14 VA: 0x7598a44f14
	internal Void SetInternal(String name, String value) { }
	// RVA: 0x642d138 VA: 0x7598a45138
	public override Void Remove(String name) { }
	// RVA: 0x642d274 VA: 0x7598a45274
	public override String[] GetValues(String header) { }
	// RVA: 0x642d47c VA: 0x7598a4547c
	public override String ToString() { }
	// RVA: 0x642d4d8 VA: 0x7598a454d8
	internal static String GetAsString(NameValueCollection cc, Boolean winInetCompat, Boolean forTrace) { }
	// RVA: 0x642d77c VA: 0x7598a4577c
	public Void .ctor() { }
	// RVA: 0x642d7e0 VA: 0x7598a457e0
	internal Void .ctor(WebHeaderCollectionType type) { }
	// RVA: 0x642d8dc VA: 0x7598a458dc
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642daac VA: 0x7598a45aac
	public override Void OnDeserialization(Object sender) { }
	// RVA: 0x642dab0 VA: 0x7598a45ab0
	public override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642dc30 VA: 0x7598a45c30
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642dc3c VA: 0x7598a45c3c
	public override String Get(String name) { }
	// RVA: 0x642df64 VA: 0x7598a45f64
	public override IEnumerator GetEnumerator() { }
	// RVA: 0x642dfe0 VA: 0x7598a45fe0
	public override Int32 get_Count() { }
	// RVA: 0x642e010 VA: 0x7598a46010
	public override String Get(Int32 index) { }
	// RVA: 0x642e050 VA: 0x7598a46050
	public override String GetKey(Int32 index) { }
	// RVA: 0x642e090 VA: 0x7598a46090
	public override String[] get_AllKeys() { }
	// RVA: 0x642e0c0 VA: 0x7598a460c0
	private static Void .cctor() { }
}
```