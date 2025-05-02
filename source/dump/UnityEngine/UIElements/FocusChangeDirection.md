# FocusChangeDirection

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class FocusChangeDirection : IDisposable
{
	private static readonly FocusChangeDirection <unspecified>k__BackingField; // 0x0
	private static readonly FocusChangeDirection <none>k__BackingField; // 0x8
	private static readonly FocusChangeDirection <lastValue>k__BackingField; // 0x10
	private readonly Int32 m_Value; // 0x10

	public static FocusChangeDirection unspecified { get; }
	public static FocusChangeDirection none { get; }
	protected static FocusChangeDirection lastValue { get; }

	// RVA: 0x6936d64 VA: 0x7598f4ed64
	public static FocusChangeDirection get_unspecified() { }
	// RVA: 0x6936dbc VA: 0x7598f4edbc
	public static FocusChangeDirection get_none() { }
	// RVA: 0x6936e14 VA: 0x7598f4ee14
	protected static FocusChangeDirection get_lastValue() { }
	// RVA: 0x6936e6c VA: 0x7598f4ee6c
	protected Void .ctor(Int32 value) { }
	// RVA: 0x6936e94 VA: 0x7598f4ee94
	public static Int32 op_Implicit(FocusChangeDirection fcd) { }
	// RVA: 0x6936ea0 VA: 0x7598f4eea0
	private Void System.IDisposable.Dispose() { }
	// RVA: 0x6936eac VA: 0x7598f4eeac
	protected virtual Void Dispose() { }
	// RVA: 0x6936eb0 VA: 0x7598f4eeb0
	internal virtual Void ApplyTo(FocusController focusController, Focusable f) { }
	// RVA: 0x6937198 VA: 0x7598f4f198
	private static Void .cctor() { }
}
```