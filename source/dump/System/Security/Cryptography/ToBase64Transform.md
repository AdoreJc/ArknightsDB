# ToBase64Transform

**Namespace:** `System.Security.Cryptography`


## Properties

- `Int32 InputBlockSize`

- `Int32 OutputBlockSize`

- `Boolean CanTransformMultipleBlocks`


## Methods

- `Int32 get_InputBlockSize()`

- `Int32 get_OutputBlockSize()`

- `Boolean get_CanTransformMultipleBlocks()`

- `Int32 TransformBlock(Byte[], Int32, Int32, Byte[], Int32)`

- `Void Dispose()`

- `Void Clear()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class ToBase64Transform : ICryptoTransform, IDisposable
{

	public Int32 InputBlockSize { get; }
	public Int32 OutputBlockSize { get; }
	public Boolean CanTransformMultipleBlocks { get; }
	public virtual Boolean CanReuseTransform { get; }

	// RVA: 0x5f4e67c VA: 0x759856667c
	public Int32 get_InputBlockSize() { }
	// RVA: 0x5f4e684 VA: 0x7598566684
	public Int32 get_OutputBlockSize() { }
	// RVA: 0x5f4e68c VA: 0x759856668c
	public Boolean get_CanTransformMultipleBlocks() { }
	// RVA: 0x5f4e694 VA: 0x7598566694
	public virtual Boolean get_CanReuseTransform() { }
	// RVA: 0x5f4e69c VA: 0x759856669c
	public Int32 TransformBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount, Byte[] outputBuffer, Int32 outputOffset) { }
	// RVA: 0x5f4e90c VA: 0x759856690c
	public Byte[] TransformFinalBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5f4eb38 VA: 0x7598566b38
	public Void Dispose() { }
	// RVA: 0x5f4eb3c VA: 0x7598566b3c
	public Void Clear() { }
	// RVA: 0x5f4eba8 VA: 0x7598566ba8
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x5f4ebac VA: 0x7598566bac
	protected override Void Finalize() { }
	// RVA: 0x5f4ec4c VA: 0x7598566c4c
	public Void .ctor() { }
}
```