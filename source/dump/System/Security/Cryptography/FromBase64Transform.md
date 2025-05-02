# FromBase64Transform

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 _inputIndex`

- `FromBase64TransformMode _whitespaces`


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

- `Void Reset()`

- `Void Clear()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class FromBase64Transform : ICryptoTransform, IDisposable
{
	private Byte[] _inputBuffer; // 0x10
	private Int32 _inputIndex; // 0x18
	private FromBase64TransformMode _whitespaces; // 0x1c

	public Int32 InputBlockSize { get; }
	public Int32 OutputBlockSize { get; }
	public Boolean CanTransformMultipleBlocks { get; }
	public virtual Boolean CanReuseTransform { get; }

	// RVA: 0x5f4ec54 VA: 0x7598566c54
	public Void .ctor() { }
	// RVA: 0x5f4ec5c VA: 0x7598566c5c
	public Void .ctor(FromBase64TransformMode whitespaces) { }
	// RVA: 0x5f4ecd4 VA: 0x7598566cd4
	public Int32 get_InputBlockSize() { }
	// RVA: 0x5f4ecdc VA: 0x7598566cdc
	public Int32 get_OutputBlockSize() { }
	// RVA: 0x5f4ece4 VA: 0x7598566ce4
	public Boolean get_CanTransformMultipleBlocks() { }
	// RVA: 0x5f4ecec VA: 0x7598566cec
	public virtual Boolean get_CanReuseTransform() { }
	// RVA: 0x5f4ecf4 VA: 0x7598566cf4
	public Int32 TransformBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount, Byte[] outputBuffer, Int32 outputOffset) { }
	// RVA: 0x5f4f234 VA: 0x7598567234
	public Byte[] TransformFinalBlock(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5f4f07c VA: 0x759856707c
	private Byte[] DiscardWhiteSpaces(Byte[] inputBuffer, Int32 inputOffset, Int32 inputCount) { }
	// RVA: 0x5f4f5a0 VA: 0x75985675a0
	public Void Dispose() { }
	// RVA: 0x5f4f598 VA: 0x7598567598
	private Void Reset() { }
	// RVA: 0x5f4f60c VA: 0x759856760c
	public Void Clear() { }
	// RVA: 0x5f4f610 VA: 0x7598567610
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x5f4f65c VA: 0x759856765c
	protected override Void Finalize() { }
}
```