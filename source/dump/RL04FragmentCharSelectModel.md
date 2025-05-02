# RL04FragmentCharSelectModel

**Namespace:** ` `


## Fields

- `Int32 maxSelectedNum`

- `Int32 baseLimitWeight`

- `Int32 currLimitWeight`


## Methods

- `Void LoadData(String)`

- `Void _RefreshWeight()`

- `Int32 _SortWeightCharData(RL04FragmentCharViewModel, RL04FragmentCharViewModel)`

- `Void _LoadWeightCharData(CurrentData, Fragment)`

- `Void _LoadSelectedChar(Fragment)`

- `Boolean SelectChar(Int32)`

- `Int32 <_LoadWeightCharData>b__11_0(KeyValuePair`2, KeyValuePair`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL04FragmentCharSelectModel : IHotfixable
{
	public Int32 maxSelectedNum; // 0x10
	public Int32 baseLimitWeight; // 0x14
	public Int32 currLimitWeight; // 0x18
	public ListDict`2 charList; // 0x20
	public List`1 selectedChar; // 0x28
	private List`1 m_charListData; // 0x30
	private static DelegateBridge __Hotfix0_get_charListData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__RefreshWeight; // 0x10
	private static DelegateBridge __Hotfix0__SortWeightCharData; // 0x18
	private static DelegateBridge __Hotfix0__LoadWeightCharData; // 0x20
	private static DelegateBridge __Hotfix0__LoadSelectedChar; // 0x28
	private static DelegateBridge __Hotfix0_SelectChar; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 charListData { get; }

	// RVA: 0x2b1d550 VA: 0x7595135550
	public List`1 get_charListData() { }
	// RVA: 0x2b1e02c VA: 0x759513602c
	public Void LoadData(String topicId) { }
	// RVA: 0x2b1f0c8 VA: 0x75951370c8
	private Void _RefreshWeight() { }
	// RVA: 0x2b1f2a4 VA: 0x75951372a4
	private Int32 _SortWeightCharData(RL04FragmentCharViewModel lhs, RL04FragmentCharViewModel rhs) { }
	// RVA: 0x2b1e9ac VA: 0x75951369ac
	private Void _LoadWeightCharData(CurrentData playerData, Fragment playerFragment) { }
	// RVA: 0x2b1ef00 VA: 0x7595136f00
	private Void _LoadSelectedChar(Fragment playerFragment) { }
	// RVA: 0x2b1d7cc VA: 0x75951357cc
	public Boolean SelectChar(Int32 index) { }
	// RVA: 0x2b1df18 VA: 0x7595135f18
	public Void .ctor() { }
	// RVA: 0x2b1f3f8 VA: 0x75951373f8
	private Int32 <_LoadWeightCharData>b__11_0(KeyValuePair`2 lhs, KeyValuePair`2 rhs) { }
}
```