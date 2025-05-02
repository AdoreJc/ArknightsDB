# EnemyDuelPrepareSelectModeSelectionViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 seqNum`

- `Int32 cardSelectIdx`


## Properties

- `Int32 cardCount`

- `EnemyDuelPrepareSelectModeCardViewModel selectedViewModel`


## Methods

- `Int32 get_cardCount()`

- `EnemyDuelPrepareSelectModeCardViewModel get_selectedViewModel()`

- `Void LoadData(EnemyDuelPrepareSelectModeViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareSelectModeSelectionViewModel
{
	public Int32 seqNum; // 0x10
	public Int32 cardSelectIdx; // 0x14
	public List`1 cardViewModels; // 0x18

	public Int32 cardCount { get; }
	public EnemyDuelPrepareSelectModeCardViewModel selectedViewModel { get; }

	// RVA: 0x29a0558 VA: 0x7594fb8558
	public Int32 get_cardCount() { }
	// RVA: 0x299f830 VA: 0x7594fb7830
	public EnemyDuelPrepareSelectModeCardViewModel get_selectedViewModel() { }
	// RVA: 0x29a0060 VA: 0x7594fb8060
	public Void LoadData(EnemyDuelPrepareSelectModeViewModel mainViewModel, String selectedModeId) { }
	// RVA: 0x29a0058 VA: 0x7594fb8058
	public Void .ctor() { }
}
```