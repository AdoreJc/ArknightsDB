# Tuple

**Namespace:** `System`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class Tuple`4 : IStructuralEquatable, IStructuralComparable, IComparable, ITupleInternal, ITuple
{
	private readonly T1 m_Item1; // 0x0
	private readonly T2 m_Item2; // 0x0
	private readonly T3 m_Item3; // 0x0
	private readonly T4 m_Item4; // 0x0

	private Int32 System.Runtime.CompilerServices.ITuple.Length { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor(T1 item1, T2 item2, T3 item3, T4 item4) { }
	// RVA: 0x VA: 0x0
	public override Boolean Equals(Object obj) { }
	// RVA: 0x VA: 0x0
	private Boolean System.Collections.IStructuralEquatable.Equals(Object other, IEqualityComparer comparer) { }
	// RVA: 0x VA: 0x0
	private Int32 System.IComparable.CompareTo(Object obj) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IStructuralComparable.CompareTo(Object other, IComparer comparer) { }
	// RVA: 0x VA: 0x0
	public override Int32 GetHashCode() { }
	// RVA: 0x VA: 0x0
	private Int32 System.Collections.IStructuralEquatable.GetHashCode(IEqualityComparer comparer) { }
	// RVA: 0x VA: 0x0
	public override String ToString() { }
	// RVA: 0x VA: 0x0
	private String System.ITupleInternal.ToString(StringBuilder sb) { }
	// RVA: 0x VA: 0x0
	private Int32 System.Runtime.CompilerServices.ITuple.get_Length() { }
}
```