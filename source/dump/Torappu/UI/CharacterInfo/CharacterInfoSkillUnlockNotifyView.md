# CharacterInfoSkillUnlockNotifyView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _skillIcon`

- `Text _textDesc`

- `Text _textName`


## Methods

- `Sprite _LoadSkillIcon(SkillData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillUnlockNotifyView : UINotifyView`1
{
	private Image _skillIcon; // 0x30
	private Text _textDesc; // 0x38
	private Text _textName; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__LoadSkillIcon; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d7b6b0 VA: 0x75953936b0
	protected override Void Render(Param param) { }
	// RVA: 0x2d7b82c VA: 0x759539382c
	private Sprite _LoadSkillIcon(SkillData skillData) { }
	// RVA: 0x2d7b9c0 VA: 0x75953939c0
	public Void .ctor() { }
}
```