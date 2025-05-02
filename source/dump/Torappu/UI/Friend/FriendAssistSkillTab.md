# FriendAssistSkillTab

**Namespace:** `Torappu.UI.Friend`


## Fields

- `ThreeStateToggle _stateControl`

- `Text _levelText`

- `Image _skillIcon`

- `Text _skillName`

- `TwoStateToggle _SelectState`

- `Image _speicailizedIcon`


## Methods

- `Void ResetData()`

- `Void ApplyData(String, Int32, Boolean, Boolean)`

- `Void ApplyData(SkillData, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistSkillTab : MonoBehaviour
{
	private ThreeStateToggle _stateControl; // 0x18
	private Text _levelText; // 0x20
	private Image _skillIcon; // 0x28
	private Text _skillName; // 0x30
	private TwoStateToggle _SelectState; // 0x38
	private Image _speicailizedIcon; // 0x40


	// RVA: 0x28c9fe4 VA: 0x7594ee1fe4
	public Void ResetData() { }
	// RVA: 0x28ca004 VA: 0x7594ee2004
	public Void ApplyData(String skillName, Int32 skillLvl, Boolean assign, Boolean unlocked) { }
	// RVA: 0x28ca0ac VA: 0x7594ee20ac
	public Void ApplyData(SkillData skillData, Boolean assign, Boolean unlocked) { }
	// RVA: 0x28ca23c VA: 0x7594ee223c
	public Void .ctor() { }
}
```