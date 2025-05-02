# AdvancedRuneHolder

**Namespace:** `Torappu.Battle.Runes`


## Methods

- `Void AddPackedRuneData(PackedRuneData)`

- `Void AddRuneHolder(IRuneDataHolder)`

- `Void Reset()`

- `Void ForeachRuneData(Action`1)`

- `Void ForeachPackedRuneData(Action`1)`

- `Void _HolderForeachRuneData(Action`1)`

- `Void _HolderForeachPackedRuneData(Action`1)`

- `Void _DataForeachRuneData(Action`1)`

- `Void _DataForeachRuneData(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Runes
public class AdvancedRuneHolder : IRuneDataHolder
{
	private List`1 m_runeDataPackList; // 0x10
	private List`1 m_runeDataHolders; // 0x18


	// RVA: 0x1d35e6c VA: 0x759434de6c
	public Void AddPackedRuneData(PackedRuneData runeData) { }
	// RVA: 0x1d35f1c VA: 0x759434df1c
	public Void AddRuneHolder(IRuneDataHolder holder) { }
	// RVA: 0x1d35fcc VA: 0x759434dfcc
	public Void Reset() { }
	// RVA: 0x1d36074 VA: 0x759434e074
	public Void ForeachRuneData(Action`1 visitor) { }
	// RVA: 0x1d36538 VA: 0x759434e538
	public Void ForeachPackedRuneData(Action`1 visitor) { }
	// RVA: 0x1d3636c VA: 0x759434e36c
	private Void _HolderForeachRuneData(Action`1 visitor) { }
	// RVA: 0x1d36714 VA: 0x759434e714
	private Void _HolderForeachPackedRuneData(Action`1 visitor) { }
	// RVA: 0x1d3609c VA: 0x759434e09c
	private Void _DataForeachRuneData(Action`1 visitor) { }
	// RVA: 0x1d36560 VA: 0x759434e560
	private Void _DataForeachRuneData(Action`1 visitor) { }
	// RVA: 0x1d368e4 VA: 0x759434e8e4
	public Void .ctor() { }
}
```