# InternalEncoderBestFitFallback

**Namespace:** `System.Text`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
internal class InternalEncoderBestFitFallback : EncoderFallback
{
	internal Encoding _encoding; // 0x10
	internal Char[] _arrayBestFit; // 0x18

	public override Int32 MaxCharCount { get; }

	// RVA: 0x613c290 VA: 0x7598754290
	internal Void .ctor(Encoding encoding) { }
	// RVA: 0x613c2c8 VA: 0x75987542c8
	public override EncoderFallbackBuffer CreateFallbackBuffer() { }
	// RVA: 0x613c470 VA: 0x7598754470
	public override Int32 get_MaxCharCount() { }
	// RVA: 0x613c478 VA: 0x7598754478
	public override Boolean Equals(Object value) { }
	// RVA: 0x613c53c VA: 0x759875453c
	public override Int32 GetHashCode() { }
}
```