# ClimbTowerSquadMultiEditModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `EditType m_editType`

- `Int32 m_viewIndex`

- `Single m_columnIndex`

- `Int64 m_gameStartTs`


## Properties

- `EditType editType`

- `Int32 viewIndex`

- `Single columnIndex`

- `Int64 gameStartTs`


## Methods

- `EditType get_editType()`

- `Int32 get_viewIndex()`

- `Single get_columnIndex()`

- `Int64 get_gameStartTs()`

- `Void SetFocusIndex(Int32, Single)`

- `Void ToggleEditType()`

- `ClimbTowerSquadMultiEditCharModel FindCharModelByCardId(Int32)`

- `Void LoadData(UIPage, Dictionary`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditModel
{
	private List`1 m_charEditList; // 0x10
	private EditType m_editType; // 0x18
	private Int32 m_viewIndex; // 0x1c
	private Single m_columnIndex; // 0x20
	private Int64 m_gameStartTs; // 0x28

	public EditType editType { get; }
	public Int32 viewIndex { get; }
	public Single columnIndex { get; }
	public List`1 charEditList { get; }
	public Int64 gameStartTs { get; }

	// RVA: 0x2cc5f30 VA: 0x75952ddf30
	public EditType get_editType() { }
	// RVA: 0x2cc5f38 VA: 0x75952ddf38
	public Int32 get_viewIndex() { }
	// RVA: 0x2cc5f40 VA: 0x75952ddf40
	public Single get_columnIndex() { }
	// RVA: 0x2cc5f48 VA: 0x75952ddf48
	public List`1 get_charEditList() { }
	// RVA: 0x2cc5f50 VA: 0x75952ddf50
	public Int64 get_gameStartTs() { }
	// RVA: 0x2cc5f24 VA: 0x75952ddf24
	public Void SetFocusIndex(Int32 viewIndex, Single columnIndex) { }
	// RVA: 0x2cc4f6c VA: 0x75952dcf6c
	public Void ToggleEditType() { }
	// RVA: 0x2cc5408 VA: 0x75952dd408
	public ClimbTowerSquadMultiEditCharModel FindCharModelByCardId(Int32 cardId) { }
	// RVA: 0x2cc5cc0 VA: 0x75952ddcc0
	public Void LoadData(UIPage page, Dictionary`2 cards, Dictionary`2 editDict) { }
	// RVA: 0x2cc6198 VA: 0x75952de198
	public Void .ctor() { }
}
```