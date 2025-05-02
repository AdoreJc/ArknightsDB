# WWWForm

**Namespace:** `UnityEngine`


## Fields

- `Boolean containsFiles`


## Methods

- `Void AddField(String, String, Encoding)`

- `Void AddBinaryData(String, Byte[], String)`

- `Void AddBinaryData(String, Byte[], String, String)`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine
public class WWWForm
{
	private List`1 formData; // 0x10
	private List`1 fieldNames; // 0x18
	private List`1 fileNames; // 0x20
	private List`1 types; // 0x28
	private Byte[] boundary; // 0x30
	private Boolean containsFiles; // 0x38
	private static Byte[] dDash; // 0x0
	private static Byte[] crlf; // 0x8
	private static Byte[] contentTypeHeader; // 0x10
	private static Byte[] dispositionHeader; // 0x18
	private static Byte[] endQuote; // 0x20
	private static Byte[] fileNameField; // 0x28
	private static Byte[] ampersand; // 0x30
	private static Byte[] equal; // 0x38

	internal static Encoding DefaultEncoding { get; }
	public Dictionary`2 headers { get; }
	public Byte[] data { get; }

	// RVA: 0x6a82dd8 VA: 0x759909add8
	internal static Encoding get_DefaultEncoding() { }
	// RVA: 0x6a82de0 VA: 0x759909ade0
	public Void .ctor() { }
	// RVA: 0x6a82fa0 VA: 0x759909afa0
	public Void AddField(String fieldName, String value, Encoding e) { }
	// RVA: 0x6a83224 VA: 0x759909b224
	public Void AddBinaryData(String fieldName, Byte[] contents, String fileName) { }
	// RVA: 0x6a8322c VA: 0x759909b22c
	public Void AddBinaryData(String fieldName, Byte[] contents, String fileName, String mimeType) { }
	// RVA: 0x6a83558 VA: 0x759909b558
	public Dictionary`2 get_headers() { }
	// RVA: 0x6a83698 VA: 0x759909b698
	public Byte[] get_data() { }
	// RVA: 0x6a84a1c VA: 0x759909ca1c
	private static Void .cctor() { }
}
```