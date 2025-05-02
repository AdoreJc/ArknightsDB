# BranchRuntime

**Namespace:** ` `


## Fields

- `BranchData data`

- `Int32 cursor`


## Properties

- `Boolean hasNext`


## Methods

- `Boolean get_hasNext()`

- `Boolean TryPickNextPhase(out, Boolean)`

- `Boolean TryPickRandomPhase(out)`

- `Boolean TryPickRandomPhaseNotRepeat(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BranchRuntime
{
	public BranchData data; // 0x10
	public Int32 cursor; // 0x18
	public List`1 playList; // 0x20

	public Boolean hasNext { get; }

	// RVA: 0x40d25e4 VA: 0x75966ea5e4
	public Boolean get_hasNext() { }
	// RVA: 0x40d176c VA: 0x75966e976c
	public Void .ctor(BranchData branchData) { }
	// RVA: 0x40d2c28 VA: 0x75966eac28
	public Boolean TryPickNextPhase(out PhaseData result, Boolean isLoop) { }
	// RVA: 0x40d305c VA: 0x75966eb05c
	public Boolean TryPickRandomPhase(out PhaseData result) { }
	// RVA: 0x40d3358 VA: 0x75966eb358
	public Boolean TryPickRandomPhaseNotRepeat(out PhaseData result) { }
}
```