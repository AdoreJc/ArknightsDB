# AdvancedSelectorWithTrapSheltr

**Namespace:** `Torappu.Battle`


## Fields

- `String _sheltrBuffKey`

- `String _exposedBuffKey`

- `Boolean _checkOnTheSameLine`

- `FP _offsetMinX`

- `FP _offsetMaxX`

- `FP _offsetMinY`

- `FP _offsetMaxY`

- `Single m_upSheltrPos`

- `Single m_downSheltrPos`

- `Single m_leftSheltrPos`

- `Single m_rightSheltrPos`


## Properties

- `Boolean checkOnTheSameLine`


## Methods

- `Boolean get_checkOnTheSameLine()`

- `Void _AssignSheltrPos(Entity)`

- `Boolean _CheckCandidateBehindSheltr(Entity)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithTrapSheltr : AdvancedSelector
{
	private String _sheltrBuffKey; // 0xe8
	private String _exposedBuffKey; // 0xf0
	private Boolean _checkOnTheSameLine; // 0xf8
	private FP _offsetMinX; // 0x100
	private FP _offsetMaxX; // 0x108
	private FP _offsetMinY; // 0x110
	private FP _offsetMaxY; // 0x118
	private Single m_upSheltrPos; // 0x120
	private Single m_downSheltrPos; // 0x124
	private Single m_leftSheltrPos; // 0x128
	private Single m_rightSheltrPos; // 0x12c
	private static DelegateBridge __Hotfix0_get_checkOnTheSameLine; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge __Hotfix0__AssignSheltrPos; // 0x10
	private static DelegateBridge __Hotfix0__CheckCandidateBehindSheltr; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean checkOnTheSameLine { get; }

	// RVA: 0x1bbcc5c VA: 0x75941d4c5c
	public Boolean get_checkOnTheSameLine() { }
	// RVA: 0x1bbccc4 VA: 0x75941d4cc4
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbd148 VA: 0x75941d5148
	private Void _AssignSheltrPos(Entity sheltr) { }
	// RVA: 0x1bbd4a8 VA: 0x75941d54a8
	private Boolean _CheckCandidateBehindSheltr(Entity candidate) { }
	// RVA: 0x1bbd7c0 VA: 0x75941d57c0
	public Void .ctor() { }
	// RVA: 0x1bbd90c VA: 0x75941d590c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```