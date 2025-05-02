# Act20sideCarVoteViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Int32 m_focusedIndex`

- `Int32 m_currentRound`


## Properties

- `Int32 focusedIndex`

- `Int32 currentRound`

- `Boolean roundOver`


## Methods

- `Int32 get_focusedIndex()`

- `Void set_focusedIndex(Int32)`

- `Int32 get_currentRound()`

- `Boolean get_roundOver()`

- `Void LoadData(String, ExhibitionVersus)`

- `VoteCarViewModel ArchieveVoteCarDataByUid(String)`

- `Boolean _CheckNewEquipment(String, Cart)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteViewModel : IHotfixable
{
	private List`1 m_voteCarDatas; // 0x10
	private Int32 m_focusedIndex; // 0x18
	private Int32 m_currentRound; // 0x1c
	private static DelegateBridge __Hotfix0_get_focusedIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_focusedIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_voteCarDatas; // 0x10
	private static DelegateBridge __Hotfix0_get_currentRound; // 0x18
	private static DelegateBridge __Hotfix0_get_roundOver; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_ArchieveVoteCarDataByUid; // 0x30
	private static DelegateBridge __Hotfix0__CheckNewEquipment; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 focusedIndex { get; set; }
	public List`1 voteCarDatas { get; }
	public Int32 currentRound { get; }
	public Boolean roundOver { get; }

	// RVA: 0x32f5714 VA: 0x759590d714
	public Int32 get_focusedIndex() { }
	// RVA: 0x32f577c VA: 0x759590d77c
	public Void set_focusedIndex(Int32 value) { }
	// RVA: 0x32f58e4 VA: 0x759590d8e4
	public List`1 get_voteCarDatas() { }
	// RVA: 0x32fdfc0 VA: 0x7595915fc0
	public Int32 get_currentRound() { }
	// RVA: 0x32f50dc VA: 0x759590d0dc
	public Boolean get_roundOver() { }
	// RVA: 0x32f4e58 VA: 0x759590ce58
	public Void LoadData(String actId, ExhibitionVersus versus) { }
	// RVA: 0x32f607c VA: 0x759590e07c
	public VoteCarViewModel ArchieveVoteCarDataByUid(String uid) { }
	// RVA: 0x330296c VA: 0x759591a96c
	private Boolean _CheckNewEquipment(String actId, Cart info) { }
	// RVA: 0x3302bb4 VA: 0x759591abb4
	public Void .ctor() { }
}
```