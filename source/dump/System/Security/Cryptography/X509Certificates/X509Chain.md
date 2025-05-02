# X509Chain

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Fields

- `X509ChainImpl impl`


## Properties

- `X509ChainElementCollection ChainElements`

- `X509ChainPolicy ChainPolicy`


## Methods

- `X509ChainElementCollection get_ChainElements()`

- `X509ChainPolicy get_ChainPolicy()`

- `Boolean Build(X509Certificate2)`

- `Void Reset()`

- `Void Dispose()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
public class X509Chain : IDisposable
{
	private X509ChainImpl impl; // 0x10

	internal X509ChainImpl Impl { get; }
	public X509ChainElementCollection ChainElements { get; }
	public X509ChainPolicy ChainPolicy { get; }
	public X509ChainStatus[] ChainStatus { get; }

	// RVA: 0x63a72d4 VA: 0x75989bf2d4
	internal X509ChainImpl get_Impl() { }
	// RVA: 0x63a7330 VA: 0x75989bf330
	public Void .ctor() { }
	// RVA: 0x63a7338 VA: 0x75989bf338
	public Void .ctor(Boolean useMachineContext) { }
	// RVA: 0x63a73d0 VA: 0x75989bf3d0
	internal Void .ctor(X509ChainImpl impl) { }
	// RVA: 0x63a7408 VA: 0x75989bf408
	public Void .ctor(IntPtr chainContext) { }
	// RVA: 0x63a7450 VA: 0x75989bf450
	public X509ChainElementCollection get_ChainElements() { }
	// RVA: 0x63a747c VA: 0x75989bf47c
	public X509ChainPolicy get_ChainPolicy() { }
	// RVA: 0x63a74a8 VA: 0x75989bf4a8
	public X509ChainStatus[] get_ChainStatus() { }
	// RVA: 0x63a6064 VA: 0x75989be064
	public Boolean Build(X509Certificate2 certificate) { }
	// RVA: 0x63a74d4 VA: 0x75989bf4d4
	public Void Reset() { }
	// RVA: 0x63a6008 VA: 0x75989be008
	public static X509Chain Create() { }
	// RVA: 0x63a7500 VA: 0x75989bf500
	public Void Dispose() { }
	// RVA: 0x63a756c VA: 0x75989bf56c
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63a7608 VA: 0x75989bf608
	protected override Void Finalize() { }
}
```