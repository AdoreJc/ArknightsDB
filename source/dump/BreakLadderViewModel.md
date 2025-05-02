# BreakLadderViewModel

**Namespace:** ` `


## Fields

- `Int32 killCnt`

- `Int32 breakFeeAdd`

- `State state`

- `Int32 index`


## Properties

- `Boolean isReadyToConfirm`

- `Boolean isConfirmed`


## Methods

- `Boolean get_isReadyToConfirm()`

- `Boolean get_isConfirmed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BreakLadderViewModel
{
	public Int32 killCnt; // 0x10
	public Int32 breakFeeAdd; // 0x14
	public UIItemViewModel[] rewards; // 0x18
	public State state; // 0x20
	public Int32 index; // 0x24

	public Boolean isReadyToConfirm { get; }
	public Boolean isConfirmed { get; }

	// RVA: 0x2f767b4 VA: 0x759558e7b4
	public Boolean get_isReadyToConfirm() { }
	// RVA: 0x2f767c4 VA: 0x759558e7c4
	public Boolean get_isConfirmed() { }
	// RVA: 0x2f763d4 VA: 0x759558e3d4
	public Void .ctor(BreakRewardLadder breakLadder, Int32 index_) { }
}
```