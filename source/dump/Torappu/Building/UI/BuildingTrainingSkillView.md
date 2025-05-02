# BuildingTrainingSkillView

**Namespace:** `Torappu.Building.UI`


## Fields

- `UIIntEvent _eventSkillToggleClick`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnSkillToggleClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingTrainingSkillView : DataBinder`1
{
	private CharacterInfoSelectSkillView[] _skillViews; // 0x20
	private UIIntEvent _eventSkillToggleClick; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnSkillToggleClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d5cdc4 VA: 0x7596374dc4
	private Void _InitIfNot() { }
	// RVA: 0x3d5cee8 VA: 0x7596374ee8
	public override Void OnValueChanged(SkillGroupViewProperty property) { }
	// RVA: 0x3d5d094 VA: 0x7596375094
	private Void _OnSkillToggleClick(Int32 skillIndex) { }
	// RVA: 0x3d5d140 VA: 0x7596375140
	public Void .ctor() { }
}
```