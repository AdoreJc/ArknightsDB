# MeetingClueAdapter

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _clueProto`

- `Transform _poolTransform`

- `Boolean _showBonusLabel`

- `Boolean _showRemoveButton`

- `Int32 overrideBonus`

- `GameObjectPool m_objectPool`

- `IMeetingClue m_selectedClue`


## Properties

- `IMeetingClue selectedClue`


## Methods

- `Void add_onClueClicked(Action`2)`

- `Void remove_onClueClicked(Action`2)`

- `Void add_onClueRemoveClicked(Action`2)`

- `Void remove_onClueRemoveClicked(Action`2)`

- `Void add_onClueUnequipClicked(Action`2)`

- `Void remove_onClueUnequipClicked(Action`2)`

- `Void set_selectedClue(IMeetingClue)`

- `Void _OnClueClicked(IMeetingClue, MeetingClueItemView)`

- `Void _OnClueRemoveClicked(IMeetingClue, MeetingClueItemView)`

- `Void _OnClueUnequipClicked(IMeetingClue, MeetingClueItemView)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueAdapter : LoopScrollAdapter`2
{
	private GameObject _clueProto; // 0x58
	private Transform _poolTransform; // 0x60
	private Boolean _showBonusLabel; // 0x68
	private Boolean _showRemoveButton; // 0x69
	public Int32 overrideBonus; // 0x6c
	private GameObjectPool m_objectPool; // 0x70
	private Action`2 onClueClicked; // 0x78
	private Action`2 onClueRemoveClicked; // 0x80
	private Action`2 onClueUnequipClicked; // 0x88
	private IMeetingClue m_selectedClue; // 0x90
	private static DelegateBridge __Hotfix0_add_onClueClicked; // 0x0
	private static DelegateBridge __Hotfix0_remove_onClueClicked; // 0x8
	private static DelegateBridge __Hotfix0_add_onClueRemoveClicked; // 0x10
	private static DelegateBridge __Hotfix0_remove_onClueRemoveClicked; // 0x18
	private static DelegateBridge __Hotfix0_add_onClueUnequipClicked; // 0x20
	private static DelegateBridge __Hotfix0_remove_onClueUnequipClicked; // 0x28
	private static DelegateBridge __Hotfix0_set_selectedClue; // 0x30
	private static DelegateBridge __Hotfix0_CreateView; // 0x38
	private static DelegateBridge __Hotfix0_UpdateView; // 0x40
	private static DelegateBridge __Hotfix0__OnClueClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnClueRemoveClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnClueUnequipClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public IMeetingClue selectedClue { set; }

	// RVA: 0x3df4ec4 VA: 0x759640cec4
	public Void add_onClueClicked(Action`2 value) { }
	// RVA: 0x3df4fb8 VA: 0x759640cfb8
	public Void remove_onClueClicked(Action`2 value) { }
	// RVA: 0x3df50ac VA: 0x759640d0ac
	public Void add_onClueRemoveClicked(Action`2 value) { }
	// RVA: 0x3df51a0 VA: 0x759640d1a0
	public Void remove_onClueRemoveClicked(Action`2 value) { }
	// RVA: 0x3df5294 VA: 0x759640d294
	public Void add_onClueUnequipClicked(Action`2 value) { }
	// RVA: 0x3df5388 VA: 0x759640d388
	public Void remove_onClueUnequipClicked(Action`2 value) { }
	// RVA: 0x3df547c VA: 0x759640d47c
	public Void set_selectedClue(IMeetingClue value) { }
	// RVA: 0x3df5500 VA: 0x759640d500
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3df55d0 VA: 0x759640d5d0
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, IMeetingClue data) { }
	// RVA: 0x3df637c VA: 0x759640e37c
	private Void _OnClueClicked(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df6428 VA: 0x759640e428
	private Void _OnClueRemoveClicked(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df64d4 VA: 0x759640e4d4
	private Void _OnClueUnequipClicked(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df6580 VA: 0x759640e580
	private Void OnDestroy() { }
	// RVA: 0x3df6610 VA: 0x759640e610
	public Void .ctor() { }
}
```