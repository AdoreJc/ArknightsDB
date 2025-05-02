# Act1VAutoChessChessShopLevelTrapGroupListViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 m_enterSequenceNum`


## Properties

- `Int32 enterSequenceNum`


## Methods

- `Int32 get_enterSequenceNum()`

- `Void LoadData(ActivityAutoChessVerify1Data, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelTrapGroupListViewModel : IHotfixable
{
	private List`1 m_trapGroupViewList; // 0x10
	private Int32 m_enterSequenceNum; // 0x18
	private static DelegateBridge __Hotfix0_get_trapGroupViewList; // 0x0
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 trapGroupViewList { get; }
	public Int32 enterSequenceNum { get; }

	// RVA: 0x3325234 VA: 0x759593d234
	public List`1 get_trapGroupViewList() { }
	// RVA: 0x3325888 VA: 0x759593d888
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x332de28 VA: 0x7595945e28
	public Void LoadData(ActivityAutoChessVerify1Data actData, Int32 iSequenceNum) { }
	// RVA: 0x332e124 VA: 0x7595946124
	public Void .ctor() { }
}
```