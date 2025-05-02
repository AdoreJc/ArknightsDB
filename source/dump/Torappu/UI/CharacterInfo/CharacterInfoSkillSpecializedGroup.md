# CharacterInfoSkillSpecializedGroup

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIIntEvent _eventSkillToggleClick`

- `Boolean m_isInited`


## Methods

- `Void _OnSkillToggleClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillSpecializedGroup : DataBinder`1
{
	private CharacterSelectSpecializedSkillView[] _skillViews; // 0x20
	private UIIntEvent _eventSkillToggleClick; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__OnSkillToggleClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d89084 VA: 0x75953a1084
	public override Void OnValueChanged(SkillGroupViewProperty property) { }
	// RVA: 0x2d895d4 VA: 0x75953a15d4
	private Void _OnSkillToggleClick(Int32 skillIndex) { }
	// RVA: 0x2d89680 VA: 0x75953a1680
	public Void .ctor() { }
}
```