# RoguelikeTaskCompleteModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeTaskData m_taskData`

- `Int32 m_curerntVal`

- `Int32 m_targetVal`


## Properties

- `RoguelikeTaskData taskData`

- `Int32 currentVal`

- `Int32 targetVal`

- `Boolean isComplted`


## Methods

- `RoguelikeTaskData get_taskData()`

- `Int32 get_currentVal()`

- `Int32 get_targetVal()`

- `Boolean get_isComplted()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTaskCompleteModel : IHotfixable
{
	private RoguelikeTaskData m_taskData; // 0x10
	private Int32 m_curerntVal; // 0x18
	private Int32 m_targetVal; // 0x1c
	private static DelegateBridge __Hotfix0_get_taskData; // 0x0
	private static DelegateBridge __Hotfix0_get_currentVal; // 0x8
	private static DelegateBridge __Hotfix0_get_targetVal; // 0x10
	private static DelegateBridge __Hotfix0_get_isComplted; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public RoguelikeTaskData taskData { get; }
	public Int32 currentVal { get; }
	public Int32 targetVal { get; }
	public Boolean isComplted { get; }

	// RVA: 0x2af9d20 VA: 0x7595111d20
	public RoguelikeTaskData get_taskData() { }
	// RVA: 0x2af9d88 VA: 0x7595111d88
	public Int32 get_currentVal() { }
	// RVA: 0x2af9df0 VA: 0x7595111df0
	public Int32 get_targetVal() { }
	// RVA: 0x2af9e58 VA: 0x7595111e58
	public Boolean get_isComplted() { }
	// RVA: 0x2af9b70 VA: 0x7595111b70
	public Void LoadData(String topicId) { }
	// RVA: 0x2af9cb0 VA: 0x7595111cb0
	public Void .ctor() { }
}
```