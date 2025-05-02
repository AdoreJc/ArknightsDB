# X509ChainElement

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `X509Certificate2 certificate`

- `String info`

- `X509ChainStatusFlags compressed_status_flags`


## Properties

- `X509Certificate2 Certificate`


## Methods

- `X509Certificate2 get_Certificate()`

- `Int32 Count(X509ChainStatusFlags)`

- `Void Set(X509ChainStatus[], ref, X509ChainStatusFlags, X509ChainStatusFlags)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509ChainElement
{
	private X509Certificate2 certificate; // 0x10
	private X509ChainStatus[] status; // 0x18
	private String info; // 0x20
	private X509ChainStatusFlags compressed_status_flags; // 0x28

	public X509Certificate2 Certificate { get; }
	public X509ChainStatus[] ChainElementStatus { get; }
	internal X509ChainStatusFlags StatusFlags { get; set; }

	// RVA: 0x63a76a8 VA: 0x75989bf6a8
	internal Void .ctor(X509Certificate2 certificate) { }
	// RVA: 0x63a7724 VA: 0x75989bf724
	public X509Certificate2 get_Certificate() { }
	// RVA: 0x63a772c VA: 0x75989bf72c
	public X509ChainStatus[] get_ChainElementStatus() { }
	// RVA: 0x63a7734 VA: 0x75989bf734
	internal X509ChainStatusFlags get_StatusFlags() { }
	// RVA: 0x63a773c VA: 0x75989bf73c
	internal Void set_StatusFlags(X509ChainStatusFlags value) { }
	// RVA: 0x63a7744 VA: 0x75989bf744
	private Int32 Count(X509ChainStatusFlags flags) { }
	// RVA: 0x63a7768 VA: 0x75989bf768
	private Void Set(X509ChainStatus[] status, ref Int32 position, X509ChainStatusFlags flags, X509ChainStatusFlags mask) { }
	// RVA: 0x63a797c VA: 0x75989bf97c
	internal Void UncompressFlags() { }
}
```