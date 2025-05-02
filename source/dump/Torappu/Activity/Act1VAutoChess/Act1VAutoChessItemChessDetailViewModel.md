# Act1VAutoChessItemChessDetailViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `ActivityAutoChessVerify1Data m_actData`

- `Int32 m_showItemIdx`

- `Act1VAutoChessItemChessDetailItemViewModel <itemViewModel>k__BackingField`

- `Act1VAutoChessItemChessDetailItemViewModel <prevItemViewModel>k__BackingField`

- `Int32 <moveSeqNum>k__BackingField`

- `Boolean <isMoveRight>k__BackingField`


## Properties

- `Act1VAutoChessItemChessDetailItemViewModel itemViewModel`

- `Act1VAutoChessItemChessDetailItemViewModel prevItemViewModel`

- `Int32 moveSeqNum`

- `Boolean isMoveRight`


## Methods

- `Act1VAutoChessItemChessDetailItemViewModel get_itemViewModel()`

- `Void set_itemViewModel(Act1VAutoChessItemChessDetailItemViewModel)`

- `Act1VAutoChessItemChessDetailItemViewModel get_prevItemViewModel()`

- `Void set_prevItemViewModel(Act1VAutoChessItemChessDetailItemViewModel)`

- `Int32 get_moveSeqNum()`

- `Void set_moveSeqNum(Int32)`

- `Boolean get_isMoveRight()`

- `Void set_isMoveRight(Boolean)`

- `Void LoadData(String, String)`

- `Void MoveRight()`

- `Void MoveLeft()`

- `Void _ShowItemByIndex(Int32)`

- `Void _MoveItem(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessItemChessDetailViewModel : IHotfixable
{
	private ActivityAutoChessVerify1Data m_actData; // 0x10
	private Int32 m_showItemIdx; // 0x18
	private List`1 m_itemDatas; // 0x20
	private Act1VAutoChessItemChessDetailItemViewModel <itemViewModel>k__BackingField; // 0x28
	private Act1VAutoChessItemChessDetailItemViewModel <prevItemViewModel>k__BackingField; // 0x30
	private Int32 <moveSeqNum>k__BackingField; // 0x38
	private Boolean <isMoveRight>k__BackingField; // 0x3c
	private static DelegateBridge __Hotfix0_get_itemViewModel; // 0x0
	private static DelegateBridge __Hotfix0_set_itemViewModel; // 0x8
	private static DelegateBridge __Hotfix0_get_prevItemViewModel; // 0x10
	private static DelegateBridge __Hotfix0_set_prevItemViewModel; // 0x18
	private static DelegateBridge __Hotfix0_get_moveSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_set_moveSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_get_isMoveRight; // 0x30
	private static DelegateBridge __Hotfix0_set_isMoveRight; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_MoveRight; // 0x48
	private static DelegateBridge __Hotfix0_MoveLeft; // 0x50
	private static DelegateBridge __Hotfix0__ShowItemByIndex; // 0x58
	private static DelegateBridge __Hotfix0__MoveItem; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Act1VAutoChessItemChessDetailItemViewModel itemViewModel { get; set; }
	public Act1VAutoChessItemChessDetailItemViewModel prevItemViewModel { get; set; }
	public Int32 moveSeqNum { get; set; }
	public Boolean isMoveRight { get; set; }

	// RVA: 0x335a108 VA: 0x7595972108
	public Act1VAutoChessItemChessDetailItemViewModel get_itemViewModel() { }
	// RVA: 0x335a170 VA: 0x7595972170
	private Void set_itemViewModel(Act1VAutoChessItemChessDetailItemViewModel value) { }
	// RVA: 0x335a1f4 VA: 0x75959721f4
	public Act1VAutoChessItemChessDetailItemViewModel get_prevItemViewModel() { }
	// RVA: 0x335a25c VA: 0x759597225c
	private Void set_prevItemViewModel(Act1VAutoChessItemChessDetailItemViewModel value) { }
	// RVA: 0x335a2e0 VA: 0x75959722e0
	public Int32 get_moveSeqNum() { }
	// RVA: 0x335a348 VA: 0x7595972348
	private Void set_moveSeqNum(Int32 value) { }
	// RVA: 0x335a3c4 VA: 0x75959723c4
	public Boolean get_isMoveRight() { }
	// RVA: 0x335a42c VA: 0x759597242c
	private Void set_isMoveRight(Boolean value) { }
	// RVA: 0x3359c58 VA: 0x7595971c58
	public Void LoadData(String actId, String initFocusChessId) { }
	// RVA: 0x3359904 VA: 0x7595971904
	public Void MoveRight() { }
	// RVA: 0x3359a0c VA: 0x7595971a0c
	public Void MoveLeft() { }
	// RVA: 0x335a4ac VA: 0x75959724ac
	private Void _ShowItemByIndex(Int32 index) { }
	// RVA: 0x335a59c VA: 0x759597259c
	private Void _MoveItem(Int32 delta) { }
	// RVA: 0x3359be8 VA: 0x7595971be8
	public Void .ctor() { }
}
```