# UICharCardRankWidget

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_maxRank`

- `RarityRank m_rank`

- `Boolean m_isInited`


## Properties

- `RarityRank rank`


## Methods

- `Void _InitIfNot()`

- `RarityRank get_rank()`

- `Void set_rank(RarityRank)`

- `Void _UpdateRank(RarityRank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharCardRankWidget : MonoBehaviour
{
	private GameObject[] _rankSymbols; // 0x18
	private Int32 m_maxRank; // 0x20
	private RarityRank m_rank; // 0x24
	private Boolean m_isInited; // 0x28

	public RarityRank rank { get; set; }

	// RVA: 0x2139168 VA: 0x7594751168
	private Void _InitIfNot() { }
	// RVA: 0x2139198 VA: 0x7594751198
	public RarityRank get_rank() { }
	// RVA: 0x212b288 VA: 0x7594743288
	public Void set_rank(RarityRank value) { }
	// RVA: 0x21391a0 VA: 0x75947511a0
	private Void _UpdateRank(RarityRank rank) { }
	// RVA: 0x21392d0 VA: 0x75947512d0
	public Void .ctor() { }
}
```